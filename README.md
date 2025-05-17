# 🚲 Phân Tích Dữ Liệu Bikeshare Hoa Kỳ

Đây là một chương trình dòng lệnh viết bằng Python giúp bạn khám phá dữ liệu đi xe đạp chia sẻ (bikeshare) tại ba thành phố: **Chicago**, **New York City**, và **Washington**.

## 🧰 Tính Năng

- Lọc dữ liệu theo:
  - **Thành phố**: Chicago, New York, Washington
  - **Tháng**: Từ January đến June
  - **Thứ trong tuần**: Monday đến Sunday
- Hiển thị thống kê:
  - Thời gian đi lại phổ biến
  - Trạm bắt đầu và kết thúc phổ biến
  - Tổng và trung bình thời gian chuyến đi
  - Thống kê người dùng (loại người dùng, giới tính, năm sinh)
- Xem **dữ liệu gốc** từng phần (5 dòng một lần)
- Hỗ trợ kiểm tra và xử lý **nhập sai** hoặc **dừng chương trình đột ngột**

## 📁 Tệp Dữ Liệu

- `chicago.csv`
- `new_york_city.csv`
- `washington.csv`

> **Lưu ý**: Một số tệp (như Washington) **không có** dữ liệu về giới tính hoặc năm sinh.

## 💻 Cách Sử Dụng

### 1. Cài đặt thư viện (nếu chưa có):

```bash
pip3 install numpy pandas
```

### 2. Chạy chương trình

```bash
python3 bikeshare.py
```

### 3. Kết quả

Hello! Let's explore some US bikeshare data!

Would you like to see data for Chicago, New York, or Washington?
Washington

Look like you want to hear about Washington!

Which month you like to filter the data? January, February, March, April, May, or June?
April

Which day you like to filter the data? Monday, Tuesday, Wednesday, Thursday, Friday, Saturday, Sunday
Sunday

---

Calculating The Most Frequent Times of Travel...

The most common month: 4

The most common day of week: Sunday

The most common start hour: 12

## This took 0.0016150474548339844 seconds.

Calculating The Most Popular Stations and Trip...

The most commonly used start station: Lincoln Memorial

The most commonly used end station: Lincoln Memorial

The most frequent start station and end station trip: Start Station - Lincoln Memorial; End Station - Lincoln Memorial

## This took 0.0008218288421630859 seconds.

Calculating Trip Duration...

Total travel time: 21018493.498999998

Mean travel time: 1877.99

## This took 0.00013899803161621094 seconds.

Calculating User Stats...

Counts of user types:
User Type
Customer 5683
Subscriber 5509
Name: count, dtype: int64

## This took 0.0005831718444824219 seconds.

Would you like to view individual trip data? Type 'yes' or 'no'.
no

Would you like to restart? Enter yes or no.
no

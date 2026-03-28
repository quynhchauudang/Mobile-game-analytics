# 🎮 Mobile Game Analytics Project

## 📌 Overview

Dự án phân tích dữ liệu game mobile nhằm hiểu hành vi người chơi và tối ưu hiệu suất kinh doanh.

## 📊 Dataset

Dữ liệu bao gồm 4 bảng chính:

* **overview_date.csv**: Thông tin tổng quan theo ngày (DAU, session, engagement…)
* **level_end.csv**: Kết quả mỗi level (win / fail / quit)
* **in_app_purchase.csv**: Giao dịch mua hàng trong game
* **cost.csv**: Chi phí marketing / acquisition

## 📈 Key Metrics

* Daily Active Users (DAU)
* Revenue
* Buyer Rate
* ARPU / ARPPU
* Engagement Rate
* Fail Rate theo level

## 🧠 Key Analysis

* Phân tích funnel level (win / fail / quit)
* Xác định level gây drop user
* Phân tích hành vi spender vs non-spender
* Đánh giá hiệu quả chi phí (ROAS / Profit)

## 📊 Sample Insights

* Một số level có fail rate cao bất thường → cần điều chỉnh độ khó
* Revenue tập trung vào nhóm small % users (whales)
* Có biến động mạnh tại một số ngày → nghi vấn campaign hoặc tracking issue
* Cần bổ sung tutorial, play-time để nghiên cứu kỹ hơn hành vi người dùng để điều chỉnh

## 🛠 Tools Used

* Python (Pandas, Matplotlib)
* Jupyter Notebook

## 📂 Project Structure

* `data/`: chứa sample dataset
* `notebooks/`: notebook phân tích

## 🚀 Author

Dang Chau

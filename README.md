# 🚲 Bicycle Store Sales Dashboard

## 📌 Giới thiệu
Project mô phỏng hệ thống báo cáo BI cho chuỗi cửa hàng xe đạp,
xây dựng theo quy trình end-to-end từ lưu trữ dữ liệu đến trực quan hóa.

> ⚠️ Data trong project này là data mẫu tự tạo cho mục đích học tập.

## 🛠 Tech Stack
| Layer              | Tool       |
-----------------------------------
| Storage & Modeling | SQL Server |
| ETL Pipeline       | SSIS       |
| Visualization      | Power BI   |

## 🔄 Pipeline
SQL Server → SSIS (ETL) → Power BI

## 🗄 Database Schema
![Galaxy Schema](SQL/Galaxy_schema.png)

## 🔧 SSIS ETL Pipeline

### Control Flow
![Control Flow](SSIS/Control_Flow.png)

### Data Flow - Staging
![Data Flow Staging](SSIS/Data_Flow_Clear_Stagging.png)

### Data Flow - Transform
![Data Flow Transform](SSIS/Data_Flow_Transform.png)

### Data Flow - Load Dimension
![Data Flow Dim](SSIS/Data_Flow_Load_Dim.png)

### Data Flow - Load Fact
![Data Flow Fact](SSIS/Data_Flow_Load_Fact.png)

## 📊 Dashboard
![Dashboard](BI_Dashboard/BI_Dashboard.png)

![Tab 4](BI_Dashboard/BI_T4.png)

![Tab 5](BI_Dashboard/BI_T5.png)

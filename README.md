# 🚲 Bicycle Store Sales Dashboard

## 📌 Giới thiệu
Xây dựng hệ thống báo cáo end-to-end cho chuỗi cửa hàng xe đạp
Thiết kế database theo Galaxy Schema, xây dựng ETL pipeline xử lý và chuẩn hóa dữ liệu bằng SSIS
Phân tích doanh thu theo tháng, tiểu bang, danh mục sản phẩm và hiệu suất nhân viên trên Power BI

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

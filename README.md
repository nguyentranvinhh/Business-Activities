
## Mock Project: Business Activities Analysis

### Mục lục

[I. Giới thiệu](#Gioithieu)

[II. Thực hiện](#thuchien)
- [1. Đối tượng](#doituong)
- [2. Tổ chức dữ liệu](#tochucdulieu)
- [3. Thực hiện trên Power BI](#powerBI)

	

===========================

<a name="Gioithieu"></a>
## I. Mở đầu

Dự án mô phỏng này hướng đến việc xây dựng một hệ thống
báo cáo giúp phân tích kết quả kinh doanh của công ty chuyên cung cấp
các thiết bị văn phòng như thiết bị điện tử, bàn ghế và văn phòng phẩm.
Công ty này hiện có 30 đại lý trải đều trên khắp cả nước. Hệ thống báo
cáo sẽ được chia thành cấp công ty và quản lý, giúp có cái nhìn tổng quan
về hoạt động kinh doanh của toàn công ty cũng như xem được các đại lý
có hoạt động hiệu quả hay không.

<a name="thuchien"></a>
## II. Thực hiện

<a name="doituong"></a>
### 1. Đối tượng
Xây dựng báo cáo cho công ty tổ chức theo mô hình đại lý. Báo cáo thành
hai phần chính được sử dụng cho từng đối tượng cụ thể:
1. Báo cáo cấp công ty: Giám đốc cấp công ty
2. Báo cáo cấp đại lí: Giám đốc cấp công ty, Chủ đại lí


<a name="tochucdulieu"></a>
### 2. Tổ chức dữ liệu

![image](https://user-images.githubusercontent.com/94583538/223432785-5cd7d329-c311-4415-b822-d8650bb52671.png)

Data model theo dạng Star Schema
1. Fact Table: Sales.
2. Dim Table: Date, Products, Distributors.

<a name=powerBI></a>
### 3. Thực hiện trên Power BI
Báo cáo chia làm 2 page:
- Báo cáo cấp công ty

![image](https://user-images.githubusercontent.com/94583538/223433950-cf3bd14b-f476-4943-80f2-ec9ce7f9b318.png)

- Báo cáo cấp đại lý

![image](https://user-images.githubusercontent.com/94583538/223434118-8922e251-d1a2-4160-82be-dce801d83f7f.png)



# DMZ Network Project

## Mô tả
Đồ án mô phỏng mô hình mạng DMZ sử dụng GNS3 và các máy ảo Linux (Ubuntu 18.04 và 22.04), với ba vùng mạng: External, DMZ, và Internal. Sử dụng Bash Shell Script để cấu hình router, firewall (firewalld), NAT và port forwarding, đảm bảo client từ External và Internal có thể truy cập website trên Web server trong DMZ.

## Cấu trúc mạng
- **External network:** 192.168.10.0/24
- **DMZ network:** 192.168.20.0/24
- **Internal network:** 192.168.30.0/24

## Công nghệ sử dụng
- GNS3
- VirtualBox & VMware
- Bash Shell Script
- Ubuntu 18.04 / 22.04
- Firewalld, Iptables

## Cấu hình chính
- Thiết lập router với 3 interface
- Gán zone tương ứng cho từng interface bằng firewalld
- Cài đặt Web server trên DMZ
- Cấu hình NAT và port forwarding trên router

## Người thực hiện
- **Tên:** Phan Dương Linh  
- **MSSV:** 20120319  
- **Lớp:** 20_4  
- **Môn học:** Quản trị dịch vụ mạng  
- **Giảng viên:** Lê Hà Minh

## Hướng dẫn chạy
1. Tải file Bash script từ portal và giải nén.
2. Chạy script trên máy ảo router.
3. Kiểm tra kết nối giữa các vùng mạng.
4. Truy cập web server từ External và Internal.

## Tài liệu tham khảo
- hocdevops.com – So sánh chuỗi trong Bash
- HW_BashShell_2.docx – Lê Hà Minh
- 06-Bash_p1.pdf – Nguyễn Thị Minh Tuyền

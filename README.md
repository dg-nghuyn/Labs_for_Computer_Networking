# 📡 PTIT Computer Networking Labs

Tổng hợp 4 bài thực hành cá nhân do mình thiết kế. Các bài lab này được phát triển và hướng dẫn thực hành trực tiếp trên hệ thống **Seclab** (nền tảng chấm điểm tự động tương tự CodePTIT).

> 💡 **Note:** Repository này chỉ chứa các bài lab do mình đóng góp. Để tham khảo kho tài liệu thực hành Mạng máy tính đầy đủ và tổng quát hơn, các bạn hãy ghé thăm: **[NCKH-D23/Lab-MMT](https://github.com/NCKH-D23/Lab-MMT)**.

## 📂 Danh sách Lab

* **`ptit-tcpdump-lab`** (Packet Analysis)
    Thực hành bắt và phân tích các loại gói tin mạng (ICMP, TCP, DNS) bằng công cụ `tcpdump` trong môi trường Labtainer. Sinh viên sẽ học cách lọc và lưu trữ lưu lượng mạng để kiểm tra kết nối.

* **`ptit-internet-sim`** (Routing & Topology)
    Mô phỏng hệ thống mạng đa lớp gồm LAN, Router, ISP và Internet Gateway. Bài thực hành tập trung vào việc bật IP forwarding và cấu hình định tuyến tĩnh (Static Route) để thông mạng giữa các thành phần.

* **`ptit-scapy-lab`** (Packet Crafting & Security)
    Sử dụng thư viện Scapy (Python) để tự "chế tạo" và gửi các gói tin ICMP, UDP, TCP thay vì dùng tool có sẵn. Đặc biệt, bài lab bao gồm thực hành kỹ thuật giả mạo địa chỉ IP (IP Spoofing) để hiểu về an toàn mạng.

* **`ptit-dynamic-nat`** (NAT/Masquerade)
    Cấu hình NAT động (Dynamic NAT / PAT) trên Linux sử dụng `iptables` để cho phép mạng nội bộ truy cập Internet. Sinh viên sẽ phân tích sự thay đổi IP nguồn của gói tin khi đi qua Router.

---

## 📬 Connect

* **GitHub:** [dg-nghuyn](https://github.com/dg-nghuyn)
* **Email:** huyendtn18.cdc@gmail.com

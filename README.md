Lộ trình học việc kỹ thuật IT

Bắt đầu
1.	Đọc bảng lộ trình bên dưới và chọn chủ đề cần thực hành.
2.	Mở tài liệu của chủ đề để xem yêu cầu, thời gian và kết quả trong nguồn.
3.	Sao chép mẫu báo cáo lab, ghi lại quá trình thực hiện và minh chứng.
4.	Cập nhật checklist trong tài liệu, gửi thay đổi để người hướng dẫn xem xét.
5.	Dùng mẫu báo cáo ngày để báo cáo tiến độ.
Lộ trình theo bảng nguồn
STT nguồn	Chủ đề	Thời gian đã ghi	Số dòng ghi OK
1	Môi trường làm việc	2h	0
2	Công cụ làm việc	4h	1
3	Network	1w, 1d	6
4	Hardware system	2d	0
6	Operating system	1w	2
7	Tổng quan ảo hóa	1h	0
8	Proxmox	Chưa ghi	1
9	pfSense	Chưa ghi	1
10	Zabbix và Graylog	Chưa ghi	0
11	Checkmk	Chưa ghi	1
12	RSAT và Active Directory	Chưa ghi	0
13	Rclone và Wasabi	Chưa ghi	1
14	Nextcloud, Keycloak, Mailcow và HAProxy	Chưa ghi	1

STT được giữ theo nguồn: không có mục 5. “Số dòng ghi OK” đếm ô đánh giá có giá trị OK trong từng nhóm, không phải tỷ lệ hoàn thành toàn bộ chủ đề. Ô trống được hiển thị là “—”, không tự hiểu là chưa làm hoặc đã làm.
Các mốc h, d, w được giữ nguyên (giờ, ngày, tuần). Không cộng thành tổng thời gian vì nguồn chưa chỉ rõ các mốc chi tiết có nằm trong thời lượng nhóm hay không.
Nội dung chính
·	Công cụ: GitHub; MobaXterm, PuTTY, SecureCRT; Telegram, Zalo; Lightshot; draw.io; hapbx.com, Zoiper 5; Nextcloud.
·	Network: địa chỉ IP, gateway, DNS, DHCP, NAT, MAC, route; OSI/TCP; công cụ kiểm tra; VLAN; FortiGate 300E, Omada, MikroTik; VPN site-to-site và client-to-site.
·	Phần cứng: các bộ phận máy chủ, tháo lắp, RAID 0/1/5/6/10 và kiểm thử trong lab.
·	Hệ điều hành: cài đặt, IP, tài khoản, phân vùng, iDRAC/iLO/BMC; các phiên bản được ghi chi tiết trong tài liệu nguồn.
·	Ảo hóa và firewall: tổng quan, Proxmox, storage, network, VM, backup/restore, cloud-init; pfSense, NAT, rule, DHCP, OpenVPN và HA.
·	Giám sát: Zabbix, Graylog, Checkmk và kết nối Grafana.
·	Dịch vụ: RSAT/AD, Rclone/Wasabi, Nextcloud/Talk/Office, Keycloak, HAProxy và Mailcow.
Cách đọc dữ liệu
Mỗi tài liệu chủ đề có hai phần riêng:
·	Yêu cầu từ bảng nguồn: giữ nội dung chi tiết, thời gian, kết quả và đánh giá của từng dòng.
·	Checklist và hồ sơ cần nộp: phần bổ sung để theo dõi thực hành và lưu minh chứng.
Các tên phiên bản như Proxmox 9.1, Ubuntu 18/20/22.04, CentOS 7, ESXi 6/7 được giữ theo bảng; đây không phải kết quả kiểm tra phiên bản hay khuyến nghị triển khai mới. Cụm “Crit 805” trong mục Checkmk được giữ nguyên, cần hỏi người hướng dẫn để xác nhận giá trị mong muốn. Các dòng chỉ có “Kết quả” mà không có nội dung chi tiết vẫn được giữ.
Cấu trúc tài liệu
Đường dẫn	Nội dung
README.md	Tổng quan và liên kết từng chủ đề
docs/	13 chủ đề học việc theo STT nguồn
templates/bao-cao-lab.md	Mẫu ghi nhận một bài lab
templates/bao-cao-ngay.md	Mẫu báo cáo tiến độ
data/yeu-cau-ky-thuat-hoc-viec.csv	Bản CSV nguyên gốc của tab đã tải
HUONG-DAN-DUA-LEN-GITHUB.md	Cách đưa bộ tài liệu lên repository

Quy ước cập nhật
·	Đánh dấu [x] khi đã hoàn tất thực hành và có minh chứng.
·	Lưu báo cáo trong thư mục reports/, ví dụ reports/2026-10-20-network.md.
·	Đặt ảnh trong images/ và dùng đường dẫn tương đối để ảnh hiển thị trên GitHub.
·	Không đưa mật khẩu, khóa riêng, token hoặc bản sao cấu hình có bí mật vào repository.
·	Khi sửa yêu cầu đào tạo, ghi rõ nguồn thay đổi và thời điểm cập nhật.
Bộ tài liệu này tổ chức lộ trình và hồ sơ học việc; các hướng dẫn cấu hình chi tiết cần bổ sung từ môi trường lab thực tế và tài liệu chính thức của thiết bị.

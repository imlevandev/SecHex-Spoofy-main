# IMDEV-Spoofy [1.5.8] [![Github All Releases](https://img.shields.io/github/downloads/SecHex/SecHex-Spoofy/total)]()

Simple HWID-Changer 🔑︎
Một số dòng của Phiên bản CLI đến từ @imdev

**Windows 11** Phiên bản 10.0.22621 Bản dựng 22621 ✅
**Windows 10** Phiên bản 22H2 Bản dựng 19045.2965 ✅

Hiện tại tôi vẫn đang học và spoofer còn lâu mới hoàn hảo 100%. Nhưng tôi đang cố gắng hết sức.

# Chức năng ⚡
+ **Disk Spoofing** - [18.05.23]
• Truy xuất thông tin cổng SCSI và bus từ sổ đăng ký Windows.
• Kiểm tra xem loại thiết bị có phải là thiết bị ngoại vi đĩa không.
• Tạo mã định danh và số sê-ri ngẫu nhiên cho thiết bị ngoại vi đĩa.
• Cập nhật các giá trị sổ đăng ký cho thiết bị ngoại vi đĩa bằng mã định danh và số sê-ri mới.

+ **Guid Spoofing** - [18.05.23]
• Tạo GUID (Mã định danh duy nhất toàn cầu) mới cho nhiều khóa sổ đăng ký khác nhau.
• Cập nhật các giá trị sổ đăng ký HwProfileGuid, MachineGuid và MachineId bằng GUID mới.
• Tạo ngày phát hành BIOS ngẫu nhiên.

+ **PC-name Spoofing** - [18.05.23]
• Giả mạo tên máy tính bằng cách cập nhật nhiều khóa sổ đăng ký khác nhau.
• Truy xuất tên máy tính gốc từ sổ đăng ký.
• Tạo tên máy tính mới ngẫu nhiên.
• Cập nhật các giá trị sổ đăng ký cho ComputerName, ActiveComputerName, Hostname và NV Hostname.

+ **MAC ID Spoofing** - [19.05.23]
• Cố gắng giả mạo địa chỉ MAC của bộ điều hợp mạng.
• Truy xuất thông tin bộ điều hợp mạng từ sổ đăng ký Windows.
• Tạo một địa chỉ MAC ngẫu nhiên.
• Cập nhật các giá trị sổ đăng ký cho địa chỉ MAC bằng địa chỉ giả mạo mới.
• Vô hiệu hóa và kích hoạt kết nối vùng cục bộ để áp dụng các thay đổi.

+ **Ubisoft cache cleaner** - [19.05.23]
• Dọn dẹp Cache của Ubisoft

+ **Valorant cache cleaner** - [19.05.23]
• Dọn dẹp Cache của Riot Game

+ **Installation ID Spoofing** - [26.05.23]
• Cố gắng giả mạo Windows ID bằng cách thay đổi giá trị sổ đăng ký MachineGuid.
• Truy xuất giá trị MachineGuid hiện tại từ sổ đăng ký.
• Tạo một MachineGuid giả mạo ngẫu nhiên mới.
• Lưu thông tin nhật ký trước và sau.
• Cập nhật giá trị sổ đăng ký bằng MachineGuid giả mạo.

+ **Spoof EFI Bootloader** - [26.05.23]
• Mở khóa sổ đăng ký cho các biến EFI.
• Truy xuất ID biến EFI hiện tại từ sổ đăng ký.
• Tạo ID Biến EFI ngẫu nhiên mới.
• Cập nhật giá trị sổ đăng ký bằng ID Biến EFI mới.

+ **Spoof SMBIOS** - [26.05.23]
• Mở khóa sổ đăng ký cho dữ liệu SMBIOS.
• Truy xuất SystemSerialNumber hiện tại từ sổ đăng ký.
• Tạo SystemSerialNumber ngẫu nhiên mới.
• Cập nhật giá trị sổ đăng ký bằng SystemSerialNumber mới.

+ **Lấy tất cả thông tin Hệ thống** *[Mới]* - [27.05.23]
• Lấy tất cả thông tin Hệ thống.

+ **Trình kiểm tra sổ đăng ký** *[Mới]* - [07.06.23]
• Xác định một mảng các mục nhập sổ đăng ký để kiểm tra.
• Kiểm tra xem các khóa sổ đăng ký được chỉ định trong mảng có tồn tại không.
• Tạo danh sách các mục nhập sổ đăng ký bị thiếu.
• Hiển thị thông báo lỗi với các mục nhập bị thiếu, nếu có.
• Hiển thị thông báo thành công nếu tìm thấy tất cả các mục nhập sổ đăng ký.

+ **Hệ thống nhật ký** *[Mới]* (đang thử nghiệm) - [10.06.23]
• Ghi lại mọi thay đổi trong tệp .txt

+ **Hệ thống sao lưu** *[Mới]*

Tác giả: Nguyễn Chí Thành

![IMG_1674314482411_1674314628494](https://user-images.githubusercontent.com/82578024/231749370-cff3f452-4349-46bd-80e4-dd85653ca27f.jpg)

# A. COREL PORTAL #

- ## [COREL 2022 PORTAL](https://1drv.ms/u/s!AjzhqlUXIkYVgQWTMZh5F8quOz4B?e=53LTzg) ##
    - Link download [tại đây](https://1drv.ms/u/s!AjzhqlUXIkYVgQWTMZh5F8quOz4B?e=53LTzg)
    - Link tải dự phòng [tại đây](https://terabox.com/s/1ZHDXgogh21YGMvMJVzAwcA)
    - **Lưu ý:** có một số file khi giải nén bị **Windows Security** ăn thịt nhưng vẵn chạy tốt!
- ## [COREL 2020 PORTAL](https://1drv.ms/u/s!AjzhqlUXIkYVgQQjGkJS4plP-ii-?e=wE5er9) ##
    - Link download [tại đây](https://1drv.ms/u/s!AjzhqlUXIkYVgQQjGkJS4plP-ii-?e=wE5er9)
    - Link tải dự phòng: https://drive.google.com/file/d/1joRd4lF-7VhlN-8xw7LoWpOjoLVzR-Dh/view?usp=sharing
- ## [CORELDRAW X8 PORTAL](https://1drv.ms/u/s!AjzhqlUXIkYVgQPMq4dosNUTXckW?e=pkiiTr) ##
    - Link download [tại đây](https://1drv.ms/u/s!AjzhqlUXIkYVgQPMq4dosNUTXckW?e=pkiiTr)
    - Link tải dự phòng: https://drive.google.com/file/d/1UJqlpiQg1icYItARYSXwNpEHhxVWX_lG/view?usp=sharing
- ## [Coreldraw X7 PORTAL](https://1drv.ms/u/s!AjzhqlUXIkYVgQbJPBDmmGHd79OF?e=PZJKv7) ##
    - Link download [tại đây](https://1drv.ms/u/s!AjzhqlUXIkYVgQbJPBDmmGHd79OF?e=PZJKv7)
    - Link tải dự phòng: https://drive.google.com/file/d/1hUTpOujSOKx1GMtXDdNF-0ECsTDHc0-s/view?usp=sharing

# B. COREL CÀI ĐẶT #

- ## COEREL 2021 ##
    - Tiếp theo chỉnh file hosts! File này nằm trong đường dẫn: C:\Windows\System32\drivers\etc
    - **Nội dung cần thêm vào file hot:**

```php
0.0.0.0 mc.corel.com
0.0.0.0 apps.corel.com
0.0.0.0 origin-mc.corel.com
0.0.0.0 iws.corel.com
0.0.0.0 compute-1.amazonaws.com  
0.0.0.0 ipm.corel.com
0.0.0.0 corelvietnam.com  
0.0.0.0 coreldraw.com
0.0.0.0 dev1.ipm.corel.public.corel.net 
127.0.0.1 instead of 0.0.0.0 at the begginning
```

- **Giải pháp sửa file hosts:**
    - Một số máy không cho chỉnh file hosts trực tiếp, mà chỉnh bằng cách:
    - Truy cập vào đường dẫn: C:\Windows\System32\drivers\etc
    - Copy files hosts ra một vị trí nào đó ví dụ màn hình desktop
    - Dùng NotePad mở file hosts lên, copy nội dung cần vào cuối của file, bấm "Save"
    - Sau đó ra màn hình desktop, copy file hosts đó, ghi đè vào đường dẫn: C:\Windows\System32\drivers\etc
    - Vậy là xong!
    - Restart máy là OK.

# Xóa rác trong file tạm do Corel sinh ra #
- Bấm biểu tượng **Windows + R**
- Một cửa sổ hiện lên, gõ vào **temp** bấm enter, sau đó thư mục **C:\Windows\Temp** hiện lên, xóa hết các file và thư mục trong đó, đóng thư mục lại.
- Bấm biểu tượng **Windows + R**
- Một cửa sổ hiện lên, gõ vào **%temp%** bấm enter, sau đó thư mục **C:\Users\<YourUserName>\AppData\Local\Temp** hiện lên, xóa hết các file và thư mục trong đó, đóng thư mục lại.

# Tắt file backup trong CorelDRAW #

Sau khi sử dụng Corel 1 thời gian, chúng ta sẽ thấy xuất hiện 1 loạt các file có dạng Backup…. đây là các file mà CorelDRAW đã tự động sao lưu ra mỗi khi chúng ta chỉnh sửa file đó, Tính năng này mặc định sau khi cài đặt, tưởng chừng như là hay nhưng đôi khi nó lại làm phiền chúng ta rất nhiều, có khi chúng ta sẽ có cả trăm nghìn file backup như vậy. Sau đây là cách để chúng ta bỏ tính năng đó:

- Bước 1: Vào Tool/ Option (Phím tắt Ctrl + J), Hộp thoại hiện ra chúng ta mở rộng Workspace bằng cách nhấn vào dấu cộng, chọn mục save:
- ![image](https://github.com/BsNgChiThanh/Kich-hoat-Corel/assets/82578024/20b1a7d7-1445-48b8-aa6b-40412440d188)
- Bước 2: Bỏ chọn dấu tích Back up original file before saving trong tùy chọn Save:
- ![image](https://github.com/BsNgChiThanh/Kich-hoat-Corel/assets/82578024/5500aa2e-7b9b-4b4a-9136-59d653e7dc43)
- OK xong, vừa rồi là chi tiết các Bỏ backup trong CorelDRAW, từ nay chúng ta sẽ không bao giờ phải chịu phiền toái vì những file backup quá nhiều nữa!

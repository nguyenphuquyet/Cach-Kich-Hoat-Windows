Hướng dẫn cách kích hoạt Windows 11 Pro miễn phí
## Tại sao?
Bởi vì bạn sẽ nhận được một số tính năng khác như Bitlocker và lưu trữ thiết bị của mình dưới dạng Máy tính để bàn ngoài có thể truy cập qua Internet
## Tôi cũng có thể chuyển từ bất kỳ phiên bản nào khác sang Pro không?
Câu trả lời là có! Bạn có thể chuyển từ hầu hết mọi phiên bản sang Pro hoàn toàn miễn phí!
## Lưu ý cho người dùng có phiên bản Pro chưa kích hoạt
Những người đã có Pro nhưng chưa kích hoạt có thể bỏ qua [bước này](https://gist.github.com/Minionguyjpro/d913b3931e844ad8ad9a758a4aca4b63#activating-windows-pro).
## Bắt đầu
Đầu tiên, bạn cần mở CMD (Command Prompt) với tư cách Quản trị viên bằng phím bàn phím này:

Phím logo Windows + R

Và bây giờ nhập "cmd.exe" vào hộp

Bây giờ nó sẽ trông giống như thế này:

![image](https://user-images.githubusercontent.com/66115754/134801377-b9769c34-8a9d-4d4f-ba8e-6c073f1ce4a2.png)

Bây giờ hãy nhấn các phím này trên bàn phím của bạn:

ctrl+shift+enter

Bây giờ bạn sẽ có thứ gì đó giống như cái này:

![image](https://user-images.githubusercontent.com/66115754/134801445-9b90e121-350b-42ea-afec-b499f1fbfae9.png)

Bây giờ, nhấp vào "có"

Bây giờ bạn có thứ gì đó như thế này:

![image](https://user-images.githubusercontent.com/66115754/134807479-53ccdaf9-feb0-49a3-9843-5bb4db016128.png)

### Các lệnh
Bây giờ, nhập lệnh sau:
``slmgr.vbs /upk``
Bây giờ nó sẽ đưa ra một thông báo, nhấp vào OK

Và bây giờ lệnh này:
``slmgr.vbs /cpky``
Nó sẽ đưa ra một thông báo một lần nữa, và nhấp vào OK một lần nữa

Và bây giờ hãy nhập lệnh này:
``slmgr.vbs /ckms``
Một lần nữa hãy nhấp vào OK khi bạn nhận được thông báo
### Lệnh kiểm tra khả năng nâng cấp phiên bản
Bây giờ chúng ta sẽ kiểm tra xem phiên bản của bạn có được hỗ trợ để nâng cấp lên Pro không, hãy chạy lệnh sau để kiểm tra:
``DISM /online /Get-TargetEditions``
Nếu bạn thấy "Professional" trong danh sách, thì bạn có thể nâng cấp phiên bản Windows của mình lên Pro miễn phí!

### Chạy trình cài đặt Windows Pro
Bây giờ, hãy sao chép và dán lệnh đầy đủ này:

sc config LicenseManager start= auto & net start LicenseManager

sc config wuauserv start= auto & net start wuauserv

changepk.exe /productkey VK7JG-NPHTM-C97JM-9MPGT-3V66T

exit

Nó sẽ chạy trình cài đặt và bạn sẽ thấy thông báo: "% hoàn thành"

Bây giờ hãy đợi cho đến khi đạt 100% và không có gì lạ khi bạn gặp lỗi

Khi gặp lỗi, chỉ cần nhấp vào Thoát rồi khởi động lại máy tính của bạn.

Bây giờ bạn sẽ thấy thông báo rằng nó đang chạy bản cập nhật và đang cài đặt các tính năng, chỉ cần đợi cho đến khi hoàn tất và kiểm tra "thông tin" trong cài đặt, bạn sẽ thấy Windows 11 Pro đã được cài đặt!

Nhưng chúng ta chưa xong, bạn sẽ thấy rằng nó chưa được kích hoạt và bạn không thể thay đổi một số cài đặt, bây giờ chúng ta sẽ sửa lỗi đó!

## Kích hoạt Windows Pro
Bây giờ chúng ta sẽ chạy một số lệnh khác để kích hoạt Windows 11 Pro

Nhấn các phím bàn phím này một lần nữa:

Phím logo Windows+R

Nó trông giống thế này một lần nữa:

![Run Dialog With cmd.exe Text In It](https://user-images.githubusercontent.com/66115754/134801377-b9769c34-8a9d-4d4f-ba8e-6c073f1ce4a2.png)

Nhấn ctrl+shift+enter

Bạn sẽ nhận được một thông báo, chỉ cần nhấp vào Có

Bây giờ bạn sẽ nhận được Dấu nhắc lệnh.

Nhập từng lệnh sau để kích hoạt:

slmgr /ipk W269N-WFGWX-YVC9B-4J6C9-T83GX

slmgr /skms kms8.msguides.com

slmgr /ato

Bây giờ bạn đã có Windows 11 Pro và nó đã được kích hoạt! Bạn có thể kiểm tra cài đặt để xem.
# Video hướng dẫn
Ngoài ra còn có video hướng dẫn để bạn dễ dàng làm theo. Nhấp vào hình ảnh bên dưới để xem video hướng dẫn trên YouTube.

[![Video hướng dẫn](https://img.youtube.com/vi/Q132Tr40z_8/0.jpg)](https://www.youtube.com/watch?v=Q132Tr40z_8)

# Lời cuối
Tôi hy vọng bạn thích nó!
Nếu bạn có bất kỳ câu hỏi nào khác, bạn có thể gửi email cho tôi theo địa chỉ "Minionguyjpro@gmail.com" hoặc bình luận về hướng dẫn này.

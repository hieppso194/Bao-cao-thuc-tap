#Tích hợp các công nghệ Mysql Server, Azure Microsoft và PowerBI.

----
#Mục lục
* [I. Tích hợp local Database với Azure Microsoft.] (#1)
* [II. Tích hợp Microsoft Azure với PowerBI .] (#2)
  
----
<a name="1"></a>
## Tích hợp local Database với Azure Microsoft.
* Chúng ta tiến hành việc tích hợp local Database với nền tảng Azure Microsoft theo các bước sau đây (ở đây tôi dùng local DBMS là Sql
Server 2016):
* Tiến hành deploy database.
![](http://imgur.com/UwdEDth.png)
![](http://imgur.com/1eeKyGq.png)
![](http://imgur.com/1iat9xw.png)
*Lưu ý: Để kết nối chúng ta cần điền các thông tin là: tên sql server trên Azure, tài khoản admin và password. Các thông tin này được khởi tạo khi tạo sql server trên Azure và chúng có thể đươc xem trên Azure sql server information.
![](http://imgur.com/uPkFhp1.png)
* Đặc biệt, Để việc kết nối giữa local server của chúng ta với Azure sql server thành công thì chúng ta cần cấp phép truy cập cho client IP của local server tới azure sql server bằng cách Add Client Ip như sau:
![](http://imgur.com/DDCctrs.png)
* Sau khi kêt nối đã thành công, chúng ta điều chỉnh các thông số cho database mà chúng ta deploy như max size,...
![](http://imgur.com/cRUGNKg.png)
* Verify lại thông tin 1 lần nữa.
![](http://imgur.com/IpzI8LS.png)
* Và quá trình tích hợp hoàn thành như hình sau:
![](http://imgur.com/cBhN9qk.png)
* Và thành quả là database trên local của chúng ta đã có mặt trên Azure Cloud.
![](http://imgur.com/reQqB8x.png)

----
<a name="2"></a>
## Tích hợp Microsoft Azure với PowerBI .
* Chúng ta tiến hành theo các bước sau
* Kết nối PowerBI tới sql server trên Azure.
![](http://imgur.com/Af6PK3N.png)
* Sau khi kết nối thành công, database trên server sẽ hiện lên và bao gồm các tables của nó, chúng ta có thể preview trước khi tải
chúng về PowerBI Desktop của mình.
![](http://imgur.com/12pElsh.png)
* Để lọc và làm sạch dữ liệu trước khi load chúng ta click vào edit để thực hiện mục đích của mình. Sau khi đã có dữ liệu mong muốn chúng ta tải dữ liệu từ Azure sql server về máy PowerBI Desktop của mình.
![](http://imgur.com/0BdKdsB.png)
* Chúng ta đã có dữ liệu để phục vụ cho mục đích visualize và analysis cho các ứng dụng BI.



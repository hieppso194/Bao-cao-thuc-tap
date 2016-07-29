#Tích hợp các công nghệ Mysql Server, Azure Microsoft và PowerBI.

----
#Mục lục
* [I. Tích hợp local Database với Azure Microsoft.] (#1)
  * [I.1 Công cụ PowerBI là gì?] (#1.1)
  * [I.2 PowerBI Desktop.] (#1.2)
    * [I.2.1 PowerBI Desktop là gì?] (#1.2.1)
    * [I.2.2 PowerBI Desktop kết nối dữ liệu như thế nào?] (#1.2.2)
    * [I.2.3 Làm sạch dữ liệu.] (#1.2.3)
* [II. Tích hợp Microsoft Azure .] (#2)
  * [II.1. MICROSOFT AZURE LÀ GÌ?] (#2.1)
  * [II.2. CORE SERVICES] (#2.2)
  * [II.3. SQL AZURE-DATABASE] (#2.3)
  
----
<a name="1"></a>
## Tích hợp local Database với Azure Microsoft.
* Chúng ta tiến hành việc tích hợp local Database với nền tảng Azure Microsoft theo các bước sau đây (ở đây tôi dùng local DBMS là Sql
Server 2016):
* *Bước 1: *Kết nối từ local server tới azure sql server.

![](http://imgur.com/UwdEDth.png)
![](http://imgur.com/1eeKyGq.png)
![](http://imgur.com/1iat9xw.png)
* *Lưu ý: *Để kết nối chúng ta cần điền các thông tin là: tên sql server trên Azure, tài khoản admin và password.

#Tìm hiểu Công cụ PowerBI và nền tảng Azure của Microsoft.

----
#Mục lục
##[I. Công cụ PowerBI.] (#1)
  ###[I.1 Công cụ PowerBI là gì?] (#1.1)
  ###[I.2 PowerBI Desktop.] (#1.2)
    ####[I.2.1 PowerBI Desktop là gì?] (#1.2.1)
    ####[I.2.2 PowerBI Desktop kết nối dữ liệu như thế nào?] (#1.2.2)
    ####[I.2.3 Làm sạch dữ liệu.] (#1.2.3)
##[II. Nền tảng Microsoft Azure.] (#2)
  ###[II.1. MICROSOFT AZURE LÀ GÌ?] (#2.1)
  ###[II.2. CORE SERVICES] (#2.2)
  ###[II.3. SQL AZURE-DATABASE] (#2.3)
  
----
<a name="1"></a>
##I. Công cụ PowerBI
<a name="1.1"></a>
###I.1 Công cụ PowerBI là gì?
* PowerBI là tập các dịch vụ phần mềm, ứng dụng và các bộ kết nối (connectors), chúng làm việc cùng nhau để chuyển các nguồn dữ liệu không 
liên quan thành các dữ hiệu có tính mạch lạc, mang tính trực quan và khả năng tương tác cao. Cho dù dữ liệu của bản là 1 bản excel đơn
giản, hoặc là 1 tập dữ liệu trên cloud và kho dữ liệu tổng hợp tại chỗ, công cụ này cho phép bạn kết nối tới các nguồn dữ liệu một cách 
đơn giản, hiển thị những phần quan trong, có ích cho công việc kinh doanh của bạn và thậm chí còn có khả năng chia sẻ cho bất cứ ai mà
bạn muốn.
* Power BI gồm 3 thành phần là:
  -	Power BI Desktop: Là nơi chúng ta tạo nên các báo cáo.
  -	Power BI service: Là 1 SAAS, nơi các báo cáo được publish.
  -	Power BI Mobile: Là ứng dụng nơi thu thập các giá trị từ các báo cáo, từ đó đưa ra các định hướng kinh doanh. Ứng dụng có sẵn trên 3 nền tảng: IOS, Android, Windows Phone.
  ![](http://i.imgur.com/QnltSl3.png)
  
----
<a name="1.2"></a>
###I.2 PowerBI Desktop.
<a name="1.2.1"></a>
####I.2.1 PowerBI Desktop là gì?
* PowerBI Desktop là một công cụ để kết nối, làm sạch, và hiển thị dữ liệu của bạn. Với Power BI Desktop, bạn có thể kết nối dữ liệu
và sau đó mô hình hóa và hiển thị nó theo những cách khác nhau. 

<a name="1.2.2"></a>
####I.2.2 PowerBI Desktop kết nối dữ liệu như thế nào?
* PowerBI Desktop có thể kết nối với một loạt các nguồn dữ liệu, bao gồm cả cơ sở dữ liệu trên local, bảng tính Excel, và các dịch vụ điện toán đám mây. Hiện nay, hơn 59 dịch vụ đám mây khác nhau như GitHub và Marketo có kết nối cụ thể, và bạn có thể kết nối với các nguồn chung thông qua XML, CSV, văn bản, và ODBC. 
  ![](http://i.imgur.com/TY4GsMe.png)
* Sau khi kết nối, cửa sổ đầu tiên bạn sẽ thấy là Navigator. Các Navigator hiển thị các bảng hoặc các thực thể của nguồn dữ liệu của bạn, và click vào những cung cấp cho bạn một bản xem trước nội dung của nó. Sau đó bạn có thể import các bảng được lựa chọn của bạn ngay lập tức, hoặc chọn Chỉnh sửa để thay đổi và làm sạch dữ liệu của bạn trước khi import. 
  ![](http://i.imgur.com/lbdow5m.png)
* Một khi bạn đã lựa chọn các bảng bạn muốn đưa vào PowerBI Desktop, bạn có thể chọn để load chúng vào PowerBI Desktop bằng cách chọn nút Load ở góc dưới bên phải của Navigator.Bạn có thể muốn thay đổi các bảng trước khi bạn load chúng vào Power BI Desktop. Bạn có thể muốn chỉ là một tập hợp con của khách hàng, hoặc lọc dữ liệu cho bán hàng mà chỉ xảy ra ở một quốc gia cụ thể. Trong những trường hợp đó, bạn có thể chọn nút Edit và lọc hoặc biến đổi dữ liệu trước khi đưa tất cả vào PowerBI Desktop.
  ![](http://i.imgur.com/t6AE7Lm.png)
* PowerBI Desktop bao gồm **Query Editor**, một công cụ mạnh mẽ cho việc định hình (shaping) và chuyển đổi dữ liệu (transforming) để nó sẵn sàng cho các mô hình và việc hiển thị của bạn.
  ![](http://imgur.com/ZWJXsfn.png)
* Một số chức năng hữu dụng khác:
  * **Filter**: Công cụ hữu hiệu giúp người dùng lọc các giá trị cần thiết.
  * **Add Custom Column**: cho người dùng tùy chọn các biểu thức bằng văn bản truy vấn từ đầu bằng cách sử dụng ngôn ngữ M mạnh mẽ. Bạn có thể thêm một cột tùy chỉnh dựa trên báo cáo ngôn ngữ truy vấn M, và nhận được dữ liệu của bạn chỉ là cách bạn muốn nó.
  ![](http://imgur.com/a4Oo2fy.png)

<a name="1.2.3"></a>
####I.2.3 Làm sạch dữ liệu.
* Trong khi PowerBI có thể nhập dữ liệu từ hầu như bất cứ nguồn nào, hình dung và mô hình hóa các công cụ của nó làm việc tốt nhất với dữ liệu cột. Đôi khi dữ liệu của bạn sẽ không được định dạng trong cột đơn giản, thường là trường hợp với các bảng tính Excel, nơi bố trí một bảng mà sẽ dễ quan sát cho người đọc mà không phải là tối ưu cho các truy vấn tự động. Ví dụ, các bảng tính sau đây có tiêu đề mà kéo dài nhiều cột
  ![](http://imgur.com/6JHK7q0.png)
Chính vì lẽ đó mà PowerBI có các công cụ để nhanh chóng chuyển đổi bảng nhiều cột thành bộ dữ liệu mà bạn có thể sử dụng.
* Các công cụ là:
  * **Transpose data**: bạn có thể lật dữ liệu (cột lần lượt vào các hàng, và các hàng thành cột), do đó bạn có thể đinh dạng dữ liệu thành định dạng mà bạn có thể thao tác
  ![](http://imgur.com/MaUqXpr.png)
  * **Format data**: bạn cũng có thể cần phải định dạng dữ liệu, vì vậy PowerBI đúng cách có thể phân loại và xác định dữ liệu mà một khi nó được import.
  Với một số ít các biến đổi, bao gồm cả việc thúc đẩy hàng vào tiêu đề vào để phá vỡ các tiêu đề, sử dụng **Fill** để biến các giá trị null vào các giá trị tìm thấy trên hoặc dưới trong một cột nào đó, và Cột **UNPIVOT**, bạn có thể làm sạch dữ liệu đó vào một tập dữ liệu mà bạn có thể sử dụng trong Power BI.
  ![](http://imgur.com/rMvTGYW.png)

----
<a name="2"></a>
##II. Nền tảng Microsoft Azure.
<a name="2.1"></a>
###II.1. MICROSOFT AZURE LÀ GÌ?
* Microsoft Azure là một nền tảng ứng dụng cho công nghệ điện toán đám mây. Bạn có thể sử dụng nền tảng này theo nhiều cách khác nhau. Chẳng hạn, bạn có thể sử dụng Microsoft Azure để xây dựng các ứng dụng web để chạy hoặc lưu trữ dữ liệu trong Microsoft Azure DataCenters. Ngoài ra, chúng ta có thể dùng Microsoft Azure để tạo các máy ảo cho phát triển và kiểm thử phần mềm hoặc chạy SharePoints hay các nền tảng ứng dụng khác.
* Các thành phần trong windows azure:
  Execution Models
  Data Management
  Networking
  Business Analytics
  Messaging
  Caching
  Identity
  High-Performance Computing (HPC)
  Media
  Commerce
  SDKs

Mô hình các component của windows azure:
  ![](http://imgur.com/wcmG7wL.png)
<a name="2.2"></a>

###II.2. CORE SERVICES
* COMPUTE SERVICES
  * Dịch vụ tính toán Microsoft Azure có thể chạy nhiều kiểu ứng dụng khác nhau. Mục tiêu chính của kiến trúc này, là hỗ trợ các ứng dụng có lượng người sử dụng truy cập đồng thời cực lớn. Có thể đạt được mục tiêu này bằng cách tăng cường sử dụng nhiều máy chủ lớn hơn. Nhưng thay vì như vậy, Microsoft Azure được thiết kế để hỗ trợ ứng dụng tốt nhất, chạy nhiều bản sao của cùng một mã nguồn trên nhiều máy chủ khác nhau. Để đạt được điều này, ứng dụng Microsoft Azure có thể có nhiều thực thể (instance), thực thể được thực thi trên một máy ảo.
  * Để chạy một ứng dụng, lập trình viên truy cập Microsoft Azure portal thông qua trình duyệt, đăng nhập với một Windows Live ID. Sau đó, lập trình viên tạo ra một tài khoản hosting để chạy ứng dụng, hoặc một tài khoản lưu trữ (storage) để lưu trữ dữ liệu, hoặc cả hai. Một khi lập trình viên có tài khoản hosting thì có thể upload ứng dụng của mình, chỉ ra bao nhiêu thực thể mà ứng dụng cần, cũng như cấu hình của máy ảo. Microsoft Azure sẽ tạo ra các máy ảo tương ứng để chạy ứng dụng. Lập trình viên, chỉ có thể thấy được trạng trái của ứng dụng được triển khai, thông qua Microsoft Azure portal. Một khi ứng dụng được triển khai, nó hoàn toàn được quản lý bởi Windows Azure. Điều duy nhất bạn phải làm là, chỉ ra các thông số sử dụng cho ứng dụng, còn lại, việc triển khai, tính mở rộng, tính sẵn sàng, nâng cấp, chuẩn bị phần cứng server đều được thực hiện bởi Microsoft Azure cho các ứng dụng đám mây.
  
* Máy ảo của của Microsoft Azure gồm 3 thành phần:
  * Web Role: có thể chấp nhận một request HTTP/HTTPS. Để cho phép điều này, nó chạy trên một máy ảo có Internet Information Services (IIS) 7. Lập trình viên có thể tạo ra Web role bằng ASP.NET, WCF, hay bất kì kĩ thuật .NET nào có thể hoạt động được với IIS 7. Ngoài ra, lập trình viên có thể viết các ứng dụng với native code – việc sử dụng .NET Framework thì không yêu cầu. Có nghĩa là có thể upload và chạy các ứng dụng sử dụng kĩ thuật khác, ví dụ PHP và Java. Khi một request được gửi đến Web role, nó sẽ được truyền qua bộ cân bằng tải đến các thực thể của Web role trong cùng một ứng dụng. Do đó, không đảm bảo rằng, các yêu cầu từ một người dùng có thể được gởi đến cùng một thực thể của ứng dụng.
  * Worker Role: Worker role không giống như Web role, nó không chấp nhận request từ bên ngoài, các máy ảo của nó không chạy IIS. Một Worker role cho bạn khả năng để chạy các xử lý ngầm liên tục trên đám mây. Một Worker role có thể làm việc với queue, table, blob trong dịch vụ lưu trữ. Nó chạy hoàn toàn độc lập với thực thể Web role, mặc dù có thể cùng thuộc một phần của dịch vụ. Việc liên lạc giữa Web role và Worker role có thể thông qua queue của dịch vụ lưu trữ.
  * VM Role: chạy đồng thời các tác nhân (Windows Azureagent). Các tác nhân để phục vụ cho sự tương tác hệ giữa các thực thể với Microsoft Azure Fabric. Các agent này trình bày các API được định nghĩa để các thực thể có thể làm một số việc như: ghi chép, tìm thư mục gốc của tài nguyên lưu trữ cục bộ trên máy ảo của nó.
  
* **Lưu ý: **Lập trình viên có thể chỉ sử dụng thực thể Web role, hay Worker role, hoặc kết hợp cả hai để tạo ra ứng dụng Windows Azure. Có thể sử dụng Microsoft Azure portal để thay đổi số lượng thực thể của Web role, Worker role tùy theo yêu cầu của ứng dụng.

<a name="2.3"></a>
###II.3. SQL AZURE-DATABASE
* Cơ sở dữ liệu SQL Azure cung cấp một hệ thống quản lí cơ sở dữ liệu dựa trên đám mây (DBMS). Công nghệ này cho phép ứng dụng On-Premise và đám mây lưu trữ dữ liệu quan hệ và những kiểu dữ liệu khác trên các máy chủ trong trung tâm dữ liệu Microsoft. Cũng như các công nghệ đám mây khác, tổ chức chỉ trả cho những gì họ sử dụng. Sử dụng dữ liệu đám mây cho phép chuyển đổi những chi phí vốn như: phần cứng, phần mềm hệ thống quản lí lưu trữ, vào chi phí điều hành
  ![](http://imgur.com/DH7k5fG.png)
* SQL Azure cung cấp các dịch vụ định hướng dữ liệu trong đám mây
* Cơ sở dữ liệu SQL Azure được xây dựng trên Microsoft SQL Server. Cho qui mô lớn, công nghệ này cung cấp môi trường SQL Server trong đám mây, bổ sung với Index, View, Store Procedure, Trigger,…và còn nữa. Dữ liệu này có thể được truy xuất bằng ADO.Net và các giao tiếp truy xuất dữ liệu Windows khác. Khách hàng cũng có thể sử dụng phần mềm On-Premise như SQL Server Reporting Service để làm việc với dữ liệu dựa trên đám mây.
* Khi ứng dụng sử dụng Cơ sở dữ liệu SQL Azure thì yêu cầu về quản lí sẽ được giảm đáng kể. Thay vì lo lắng về cơ chế, như giám sát việc sử dụng đĩa và theo dõi tập tin nhật ký (log file), khách hàng sử dụng Cơ sở dữ liệu SQL Azure có thể tập trung vào dữ liệu. Microsoft sẽ xử lí các chi tiết hoạt động. Và giống như các thành phần khác của nền tảng Windows Azure, để sử dụng Cơ sở dữ liệu SQL Azure chỉ cần đến Microsoft Azure Web Portal và cung cấp các thông tin cần thiết.
* Ứng dụng có thể dựa vào SQL Azure với nhiều cách khác nhau.
* Một ứng dụng Microsoft Azure có thể lưu trữ dữ liệu trong Cơ sở dữ liệu SQL Azure. Trong khi bộ lưu trữ Microsoft Azure không hỗ trợ các bảng dữ liệu quan hệ, mà nhiều ứng dụng đang tồn tại sử dụng cơ sở dữ liệu quan hệ. Vì vậy lập trình viên có thể chuyển ứng dụng đang chạy sang ứng dụng Microsoft Azure với lưu trữ dữ liệu trong Cơ sở dữ liệu SQL Azure.
###II.4. STORAGE
* Storage services trong Microsoft Azure là dịch vụ lưu trữ mở rộng vô cùng tiện ích cho các lập trình viên với 100TB mỗi tài khoản, tự động thu gọn để truy xuất các dữ liệu băng thông rộng.
* Storage services hỗ trợ 3 kiểu dịch vụ lưu trữ bảng: blob, table, queue
 ![](http://imgur.com/vdnGufy.png)
Hình mô tả các kiểu lưu trữ trong Storage Services.
Các kiểu dịch vụ này hỗ trợ cục bộ cũng như truy cập trực tiếp thông qua REST services. Sau đây là bảng so sánh giữa các kiểu lưu trữ này:

Bảng so sánh các đặc điểm của các kiểu lưu trữ trong Storage Services
![](http://imgur.com/a8xKTUw.png)

# NoteBasicLanguage1
## 4 nguyên lí của lập trình hướng đối tượng:
-  Tính đóng gói:Giới hạn khả năng truy cập vào thuộc tính  phương thức bằng cách thể hiện qua các AcessModifier.
-  Tính trừu tượng:Trừu tượng hóa 1 vấn đề tức là ẩn dấu những thông tin chi tiết đi,tức là sẽ cho người dùng biết được chức năng chi tiết của hệ thống.nhưng thực hiện như thế nào 
thì ẩn dấu nó đi.Việc trừu tượng hóa ta có thể trừu tượng nó bằng abstract hoặc interface.
-  Tính kế thừa:Kế thừa những đặc tính,phương thức của lớp cha
-  Tính đa hình:Được thể hiện qua việc 1 biến ,1 hàm,1 phương thức được thực hiện thông qua nhiều hình thức khác nhau.và nó sẽ được thể hiện qua 2 hình thức.
 -    +1 là overload ,có nghĩa là nạp chồng phương thức .tức là các phương thức cùng tên nhưng khác tham số truyền vào,cùng tham số khác kiểu dữ liệu,củng như khác thứ tự kiểu dữ liệu.Hàm tạo củng có thể được nạp chồng.Đây người ta gọi là đa hình lúc biên dich.
 -    +1 là override ,có nghĩa là ghi đè các phương thức thức của lớp cha.Nó cùng đối số ,cùng kiểu trả về.Chú ý ta ko thể ghi đè nếu phương thức đó là final vs abstract.Đây người ta gọi nó là đa hình lúc runtime.Tức là khi chương trình chạy đa hình mới được chay.
## So sánh giữa abstract vs interface:
 ### Interface:
 #### Java:
 - Đối với Java7 chỉ khai báo hằng số với phương thức trừu tượng.Vấn đề xảy ra là khi chúng ta có nhiều đối tượng cùng triển khai 1 phương thức xữ lý cùng kết quả giống nhau , vậy rõ ràng lặp lại code,để giải quyết thì ta cần sử dụng thằng 1 abstract thực hiện cùng chức năng ,sau cho đó cho tất cả đối tượng cùng triển khai lớp abstract đó thì lúc đó sẽ giải quyết được vấn đề.Nhưng nhớ rằng java chỉ cho phép đơn kế thừa ,vậy rõ ràng đã bất cập.Từ đó thằng java8 ra đời.
 - Java 8 ra đời có cái gì:Ngoài các hắng số và phương thức trừu tượng thì chúng ta cần có thêm phương thức mặc định và phương thức static.Vậy chúng ta sẽ quay trở lại xem cái lúc đầu rõ ràng ,đây là 1 interface nhiều đối tượng củng có thể triển khai chúng và nhiều đối tượng đó có cùng 1 phương thức thì lúc đó ta thằng phương thức default được sử dụng đến.
Và tiếp tục bất cập ở đây là gì ,là lúc mà khối code xữ lý thằng default quá dài thì ta cần tách ra các hàm nhưng phải public vậy lại là điều chúng ta ko mong muốn.Vậy lúc đó thằng java 9 ra đời.
### Abstract:
#### Java:
#### Kotlin:

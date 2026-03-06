# Co_so_toan_KHDL

> # Buổi 2

tena@ueh.edu.vn

Subject: [DHKHTN-CSTN]

## 1. Giới thiệu 

- NN biên dịch: C, C++, Pascal,.. Sau khi viết code xong -> kiểm tra syntax -> chuyển qua file binary -> kết nối thư viện tạo thành file con
- NN thông dịch: Python.
  - mã nguồn mở
  - hướng đối tượng. Procedural programming mạnh ở bài nhỏ, rõ bước. (Procedural programming là kiểu lập trình xây dựng chương trình chủ yếu bằng các thủ tục / hàm để xử lý công việc theo từng bước.) OOP mạnh ở bài lớn, nhiều thành phần, cần mở rộng lâu dài
  - .py: file mã nguồn Python thông thường, .ipynb: notebook tương tác, vừa viết code vừa xem kết quả từng phần
 
#### Các bước tìm hiểu 1 NN lập trình mới
- B1: Tìm hiểu syntax
  - từ khoá, có phân biệt chữ hoa vs chữ thường không(case sensitive), quy tắc sử dụng định danh (cách đặt tên,..)
- B2: Built-in data type
  - kiểu số gồm những kiểu số nào, kiểu chuỗi gồm gì, mỗi kiểu dữ liệu sẽ có những phép tình toán nào (operators)
  - cách thức chuyển đối kiểu dữ liệu từ kiểu này sang kiểu khác
  - biến và biểu thức, biến cục bộ và biến toàn cục
- B3: Nhập/ xuất dữ liệu (console)
  - console có nghia là màn hình và bàn phím
- B4: block, control structures
  - Sequential structure — cấu trúc tuần tự
  - Selection structure — cấu trúc chọn / rẽ nhánh
  - Iteration structure — cấu trúc lặp
- B5: Hàm UDF (user-define function)
  - passing pattern - cách truyền dữ liệu/đối số vào hàm.
- B6: Lập trình hướng đối tượng OOP
- B7: Xử lý tập tin

## 2. Các khái niệm cơ bản 
### 2.1. Định danh 

- Quy tắc đặt tên theo mnemonic là: đặt tên biến, hàm, hoặc hằng sao cho tên đó gợi nhớ ý nghĩa/chức năng của nó.
### 2.2. Các kiểu dữ liệu cơ bản 

- Kiểu số (numeric): int, float, complex(real, image).
  - Các toán tử kiểu số gồm có + - * / ,...
- Kiểu chuỗi (string)
  - ' ', " "
  - ký tự điều khiển: \n, \t
  - slice: [start:end]
    ```
    s = "Python"
      print(s[2:5])
    ```
  - toán tử: toán tử + nối 2 chuỗi
- Kiểu ngày giờ (datetime)
  - Khi chuyển từ ngày -> chuỗi phải theo yyyymmdd
- Kiểu luận lý (boolean)
    - True, False
    - default là False
    - Là kết quả của những phép so sánh ==, !=,..

### 2.3. Hằng 


# Co_so_toan_KHDL

```

```

> # Buổi 2:

### Mệnh đề là gì

- Nếu một câu có thể gán giá trị Đúng hoặc Sai, thì đó là mệnh đề.
- Một mệnh đề không thể vừa đúng vừa sai cùng lúc.

### Hàm mệnh đề p(x)

- Mệnh đề: đã biết đúng hay sai.
- Hàm mệnh đề: chưa biết đúng hay sai ngay, vì còn phụ thuộc vào biến. Hàm mệnh đề là câu chứa biến, chưa có giá trị đúng/sai cố định cho đến khi ta gán biến hoặc dùng lượng từ.

<img width="567" height="225" alt="Ảnh màn hình 2026-03-21 lúc 22 02 19" src="https://github.com/user-attachments/assets/9e1f1098-8ffc-4fcd-9ce3-75be1c71cd40" />

### Lượng từ ∀, ∃
- Lượng từ với mọi: ∀
  - ∀x∈A,p(x)
  - mọi x trong A đều thoả p(x), p(x) phải đúng với mọi phần tử trong tập A
  - ví dụ ∀x∈N, x^2 ≥ 0 
- Lượng từ tồn tại: ∃
    - có ít nhất 1 A làm cho p(x) đúng
    - ví dụ: ∃ x ∈ N, x^2=4. Câu này đúng, vì có x = 2.
  
### Phủ định lượng từ
- ¬ là ký hiệu phủ định trong logic.
-  > phủ định thành ≤
- < phủ định thành ≥
- ≥ phủ định thành <
- ≤ phủ định thành >
- = phủ định thành ≠
- = phủ định thành =

<img width="298" height="77" alt="Ảnh màn hình 2026-03-21 lúc 22 17 20" src="https://github.com/user-attachments/assets/ff89c100-2f3b-40d4-8337-bf5d64fe573b" />

- 1) tồn tại ít nhất 1 x sao cho p(x) sai
- 2) với mọi x, p(x) đều sai
  
### Kết hợp logic (AND, OR)

- p∧q: Mệnh đề p∧q chỉ đúng khi cả p và q đều đúng.
- p∨q: Mệnh đề p∨q đúng khi ít nhất một trong hai đúng.
- De Morgan là quy tắc: phủ định cả cụm thì đổi AND ↔ OR và phủ định từng phần bên trong.

<img width="569" height="342" alt="Ảnh màn hình 2026-03-21 lúc 22 34 01" src="https://github.com/user-attachments/assets/cf2d8133-70f9-4c6b-9815-97428bc21e95" />

### Mệnh đề nhiều biến

- p(x,y) hoặc p(x,y,z): Nghĩa là giá trị đúng/sai của mệnh đề phụ thuộc vào nhiều biến chứ không chỉ một biến.

<img width="571" height="352" alt="Ảnh màn hình 2026-03-21 lúc 22 36 25" src="https://github.com/user-attachments/assets/64718a7a-19ea-4182-bf23-82ae255d87ca" />

### Thứ tự lượng từ

<img width="495" height="161" alt="Ảnh màn hình 2026-03-21 lúc 22 44 03" src="https://github.com/user-attachments/assets/ab345e9b-5f66-491e-932d-21f6863494dd" />

### Quy nạp toán học

- Quy nạp toán học là một phương pháp chứng minh mệnh đề đúng với mọi số tự nhiên. ∀n∈N,p(n)
  - tức là: với mọi n tự nhiên, mệnh đề p(n) đều đúng.
  - quy nạp thường dùng để chứng minh một công thức tường minh là đúng.
<img width="548" height="335" alt="Ảnh màn hình 2026-03-22 lúc 03 02 42" src="https://github.com/user-attachments/assets/cf098d54-209f-4067-93c2-92a87509d078" />

### Truy hồi, đệ quy

- Đệ quy = quay lại gọi chính mình
- Truy hồi = số sau tính từ số trước
- Hệ thức truy hồi
  - Hệ thức truy hồi là công thức cho biết số hạng sau được tính từ các số hạng trước.
  - truy hồi cho bạn cách sinh dãy
<img width="543" height="158" alt="Ảnh màn hình 2026-03-22 lúc 02 57 39" src="https://github.com/user-attachments/assets/2f3d92df-a623-47b4-b5a9-1f3d2b824a9a" />

### Đọc các phát biểu toán học kiểu ε-δ

<img width="685" height="64" alt="Ảnh màn hình 2026-03-22 lúc 02 42 54" src="https://github.com/user-attachments/assets/73653640-85fb-4187-a888-f9740908f1c2" />

- Với mọi mức sai số đầu ra ε>0, ta luôn tìm được một mức sai số đầu vào δ>0 sao cho với mọi y, nếu y cách x nhỏ hơn δ, thì f(y) cách f(x) nhỏ hơn ε.
<img width="740" height="160" alt="Ảnh màn hình 2026-03-22 lúc 02 44 19" src="https://github.com/user-attachments/assets/f10b2487-1603-4cce-b553-97e5ddd08a70" />

___
### Dãy và ký hiệu

- Số hạng tổng quát là công thức cho biết số hạng thứ n là bao nhiêu.
<img width="428" height="306" alt="Ảnh màn hình 2026-03-22 lúc 02 50 22" src="https://github.com/user-attachments/assets/bed90916-222f-4eda-b689-8bf4e63a7c1f" />
- Ký hiệu tổng ∑
<img width="521" height="206" alt="Ảnh màn hình 2026-03-22 lúc 02 51 29" src="https://github.com/user-attachments/assets/b087031b-28c5-424d-aedc-1adc3cc86098" />

- Ký hiệu tích ∏
<img width="474" height="200" alt="Ảnh màn hình 2026-03-22 lúc 02 52 22" src="https://github.com/user-attachments/assets/e605113a-9526-431a-87f1-6ef4f8a66204" />

- Dạng truy hồi của tổng và tích
<img width="318" height="47" alt="Ảnh màn hình 2026-03-22 lúc 02 55 04" src="https://github.com/user-attachments/assets/a450c2b0-c452-46e8-bfd3-c7a187aa610f" />

___

### Hệ cơ số

- Hệ cơ số là cách biểu diễn số bằng các “chữ số” và lũy thừa của một số gốc.
- Hệ thập phân là cơ số 10. ví dụ số 2026
<img width="384" height="45" alt="Ảnh màn hình 2026-03-22 lúc 03 05 53" src="https://github.com/user-attachments/assets/056b5345-4ac3-470e-951e-207f9ac39a77" />

- Biểu diễn số theo cơ số p
<img width="587" height="210" alt="Ảnh màn hình 2026-03-22 lúc 03 09 34" src="https://github.com/user-attachments/assets/04370d12-62f6-4dd2-9a47-35e83662f500" />

- Phép chia Euclid
<img width="598" height="266" alt="Ảnh màn hình 2026-03-22 lúc 03 11 02" src="https://github.com/user-attachments/assets/a30ec8bd-ab7b-4591-8d0f-78b93ac204fb" />

- Modulo nghĩa là phần dư khi chia n cho p. ví dụ 23 mod 5 = 3 vì 23 = 5 * 4 + 3
- đổi cơ số dựa trên chia liên tiếp lấy dư
<img width="300" height="174" alt="Ảnh màn hình 2026-03-22 lúc 03 13 36" src="https://github.com/user-attachments/assets/85685336-26b3-4114-9fde-609f0f27638a" />

### Đại số hỗ trợ

- Rút gọn biểu thức (cộng trừ hạng đồng dạng, đặt nhân tử chung, khai triển, quy đồng mẫu, rút gọn phân thức)
- Lũy thừa
  - Cùng cơ số, nhân thì cộng số mũ, Chia thì trừ số mũ
<img width="169" height="44" alt="Ảnh màn hình 2026-03-22 lúc 03 16 21" src="https://github.com/user-attachments/assets/e534296d-26cf-4a97-bd37-6f82bce0a32c" />
- Căn thức
<img width="446" height="290" alt="Ảnh màn hình 2026-03-22 lúc 03 17 43" src="https://github.com/user-attachments/assets/0c4a26f9-a0be-462c-9599-30e793154c98" />

- Biến đổi công thức (khai triển, nhóm hạng, đặt nhân tử chung, thay biểu thức tương đương, đổi dạng để khớp mẫu cần chứng minh)






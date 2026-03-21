# Co_so_toan_KHDL

> # Buổi 2:

### Mệnh đề là gì

- Nếu một câu có thể gán giá trị Đúng hoặc Sai, thì đó là mệnh đề.
- Một mệnh đề không thể vừa đúng vừa sai cùng lúc.

### Hàm mệnh đề p(x)

- Mệnh đề: đã biết đúng hay sai.
- Hàm mệnh đề: chưa biết đúng hay sai ngay, vì còn phụ thuộc vào biến. Hàm mệnh đề là câu chứa biến, chưa có giá trị đúng/sai cố định cho đến khi ta gán biến hoặc dùng lượng từ.

<img width="567" height="225" alt="Ảnh màn hình 2026-03-21 lúc 22 02 19" src="https://github.com/user-attachments/assets/9e1f1098-8ffc-4fcd-9ce3-75be1c71cd40" />

```

```

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

### Truy hồi, đệ quy

### Đọc các phát biểu toán học kiểu ε-δ


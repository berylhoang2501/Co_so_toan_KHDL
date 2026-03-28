# Co_so_toan_KHDL

```

```

> # Buổi 2:

### 1. Mệnh đề là gì

- Nếu một câu có thể gán giá trị Đúng hoặc Sai, thì đó là mệnh đề.
- Một mệnh đề không thể vừa đúng vừa sai cùng lúc.

### 2. Hàm mệnh đề p(x)

- Mệnh đề: đã biết đúng hay sai.
- Hàm mệnh đề: chưa biết đúng hay sai ngay, vì còn phụ thuộc vào biến. Hàm mệnh đề là câu chứa biến, chưa có giá trị đúng/sai cố định cho đến khi ta gán biến hoặc dùng lượng từ.

<img width="567" height="225" alt="Ảnh màn hình 2026-03-21 lúc 22 02 19" src="https://github.com/user-attachments/assets/9e1f1098-8ffc-4fcd-9ce3-75be1c71cd40" />

### 3. Lượng từ ∀, ∃
- Lượng từ với mọi: ∀
  - ∀x∈A,p(x)
  - mọi x trong A đều thoả p(x), p(x) phải đúng với mọi phần tử trong tập A
  - ví dụ ∀x∈N, x^2 ≥ 0 
- Lượng từ tồn tại: ∃
    - có ít nhất 1 A làm cho p(x) đúng
    - ví dụ: ∃ x ∈ N, x^2=4. Câu này đúng, vì có x = 2.
  
### 4. Phủ định lượng từ
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
  
### 5. Kết hợp logic (AND, OR)

- p∧q: Mệnh đề p∧q chỉ đúng khi cả p và q đều đúng.
- p∨q: Mệnh đề p∨q đúng khi ít nhất một trong hai đúng.
- De Morgan là quy tắc: phủ định cả cụm thì đổi AND ↔ OR và phủ định từng phần bên trong.

<img width="569" height="342" alt="Ảnh màn hình 2026-03-21 lúc 22 34 01" src="https://github.com/user-attachments/assets/cf2d8133-70f9-4c6b-9815-97428bc21e95" />

### 6. Mệnh đề nhiều biến

- p(x,y) hoặc p(x,y,z): Nghĩa là giá trị đúng/sai của mệnh đề phụ thuộc vào nhiều biến chứ không chỉ một biến.

<img width="571" height="352" alt="Ảnh màn hình 2026-03-21 lúc 22 36 25" src="https://github.com/user-attachments/assets/64718a7a-19ea-4182-bf23-82ae255d87ca" />

### 7. Thứ tự lượng từ

<img width="495" height="161" alt="Ảnh màn hình 2026-03-21 lúc 22 44 03" src="https://github.com/user-attachments/assets/ab345e9b-5f66-491e-932d-21f6863494dd" />

### 8. Quy nạp toán học

- Quy nạp toán học là một phương pháp chứng minh mệnh đề đúng với mọi số tự nhiên. ∀n∈N,p(n)
  - tức là: với mọi n tự nhiên, mệnh đề p(n) đều đúng.
  - quy nạp thường dùng để chứng minh một công thức tường minh là đúng.
<img width="548" height="335" alt="Ảnh màn hình 2026-03-22 lúc 03 02 42" src="https://github.com/user-attachments/assets/cf098d54-209f-4067-93c2-92a87509d078" />

### 9. Truy hồi, đệ quy

- Đệ quy = quay lại gọi chính mình
- Truy hồi = số sau tính từ số trước
- Hệ thức truy hồi
  - Hệ thức truy hồi là công thức cho biết số hạng sau được tính từ các số hạng trước.
  - truy hồi cho bạn cách sinh dãy
<img width="543" height="158" alt="Ảnh màn hình 2026-03-22 lúc 02 57 39" src="https://github.com/user-attachments/assets/2f3d92df-a623-47b4-b5a9-1f3d2b824a9a" />

### 10. Đọc các phát biểu toán học kiểu ε-δ

<img width="685" height="64" alt="Ảnh màn hình 2026-03-22 lúc 02 42 54" src="https://github.com/user-attachments/assets/73653640-85fb-4187-a888-f9740908f1c2" />

- Với mọi mức sai số đầu ra ε>0, ta luôn tìm được một mức sai số đầu vào δ>0 sao cho với mọi y, nếu y cách x nhỏ hơn δ, thì f(y) cách f(x) nhỏ hơn ε.
<img width="740" height="160" alt="Ảnh màn hình 2026-03-22 lúc 02 44 19" src="https://github.com/user-attachments/assets/f10b2487-1603-4cce-b553-97e5ddd08a70" />

___
### 11. Dãy và ký hiệu

- Số hạng tổng quát là công thức cho biết số hạng thứ n là bao nhiêu.
<img width="428" height="306" alt="Ảnh màn hình 2026-03-22 lúc 02 50 22" src="https://github.com/user-attachments/assets/bed90916-222f-4eda-b689-8bf4e63a7c1f" />

- Ký hiệu tổng ∑
<img width="521" height="206" alt="Ảnh màn hình 2026-03-22 lúc 02 51 29" src="https://github.com/user-attachments/assets/b087031b-28c5-424d-aedc-1adc3cc86098" />

- Ký hiệu tích ∏
<img width="474" height="200" alt="Ảnh màn hình 2026-03-22 lúc 02 52 22" src="https://github.com/user-attachments/assets/e605113a-9526-431a-87f1-6ef4f8a66204" />

- Dạng truy hồi của tổng và tích
<img width="318" height="47" alt="Ảnh màn hình 2026-03-22 lúc 02 55 04" src="https://github.com/user-attachments/assets/a450c2b0-c452-46e8-bfd3-c7a187aa610f" />

___

### 12. Hệ cơ số

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

<img width="387" height="455" alt="Ảnh màn hình 2026-03-22 lúc 03 34 29" src="https://github.com/user-attachments/assets/d457d6f0-4316-46c5-ae42-52f0ace2b308" />

### 13. Đại số hỗ trợ

- Rút gọn biểu thức (cộng trừ hạng đồng dạng, đặt nhân tử chung, khai triển, quy đồng mẫu, rút gọn phân thức)
  
- Lũy thừa
  - Cùng cơ số, nhân thì cộng số mũ, Chia thì trừ số mũ
    
<img width="169" height="44" alt="Ảnh màn hình 2026-03-22 lúc 03 16 21" src="https://github.com/user-attachments/assets/e534296d-26cf-4a97-bd37-6f82bce0a32c" />

- Căn thức
  
<img width="446" height="290" alt="Ảnh màn hình 2026-03-22 lúc 03 17 43" src="https://github.com/user-attachments/assets/0c4a26f9-a0be-462c-9599-30e793154c98" />

- Biến đổi công thức (khai triển, nhóm hạng, đặt nhân tử chung, thay biểu thức tương đương, đổi dạng để khớp mẫu cần chứng minh)

### 14. Quan hệ 

- Quan hệ là cách mô tả xem hai phần tử có “liên hệ” với nhau hay không. Ví dụ: “bé hơn hoặc bằng”, “là ước của”, “cùng số dư khi chia cho 3”
  
- Nói đơn giản: lấy 2 phần tử x,y kiểm tra xem chúng có thỏa một điều kiện nào đó không
  - Nếu có, ta nói: xRy
  - nghĩa là x có quan hệ với y,
 
- **Tính chất của quan hệ**
  
<img width="385" height="382" alt="Ảnh màn hình 2026-03-22 lúc 03 49 59" src="https://github.com/user-attachments/assets/bba62b83-b31a-496a-9439-7b93e3dd736b" />

  - Quan hệ tương đương
    
    <img width="455" height="208" alt="Ảnh màn hình 2026-03-22 lúc 03 53 10" src="https://github.com/user-attachments/assets/7d0a05e9-1014-4d13-9fdb-812dec82df80" />
  
    <img width="437" height="107" alt="Ảnh màn hình 2026-03-22 lúc 03 54 29" src="https://github.com/user-attachments/assets/0a16ea07-e325-4c81-a9a7-9dccfb9bc28a" />

  - Quan hệ thứ tự
  
    <img width="374" height="61" alt="Ảnh màn hình 2026-03-22 lúc 03 54 43" src="https://github.com/user-attachments/assets/44b75851-aa57-4ddd-88d9-179a6e44d2e2" />

- **Tích Descartes X×X**

<img width="723" height="237" alt="Ảnh màn hình 2026-03-22 lúc 03 38 27" src="https://github.com/user-attachments/assets/8c7d8a73-4a37-4694-b641-98ab918686dd" />

<img width="879" height="308" alt="Ảnh màn hình 2026-03-22 lúc 03 38 51" src="https://github.com/user-attachments/assets/5faf511b-b224-469f-ab7d-586e09f4d752" />

- Một quan hệ trên X là một tập con của X×X là R⊆X×X

<img width="737" height="252" alt="Ảnh màn hình 2026-03-22 lúc 03 41 54" src="https://github.com/user-attachments/assets/0da5ea89-a07e-4aaa-8e02-82a7c7969734" />

---

### 15. Biểu diễn bằng đồ thị

#### 15.1. Biểu diễn quan hệ bằng đồ thị
- Một quan hệ R trên tập X có thể được vẽ bằng đồ thị có hướng.
  <img width="475" height="170" alt="Ảnh màn hình 2026-03-22 lúc 03 57 43" src="https://github.com/user-attachments/assets/f3479aeb-f029-447a-b1e9-5b96ca31558e" />

#### 15.2. Loop
<img width="405" height="198" alt="Ảnh màn hình 2026-03-22 lúc 03 58 26" src="https://github.com/user-attachments/assets/e768e939-6c63-4a37-9f10-c1b39d3bb1eb" />

- đỉnh là phần tử
- mũi tên là quan hệ
- loop là phần tử quan hệ với chính nó
- nhìn mũi tên hai chiều để đoán đối xứng
- nhìn các loop để đoán phản xạ
- nhìn đường đi 2 bước để kiểm tra bắc cầu

<img width="433" height="338" alt="Ảnh màn hình 2026-03-22 lúc 03 59 54" src="https://github.com/user-attachments/assets/03e5e1b6-f4b8-489b-85a5-658c5c9c061b" />

### 16. Cây và biểu thức
#### 16.1. Cây
- Cây là một cấu trúc gồm các nút nối với nhau theo kiểu phân nhánh.

<img width="604" height="401" alt="Ảnh màn hình 2026-03-22 lúc 09 17 49" src="https://github.com/user-attachments/assets/96afd805-c0fa-4b5d-af9d-89eee882ec5b" />


#### 16.2. Cây nhị phân

- Cây nhị phân là cây mà mỗi nút có nhiều nhất 2 con: con trái, con phải. Không bắt buộc nút nào cũng phải có đủ 2 con, chỉ là tối đa 2 con.

<img width="481" height="297" alt="Ảnh màn hình 2026-03-22 lúc 09 18 47" src="https://github.com/user-attachments/assets/726e8e34-ce40-4559-bc50-106b5caec41b" />

#### 16.3. Cây biểu thức

- Cây biểu thức là cây dùng để biểu diễn một biểu thức toán học.

- Quy tắc: nút trong thường là toán tử, lá thường là toán hạng

#### 16.4. Operator / Operand


### 17. Stack

- Stack là một cấu trúc dữ liệu hoạt động theo nguyên tắc: vào sau ra trước. Tiếng Anh là: LIFO = Last In, First Out

- Pop là thao tác lấy phần tử ở đỉnh stack ra.

- Phần tử ở trên cùng gọi là top.

- Ta luôn: push ở top, pop ở top

**Quy tắc tính biểu thức hậu tố bằng stack**

---
> # Buổi 3:

### Hàm và ánh xạ

- Trong toán rời rạc, hàm hay ánh xạ là một quy tắc gán: mỗi phần tử của một tập này tới đúng một phần tử của một tập khác. f: A→B
  - Đọc là: f là một ánh xạ từ A đến B. Trong đó: A: tập đầu vào, B: tập đích

- Đơn ánh, toàn ánh, song ánh
<img width="244" height="178" alt="Ảnh màn hình 2026-03-22 lúc 11 31 04" src="https://github.com/user-attachments/assets/dd48f47b-9ad4-469c-b71a-fd751470df60" />

- Hàm ngược: 
<img width="390" height="249" alt="Ảnh màn hình 2026-03-22 lúc 11 31 57" src="https://github.com/user-attachments/assets/a28c3d77-379c-449f-ae52-023fd1f1a80e" />

### Không gian vector
- Không gian vector là một tập hợp các phần tử gọi là vector, trong đó ta làm được 2 phép toán: cộng vector, nhân vector với một số (gọi là vô hướng) và các phép toán này phải thỏa một số quy tắc nhất định.

<img width="415" height="198" alt="Ảnh màn hình 2026-03-22 lúc 11 34 42" src="https://github.com/user-attachments/assets/1695d8a6-3444-4cc3-9d56-8d9ba367e9e4" />

- **8 tiên đề của không gian vector**

<img width="360" height="502" alt="Ảnh màn hình 2026-03-22 lúc 11 35 22" src="https://github.com/user-attachments/assets/12d370b8-6af3-40b4-9d5a-a1df3d33d9d6" />

<img width="394" height="343" alt="Ảnh màn hình 2026-03-22 lúc 11 35 36" src="https://github.com/user-attachments/assets/ee2b223a-2fa4-42d9-94e7-6bd02f43b319" />

- **Vector 0**: Vector 0 là phần tử đóng vai trò như số 0 trong phép cộng.


















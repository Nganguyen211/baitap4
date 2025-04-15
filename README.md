# baitap4
Nguyen Thi Hang Nga _K225480106050_baitap4
bai tap 4: (sql server)
yêu cầu bài toán:
 - Tạo csdl cho hệ thống TKB (đã nghe giảng, đã xem cách làm)
 - Nguồn dữ liệu: TMS.tnut.edu.vn
 - Tạo các bảng tuỳ ý (3nf)
 - Tạo được query truy vấn ra thông tin gồm 4 cột: họ tên gv, môn dạy, giờ vào lớp, giờ ra.
   trả lời câu hỏi: trong khoảng thời gian từ datetime1 tới datetime2 thì có những gv nào đang bận giảng dạy.

các bước thực hiện:
1. Tạo github repo mới: đặt tên tuỳ ý (có liên quan đến bài tập này)
2. tạo file readme.md, edit online nó:
   paste những ảnh chụp màn hình
   gõ text mô tả cho ảnh đó

Gợi ý:
  sử dung tms => dữ liệu thô => tiền xử lý => dữ liệu như ý (3nf)
  tạo các bảng với struct phù hợp
  insert nhiều rows từ excel vào cửa sổ edit dữ liệu 1 table (quan sát thì sẽ làm đc)
  

deadline: 15/4/2025

CÁC BƯỚC THỰC HIỆN:

Bước 1: Tạo Database mới có tên là QL_TKB từng bước như các bài tập trước 

![image](https://github.com/user-attachments/assets/7c5b10f2-fb90-4d13-a0be-d244d34395e8)


Bước 2: Tạo các bảng có tên: MonHoc, Lop, GV, PhongHoc, LichHoc theo chuẩn 3NF: 

![image](https://github.com/user-attachments/assets/6fff0900-40b0-4dfa-9e9b-ce5949459148)


![image](https://github.com/user-attachments/assets/50ab5360-b86c-4d0a-9343-b56dd15b3b85)


![image](https://github.com/user-attachments/assets/589c1b8f-81ec-4b6c-bb0d-0b1b96cae307)




Bước 3: Thực hiện đặt các khóa chinh và các khóa ngoại liên kết để thu được sơ đồ liên kết: 


![image](https://github.com/user-attachments/assets/e46db395-8a35-48be-84ee-a207e1348557)


Bước 4: Copy dữ liệu từ nguồn TMS.tnut.edu.vn, patse vào Excel sau đó thực hiện dán các dữ liệu cần thiết vào các bảng ở mục edit bảng trong sql: 

![image](https://github.com/user-attachments/assets/29dc7004-184d-405e-875b-47b7a08fc8ba)

![image](https://github.com/user-attachments/assets/5f6bfa13-603d-4fe5-8f8a-1028b97a3e2d)

![image](https://github.com/user-attachments/assets/44516cb6-d5f2-46d6-89df-36adf766d188)

![image](https://github.com/user-attachments/assets/50b683e0-d21e-40dd-90c3-d16b762a0736)

![image](https://github.com/user-attachments/assets/4723ebb3-578d-40be-be11-0de8fbb4cca2)

![image](https://github.com/user-attachments/assets/3d55037c-f8d4-4c19-87d4-4f995cbcfcab)


Bước 5: Truy vấn ra thông tin gồm 4 cột: họ tên gv, môn dạy, giờ vào lớp, giờ ra: 

![image](https://github.com/user-attachments/assets/68c5e0be-9884-4882-99fc-95592a1a86be)

Trả lời câu hỏi: trong khoảng thời gian từ datetime1 tới datetime2 thì có những gv nào đang bận giảng dạy: 

![image](https://github.com/user-attachments/assets/c6171bc1-5ce8-484f-9d22-084e9e8baa52)



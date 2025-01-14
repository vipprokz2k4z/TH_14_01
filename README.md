![image](https://github.com/user-attachments/assets/f6abd9c2-f304-48c3-b430-c2ce13b68141)
![09ce70b5-d767-4cd1-9a77-eabbc8377235](https://github.com/user-attachments/assets/83586a1c-a696-4e07-9587-87b4e46cb12f)
![ebf26bb0-a627-43e2-b484-32049d38bae9](https://github.com/user-attachments/assets/a47419c1-0298-4e47-9a84-288a7e98f9bb)
# **1. MỤC ĐÍCH SỬ DỤNG**
- Flatlist: Sử dụng để hiển thị danh sách dữ liệu phẳng, không phân nhóm.
- Sectionlist: Sử dụng để hiển thị danh sách phân nhóm với tiêu đề cho từng nhóm.
# **2. CẤU TRÚC DỮ LIỆU**
- Flatlist: Sử dụng một mảng phẳng (array) để hiển thị dữ liệu.
            Mỗi mục trong danh sách là một đối tượng, và bạn có thể truy cập trực tiếp các thuộc tính của nó.
- Sectionlist: Sử dụng một mảng các đối tượng để hiển thị dữ liệu, trong đó mỗi đối tượng đại diện cho một nhóm.
# **3. HIỆU NĂNG**
- Flatlist:
  Tối ưu hiệu năng cho danh sách dài bằng cách chỉ render các mục hiển thị trên màn hình.
  Dễ dàng xử lý các danh sách có hàng nghìn mục.
- Sectionlist:
  Tương tự như FlatList nhưng phải xử lý thêm các nhóm, nên có thể hơi nặng hơn với danh sách lớn và nhiều nhóm.
  Hiệu quả khi làm việc với danh sách phân nhóm nhỏ đến vừa.
# **4. TÍNH DỄ SỬ DỤNG**
- Flatlist:
    Dễ sử dụng hơn, do chỉ làm việc với một danh sách phẳng.
    Thích hợp cho danh sách cơ bản và ít thay đổi về cấu trúc.
- Sectionlist:
    Cấu trúc dữ liệu phức tạp hơn, cần xử lý thêm tiêu đề nhóm.
    Thích hợp nếu cần phân nhóm dữ liệu để cải thiện trải nghiệm người dùng.



# 📌 Đồ án Lập trình Quản lý – Giai đoạn 1

## Hệ thống Quản lý Lịch Làm Việc

### 📖 Giới thiệu

Trong giai đoạn đầu của đồ án, hệ thống quản lý lịch làm việc được khởi tạo với mục tiêu xây dựng nền tảng dữ liệu và cấu trúc project. Đây là bước quan trọng nhằm định hình các thành phần cốt lõi của hệ thống, bao gồm các thực thể (entities), mối quan hệ giữa chúng và cách tổ chức dữ liệu trong cơ sở dữ liệu.

Hệ thống hướng đến việc quản lý thông tin nhân viên, phân công công việc và theo dõi lịch làm việc trong môi trường doanh nghiệp.

---

### 🎯 Mục tiêu của giai đoạn

Giai đoạn này tập trung vào việc thiết kế và cài đặt mô hình dữ liệu cho hệ thống, đảm bảo các thực thể phản ánh đúng nghiệp vụ thực tế và có khả năng mở rộng cho các chức năng ở các giai đoạn sau.

---

### ⚙️ Nội dung đã thực hiện

Trong giai đoạn này, project đã được khởi tạo bằng nền tảng Windows Forms kết hợp với Entity Framework Core để quản lý dữ liệu. Hệ thống đã xây dựng được các lớp thực thể đại diện cho các đối tượng trong bài toán quản lý lịch làm việc.

Cụ thể, các thực thể chính bao gồm nhân viên, phòng ban, chức vụ, tài khoản, lịch làm việc, phân công công việc, loại công việc, tiến độ công việc và lịch sử hệ thống. Mỗi thực thể được định nghĩa rõ ràng với các thuộc tính cần thiết, sử dụng các annotation như `[Key]`, `[Required]`, `[StringLength]` để đảm bảo tính toàn vẹn dữ liệu.

Bên cạnh đó, các mối quan hệ giữa các thực thể cũng đã được thiết lập thông qua khóa ngoại (ForeignKey), cho phép liên kết giữa các bảng như nhân viên với phân công công việc, lịch làm việc với tiến độ công việc, hoặc tài khoản với nhân viên.

Ngoài việc định nghĩa các entity, hệ thống cũng đã xây dựng lớp DbContext để quản lý kết nối và thao tác với cơ sở dữ liệu. Thông qua đó, các DbSet tương ứng với từng bảng dữ liệu được khai báo, giúp thực hiện các thao tác CRUD trong các giai đoạn tiếp theo.

Đồng thời, project đã thực hiện migration đầu tiên để khởi tạo cơ sở dữ liệu, đảm bảo cấu trúc database phù hợp với mô hình đã thiết kế.

---

### 🛠️ Công nghệ sử dụng

* Ngôn ngữ: C#
* Nền tảng: Windows Forms
* ORM: Entity Framework Core
* Cơ sở dữ liệu: SQL Server

---

### ✅ Kết quả đạt được

Sau giai đoạn này, hệ thống đã có một nền tảng dữ liệu hoàn chỉnh với đầy đủ các bảng và mối quan hệ cần thiết. Cấu trúc project rõ ràng, dễ mở rộng, tạo tiền đề cho việc phát triển các chức năng nghiệp vụ và giao diện người dùng ở các giai đoạn tiếp theo.

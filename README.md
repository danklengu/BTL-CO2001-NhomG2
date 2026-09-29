# 🎓 Báo Cáo BTL Môn Kỹ Năng Chuyên Nghiệp Cho Kỹ Sư (CO2001) - Nhóm G2

Chào mừng các thành viên Nhóm G2! Đây là kho chứa (Repository) lưu trữ toàn bộ mã nguồn báo cáo LaTeX BTL của nhóm. Kho chứa này đã được tích hợp **GitHub CI/CD tự động biên dịch PDF**.

> 📄 **File Báo Cáo PDF Mới Nhất:** File [`Bao_Cao_BTL_CO2001_NhomG2.pdf`](./Bao_Cao_BTL_CO2001_NhomG2.pdf) ngay tại trang chủ Repo luôn tự động cập nhật bản mới nhất mỗi khi một Pull Request được Merge vào nhánh `main`!

---

## 📌 1. Quy Tắc Đặt Tên Nhánh (Branch Naming Convention)

Để giữ cho kho chứa gọn gàng và dễ theo dõi phân công, mỗi thành viên khi làm việc sẽ tạo một nhánh riêng theo cú pháp:

$$\text{Tên-nhánh} = \texttt{<tên-thành-viên>-<nhiệm-vụ>}$$

### Ví dụ phân công cụ thể:
* **Tiểu nhóm 1 (Bối cảnh & Workflow):**
  * `nguyen-boicanh-workflow` (Đinh Lê Nguyên)
  * `kiet-boicanh-workflow` (Dương Bảo Kiệt)
* **Tiểu nhóm 2 (Khung kỹ năng):**
  * `hiep-khung-ky-nang` (Đào Văn Trọng Hiệp)
  * `quan-khung-ky-nang` (Đặng Minh Quân)
* **Tiểu nhóm 3 (Tổng hợp, Rủi ro & Khuyến nghị):**
  * `quang-tong-hop-slide` (Đặng Văn Quang)
  * `minh-tong-hop-slide` (Đào Quốc Minh)

> ⚠️ **Quy tắc quan trọng:** Không push trực tiếp lên nhánh `main`. Nhánh `main` chỉ chứa bản báo cáo chính thức đã qua kiểm duyệt.

---

## 🚀 2. Hướng Dẫn 4 Bước Đơn Giản Cho Thành Viên (Zero-Install trên Trình Duyệt)

Bạn không cần cài đặt Git, VS Code hay TeX Live trên máy. Chỉ cần làm theo 4 bước dưới đây ngay trên trình duyệt:

### Bước 1: Mở giao diện chỉnh sửa trên Web
1. Truy cập Repository: [github.com/danklengu/BTL-CO2001-NhomG2](https://github.com/danklengu/BTL-CO2001-NhomG2)
2. Bấm phím dấu chấm `.` trên bàn phím (hoặc đổi `github.com` trên thanh địa chỉ thành `github.dev`).
3. Giao diện VS Code Web sẽ mở ra ngay trên trình duyệt của bạn.

### Bước 2: Chỉnh sửa file `.tex` được phân công
Mở thư mục ứng với phần việc của bạn để nhập/chỉnh sửa nội dung:
* `1. MỞ ĐẦU/` (Tiểu nhóm 1)
* `2. VÍ DỤ THỰC TẾ/` (Tiểu nhóm 2)
* `3. PHÂN TÍCH VẤN ĐỀ/` (Tiểu nhóm 1 & 2)
* `4. KẾT LUẬN/` (Tiểu nhóm 3)

### Bước 3: Lưu và tạo Nhánh mới (Commit & Branch)
1. Chọn icon **Source Control** (hình rễ cây bên thanh công cụ bên trái).
2. Nhập ghi chú ngắn (vd: `Cập nhật phần 3.1 workflow`).
3. Bấm **Commit & Push**. Hệ thống sẽ hỏi tạo Nhánh mới $\rightarrow$ Nhập tên nhánh của bạn (ví dụ: `kiet-boicanh-workflow`).

### Bước 4: Tạo Pull Request (PR)
1. Quay lại trang GitHub Repository, bạn sẽ thấy thông báo nút xanh **Compare & pull request** $\rightarrow$ Bấm chọn.
2. Bấm **Create pull request**.
3. Sau khi người phụ trách bấm **Merge pull request**, file [`Bao_Cao_BTL_CO2001_NhomG2.pdf`](./Bao_Cao_BTL_CO2001_NhomG2.pdf) ở trang chủ nhánh `main` sẽ tự động được cập nhật bản mới nhất!

---

## 🛠️ 3. Cấu Trúc Thư Mục Dự Án

```
BTL-CO2001-NhomG2/
├── .github/workflows/compile-latex.yml  # File cấu hình CI/CD tự động compile & commit PDF
├── Bao_Cao_BTL_CO2001_NhomG2.pdf         # File Báo cáo PDF chính thức (Tự động cập nhật trên main)
├── main.tex                             # File chính liên kết toàn bộ tài liệu
├── Setup.tex                            # Cấu hình package & định dạng trang
├── Cover page.tex                       # Trang bìa chuẩn Bách Khoa
├── references.bib                       # File lưu tài liệu tham khảo (BibTeX)
├── 0. FRONT MATTER/                     # Danh mục viết tắt, bảng biểu
├── 1. MỞ ĐẦU/                           # Chương 1
├── 2. VÍ DỤ THỰC TẾ/                    # Chương 2
├── 3. PHÂN TÍCH VẤN ĐỀ/                 # Chương 3
├── 4. KẾT LUẬN/                         # Chương 4
└── images/                              # Thư mục lưu hình ảnh, logo
```

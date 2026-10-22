# 📚 TÀI LIỆU TẬP HUẤN SỬ DỤNG AI - THCS CHU VĂN AN
### *TÀI LIỆU NỘI BỘ TRƯỜNG THCS CHU VĂN AN - XÃ ĐĂK HÀ (2026)*

---

## 🌐 Đường Dẫn Thực Hành Trực Tuyến (Web App)
Giáo viên có thể mở trực tiếp ứng dụng trên máy tính hoặc điện thoại mà không cần cài đặt bất kỳ phần mềm nào:
👉 **[Nhấp vào đây để mở Giao diện Thực hành AI](https://mrbin2026dh-droid.github.io/tailieutaphuanai/)**

*(Lưu ý: Để link trên hoạt động, vui lòng bật GitHub Pages trong phần **Settings -> Pages -> Branch: main / root** của kho chứa này).*

---

## 🎯 Giới Thiệu & Điểm Nổi Bật

Hệ thống được thiết kế dạng Web App trực quan, tinh gọn và tối ưu hóa tối đa cho các buổi tập huấn thực hành nội bộ của Trường THCS Chu Văn An - Xã Đăk Hà:
1. **14 Bài Thực Hành Chuyên Sâu**: Bao quát toàn bộ các hoạt động sư phạm thiết thực (Xây dựng kế hoạch bài dạy, phân hóa học sinh, thiết kế phiếu học tập, rà soát đề kiểm tra, bồi dưỡng học sinh giỏi theo khung cấu trúc đề thi, kế hoạch phụ đạo học sinh củng cố nền tảng, ra đề cương chống lộ đề, tóm tắt bài học, tạo ảnh minh họa không lỗi font tiếng Việt, xây dựng chatbot hỗ trợ...).
2. **32 Mẫu Prompt Chuẩn Sư Phạm**: Viết 100% bằng tiếng Việt chuẩn mực, tối ưu hóa theo phương pháp kỹ thuật Prompting hiện đại (Vai trò - Bối cảnh - Dữ liệu nguồn - Nhiệm vụ - Ràng buộc).
3. **1-Click Sao Chép (Copy)**: Mỗi bài thực hành đều có nút sao chép nhanh Prompt tiện lợi, tránh lỗi gõ nhầm hay thiếu sót khi thực hành.
4. **Tích Hợp NotebookLM Sâu Sát**: Hướng dẫn giáo viên tận dụng thế mạnh đọc tài liệu chính xác, chống bịa đặt (hallucination) của Google NotebookLM hoàn toàn miễn phí.
5. **Chuẩn Định Dạng Văn Bản Sạch (.docx)**: Tích hợp sẵn luật ràng buộc xuất file Word theo Nghị định 30/2020/NĐ-CP (Times New Roman 14pt, giãn dòng Single, Spacing 6pt, sạch biểu tượng rác).
6. **Cơ Sở Dữ Liệu Thời Gian Thực (Google Firebase Realtime Sync)**: Tự động đồng bộ các bài thực hành và câu lệnh Prompt từ Cloud. Mọi sửa đổi từ Quản trị viên được cập nhật đến toàn thể giáo viên tức thì (< 0.5s) mà không cần tải lại trang.
7. **Phân Quyền Quản Trị Bằng Mã PIN**: Đăng nhập nhanh bằng Mã PIN bảo mật (mã hóa SHA-256 một chiều chống soi mã). Cho phép Quản trị viên thêm/sửa/xóa bài, thêm/sửa prompt và đổi mã PIN linh hoạt ngay trên giao diện web.

---

## 🔐 Hướng Dẫn Quản Trị Viên (Admin) Sử Dụng Mã PIN

1. **Đăng nhập Quản trị**:
   * Nhấp vào nút **`[ 🔒 Quản trị ]`** ở góc trên thanh điều hướng.
   * Nhập Mã PIN bảo mật (Mã PIN mặc định ban đầu: `260388`).
   * Bấm **"Mở khóa Quản trị"**.
2. **Thực hiện Chỉnh sửa & Thêm mới**:
   * **Sửa nhanh câu lệnh Prompt**: Bấm nút **`[ ✏️ Sửa ]`** ngay cạnh nút *Sao chép Prompt* $\rightarrow$ Sửa nội dung $\rightarrow$ Bấm **"Lưu Prompt vào Firebase"**.
   * **Thêm Prompt vào bài**: Bấm **`[ ➕ Thêm Prompt ]`** trên thanh công cụ của bài đó.
   * **Sửa thông tin bài / danh mục**: Bấm **`[ ✏️ Sửa bài ]`** $\rightarrow$ Sửa tiêu đề, số thứ tự, chuyên mục $\rightarrow$ Bấm **"Lưu thay đổi"**.
   * **Thêm bài thực hành mới**: Bấm **`[ ➕ Thêm bài mới ]`** trên thanh trạng thái Admin màu vàng phía trên cùng.
   * **Đổi mã PIN mới**: Bấm **`[ 🔑 Đổi mã PIN ]`** để tự đặt mã PIN mới bí mật cho nhà trường.
3. **Đăng xuất an toàn**:
   * Bấm nút **`[ 🚪 Đăng xuất ]`** để khóa quyền quản trị, bảo vệ an toàn cho hệ thống.

---

## 📖 Hướng Dẫn Giáo Viên Thực Hành 3 Bước

1. **Bước 1: Mở ứng dụng**  
   Truy cập vào trang web thực hành: [https://mrbin2026dh-droid.github.io/tailieutaphuanai/](https://mrbin2026dh-droid.github.io/tailieutaphuanai/)
2. **Bước 2: Chọn bài & Sao chép Prompt**  
   Chọn bài thực hành tương ứng theo hướng dẫn của Báo cáo viên $\rightarrow$ Bấm nút **"Sao chép Prompt"**.
3. **Bước 3: Dán vào AI & Nhận kết quả**  
   * **Đối với bài dùng NotebookLM**: Tải file tài liệu/SGK/Khung đề thi lên trước $\rightarrow$ Dán prompt $\rightarrow$ Yêu cầu xuất file Word.
   * **Đối với Gemini / ChatGPT**: Dán prompt $\rightarrow$ Thay thế phần nội dung nháp trong ngoặc vuông $\rightarrow$ Nhận kết quả.

---

## 📁 Cấu Trúc Thư Mục Kho Chứa

* `index.html`: Giao diện ứng dụng thực hành Web App chuẩn (chạy trực tiếp trên trình duyệt & GitHub Pages).
* `gemini-code-1792572855416.html`: Bản sao lưu mã nguồn giao diện gốc.
* `Tai_lieu_Prompt_Trích xuất từ tài liệu Bo_GDDT_2026.docx`: File tài liệu Word tổng hợp trích xuất nội dung Prompt.
* `TÀI LIỆU BỘ GIÁO DỤC - Ứng dụng AI cho CBQL, GV phổ thông.pdf`: File cẩm nang gốc của Bộ Giáo dục & Đào tạo.

---
*Tài liệu nội bộ Trường THCS Chu Văn An - Xã Đăk Hà phục vụ công tác chuyển đổi số và nâng cao năng lực ứng dụng AI trong giảng dạy.*

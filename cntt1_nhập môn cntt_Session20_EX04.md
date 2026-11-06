# **Yêu cầu đầu ra**

## Lập bảng so sánh Ưu/Nhược điểm của Google Search và AI Assistant dựa trên các tiêu chí: Độ chính xác, Tính cập nhật, Khả năng giải thích và Rủi ro (Hallucination).

| Tiêu chí | Google Search | AI Assistant |
| --- | --- | --- |
| Độ chính xác | Cao (nguồn thật, cộng đồng vote) | Tùy ngữ cảnh (dễ sai nếu đoán nhầm) |
| Tính cập nhật | Thời gian thực (mới nhất) | Phụ thuộc dữ liệu huấn luyện |
| Khả năng giải thích | Phân mảnh (phải tự đọc và tổng hợp) | Trực quan (giải thích từng dòng, tương tác 2 chiều) |
| Rủi ro (Hallucination) | Không bị ảo giác | Có rủi ro bịa đặt (lệnh, hàm, đường dẫn) |

## Đưa ra lựa chọn : Trong trường hợp nào thì bắt buộc phải dùng Google Search để đảm bảo an toàn cho máy tính?

**Trường hợp bắt buộc dùng Google Search để đảm bảo an toàn máy tính :**

1. Thực thi câu lệnh hệ thống có quyền quản trị cao (Sudo / Administrator) :
 
- Xóa tiến trình (Kill process: kill -9, taskkill /F).
     
- Can thiệp tường lửa (Firewall), mở/đóng cổng hệ thống.
     
- Sửa cấu hình phân quyền (chmod, chown) hoặc Registry.

2. Cần kiểm tra độ tin cậy của file / phần mềm:
   
- Tải công cụ hoặc script khắc phục lỗi từ bên thứ 3.
     
- Kiểm tra mã độc (checksum, MD5, SHA256).

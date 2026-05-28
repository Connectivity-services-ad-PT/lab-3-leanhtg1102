# Biên Bản Xác Nhận Biên Giao Tiếp (Consumer-Provider Handshake)

- **Provider Service:** Dịch vụ Quản lý Cảnh báo (team-core)
- **Consumer Service:** Dịch vụ Thu thập Dữ liệu IoT (team-iot)
- **Phiên bản Hợp đồng API thống nhất:** OpenAPI 3.1.0

## Thỏa thuận Tích hợp
Hai bên đồng thuận cấu hình endpoint phụ thuộc `/detect` chạy thử nghiệm giả lập qua Mock Server tại địa chỉ cổng port `4011`. Mọi cấu trúc dữ liệu phản hồi lỗi bắt buộc phải tuân thủ chặt chẽ định dạng đối tượng `ProblemDetails`.
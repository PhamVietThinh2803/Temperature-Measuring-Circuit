# Mô tả dự án
Mạch đo nhiệt độ sử dụng LM35, ADC0808 và 8051
![plot](https://github.com/PhamVietThinh2803/Temperature-Measuring-Circuit/blob/main/Simulation%20Circuit.png)
+ Hai nút để kiểm tra và điều chỉnh ngưỡng nhiệt độ (Ngưỡng nhiệt độ mặc định ở 100oC)
+ Dải đo nhiệt độ từ 0-100oC với độ phân giải 1oC. Nhiệt độ hiển thị lên Led 7 thanh.
+ Khi nhiệt độ vượt ngưỡng, Led (Vàng) sẽ bật và Led 7 thanh sẽ nhấp nháy (8888). Chỉ dừng cảnh báo khi ấn nút thoát cảnh báo.
+ Nhiệt độ hiển thị 10 giây 1 lần để tránh nhiễu từ cảm biến.

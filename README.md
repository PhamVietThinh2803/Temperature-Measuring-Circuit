# Mô tả dự án
Mạch đo nhiệt độ sử dụng LM35, ADC0808 và 8051

![plot](https://github.com/PhamVietThinh2803/Temperature-Measuring-Circuit/blob/main/M%E1%BA%A1ch%20m%C3%B4%20ph%E1%BB%8Fng.png)
+ Hai nút để kiểm tra và điều chỉnh ngưỡng nhiệt độ (Ngưỡng nhiệt độ mặc định ở 100oC)
+ Dải đo nhiệt độ từ 0-100oC với độ phân giải 1oC. Nhiệt độ hiển thị lên Led 7 thanh.
+ Khi nhiệt độ vượt ngưỡng, Led (Vàng) sẽ bật và Led 7 thanh sẽ nhấp nháy (8888). Chỉ dừng cảnh báo khi ấn nút thoát cảnh báo.
+ Nhiệt độ hiển thị 10 giây 1 lần để tránh nhiễu từ cảm biến. Việc này có thể thực hiện được bằng 2 cách 
  1. Sử dụng D-FF hoạt động với xung clock có chu kỳ T = 10s. Sử dụng D-FF tạo độ trễ ổn định, tuy nhiên, khó tạo xung clock có chu kỳ T = 10s, cũng như làm tăng kích cỡ của mạch đo.

![plot](https://github.com/PhamVietThinh2803/Temperature-Measuring-Circuit/blob/main/D-FF.png)

  2. Sử dụng ngắt Timer của 8051. Không cần thêm linh kiện nhưng sẽ khó khăn hơn về phần mềm. (Nhóm sẽ sử dụng cách này để hiểu hơn về ngắt Timer)

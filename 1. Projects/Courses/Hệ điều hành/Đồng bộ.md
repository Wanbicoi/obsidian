Là vấn đề liên quan tới truy cập vào [[shared memory]]

Để dùng chung 1 vùng nhớ thì OS phải thỏa điều kiện:
1. 1 và chỉ 1 tiến trình dùng được thực thi trong [[miền găng]].
2. Không tiến trình nào ngoài [[miền găng]] ngăn cản tiến trình khác vào miền găng.
3. Không tiến trình nào đợi quá lâu để vào miền găng.
4. Không có giả thiết về tốc độ CPU, số lượng CPU.

Giải pháp BUSY WAITING
- Giải pháp phần mềm
	1. Sử dụng cờ hiệu
	2. Kiểm tra luân phiên
	3. Giải pháp Peterson
- Giải pháp phần cứng
	1. Vô hiệu hóa ngắt
	2. Chỉ thị TSL (Test-and-Set)
Giải pháp “SLEEP and WAKEUP”
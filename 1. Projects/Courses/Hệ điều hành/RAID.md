Redundant Array of Inexpensive Disk (RAID) 
- OS phân nhỏ [[ổ đĩa logic]] thành nhiều *ổ cứng* nhỏ hơn. Mục đích là để:
	- Truy xuất nhanh hơn (why? Vì truy xuất đồng thời nhiều ổ cùng lúc)
	- Bảo vệ dữ liệu, hỏng 1 cái thì cái còn lại vẫn dùng được (tuy có mất mát 😀)
- Phân thành 6 cấp độ áp dụng:
	0. Không sao lưu
	1. Sao lưu (nhân bản dữ liệu qua nhiều ổ): 
		- Khôi phục đơn giản, nhưng chi phí cao.
		- Đọc 1 trong 2, để tăng tốc độ đọc nếu yêu cầu đọc nhiều.
	2. 
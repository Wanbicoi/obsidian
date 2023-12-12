# Heuristic Search
Tính chất thuật toán
 - Tính dừng
 - Tính xác định
 - Tính đúng đắn

Kỹ thuật làm mờ (thoả hiệp ~ thoả mãn)

## Người bán hàng (Greedy traveling)
1. GTS1 
![[IMG20231016100337.jpg]]
![[IMG20231016100647.jpg]]
2. GTS2 (là GTS1 thực hiện P lần, chọn ra cái tốt nhất trong P lần đó)
3. GT3 

## Thuật giải leo đồi (Hill-Climbing Search)
![[IMG20231016102610.jpg]]

![[IMG20231016103248.jpg]]
![[IMG20231016103349.jpg]]
- Chọn h (bất kì, hợp lí là đc 🤡 ) làm sao cho h trc < h sau.

## Euclidean Heuristic
![[IMG20231016104200.jpg]]
### Bài toán 8-puzzle
![[IMG20231016110732.jpg]]
1. Heuristic 1:
Mỗi thao tác sẽ tính độ lệch với g (trường hợp này là (b)), cái nào lệch ít nhất thì chọn.
Nếu 2 cái đều ngang nhau, chọn cả 2 ( a thầy bảo đây là chưa chọn j 😀😀) sau đó xét tiếp, cái nào "tốt" hơn thì lấy. Không thì xem lại Heuristic=))
- Việc chọn lại Heuristic trong Heuristic gọi là **Meta Heuristic**
2. Heuristic 2:
Thay vì xét lệch ít nhất thì xét bao nhiêu bước để về đúng vị trí
Tính lại:
- Chuyển 1 lần ô, tính h1,h2
- Chuyển 2 lần ô, tính h1,h2
### Bài toán Tháp Hà Nội
![[IMG20231016112401.jpg]]
Làm bằng tay với n = 3 
### Bài toán phân công việc
![[IMG20231016113027.jpg]]
Nguyên lý sắp thứ tự

### Bài toán đóng gói (Packing problem)
> 1 Heuristic chỉ giải quyết được 1 bài toán thui

Vì sẽ có những trường hợp tưởng đúng nhưng không đúng (Chẳng hạn như bỏ phần tử 1 đi, heuristic sẽ bị sai)

![[IMG20231016114418.jpg]]
Cấu hỏi: 
- f là gì

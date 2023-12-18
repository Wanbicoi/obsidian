Program là chương trình thì tiến trình là cái Program đó đang chạy.

Thuộc tính của 1 tiến trình:
- **Process Id:**
- **Process State:** New, Ready, Run, Wait (Block), Complete (Terminated), Suspended Ready, Suspended Block
	- Trong đó Suspended Ready, Suspended Block xảy ra khi hàng đợi bị full.
	- **Lưu ý:** chỉ có duy nhất 1 tiến trình có trạng thái Run tại 1 thời điểm đối với (single process OS)
- **CPU registers:** địa chỉ của tiến trình này trên CPU register
- **Accounts information:** Amount of CPU used for process execution, time limits, execution ID, etc
- **I/O status information:** 
- **CPU scheduling information:** lưu độ ưu tiên, CPU chọn tiến trình nào có độ ưu tiên cao để chạy trước.

## Process Scheduling Algorithms
1. **First-come, first-served (FCFS):** là 1 cái queue
2. **Shortest Job First (SJF):** thời gian chạy (burst time) ngắn nhất thì được chạy trước.
3. **Round Robin (RR):** chia đều thời gian ra chạy tất cả các tiến trình, giống như Time-sharing.
4. **Priority Scheduling:** là 1 cái Priority Queue.
5. **Multilevel queue:** là 1 cái Priority Queue chứa nhiều cái Priority Queue khác.

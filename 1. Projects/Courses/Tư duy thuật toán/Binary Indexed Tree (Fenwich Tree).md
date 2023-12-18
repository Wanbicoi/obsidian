Là 1 cấu trúc dữ liệu dạng cây nhưng được lưu dưới dạng mảng.  Cho phép O(log n) truy xuất tổng và cập nhật tại 1 vị trí. Áp dụng vào mỗi prefix sum là chủ yếu
```c++
int getSum(int p) {
    int idx = p, ans = 0;
    while (idx > 0) {
        ans += bit[idx];
        idx -= (idx & (-idx));
    }
    return ans;
}

void update(int u, int v) {
    int idx = u;
    while (idx <= n) {
        bit[idx] += v;
        idx += (idx & (-idx));
    }
}
```

Thao tác trên mảng 2D tuy nhiên nó cũng vậy 😃
Là 1 cây **tiền tố**, được dùng quản lý 1 tập hợp các chuỗi. 

![[U31qYb0.gif]]

Tính năng cơ bản bao gồm: Thêm, xóa, tìm kiếm.

Có 2 cách xây dựng:
- Bằng mảng:
- Bằng con trỏ:
```c++
struct TrieNode
{
	 struct TrieNode *children[ALPHABET_SIZE];
	 bool isEndOfWord;
};
```


Ứng dụng (rất nhiều, phổ biến trong lập trình thi đấu hay là tính năng **autocomplete**)
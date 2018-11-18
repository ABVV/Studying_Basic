# Hàng đợi

## Yêu cầu:
- Làm hết sức
- Tìm hiểu kỹ càng, nghiên cứu sâu vào.
- Không than vãn
- Biết cách search google những câu không biết ( recomend bằng Tiếng Anh )
- Deadline : 21 /11/ 2018
## Lý thuyết:
- Tìm hiểu và tìm cách hiện thực Queue, Stack bằng Array, Linked List gồm các phương thức : push, pop.
- Tìm hiểu và hiện thực cấu trúc heap : Build heap, Down Heap, hiện thực bằng Array.
- Tìm hiểu về thuật toán DFS ( duyệt sâu), BFS ( duyệt rộng) và dùng hàng đợi nào cho mỗi thuật toán.

## Bài tập

### Bài tập 1:
Cho một biểu thức gồm các phép toán + , - :

Dùng hàng đợi stack để tính ra giá trị của biểu thức đó.

Input : Một xâu ký tự là biểu thức

Ouptut: Trả về giá trị của biểu thức đó.

Ví dụ:
```
input : "5 + 7 - 8 + 10"
output: 14
```

### Bài tập 2: 
Cũng tương tự như bài tập 1 , nhưng có thêm các dấu ( ), *.
Lưu ý: Các phép tính thực hiện từ trái qua phải, không xét tính ưu tiên. Vì vậy, các phép tính nào muốn tính trước thì để trong dấu ngoặc.
Ví dụ:
```
input: "5 + (7*10) + 8"
output: 83
```

### Bài tập 3

Cho một đồ thị gồm N đỉnh, M cạnh.

input : 
- Dòng đầu tiên gồm hai số N, M. 
- M dòng tiếp theo là hai số u v , tương ứng là có đường nối từ u -> v
- Dòng cuối cùng là hai đỉnh s và t.
        
Output: In ra đường đi từ s -> t.

Yêu cầu: Hiện thực trong hai cách : DFS, và DBS

Ví dụ:
```
input:
4 3
1 2
2 3
2 5
1 5

output: 1 2 5
```


# Game bầu cua (ver 2023)
Trò chơi lắc bầu cua phiên bản web.

> _Không khuyến khích, ủng hộ việc sử dụng như một công cụ cờ bạc. Hãy cùng bạn bè vui vẻ trong những dịp gặp mặt!_

## Hướng dẫn sử dụng

Đầu tiên, truy cập trang [Bầu cua](https://thangnd157.github.io/bau-cua-2023/):

![image](https://user-images.githubusercontent.com/94043610/225951706-25665513-345b-4e44-8046-c1647251dd28.png)

* Ở góc trên bên phải là nút bật/tắt âm thanh nền (sử dụng bài nhạc *Melodia dla Zuzi - Marek i Wacek*).
* Nút bấm $\color{#00688B}màu \space xanh$ được dùng để mở tô.
* Nút bấm $\color{#CDAD00}màu \space vàng$ được dùng để xóc tô.

Khi mở tô:

![image](https://user-images.githubusercontent.com/94043610/225962757-82a66914-46e1-4ed5-a48b-e4540336be01.png)

Xóc tô sẽ làm thay đổi các xúc xắc theo tỉ lệ ngẫu nhiên thành 1 trong 6 hình cho trước: *bầu, cua, tôm, cá, gà, hươu*.

### Lưu ý:

* Phiên bản hiện tại chỉ có bộ xóc xúc xắc, chưa bao gồm bàn bầu cua, người chơi cần chuẩn bị thêm.
* Là trang web tĩnh nên mỗi bàn chơi chỉ nên sử dụng một thiết bị truy cập để đồng bộ. Nhưng có thể sử dụng cùng lúc với nhiều bàn chơi khác nhau.
* Tương thích với giao diện của hầu hết các thiết bị (máy tính, smartphone...).

## Thông tin thêm

### Xác suất thắng thua

Với mỗi lượt chơi, sẽ có 3 trường hợp chung của 3 xúc xắc:

|Trường hợp                     |Số khả năng                |Nhà cái                                                     |Kết quả|
|-------------------------------|---------------------------|------------------------------------------------------------|-------|
|3 hình khác nhau               |$6 \times 5 \times 4 = 120$|thua 3 ô, ăn 3 ô còn lại                                    |hòa    |
|3 hình giống nhau              |$6$                        |thua 1 ô $(\times 3$), ăn 5 ô còn lại                       |lời 2/6|
| 2 hình giống nhau, 1 hinh khác|$6^3 - 120 - 6 = 90$       |thua 1 ô $(\times 2)$, thua 1 ô $(\times 1)$, ăn 4 ô còn lại|lời 1/6|

Bảng trên có xét thêm **kết quả của nhà cái** sau một lượt chơi (giả sử 6 ô đều được đặt hết với cùng một giá trị).

Có thể dễ dàng tính được:

* Xác suất nhà cái thua: $0$.
* Xác suất nhà cái hòa: $120/6^3 = 0.56$.
* Xác suất nhà cái lời: $1 - 0.56 = 0.44$.

Và trung bình nhà cái lời mỗi ván: $(2/6 \times 6 + 1/6 \times 90)/6^3 = 7.88$%.

> Bạn có thể thử tính xác suất người chơi có thể đặt trúng 1 ô. Kết quả là 42%!

_**Vì vậy đừng nên chơi bầu cua để mong kiếm lời, nhà cái sẽ luôn thắng. Chỉ nên xem nó là một trò chơi vui vẻ.**_


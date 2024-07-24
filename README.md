# Managing basic hotel system.
<h1> Mô tả nghiệp vụ hệ thống. </h1>
<td align='center' width="60">          
Một khách sạn có 3 loại phòng: phòng đơn, phòng đôi, phòng VIP với mức giá của các phòng là khác nhau. Ngoài ra còn có một vài dịch vụ kèm theo khi khách hàng thuê phòng.
<br>
Khi khách đặt phòng, lễ tân sẽ xác định số người và loại phòng mà khách hàng muốn đặt. Sau đó sẽ kiểm tra hiện tại có phòng trống nào hay không. Nếu loại phòng đó đã hết thì thông báo cho khách. Ngược lại gửi mã xác thực đồng thời ghi ngày đặt phòng, thông tin khách hàng: họ và tên, số điện thoại, email, vào sổ đặt phòng. Song cập nhật lại tình trạng phòng trên hệ thống.
<br>
Khi khách nhận phòng, lễ tân sẽ kiểm tra mã xác thực, đối chiếu mã với sổ đặt phòng và xác nhận lại thông tin. Nếu mã xác thực không đúng thì không cho nhận phòng. Ngược lại phát thẻ ra vào phòng khách sạn cho khách, đồng thời ghi các thông tin cần thiết vào sổ nhận phòng.
<br>
Khi khách trả phòng, lễ tân sẽ kiểm tra thẻ ra vào, sau đó kiểm tra lại thông tin loại phòng, các dịch vụ mà khách hàng đã sử dụng tại khách sạn theo bảng giá tiền. Song thanh toán và thu tiền của khách, đồng thời ghi các thông tin cần thiết vào sổ trả phòng.
<br>
Khi khách đến báo cáo sự cố thì kiểm tra thì kiểm tra trong sổ nhận phòng và sổ trả phòng để xác minh khách có nhận phòng và trả phòng hay chưa. Nếu không đúng như vậy thì không giải quyết. Ngược lại, tiến hành kiểm tra lại camera trên hành lang và trong các khu vực được giám sát. Nếu đúng như sự việc thì lập biên bản giải quyết và trong trường hợp cần thiết thì bồi thường cho khách.
</td>
<h1> Sơ đồ cây phân rã chức năng (FHD). </h1>
<td align='center' width="60">          
  <img src="https://github.com/Eel-Aig-gYuh/Basic-hotel-system/blob/main/Image/So%20do%20cay%20phan%20ra%20chuc%20nang.png">
</td>
<h1> Ma trận thực thể dữ liệu - chức năng</h1>
<td align='center' width="60">          
  <img src="https://github.com/Eel-Aig-gYuh/Basic-hotel-system/blob/main/Image/So%20do%20thuc%20the%20chuc%20nang.png">
</td>
<h1> Sơ đồ DFD mức ngữ cảnh. </h1>
<td align='center' width="60">          
  <img src="https://github.com/Eel-Aig-gYuh/Basic-hotel-system/blob/main/Image/So%20do%20luong%20muc%20ngu%20canh.png">
</td>
<h1> Sơ đồ DFD mức đỉnh. </h1>
<td align='center' width="60">          
  <img src="https://github.com/Eel-Aig-gYuh/Basic-hotel-system/blob/main/Image/So%20do%20luong%20muc%20dinh.png">
</td>
<h1> Giao diện. </h1>
<h2> Hệ thống (trang chủ) </h2>
<td align='center' width="60">          
  <img src="https://github.com/Eel-Aig-gYuh/Basic-hotel-system/blob/main/Image/Giao%20dien%20he%20thong.png">
</td>
<h2> Đặt phòng. </h2>
<td align='center' width="60">          
  <img src="https://github.com/Eel-Aig-gYuh/Basic-hotel-system/blob/main/Image/Giao%20dien%20dat%20phong.png">
</td>
<h2> Nhận phòng. </h2>
<td align='center' width="60">          
  <img src="https://github.com/Eel-Aig-gYuh/Basic-hotel-system/blob/main/Image/Giao%20dien%20nhan%20phong.png">
</td>
<h2> Dịch vụ. </h2>
<td align='center' width="60">          
  <img src="https://github.com/Eel-Aig-gYuh/Basic-hotel-system/blob/main/Image/Giao%20dien%20dich%20vu.png">
</td>
<h2> Thanh toán. </h2>
<td align='center' width="60">          
  <img src="https://github.com/Eel-Aig-gYuh/Basic-hotel-system/blob/main/Image/Giao%20dien%20thanh%20toan.png">
</td>

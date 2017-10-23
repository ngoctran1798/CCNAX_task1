**Trần Thị Ngọc**  
Người Thực Hiện: Trần Thị Ngọc  
Ngày cập nhật: 23/10/2017  
---------------
## Tên : Mạng Căn Bản  

### 1.Mạng là gì?  
- Là hệ thống gồm 2 hay nhiều máy tính liên kết để chia sẻ tài nguyên.    
- Được kết nối qua dây cáp,sống hồng ngoại ,vệ tinh.      
- Gồm 2 loại cơ bản:    
  + Local Area Network(còn được viết tắt là LAN)      
  + Wide Area Network(còn được viết tắt là Wan)   
  
### 2.Thành phần?  
- Mối liên kết:là phương tiện để chuyển dữ liệu từ điểm này đến điểm khác trong một mạng, bao gồm:  
  	+ Giao diện mạng: định dạng dữ liệu để truyền.    
	+ Phương tiện tuyền thông mạng: những phương tiện truyền thông giúp tin hiệu được truyền đi.    
	+ Bộ liên kết: cung cấp các điểm liên kết các phương tiện truyền thông. 
- Thiết bị chuyển mạch:các hệ thống đầu cuối thường được kết nối với  thiết bị chuyển mạch.  
- Routers:kết nối các mạng khác nhau và hỗ trợ lựa chọn con đường tốt nhất để truyền dữ liệu giữa hai mạng.  
- WLAN: Wireless LAN of WAN devices conected network devices.   

### 3.Nguồn chia sẽ và lợi ích?  
- Dữ liệu và ứng dụng:chia sẻ tập tin, phần mềm và chương trình ứng dụng.  
- Nguồn:các thiết bị đầu vào và thiết bị đầu ra.    
- Lưu trữ mạng: lưu trữ gắn trực tiếp (DAS), mạng lưu trữ đính kèm (NAS), mạng lưu trữ (SAN).  
- Các thiết bị sao lưu: cung cấp phương tiện trung tâm để lưu các tập tin từ nhiều máy tính, có khả năng lưu trữ và khắc phục sự cố .  

### 4.Ứng dụng mạng?    
- Trình duyệt wed(chrome,cốc cốc,...)  
- Ứng dụng làm việc tập thể  
- E mail( gamil,yahoo,...)  
- Chat( facebook,zalo,viber,...)  
- ...   

### 5.Đặc tính?  
- Chi phí  
- Tính bảo mật  
- Tốc độ  
- Khả năng mở rộng  
- Độ tin cậy của đường truyền trong hệ thống mạng.  
- ...  


### 6.Một số loại Topology
- **Topology của mạng là cấu trúc hình học không gian mà thực chất là cách bố trí phần tử của mạng cũng như cách nối giữa chúng với nhau.**
Thông thường mạng có 3 dạng cấu trúc là:   
	- Mạng dạng hình sao (Star Topology)  
	- Mạng dạng vòng (Ring Topology)  
	- Mạng dạng tuyến (Linear Bus Topology)  
- **Mạng dạng hình sao (Star topology):**  
	*Mạng dạng hình sao bao gồm một trung tâm và các nút thông tin. Các nút thông tin là các trạm đầu cuối, các máy tính và các thiết bị khác của mạng.* Trung tâm của mạng điều phối mọi hoạt động trong mạng với các chức năng cơ bản là:    
		-  Xác định cặp địa chỉ gửi và nhận được phép chiếm tuyến thông tin và liên lạc với nhau.  
		-  Cho phép theo dõi và xử lý sai trong quá trình trao đổi thông tin.  
		-  Thông báo các trạng thái của mạng…  
			–   **Ưu điểm:**   
				-   Mạng dạng hình sao cho tốc độ nhanh nhất  
				-   Khi cable mạng bị đứt thì thưởng chí làm mất kết nối của một máy, còn những máy khác vẫn hoạt động bình thường.  
				-    Khi có lỗi xảy ra , ta dễ dàng kiểm tra và sửa chữa  
				-    Mạng có thể được mở rộng tuỳ theo nhu cầu sử dụng của người dùng    
			–   **Nhược điểm:**     
				- Khả năng mở rộng mạng đều phụ thuộc vào khả năng của trung tâm. Khi trung tâm gặp sự cố thì toàn mạng đều ngưng hoạt động.  
				- Mạng yêu cầu nối độc lập riêng rẽ từng thiết bị ở các nút thông tin đến trung tâm.  Khoảng cách từ máy đến trung tâm rất hạn chế (100 m).  
				- Chi phí dây mạng và thiết bị trung gian tốn kém nhiều  
Nhìn chung, mạng dạng hình sao cho phép nối các máy tính vào một bộ tập trung (HUB) bằng cáp xoắn, giải pháp này cho phép nối trực tiếp máy tính với HUB không cần thông qua trục BUS, tránh được các yếu tố gây ngng trệ mạng. Gần đây, cùng với sự phát triển switching hub, mô hình này ngày càng trở nên phổ biến và chiếm đa số các mạng mới lắp.  
- **Mạng dạng vòng (Ring Topology):**  
	*Mạng dạng này, bố trí theo dạng xoay vòng, đường dây cáp được thiết kế làm thành một vòng khép kín, tín hiệu chạy quanh theo một chiều nào đó. Các nút truyền tín hiệu cho nhau mỗi thời điểm chỉ đợc một nút mà thôi. Dữ liệu truyền đi phải có kèm theo địa chỉ cụ thể của mỗi trạm tiếp nhận.*     
			– **Ưu điểm:**  
				- Mạng dạng vòng có thuận lợi là có thể nới rộng ra xa, tổng đường dây cần thiết ít hơn nên tiết kiệm được dây cable, tốc độ nhanh hơn kiểu BUS    
			– **Nhược điểm:**   
				- Nhược điểm của mạng này là tốc độ vẫn bị chậm  
				- Khi trên đường cable có sự cố thì toàn bộ mạng sẽ ngưng hoạt động  
				- Khi có sự cố rất khó kiểm tra phát hiện lỗi  
Do mạng này có nhiều nhược điểm nên trong thực tế ít được sử dụng.  
- **Mạng dạng tuyến ( BUS topology):**  
	*Theo cách bố trí hành lang các đường như hình vẽ thì máy chủ (host) cũng như tất cả các máy tính khác (workstation) hoặc các nút (node) đều được nối về với nhau trên một trục đường dây cáp chính để chuyển ti n tín hiệu.*    
	*Tất cả các nút đều sử dụng chung đường dây cáp chính này. Phía hai đầu dây cáp được bịt bởi một thiết bị gọi là terminator. Các tín hiệu và gói dữ liệu (packet) khi di chuyển lên hoặc xuống trong dây cáp đều mang theo điạ chỉ của nơi đến.*   
			– **Ưu điểm:**    
				- Loại hình mạng này dùng dây cáp ít nhất, dễ lắp đặt nên tiết kiệm được chi phí lắp đặt.    
			– **Nhược điểm:**    
				- Tuy vậy cũng có những bất lợi đó là sẽ có sự ùn tắc giao thông khi di chuyển dữ liệu với lưu lượng lớn.    
				- Khi có sự hỏng hóc ở đoạn nào đó thì rất khó phát hiện, một sự ngừng trên đường dây để sửa chữa sẽ ngừng toàn bộ hệ thống.  


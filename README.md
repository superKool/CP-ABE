# Security cloud computing using cipher text policy and attribute based encryption scheme


- Khóa được tạo ra  bởi multi authority bởi vì khóa bao gồm nhiều thuộc tính mà thuộc tính có thể thuộc nhiều địa điểm khác nhau.
(ví dụ: trong trường hợp ở trường đại học sẽ tạo được một vài khóa, ở công ty sẽ tạo được vài khóa. các khóa đó kết hợp lại sẽ tạo ra được một khóa chủ gồm nhiều thuộc tính.)
- Người sở hữu tài sản là người tạo ra dữ liệu và upload dữ liệu đó lên cloud, người sở hữu dữ liệu là những người có thể sử dụng dữ liệu đó ở trong công ty.
- Đường truyền có thể bị attacker nghe lén sau đó sửa đổi lại dữ liệu gây ra thiệt hại.
- Attacker có thể xâm nhập vào các bên liên quan rồi sau đó gửi những thông tin sai gây ra ảnh hưởng đến công ty mua bán hàng online.
(ví dụ: attacker có thể giả dạng là người của hành chính công sau đó gửi email yêu cầu công ty mua bán hàng online phải đưa cho attacker toàn bộ dữ liệu).
- Cơ chế bảo về có thể bao gồm việc khi nhận được thông tin từ một bên liên quan nào đó thì phải có cách để xác định đó có phải là từ nguồn chính thống hay là attacker giả dạng để phá hoại. 
- Các bên liên quan: 
+ Các dịch vụ hành chính công: trong lĩnh vực bán hàng, việc cấp giấy phép buôn bán,khai báo giá trị tài sản, đóng thuế phải tuân thủ đúng theo thủ tục hành chính.
(ví dụ: trong lĩnh vực bất động sản, việc xây dựng phải được nhà nước chấp thuận, các dịch vụ hành chính công có vai trò kiểm soát các hoạt động của các công ty bất động sản có đúng với quy định của pháp luật hay không.)
+ Các ngân hàng: các ngân hàng có vai trò kiểm soát nguồn tiền vay, thế chấp của các công ty bán hàng online.
+ Các dịch vụ truyền thông: Dịch vụ truyền thông có vai trò quảng cáo sản phẩm cũng như triển khai các sự kiện trên công ty.
+ Các dịch vụ vận chuyển: có vai trò vận chuyển hàng hóa đến người nhận.
+ Các dịch vụ bán lẻ như môi giới nhà đất.
+ Các dịch vụ du lịch.
+ Các công ty nguyên vật liệu.




- Bảo vệ key: trusted execution enviroment, secure enclave, sử dụng phần cứng để bảo vệ modun TPM.

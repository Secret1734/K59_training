# Cloud Computing
* Điện toán đám mây là tập hợp các tài nguyên máy tính được gộp lại các các dịch vụ cung cấp các tài nguyên đó. Cài tài nguyên và dịch vụ được đưa lên internet và các giao dịch được thực hiện thông qua web. 
* Các tài nguyên máy tính được cung cấp: bộ nhớ, máy chủ server, mạng, ứng dụng, dịch vụ
* Cloud Computing cho phép người dùng sử dụng tài nguyên máy tính một cách thuận tiện, dùng theo nhu cầu, vd: Khi cần thêm bộ nhớ, không cần mua một ổ cứng khác mà chỉ cần yêu cầu cloud cấp thêm bộ nhớ và chỉ phải trả tiền phần bộ nhớ mà mình sử dụng, từ đó giảm chi phí.
* Cloud Computing có 5 tính chất - 3 mô hình dịch vụ - 4 mô hình triển khai

## 5 tính chất cơ bản

#### On-demand seft-service: 

Tự phục vụ theo yêu cầu, người dùng tự yêu cầu với dịch vụ một số lượng tài nguyên nhất định qua mạng mà không phải đến gặp nhà cung cấp.

#### Broad netword access: 

Truy cập thông qua các chuẩn mạng

#### Resource pooling: 
Các tài nguyên do nhà cung cấp cung cấp được tự động phân chia cho người sử dụng dựa theo yêu cầu của người sử dụng.

#### Rapid Elasticity:
Khả năng cấp phát và thu hồi tài nguyên nhanh chóng.

#### Measured Service: 

Dịch vụ có thể đo đếm được, người dùng chỉ trả tiền theo lượng tài nguyên mình sử dụng.

## 3 mô hình dịch vụ

#### Software as a Service (SaaS): 

Cung cấp các **ứng dụng** trên mạng, người dùng không cần tải về máy của mình để sử dụng. VD: Gmail, Word Online.

#### Platform as a Service (PaaS): 

Cung cấp dịch vụ cho phép người sử dụng triển khai các ứng dụng của mình mà không cần quan tâm đến các **hạ tầng phần cứng và phần mềm** bên dưới như storage, memory, CPU,...Người dùng chỉ cần quan tâm tới việc triển khai, quản lý ứng dụng của mình.

#### Infrastructure as  a Service (IaaS): 

Cung cấp cho người dùng các **hạ tầng phần cứng**, người dùng sử dụng các hạ tầng phần cứng đó và triển khai các ứng dụng. Trong mô hình này, người sử dụng phải quan tâm tới các yêu cầu về phầm mềm của ứng dụng cần được triển khai. VD: Hệ điều hành, thư viện lập trình, ngôn ngữ lập trình,...  

## 4 mô hình triển khai

#### Private Cloud: 

Cloud được tạo ra bởi một tổ chức nào đó chỉ để phục vụ nội bộ trong tổ chức đó. Cloud này được sử dụng để đảm bảo tính bảo mật thông tin của tổ chức.

#### Community Cloud: 

Giống Private Cloud nhưng ở đây là một số các tổ chức liên kết với nhau và phục vụ nhóm tổ chức đó.

#### Public Cloud: 

Cloud được tạo ra nhằm phục vụ tất cả mọi đối tượng, tổ chức.

#### Hybrid Cloud: 

Cloud được tạo ra bởi sự kết hợp giữa các thành phần (private/community/public cloud) trong cùng một tổ chức. Mô hình này được sử dụng để vừa có thể đảm bảo tính bảo một dữ liệu của thông tin trong tổ chức vừa tận dụng được các tài nguyên dư thừa, làm giảm chi phí vận hành.


# Big Data 

Big Data là một mô hình trong đó cho phép lưu trữ và tính toán trên một khối lượng rất lớn dữ liệu mà không thể lưu trữ, xử lý trên một máy tính hay một server riêng lẻ.

Big Data đúng như cái tên của nó là nói về dữ liệu lớn. Nhưng trong big data, dữ liệu không chỉ lớn mà nó còn có các tính chất 5Vs sau: 

## 5Vs

#### Volume
Dữ liệu trong big data được sinh ra bởi các tổ chức rất lớn lên thường tính bằng GB hay TB.Những dữ liệu này do tuy chưa thể tìm ra được giá trị của nó nhưng sau này có thể sẽ rất hữu ích cho tổ chức đó nên cần được lưu lại. 

#### Variety

Dữ liệu trong big data rất đa dạng, không tuân theo một khuôn mẫu chung, có thể là các bảng truyền thống nhưng cũng có thể là các tín hiệu do các thiết bị gửi về không được định dạng dưới dạng bảng

#### Velocity

Dữ liệu trong big data được sinh ra với một tốc độ nhanh.
#### Variability

Bộ dữ liệu không nhất quán

#### Veracity 

Tính không chính xác của dữ liệu, điều này ảnh hưởng tới việc xử lý và phân tích dữ liệu.


## Hadoop
Do dữ liệu trong big data rất lớn nên nó phải được lưu trữ và tính toán phân tán. Một công cụ giải quyết vấn đề này chính là Hadoop.

- Hadoop là một open-source framework giúp lưu trữ, quản lý và chạy các ứng dụng Big Data. 
- Hadoop gồm 2 thành phần: 
  * Hadoop Mapreduce : Thực hiện các công việc xử lý, tính toán trên dữ liệu một cách phân tán.
  * Hadoop Distributed File System : Quản lý phân tán dữ liệu trên các máy chủ Hadoop.

# Ubiquitous Computing : Tính toán rộng khắp

* Ubiquitous Computing là một mô hình trong đó việc tính toán được xuất hiện ở mọi nơi, tại mọi thời điểm. 
* Để làm được điều đó, các thành phần của Ubiquitous Computing phải là những thiết vị có kích thước nhỏ, giá thành rẻ, có khả năng xử lý mạnh mẽ và được kết nối với nhau tuy nhiên không nhất thiết phải kết nối với internet. Các thành phần này được gắn với các vật dụng sinh hoạt hằng ngày nhằm làm cho các vật dụng đó "thông minh" hơn, cải thiện trải nghiệm người dùng, chất lượng cuộc sống.
* Giao tiếp giữa người và máy một cách tự nhiên (ví dụ: ta chỉ cần ra lệnh cho tivi chuyển kênh, tivi sẽ tự chuyển kênh theo mong muốn)
* Các công nghệ liên quan, hỗ trợ cho Ubiquitous Computing: internet, advanced middleware, operation system, mobile code, sensors, microprocessor, new I/O, giao diện người dùng, mạng, các giao thức di động,...
* Dựa trên kích thước, người ta chia các thiết bị Ubiquitous Computing thành 3 loại:
  * Tabs: các thiết bị kích cỡ rất nhỏ, cỡ cen-ti-met có thể đeo được
  * Pads: các thiết bị cỡ decimet, có thể cầm được
  * Boards: các thiết bị cỡ mét, dùng để hiển thị giao tiếp.
* Các ứng dụng của Ubiquitous bao gồm: năng lượng, quân sự, chăm sóc sức khỏe, sản xuất, logistic, mua bán hàng hóa,...

# IOT - Internet of Things

* Là mô hình trong đó các vật được kết nối với nhau thông qua internet và trở thành các đồ vật "thông minh". Các "vật" ở đây có thể là bất cứ cài gì như máy lạnh, máy giặt, ti vi, điện thoại, smarthome,...
* Các "vật" được gắn thêm các thiết bị có khả năng cảm biến, tính toán để làm vật đó trở nên thông minh.
* Các "vật" trong IOT có thể giao tiếp với các "vật" khác thông qua mạng không dây.
* IOT sử dụng các cảm biến sensors để thu thập dữ liệu.
* Các "vật" trong IOT thu thập các dữ liệu, thực hiện tính toán trên các dữ liệu đó để đưa ra một hành động hợp lý nào đó.
* Người sử dụng có thể điểu khiển các một từ xa thông qua internet.
* IOT được ứng dụng trong rất nhiều các lĩnh vực của đời sống: y tế, hành chính, giao thông vận tải,...

# So sánh IOT với các chủ đề và mối quan hệ giữa chúng

#### Mối quan hệ giữa IOT và Cloud Computing

* IOT sử dụng các sensor thu thập dữ liệu, gửi dữ liệu lên Cloud để thực hiện việc tính toán, xử lý dữ liệu và đưa ra một hành động cụ thể

#### Mối quan hệ giữa IOT và Big Data

* IOT thu thập dữ liệu, những dữ liệu này có thể còn tái sử dụng được về sau nên cần lưu trữ lại. Khi lượng dữ liệu lưu trữ quá lớn, công việc tính toán gặp khó khăn, ta phải sử dụng Big Data để lưu trữ và tính toán dữ liệu.

#### Mối quan hệ giữa IOT và Ubiquitous Computing 

* Cả 2 đều mô hình đều cho phép ẩn đi công việc tính toán, xử lý dữ liệu với người sử dụng.

* Trong Ubiquitous Computing:
  * giao tiếp là giao tiếp giữa người - máy.
  * Các vật không kết nối với internet

* Trong IOT: 
  * giao tiếp máy - máy
  * các vật được kết nối với internet

   

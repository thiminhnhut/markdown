# Sử dụng ngôn ngữ Markdown trên Github

Thực hiện: Thi Minh Nhựt - Email: thiminhnhut@gmail.com

Thời gian: Ngày 22 tháng 02 năm 2017

## Nguồn tham khảo

1. [Markdown Cheat Sheet](http://support.mashery.com/docs/customizing_your_portal/Markdown_Cheat_Sheet)

## Giới thiệu

Chúng ta có thể sử dụng ngôn ngữ đánh dấu `Markdown` để viết nội dung cho file `REAMD.md` 
hoặc các file hướng dẫn đơn giản.

## Một số lệnh cơ bản của ngôn ngữ Markdown

### Đánh dấu các tiêu đề

* Ví dụ: muốn đánh dấu các tiêu đề (như bài hướng dẫn này) chúng ta sử dụng các lệnh sau:

		# Tiêu đề cấp 1
		
		## Tiêu đề cấp 2
		
		### Tiêu đề cấp 3
		
		#### Tiêu đề cấp 4
		
		##### Tiêu đề cấp 5
		
		###### Tiêu đề cấp 6
		
* Kết quả: [Đánh dấu tiêu đề](https://github.com/thiminhnhut/markdown/blob/99120fd461ef57b6cd10550fd30ed6ef7ac4dd6e/github-markdown/examples/headers.md)

### Đoạn văn và ngắt dòng

* Bình thường khi chúng ta nhấn phím `Enter` một lần thì không tự động ngắt dòng.

	+ Ví dụ:
	
			Nội dung được tiếp nối khi nhấn phím Enter một lần
			do không tự động ngắt dòng được.
			
	+ Kết quả: [Không ngắt dòng](https://github.com/thiminhnhut/markdown/blob/9651847f58eeacdc59e0cb1d83362c7f09184370/github-markdown/examples/nolinebreak.md)
	
* Muốn ngắt dòng chúng ta kết thúc một đoạn văn bằng 2 hay nhiều dấu cách.

	+ Ví dụ:
	
			Muốn ngắt dòng chúng ta kết thúc đoạn văn bằng 2 hay nhiều dấu cách  
			rồi nhấn phím Enter.
			
	+ Kết quả: [Ngắt dòng](https://github.com/thiminhnhut/markdown/blob/ef9e23e5c3a6346000a3b67e384b63f0d8931792/github-markdown/examples/linebreak.md)

* Muốn tạo ra các đoạn văn, chúng ta nhấn phím `Enter` hai lần để tạo ra một dòng trống phân cách 
giữa các đoạn.

	+ Ví dụ:
	
			Đoạn 1: Nội dung đoạn 1.
			
			Đoạn 2: Nội dung đoạn 2.
			
	+ Kết quả: [Tạo đoạn văn](https://github.com/thiminhnhut/markdown/blob/6a5ac68a9e407b4df4fba1b22b5d25fc8df4155b/github-markdown/examples/paragraph.md)

### Định dạng các text

| Định dạng      |  Ví dụ           |  Kết quả         |
|:---------------|:-----------------|:-----------------|
| Chữ in nghiêng | `*chữ nghiêng*`  | *chữ nghiêng*    |
| Chữ in đậm     | `**chữ đậm**`    | **chữ đậm**      |
| Chữ bị gạch    | `~~chữ bị gạch~~`  | ~~chữ bị gạch~~|

### Hiển thị các ký tự đặc biệt

* Các ký tự đặc biệt: \\ \` \* \_ \{\} \[\] \(\) \# \+ \- \. \! \: \|

* Thêm dấu `\` vào trước các ký tự đặc biệt muốn hiển thị.

### Tạo danh sách

#### Danh sách không đánh số

* Sử dụng các dấu `*` hoặc `+` hoặc `-` để tạo các danh sách không đánh số.
Các dấu này có thể lồng ghép vào nhau.

* Ví dụ:

		* Nội dung A
		
		* Nội dung B
		
			+ Nội dung A1
			
			+ Nội dung B1
				
				- Nội dung A2
				
				- Nội dung B2
				
					* Nội dung A3
			
					* Nội dung B3
				
						* Nội dung A4
				
						* Nội dung B4
						

* Kết quả: [Danh sách không đánh số](https://github.com/thiminhnhut/markdown/blob/549e01cc872dcc10cedd7e566af693206c2284b1/github-markdown/examples/list-unnumber.md)

#### Danh sách đánh số

* Ví dụ:

		1. Nội dung 1

		1. Nội dung 2

		1. Nội dung 3

		1. Nội dung 4

* Kết quả: [Danh sách đánh số](https://github.com/thiminhnhut/markdown/blob/12a64fe92a3f1385b6455e37d0f35625b1f7786a/github-markdown/examples/list-number.md)

### Định dạng code

* Thụt vào đầu dòng với 4 dấu cách so với đoạn hiện hành để định dạng code.

* Ví dụ: [Định dạng code](https://github.com/thiminhnhut/markdown/blob/ccd00b375e6d4d3b60d2a12e8066860457d2a624/github-markdown/examples/code-block.md)

### Chèn hình

* Ví dụ:

		* Không hiện tên khi gê chuột vào hình:

		![](https://raw.githubusercontent.com/thiminhnhut/markdown/master/github-markdown/examples/github-logo.png)

		* Hiện tên khi gê chuột vào hình:

		![](https://raw.githubusercontent.com/thiminhnhut/markdown/master/github-markdown/examples/github-logo.png "Logo GitHub")
		
* Kết quả: [Chèn hình](https://github.com/thiminhnhut/markdown/blob/8519cec2e71adcc186bc2fbffb821892e350d059/github-markdown/examples/insert-image.md)

### Chèn bảng

* Ví dụ:

		|Canh trái |Canh giữa  |Canh phải |
		|:-------- |:---------:|---------:|
		|A         |B          |C         |
		|D         |E          |F         |
		
* Kết quả: [Chèn bảng](https://github.com/thiminhnhut/markdown/blob/7a8ecc99a6230de79c9ae091caa6e5c07cf79b69/github-markdown/examples/insert-table.md)

### Chèn đường link

* Ví dụ:

		* Chèn link trên một dòng: [Github](https://github.com/)
	
		* Tự động tạo link: link có dạng <https://github.com/> hoặc <abc@gmail.com>

* Kết quả: [Chèn link](https://github.com/thiminhnhut/markdown/blob/57a8995108449049d59fd70a4f648b4dd91a9a10/github-markdown/examples/insert-link.md)

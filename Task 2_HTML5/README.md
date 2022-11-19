# Giới thiệu
Tên đề tài: Tìm hiểu về HTML5 cơ bản  
Thời hạn: 10/11/2022-17/11/2022  
Người viết: Chu Quý Tộc
Người hướng dẫn: Nguyễn Quang Đức  

# Nội dung
[I. Tổng hợp các thẻ trong HTML?](#I)
[1.1. Basic](#1.1)
[1.2. Formatting](#1.2)
[1.3. Frames](#1.3)
[1.4. Images](#1.4)
[1.5. Audio/Video](#1.5)
[1.6. Links](#1.6)
[1.7. Lists](#1.7)
[1.8. Tables](#1.8)
[1.9. Styles and Semantics](#1.9)
[1.10. Meta info](#1.10)
[1.11. Programming](#1.11)
[II. Phân biệt sự khác nhau giữa HTML và HTML5?](#II)
[2.1. Cấu trúc](#2.1)
[2.2. Tính năng](#2.2)
[2.3. Bảng so sánh](#2.3)
[2.4. Ưu điểm](#2.4)
[2.5. Nhược điểm](#2.5)
[III. Một số web tự code](#III)




<a name = "I"></a>
## I. Tổng hợp các thẻ trong HTML?
<a name="1.1"></a>
### 1.1. Basic
|Thẻ|Mô tả chức năng|
|---|-------------------|
|`<!DOCTYPE>`|Xác định cho trình duyệt biết phiên bản HTML mà bạn đang sử dụng|
|`<html>`|Xác định một tài liệu HTML|
|`<!-- -->`|Xác định một đoạn chú thích|
|`<head>`|Xác định phần đầu của tài liệu HTML (chứa các thẻ cung cấp thông tin cho trang web)|
|`<title>`|Xác định tiêu đề của trang web|
|`<body>`|Xác định phần thân của tài liệu HTML (chứa những phần tử sẽ được hiển thị lên màn hình trình duyệt)|
|`<h1>-<h6>`|Tạo những đề mục quan trọng trong trang web|
|`<p>`|Xác định một đoạn văn bản|
|`<br>`|Chèn một ngắt xuống dòng|
|`<hr>`|Tạo một đường kẻ phân cách nằm ngang|

<a name="1.2"></a>
### 1.2. Formatting
|Thẻ|Mô tả chức năng|
|---|-------------------------|
|`<abbr>`|Định nghĩa một từ viết tắt|
|`<address>`|Xác định thông tin liên hệ của tác giả (hoặc chủ sở hữu) trang web|
|`<b>`|Xác định đoạn văn bản được in đậm|
|`<bdo>`|Điều hướng một đoạn văn bản được chỉ định|
|`<big>`|Xác định một đoạn văn bản có kích thước chữ to hơn văn bản bình thường|
|`<blockquote>`|Xác định một "đoạn trích dẫn" từ một website khác|
|`<code>`|Xác định một đoạn văn bản mang ý nghĩa là các mã lệnh|
|`<del>`|Tạo một đường kẻ ngang lên văn bản|
|`<em>`|Xác định một đoạn văn bản được định dạng kiểu chữ in nghiêng|
|`<i>`|Xác định một đoạn văn bản được định dạng kiểu chữ in nghiêng|
|`<ins>`|Tạo một đường gạch chân lên văn bản|
|`<kbd>	`|Xác định một từ (hoặc cụm từ) mang ý nghĩa là một phím hoặc tổ hợp phím|
|`<mark>`|Đánh dấu màu nền nổi bật cho văn bản|
|`<meter>`|Tạo phần tử có ý nghĩa giống như: thước đo, ổ đĩa, ....|
|`<pre>	`|Giúp cho nội dung mà bạn muốn hiển thị lên màn hình được giữ nguyên định dạng giống như trong lúc soạn thảo|
|`<progress>`|Tạo một thanh tiến trình|
|`<q>`|Xác định một câu trích dẫn ngắn|
|`<s>`|Tạo một đường kẻ ngang lên văn bản|
|`<small>`|Xác định một đoạn văn bản có kích thước chữ nhỏ hơn văn bản bình thường|
|`<strong>`|Xác định đoạn văn bản được in đậm|
|`<sub>	`|Tạo văn bản có kích thước nhỏ, nằm ở khoảng nửa dưới văn bản bình thường|
|`<sup>	`|Tạo văn bản có kích thước nhỏ, nằm ở khoảng nửa trên văn bản bình thường|
|`<time>`|Đánh dấu những phần văn bản là: thời gian, ngày tháng, ngày lễ, ....|
|`<u>`|Tạo một đường gạch chân lên văn bản|
|`<wbr>`|Ngắt bớt ký tự của một từ xuống dòng (trong trường hợp chiều rộng của phần tử không đủ để chứa hết từ đó)|

<a name="1.3"></a>
### 1.3. Frames
|Thẻ|Mô tả chức năng|
|---|------------------------|
|`<frame>`|Xác định một khung trong một bộ khung|
|`<frameset>`|Xác định một bộ khung|
|`<noframes>`|Xác định một nội dung sẽ được hiển thị khi trình duyệt không hỗ trợ thẻ <frame>|
|`<iframe>`|Nhúng một trang web khác vào trang web hiện tại|

<a name="1.4"></a>
### 1.4. Images
|Thẻ|Mô tả chức năng|
|---|--------------------|
|`<img>`|Chèn hình ảnh vào trang web|
|`<map>&<area>`|Tạo một bản đồ ảnh|
|`<figcaption>`|Tạo một tiêu đề cho nội dung được đặt bên trong phần tử `<figure>`|
|`<figure>`|Xác định một nội dung cần được tách biệt rõ ràng|

<a name="1.5"></a>
### 1.5. Audio/Video
|Thẻ|Mô tả chức năng|
|---|------------------------|
|`<audio>`|Tạo một "trình phát nhạc" cho trang web|
|`<source>`|Chỉ định tài nguyên cho trình nghe nhạc hoặc trình xem phim|
|`<track>`|Chèn một bản phụ đề vào video|
|`<video>`|Tạo một "trình xem phim" cho trang web|

<a name="1.6"></a>
### 1.6. Links
|Thẻ|Mô tả chức năng|
|---|------------------------|
|`<a>`|Tạo một liên kết đến một tài liệu nào đó (khi người dùng bấm vào liên kết thì sẽ được chuyển đến tài liệu đó)|
|`<nav>`|Xác định một tập hợp các liên kết & thường được sử dụng kết hợp với CSS để tạo một thanh menu|

<a name="1.7"></a>
### 1.7.Lists
|Thẻ|Mô tả chức năng|
|---|------------------------|
|`<ul>`|Xác định một danh sách không có thứ tự|
|`<ol>`|Xác định một danh sách có thứ tự|
|`<li>`|Xác định một "danh mục" trong danh sách|

<a name="1.8"></a>
### 1.8. Tables
|Thẻ|Mô tả chức năng|
|---|--------------------|
|`<table>`|Xác định phần tử là một cái bảng|
|`<caption>`|Tạo tiêu đề cho bảng|
|`<th>`|Xác định phần tử là một ô tiêu đề trong hàng|
|`<tr>`|Xác định phần tử là một hàng trong bảng|
|`<td>`|Xác định phần tử là một ô trong hàng|
|`<thead>`|Xác định những dòng nào thuộc "phần đầu" của bảng|
|`<tbody>`|Xác định những dòng nào thuộc "phần thân" của bảng|
|`<tfoot>`|Xác định những dòng nào thuộc "phần chân" của bảng|

<a name="1.9"></a>
### 1.9. Styles and Semantics
|Thẻ|Mô tả chức năng|
|---|------------------------|
|`<style>`|Dùng để làm thùng chứa cho các đoạn mã CSS|
|`<div>`|Nhóm các phần tử lại với nhau để tiện cho việc định dạng cũng như thiết kế bố cục của trang web|
|`<span>`|Nhóm các phần tử nội tuyến lại với nhau để tiện cho việc định dạng CSS|
|`<header>`|Xác định phần đầu của trang web|
|`<footer>`|Xác định phần chân của trang web|
|`<main>`|Xác định phần thân của trang web|
|`<dialog>`|Tạo một hộp thoại|
|`<summary>&<details>`|Tạo phần tử có dạng: "chỉ hiển thị tiêu đề còn chi tiết bị ẩn, khi bấm vào tiêu đề thì chi tiết mới hiển thị"|

<a name="1.10"></a>
### 1.10. Meta info
|Thẻ|Mô tả chức năng|
|---|------------------------|
|`<head>`|Xác định phần đầu của tài liệu HTML (chứa các thẻ cung cấp thông tin cho trang web)|
|`<meta>`|Cung cấp thêm "thông tin về trang web" cho trình duyệt và các công cụ tìm kiếm|
|`<base>`|Xác định "đường dẫn cơ sở" trong trang web và kiểu mở liên kết mặc định|

<a name="1.11"></a>
### 1.11. Programming
|Thẻ|Mô tả chức năng|
|---|------------------------|
|`<script>`|Dùng để làm thùng chứa cho các câu lệnh JavaScript|
|`<noscript>`|Xác định một nội dung HTML sẽ được hiển thị khi trình duyệt không hỗ trợ JavaScript hoặc đã tắt JavaScript|
|`<embed>`|Dùng để nhúng một "tài liệu" nào đó vào trang web|
|`<object>`|Dùng để nhúng một "tài liệu" nào đó vào trang web|

<a name="II"></a>
## II. Phân biệt sự khác nhau giữa HTML và HTML5?
<a name="2.1"></a>
## 2.1. Về cấu trúc

2.1.1. Cấu trúc cơ bản của HTML
```
<!DOCTYPE html>
<html>
    <head>
        <title>Homepage</title>
    </head>
    <body>
        <h1>Headline 1</h1>
        <p>Paragraph</p>
    </body>
</html>
```
2.1.2. Cấu trúc cơ bản của HTML5
```
<!doctype html>
<html lang="vi">
<head>
  <meta charset="utf-8">
  <title>Title</title>
  <meta name="name" content="content">
  <meta name="author" content="content">
  <link rel="stylesheet" href="/css/styles.css?v=1.0">
</head>
<body>
  <script src="/js/scripts.js"></script>
</body>
</html>
```
<a name="2.2"></a>
## 2.2. Về các tính năng

2.2.1. Các tính năng của HTML
- Là một ngôn ngữ độc lập với các nền tảng
- Không phân biệt chữ hoa, chữ thường
- Có thể thay đổi màu sắc, font chữ, cỡ chữ, ... bằng cách sử dụng CSS (Cascading Style Sheets)
- Hỗ trợ hiển thị bảng
- Xây dựng các trang web bằng cách sử dụng các thành phần, các thẻ.
- Hỗ trợ hiển thị văn bản bằng nhiều font chữ, kích thước khác nhau.
- Hỗ trợ sử dụng đồ hoạ.
- Giúp bạn tạo các link điều hướng
- Tạo nhiều cửa số trong một trang web

2.2.2. Các tính năng của HTML5
- Hỗ trợ sử dụng Local storage
- Có thêm các thẻ sematic mới: `<header>`, `<footer>`, `<article>`, `<section>`, `<nav>`, ....
- Cung cấp các điều khiển mẫu mới như: ngày, lịch, thời gian, URL, email và tìm kiếm
- Thẻ <canvas> giúp cho việc vẽ sơ đồ 2D
- Hỗ trợ CSS3
- Có các phương tiện hỗ trợ người dùng
- Có khả năng xử lý các lỗi cú pháp
- Có thể lưu toàn bộ dữ liệu mà không ảnh hưởng đến hiệu suất trang web

<a name="2.3"></a>
## 2.3. Bảng so sánh HTML và HTML5
|HTML|HTML5|
|--------|---------|
|Khai báo HTML Doctype dài dòng| Khai báo DOCTYPE trong HTML5 rất đơn giản|
|Mã hóa ký tự HTML dài hơn| Khai báo mã hóa ký tự HTML5 rất đơn giản |
| Âm thanh và video không phải là phần HTML |Âm thanh và video là một phần HTML5|
| Có thể vẽ vectơ với sự trợ giúp của các công nghệ khác như Silverlight, Flash, VML, v.v | Đồ họa vectơ là một phần của HTML5, ví dụ: canvas, SVG |
| Không thể có được Vị trí địa lý thực tế của một người đang duyệt bất kỳ trang web nào | JS Geolocation API trong HTML5 cho phép bạn xác định vị trí của người dùng đang duyệt bất kỳ trang web nào |
| HTML cung cấp bộ nhớ cục bộ thay vì cookie | Html5 sử dụng cookie để lưu trữ dữ liệu |
| Trong HTML, không thể vẽ các hình dạng cơ bản | Trong Html5, có thể vẽ các hình dạng cơ bản |
| Nó cho phép bạn chạy JavaScript trong trình duyệt | Nó cho phép bạn chạy mã JavaScript trong nền |
| Bạn có thể sử dụng HTML với tất cả các trình duyệt cũ | Bạn có thể sử dụng HTML5 với tất cả các trình duyệt mới |
| Bạn có thể sử dụng bộ nhớ cache của trình duyệt làm bộ nhớ tạm thời | Bạn có thể sử dụng ứng dụng (cơ sở dữ liệu và lưu trữ web) Cache làm bộ nhớ tạm thời |
| Web Socket không khả dụng |Bạn có thể thiết lập các kênh giao tiếp song công với một máy chủ bằng cách sử dụng Web Sockets|
| Không có quy trình xử lý các mã HTML không chính xác về mặt cấu trúc | HTML5 hỗ trợ xử lý lỗi liên tục thông qua quy trình xử lý lỗi ứng biến |
| HTML ít thân thiện với thiết bị di động hơn | HTML5 thân thiện với thiết bị di động |
| Các thuộc tính như async, charset và ping không có trong HTML | Các thuộc tính async, ping, charset và là một phần của HTML5|
| HTML không cho phép kéo và thả hiệu ứng| HTML5 cho phép kéo và thả các hiệu ứng|
|Cung cấp các thuộc tính mới như tabinex, id, tabinex, v.v.| Đây là những thuộc tính nhất định được áp dụng cho các phần tử HTML 5|

<a name="2.4"></a>
## 2.4. Các ưu điểm

2.4.1. Ưu điểm của HTML
Dễ dàng sử dụng trong việc phát triển web
Dễ dàng tạo tài liệu web
Dễ dàng điều hướng trong các trang web và giữa các trang web với nhau
Người dùng không thể lưu dữ liệu trong trình duyệt

2.4.2. Ưu điểm của HTML5
Có khả năng lưu trữ dữ liệu cũng như tạo ra các SPA
Dễ dàng tạo ra một trang web mới
Có thể sửa lỗi một cách trực tiếp
Doctype và các ký tự được đơn giản hoá
Cung cấp các phần tử như: `<details>`, `<dialog>`, `<mark>`, ...
Các biểu mẫu của thẻ input được cải thiện
Hỗ trợ local storage giúp cho việc phát triển các tính năng dễ dàng hơn mà không cần dùng bên thứ 3
Việc đánh dấu được đơn giản hoá
Hỗ trợ đồ hoạ 2D và có thể lập trình bằng javascript
Cho phép tạo từ vựng của riêng mình
Có thể tạo ra các thẻ sematic riêng
Hỗ trợ tích hợp nhiều video
Với khả năng tương thích với API đã nâng cao khẳ năng trải nghiệm người dùng.

<a name="2.5"></a>
## 2.5. Các nhược điểm

2.5.1. Nhược điểm của HTML
Không hỗ trợ tạo các các trang web động
Tính năng bảo mật kém
Khá tốn thời gian để phát triển các tính năng mới
Không tuân theo việc tiếp cận tập trung. Bạn cần chỉnh sửa trang web một các riêng biệt

2.5.2. Nhược điểm của HTML5
Yêu cầu các trình duyệt hiện đại để có thể hiểu được chúng
Có các vấn đề về quyền sử dụng truyền thông
Chưa thự sự đáp ứng được tất cả các thiết bị
Vẫn đang trong quá trình hoàn thiện và phát triển
Việc chơi game gặp khó khăn với JS
Không có một IDE nào có sẵn trong HTML5

## III. Một số web tự code
## Homepage
```
<!doctype html>
<html>
<head>
	<title>Chào mừng đến với Chu.com!</title>
      <meta charset="utf-8" />
      <meta name="description" content="This is my first task about HTML"/>
      <meta name="author" content="Chu" />
      <meta name="keyword" content="HTML basics" />
      <link rel="stylesheet" type="text/css" href="Task1_HTML.css">
</head>
<body>
	<h1 class="container">Chào mừng các bạn đến với Chu.com!<br>Website này được tạo để thực hiện task được giao!</h1>
	<hr>
	<h2 class="introduce">Giới thiệu</h2>
	<p class="introduce">
		Đền tài: Tìm hiểu về HTML, HTML5, CSS<br>
		Người thực hiện: Chu<br>
		Người hướng dẫn: Nguyễn Quang Đức<br>
		Thời gian thực hiện: 11/11/2022 - 18/11/2022
	</p>
	<hr>
	<section class="overview">
		<h2>Tổng quan</h2>
		<ol type="I">
			<li><a href="#anh" title="anh">Ảnh</a></li>
			<li><a href="#mv" title="mv">MV</a></li>
			<li><a href="#loibaihat" title="lobaihat">Lời bài hát</a></li>
			<ul>
				<li><a href="#mot">1 con vịt</a></li>
				<li><a href="#hai">2 con vịt</a></li>
				<li><a href="#ba">3 con vịt</a></li>
				<li><a href="#bon">4 con vịt</a></li>
				<li><a href="#nam">5 con vịt</a></li>
				<li><a href="#sau">6 con vịt</a></li>
				<li><a href="#bay">7 con vịt</a></li>
				<li><a href="#tam">8 con vịt</a></li>
				<li><a href="#chin">9 con vịt</a></li>
				<li><a href="#muoi">10 con vịt</a></li>
				<li><a href="#muoimot">11 con vịt</a></li>
				<li><a href="#muoihai">12 con vịt</a></li>
			</ul>
	</ol>
	</section>
	<hr>
	<section class="news">
		<img class="center" id="anh" src="aduck.png" alt="Một con vịt" title="Một con vịt" width="100px" height="auto" />
		<p id="mv">
			<iframe width="100%" height="666px" src="https://www.youtube.com/embed/7f4x5klGuvk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
		</p>
    <div class="image-news">
      <img src="/exercises/images/img_300x400.png" alt="">
    </div>

    <div class="info-news">
      <h2 id="loibaihat">Lời bài hát</h2>
      <h2 id="mot">Bài hát "1 con vịt"</h2>
        <pre>
        Một con vịt xòe ra hai cái cánh.
        Nó kêu rằng quác quác quác quạc quạc quạc.
        ...
        <a href="#" target="_blank">Chi tiết</a>
        </pre>

      <h2 id="hai">Bài hát "2 con vịt"</h2>
        <pre>
        Một con vịt xòe ra hai cái cánh.<br>
        Nó kêu rằng quác quác quác quạc quạc quạc.<br>
        ...
        <a href="#" target="_blank">Chi tiết</a>
        </pre>

        <h2 id="ba">Bài hát "3 con vịt"</h2>
        <pre>
        Một con vịt xòe ra hai cái cánh.<br>
        Nó kêu rằng quác quác quác quạc quạc quạc.<br>
        ...
        <a href="#" target="_blank">Chi tiết</a>
        </pre>

      <h2 id="bon">Bài hát "4 con vịt"</h2>
        <pre>
        Một con vịt xòe ra hai cái cánh.<br>
        Nó kêu rằng quác quác quác quạc quạc quạc.<br>
        ...
        <a href="#" target="_blank">Chi tiết</a>
        </pre>

        <h2 id="nam">Bài hát "5 con vịt"</h2>
        <pre>
        Một con vịt xòe ra hai cái cánh.<br>
        Nó kêu rằng quác quác quác quạc quạc quạc.<br>
        ...
        <a href="#" target="_blank">Chi tiết</a>
        </pre>

      <h2 id="sau">Bài hát "6 con vịt"</h2>
        <pre>
        Một con vịt xòe ra hai cái cánh.<br>
        Nó kêu rằng quác quác quác quạc quạc quạc.<br>
        ...
        <a href="#" target="_blank">Chi tiết</a>
        </pre>

        <h2 id="bay">Bài hát "7 con vịt"</h2>
        <pre>
        Một con vịt xòe ra hai cái cánh.<br>
        Nó kêu rằng quác quác quác quạc quạc quạc.<br>
        ...
        <a href="#" target="_blank">Chi tiết</a>
        </pre>

      <h2 id="tam">Bài hát "8 con vịt"</h2>
        <pre>
        Một con vịt xòe ra hai cái cánh.<br>
        Nó kêu rằng quác quác quác quạc quạc quạc.<br>
        ...
        <a href="#" target="_blank">Chi tiết</a>
        </pre>

        <h2 id="chin">Bài hát "9 con vịt"</h2>
        <pre>
        Một con vịt xòe ra hai cái cánh.<br>
        Nó kêu rằng quác quác quác quạc quạc quạc.<br>
        ...
        <a href="#" target="_blank">Chi tiết</a>
        </pre>

      <h2 id="muoi">Bài hát "10 con vịt"</h2>
        <pre>
        Một con vịt xòe ra hai cái cánh.<br>
        Nó kêu rằng quác quác quác quạc quạc quạc.<br>
        ...
        <a href="#" target="_blank">Chi tiết</a>
        </pre>

        <h2 id="muoimot">Bài hát "11 con vịt"</h2>
        <pre>
        Một con vịt xòe ra hai cái cánh.<br>
        Nó kêu rằng quác quác quác quạc quạc quạc.<br>
        ...
        <a href="#" target="_blank">Chi tiết</a>
        </pre>

      <h2 id="muoihai">Bài hát "12 con vịt"</h2>
        <pre>
        Một con vịt xòe ra hai cái cánh.<br>
        Nó kêu rằng quác quác quác quạc quạc quạc.<br>
        ...
        <a href="#" target="_blank">Chi tiết</a>
        </pre>
      </div>

      <p class="detail"><a href="./">Xem thêm</a></p>

  </section>
  <hr>
  <footer>
  	<p>&copy; Chu</p>
  <p><a href="superman.chutridung@gmail.com">superman.chutridung@gmail.com</a></p>
  </footer>
</body>
</html>
```

## Login
```
<!DOCTYPE html>
<html lang="vi">
   <head>
      <title>Chào mừng đến với Chu.com!</title>
      <meta charset="utf-8" />
      <meta name="description" content="This is my first task about HTML"/>
      <meta name="author" content="Chu" />
      <meta name="keyword" content="HTML basics" />
      <link rel="stylesheet" type="text/css" href="Task1_HTML.css">
   </head>
   <body>

      <form action="Task1_homepage">
         <div class="container">
            <h1>ĐĂNG NHẬP</h1>
            <p>Vui lòng nhập thông tin bên dưới!</p>
            <hr>
         </div>
         <div class=type>
            <label><strong>Email</strong></label>
            <input type="text" placeholder="Nhập email" name="email" required>
            <br>
            <br>
            <label><strong>Mật khẩu</strong></label>
            <input type="password" placeholder="Nhập mật khẩu" name="password" required>
            <br>
            <br>
         </div>
         <div class=login-button>
            <button type="submit">Đăng nhập</button>
         </div>
         </form>

         <br>
         <br>

         <form action="Task1_HTML_forgetpassword">
         <div class=forget-password>
            <a href="Task1_HTML_forgetpassword" target="_blank">Quên mật khẩu?</a>
         </div>
         </form>

         <br>

         <form action="Task1_HTML_signup">
         <div class="signup">
            <p>Bạn không có tài khoản đăng nhập? <span><a href="Task1_HTML_signup" tagert=_blank>Đăng ký ngay</a></span></p>
         </div>
         </form>

   </body>
</html>
```

## Sign up
```
<!DOCTYPE html>
<html lang="vi">
	<head>
		<title>Chào mừng đến với Chu.com!</title>
		<meta charset="utf-8" />
		<meta name="description" content="This is my first task about HTML"/>
		<meta name="author" content="Chu" />
		<meta name="keyword" content="HTML basics" />
		<link rel="stylesheet" type="text/css" href="Task1_HTML.css">

	</head>
	<body>
		<form action="Task1_HTML_homepage">
			<div class="container">
				<h1>ĐĂNG KÝ</h1>
				<p>Vui lòng nhập thông tin bên dưới!</p>
				<hr>
			</div>
			<div class="type">
				<label><strong>Email</strong></label>
				<input type="text" placeholder="Nhập email" name="email" required>
				<br>
				<br>
				<label><strong>Mật khẩu</strong></label>
				<input type="password" placeholder="Nhập mật khẩu" name="password">
				<br>
				<br>
				<label><strong>Nhập lại mật khẩu</strong></label>
				<input type="password" placeholder="Nhập lại mật khẩu" name="password-repeat">
				<br>
				<br>
			</div>
			<div class ="signup-button">
				<button type="submit">Đăng ký</button>
			</div>
		</form>
	</body>
</html>
```

## Forget Password
```
<!DOCTYPE html>
<html>
<head>
	 <title>Chào mừng đến với Chu.com!</title>
      <meta charset="utf-8" />
      <meta name="description" content="This is my first task about HTML"/>
      <meta name="author" content="Chu" />
      <meta name="keyword" content="HTML basics" />
      <link rel="stylesheet" type="text/css" href="Task1_HTML.css">
</head>
<body>
	<form action="#">
		<div class="container">
			<h1>Quên mật khẩu?</h1>
			<hr>
		</div>
		<div class="type">
			<label><strong>Email</strong></label>
			<input type="text" placeholder="Nhập email đã đăng ký" name="email" required>
		</div>
		<br>
		<br>
		<div class="confirm-button">
			<button type="submit">Xác nhận</button>
		</div>
	</form>
</body>
</html>
```

### CSS
```

body {
   font-family: 'Noto Sans JP', sans-serif;
 }

h1, label{
   color: DodgerBlue;
 }

 .container {
   text-align: center;
   padding-top: 20px ;
 }
.introduce {
   text-align: center;
   font-family: monospace;
}
.center {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 30%;
}
.type {
   padding-left: 10px;
   border: none;
   width:95%;
   resize: vertical;
   display: inline-block;
   border:0;
}

input[type=text], input[type=password] {
   width: 100%;
   margin: 5px 0 5px 0;
   display: block;
   border: none;
   width:100%;
   resize: vertical;
   padding:15px;
   border:none;
   box-shadow:4px 4px 10px rgba(0,0,0,0.2);
 }


.login-button {
   text-align-last: center;
 }
 
.signup-button {
   text-align-last: center;
 }
 .confirm-button {
   text-align-last: center;
 }
button {
   background-color: #4CAF50;
   color: white;
   padding: 15px 20px;
   margin: auto;
   border: none;
   cursor: pointer;
   width: 10%;
   opacity: 100;
 }

.forget-password {
   text-align-last: center;
 }
 .signup {
   text-align-last: center;
 }

```











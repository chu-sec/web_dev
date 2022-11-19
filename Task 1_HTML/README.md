# Giới thiệu
Tên đề tài: Tìm hiểu về HTML cơ bản  
Thời hạn: 10/11/2022-17/11/2022  
Người viết: Chu Quý Tộc
Người hướng dẫn: Nguyễn Quang Đức  

# Nội dung
[I. HTML là gì?](#I)
[II. HTML được xử lý như thế nào?](#II)
[III. Vai trò của HTML?](#III)
[IV. Các thẻ và thuộc tính phổ biến trong HTML?](#IV)
[V. Subtask](#V)

<a name = "I"></a>
## I. HTML là gì?
- HTML (Hyper Text Markup Language) là ngôn ngữ đánh dấu siêu văn bản dùng để tạo giao diện một trang web, trên một website có thể chưa nhiều trang, mỗi trang là một tập tin HTML.  
- Một tập tin HTML được hình thành bởi các phần tử HTML (HTML elements) được quy định bằng các tag (thẻ), các thẻ có cấu tạo `<tagname>` và thường sẽ đi theo cặp bao gồm thẻ mở và thẻ đóng, ví dụ `<h1></h1>`.`<p></p>`, `<strong></strong>`, `<u></u>`, `<i></i>`. Tuy nhiên có một số tag đặc biệt sẽ không có thẻ đóng ví dụ như `<br>`, `<img>`, `<source>`, `<meta>`, `<input>`.  
- Một tập tin HTML được lưu dưới dạng đuôi mở rộng là `.html` hoặc `.htm`.

<a name = "II"></a>
## II. HTML được xử lý như thế nào?
Khi một tập tin HTML được hình thành, trình duyệt sẽ đóng vai trò đọc hiểu nội dung HTML đó và xử lý.

<a name = "III"></a>
## III. Vai trò của HTML?
- HTML mô tả cấu trúc của một trang web.
- Các phần tử HTML cho trình duyệt biết cách hiển thị nội dung.

<a name = "IV"></a>
## IV. Các thẻ và thuộc tính phổ biến trong HTML?
### Cấu trúc một đoạn HTML
```
<!DOCTYPE html>
<html>
<head>
        <title>Title</title>
	<meta charset="utf-8">
	<meta name="description" content="Desciptions">
	<meta name="author" content="Chu">
</head>
<body>
	<p>Contents</p>
</body>
</html>
```
Trong đó:
- Khai báo `<! DOCTYPE html>` xác định rằng tài liệu này là tài liệu HTML5.
- Phần tử `<html>` là phần tử gốc của trang HTML.
- Phần tử `<head>` chứa thông tin meta về trang HTML.
- Phần tử `<meta>` cung cấp thông tin về trang web cho công cụ tìm kiếm. Những thông tin đó thường gồm: tiêu đề, từ khóa chính, tóm tắt nội dung, ngôn ngữ chính được sử dụng...
- Phần tử `<title>` chỉ định tiêu đề cho trang HTML (được hiển thị trong thanh tiêu đề của trình duyệt hoặc trong tab của trang).
- Phần tử `<body>` xác định nội dung của tài liệu và là vùng chứa cho tất cả nội dung hiển thị, chẳng hạn như tiêu đề, đoạn văn, hình ảnh, siêu liên kết, bảng, danh sách, v.v.
- Phần tử `<p>` xác định một đoạn văn.

Với một cấu trúc HTML như vậy, chúng ta cần phải khai báo tập tin html trước tiên. Tiếp theo là thẻ mở `<html>` đi cùng với thẻ đóng `</html>` của nó, những thứ bên trong hai thẻ đó là nội dung liên quan đến trang web. Nội dung này được chia làm hai phần gồm một phần `<head></head>` và một phần `<body></body>`.

Ở phần  `<head></head>` chứa các thẻ khai báo thôn tin cho trang web như tiêu đề, từ khóa chính, ngôn ngữ chính được sử dụng...Những nội dung bên trong này sẽ không hiển thị trên trang web mà nó giúp cho công cụ tìm kiếm xử lý chúng.
Thẻ `<title>Title</title>` ở đây cho biết tiêu đề trang web được hiển thị là `Title`.
Thẻ `<meta charset="utf-8">` định nghĩa dạng mã hóa phù hợp với các tập tin HTML.
Thẻ `<meta name="description" content="Desciptions">` định nghĩa mô tả cho trang web.
Thẻ `<meta name="author" content="Chu">` cho biết tên tác giả là `Chu`.

Ở phần `<body></body>` sẽ chứa tất cả nội dung sẽ được hiển thị trên trang web.
Ở phía trên ta chỉ giới thiệu một thẻ là `<p></p>` nhưng trong thực tế có rất nhiều thẻ khác được dùng trong này. Ví dụ:
- `<h1></h1>` cho đến `<h6></h6>`
- `<hr>` chèn một đường thẳng phân cách nằm ngang cho dễ nhìn
- `<br>` ngắt dòng
- `<strong></strong>` in đậm văn bản
- `<i></i>` in nghiêng
- `<u></u>` gạch chân
- `<strike></strike>` gạch ngang
Ngoài ra còn có các thẻ mà chúng ta dùng để tạo một danh sách có sắp xếp hoặc một danh sách không có sắp xếp hoặc một danh sách có mô tả.
Cấu trúc một danh sách có sắp xếp:
```
<ol type="I">	
	<li>Một</li>
	<li>Hai</li>
</ol>
```
Ở giá trị trong type `<ol type="I">` ta có thể thay bằng `i, a, A, 1` nếu không có giá trị type đó thì mặc định được sắp xếp theo số thự tự `1, 2, 3 ...`
Cấu trúc một danh sách không sắp xếp:
```
<ul>
	<li>Một</li>
	<li>Hai</li>
	<li>Ba</li>
</ul>
```
Ở danh sách này sẽ hiển thị kí hiệu khác, giống nhau ở mỗi dòng trong danh sách thay vì kí tự chữ cái hoặc số như danh sách có sắp xếp.
Cấu trúc một danh sách có mô tả:
```
<dl>
    <dt>WordPress</dt>
    <dd>Mã nguồn mở</dd>
    <dt>HTML</dt>
    <dd>Ngôn ngữ đánh dấu văn bản</dd>
</dl>
```
Danh sách này sẽ hiển thị tiêu đề và mô tả cho tiêu đề đó.


Một thẻ nữa cũng rất phổ biến trong HTML đó là thẻ `<a></a>`. Thẻ này dùng để tạo một liên kết điều hướng tới  một tập tin HTML khác. Cấu trúc của thẻ này là:
`<a href="Filename.html" title="Titlename" target="_blank">Contents</a>`
Thẻ này đi kèm các thuộc tính `href`, `title`, `target`... Thuộc tính `href` sẽ tạo liên kết điều hướng đến tập tin HTML mà chúng ta muốn hoặc nếu không muốn thì chúng ta viết `href=#`. Thuộc tính `title` dùng để khai báo tiêu đề cho thẻ đang chứa nó. Thuộc tính `target` dùng để xác định xem chúng ta muốn mở liên kết đến 1 trang khác bằng `_blank` hoặc mở liên kết tại trang web hiện tại bằng `_self`.

Việc chèn hình ảnh, video, audio khiên trang web trở nên sinh động hơn là điều cần thiết. 
- Để chèn được hình ảnh vào trang web ta sử dụng cấu trúc:
` <img src="Image.png" alt="ABC" title="XYZ" width="500px" height="auto">`
Thẻ `<img>` này dùng để chèn hình ảnh, với `src=""` cho biết nguồn hình ảnh được chọn để tải, ở đây ta có thể dùng một nguồn có sẵn trên web hoặc ta dùng một nguồn trên internet cũng được. Thuộc tính `alt=""` dùng để hiển thị thay thế khi mà ảnh của chúng ta không thể hiển thị được. Thuộc tính `title=""` để hiển thị tiêu đề cho ảnh đó. Thuộc tính `width=""` và `height=""` dùng để định dạng kích thước cho ảnh.
- Để chèn video vào trang web ta sử dụng cấu trúc:
```
<video width="320px" height="auto" controls>
	<source src="Video.mp4" type="video/mp4">
	Trình duyệt của bạn không hỗ trợ HTML5.
</video>
```
Thẻ `<video></video>` dùng để chèn video vào trang web. Trong đó, thuộc tính `width` và `height` dùng để định dạng kích thước video. Thuộc tính `controls` dùng để thêm các nút thao tác cơ bản vào video đó. Thuộc tính `<source>` chỉ cho ta biết video nào được chèn vào, ta có thể lấy sẵn trên máy hoặc trên Youtube. Thuộc tính `type=""` để định dạng loại video.
- Để chèn audio vào trang web ta sử dụng cấu trúc:
```
<audio>
	<source src="http://www.w3schools.com/tags/horse.mp3" type="audio/mp3">
</audio>
```
Thẻ `<audio></audio>` dùng để chèn audio. Trong đó. Trong đó thuộc tính `<source>` chỉ cho ta biết audio nào được chèn vào, ta có thể lấy sẵn trên máy hoặc trên internet. Thuộc tính `type=""` định dạng loại audio.
- Để chèn một web khác vào trang web ta dùng cấu trúc:
```
<iframe src="https://www.google.com/" width="500px" height="auto" scrolling="auto" name="name"></iframe>
```
Thẻ `<iframe></iframe>` dùng để chèn web. Trong đó, thuộc tính `src=""` cho biết web nào ta muốn chèn vào. Thuộc tính `width` và `height` định dạng kích thước web đó. Thuộc tính `scrolling=""` cho phép cuộn trang hay không. Thuộc tính `name=""` dùng để đặt tên cho web đó.

Một loại mà chúng ta hay gặp trong các web đó là kiểu nhập liệu.
Để tạo một form nhập liệu ta sử dụng cấu trúc:
```
<form action="Filename.html" method="post" name="login">
	Username: <input type="text" name="username"> <br>
	Password: <input type="password" name="password"><br>
	<input type="submit" value="Login" name="submit">
</form>
```
Thẻ `<form></form>` dùng để tạo form. Trong đó, thuộc tính `action=""` thực hiện một hành động mà tương tác đến tập tin có tên đó. Thuộc tính `method=""` chỉ phương thức được sử dụng, ta có thể sử dụng phương thức khác ở đó, ví dụ: `GET` tùy vào mục đích sử dụng. Thuộc tính `name=""` cho biết tên của form đó. 
Bên trong thẻ `<form></form>` chứa các thành phần, chúng được khai báo với thẻ `<input>` với các thuộc tính `type`, `value`, `name`. Với thuộc tính `type=""` ta có thể để dạng `text`, `password`, `submit`, `range`, `date` tùy vào mục đích sử dụng. Thuộc tính `value=""` hiển thị đoạn text trên nút. Thuộc tính `name=""` là tên của thẻ tương ứng.

Ngoài ra còn có thẻ `<div></div>` dùng để nhóm các phần tử HTML lại với nhau cho tiện quản lý.

<a name="V"></a>
## Subtask
### Một chiếc web nho nhỏ sử dụng kiến thức đã học được
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

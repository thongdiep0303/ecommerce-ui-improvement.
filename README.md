
# E-commerce UI Improvement

## Bài tập cá nhân Buổi 1 & Buổi 2
**Môn học:** Phát triển ứng dụng WEB/TMĐT

## 1. Giới thiệu

Dự án cải tiến giao diện hiển thị thẻ sản phẩm trên website thương mại điện tử, tập trung làm nổi bật giá bán, giá gốc và tỷ lệ giảm giá, đồng thời cải thiện khả năng hiển thị trên các thiết bị có kích thước màn hình khác nhau.

Ở Buổi 1, em đã xây dựng giao diện danh sách sản phẩm cơ bản bằng HTML5 và CSS3.

Sang Buổi 2, em tiếp tục hoàn thiện cấu trúc HTML5, tách CSS thành tệp riêng và thực hành CSS Selector, Box Model, Flexbox, CSS Grid, hiệu ứng Hover/Focus và Responsive.

Dự án kế thừa mã nguồn Buổi 1, không xây dựng lại website từ đầu.

## 2. Website tham khảo

- Tên website: Shopee / Tiki
- Khu vực khảo sát: Danh mục sản phẩm và Trang chủ
- Khu vực lựa chọn cải tiến: Danh sách sản phẩm và thẻ thông tin sản phẩm

Mục tiêu cải tiến là giúp thông tin giá và khuyến mãi dễ nhận biết, đồng thời tổ chức các thẻ sản phẩm thành bố cục nhất quán.

## 3. Chức năng và giao diện

Website hiện có bốn sản phẩm mẫu:
- Tai nghe Bluetooth
- Bàn phím cơ không dây
- Chuột công thái học
- Giá đỡ laptop

Các thành phần giao diện:
- Hiển thị danh sách sản phẩm dạng lưới bằng CSS Grid.
- Hiển thị hình ảnh, tên sản phẩm và thông tin giá.
- Làm nổi bật giá khuyến mãi bằng màu đỏ.
- Hiển thị giá gốc có đường gạch ngang.
- Hiển thị nhãn tỷ lệ giảm giá.
- Có nút "Thêm vào giỏ" với hiệu ứng Hover và Focus.

Website hiện là giao diện tĩnh. Nút "Thêm vào giỏ" chưa được tích hợp chức năng xử lý bằng JavaScript.

### Responsive

Bố cục được điều chỉnh bằng CSS Media Queries:
- Màn hình lớn trên 992px: 4 cột.
- Màn hình từ trên 420px đến 992px: 2 cột.
- Màn hình tối đa 420px: 1 cột.

## 4. Công nghệ và kiến thức đã thực hành

### HTML5
- Sử dụng các phần tử header, main, section và article.
- Tổ chức thứ bậc tiêu đề h1, h2 và h3.
- Sử dụng thuộc tính alt cho hình ảnh.
- Sử dụng phần tử del cho giá gốc.
- Sử dụng button cho nút thao tác.

### CSS3
- CSS Selector: element, class và descendant selector.
- CSS Box Model: margin, padding, border, border-radius.
- Flexbox: display flex, justify-content, align-items và gap.
- CSS Grid: display grid, grid-template-columns, repeat và gap.
- Media Queries để xây dựng bố cục Responsive.
- Hiệu ứng hover, transition và focus-visible.

Website sử dụng HTML5 và CSS3 thuần, không sử dụng Bootstrap hoặc Tailwind CSS.

## 5. Cách chạy website

### Cách 1: Chạy trực tiếp bằng GitHub Pages

Truy cập:

https://thongdiep0303.github.io/ecommerce-ui-improvement./

### Cách 2: Chạy trên máy tính

1. Tải repository về máy.
2. Giữ nguyên cấu trúc thư mục.
3. Mở file index.html bằng trình duyệt Google Chrome.

File HTML liên kết CSS thông qua:

```html
<link rel="stylesheet" href="css/style.css">
```

### Cấu trúc thư mục

```text
ecommerce-ui-improvement./
├── AI_USAGE.md
├── README.md
├── css/
│   └── style.css
└── index.html
```

## 6. Cải tiến đã thực hiện

### Buổi 1 – Xây dựng giao diện ban đầu

- Tạo danh sách bốn sản phẩm bằng HTML/CSS.
- Làm nổi bật giá khuyến mãi bằng màu đỏ.
- Hiển thị giá gốc và nhãn giảm giá.
- Bo góc thẻ sản phẩm.
- Sử dụng CSS Grid và Media Query cho bố cục.

### Buổi 2 – Hoàn thiện HTML5 và CSS3

**Cấu trúc HTML5**
- Bổ sung tiêu đề khu vực danh sách sản phẩm.
- Điều chỉnh thứ bậc tiêu đề h1, h2 và h3.
- Cải thiện cách sử dụng các phần tử có ngữ nghĩa.

**Tổ chức CSS**
- Tách CSS khỏi file index.html.
- Tạo và liên kết file css/style.css.

**CSS Selector và Box Model**
- Điều chỉnh border thành 2px solid #91b5e8.
- Điều chỉnh border-radius của thẻ thành 16px.
- Tăng padding khu vực thông tin sản phẩm lên 24px trên màn hình lớn.
- Điều chỉnh margin-bottom của tên sản phẩm thành 18px.
- Thực hành descendant selector cho nút thao tác.

**Flexbox**
- Thử nghiệm cách căn chỉnh giá bán và giá gốc.
- Sử dụng justify-content, align-items và gap.

**CSS Grid**
- Thử nghiệm bố cục hai cột và ba cột.
- Lựa chọn duy trì bốn cột trên màn hình máy tính lớn.

**Hover và Focus**
- Bổ sung bóng đổ khi hover vào nút Thêm vào giỏ.
- Sử dụng transition để tạo chuyển đổi nhẹ.
- Sử dụng focus-visible để hiển thị đường viền màu cam khi điều hướng bằng bàn phím.

**Responsive**
- Phát hiện hạn chế về không gian hiển thị khi sử dụng hai cột trên điện thoại.
- Bổ sung Media Query max-width: 420px.
- Điều chỉnh danh sách thành một cột trên màn hình nhỏ.

## 7. Kiểm thử giao diện

Công cụ kiểm thử: Google Chrome và Chrome DevTools.

### Kết quả kiểm tra Responsive

| Chiều rộng | Bố cục | Kết quả |
|---|---|---|
| 1366px | 4 cột | Đạt |
| 768px | 2 cột | Đạt |
| 390px | 1 cột | Đạt |

Tại chiều rộng 390px, kết quả Console ghi nhận:
- viewport = 390
- gridColumns = 366px
- mobileRuleActive = true

Kết quả xác nhận Media Query dành cho màn hình nhỏ đã được kích hoạt và CSS Grid chuyển sang bố cục một cột.

### Kiểm tra tương tác

- Trạng thái bình thường: Nút màu xanh, chữ trắng.
- Hover: Nút chuyển sang xanh đậm.
- Focus-visible: Xuất hiện đường viền màu cam khi nhận focus bằng bàn phím.

Các trạng thái đã được kiểm tra trực tiếp trên trình duyệt.

## 8. Hỗ trợ từ AI

### Buổi 1

Sử dụng Gemini để tham khảo cách xây dựng cấu trúc HTML/CSS, bố cục CSS Grid và Media Queries.

Đã kiểm tra và điều chỉnh một số yếu tố giao diện như màu sắc, khoảng cách và độ bo góc.

### Buổi 2

Sử dụng ChatGPT để hỗ trợ:
- Phân tích cấu trúc HTML5.
- Giải thích CSS Selector và Box Model.
- Thực hành Flexbox và CSS Grid.
- Đề xuất cải thiện hiệu ứng Hover/Focus.
- Hướng dẫn kiểm tra Responsive bằng Chrome DevTools.

Các đề xuất được đối chiếu với mã nguồn và kết quả hiển thị thực tế trước khi sử dụng.

Nội dung chi tiết được ghi trong AI_USAGE.md.

## 9. Định hướng phát triển

Website hiện chỉ tập trung vào giao diện tĩnh bằng HTML5/CSS3.

Trong các buổi tiếp theo, dự án có thể được phát triển thêm bằng JavaScript nhằm hỗ trợ:
- Tìm kiếm sản phẩm.
- Lọc danh mục.
- Sắp xếp sản phẩm theo giá.
- Thêm sản phẩm vào giỏ hàng.

## 10. Đường dẫn dự án

**GitHub Repository:**
https://github.com/thongdiep0303/ecommerce-ui-improvement.

**GitHub Pages:**
https://thongdiep0303.github.io/ecommerce-ui-improvement./

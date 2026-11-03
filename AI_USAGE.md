
# AI Usage Log

## PHẦN I. SỬ DỤNG AI TRONG BÀI TẬP BUỔI 1

### 1. Công cụ AI
Gemini

### 2. Mục đích sử dụng
Hỗ trợ đề xuất cấu trúc mã nguồn HTML5/CSS3 chuẩn responsive cho thành phần Product Card.

### 3. Prompt đã sử dụng
Tôi đang thực hiện bài tập phát triển giao diện website thương mại điện tử bằng HTML5 và CSS3. Hãy tạo một trang giao diện thương mại điện tử có tiêu đề, khu vực tối thiểu 4 sản phẩm mẫu chuẩn responsive.

### 4. Kết quả AI đề xuất
AI cung cấp cấu trúc thẻ `article`, sử dụng thuộc tính `grid-template-columns` và media query co giãn theo màn hình.

### 5. Kiểm tra và điều chỉnh
Đã kiểm tra giao diện qua Chrome DevTools ở kích thước 375px (iPhone) và điều chỉnh lại font chữ, bo góc thẻ và màu sắc phù hợp.

### 6. Phần tôi hiểu và có thể giải thích
Hiểu rõ cách hoạt động của CSS Grid (`repeat(4, 1fr)`), cách dùng `position: absolute` để đè nhãn giảm giá lên góc ảnh và cách dùng Media Query `@media (max-width: 576px)`.

---

## PHẦN II. SỬ DỤNG AI TRONG BÀI TẬP BUỔI 2

### 1. Công cụ AI

ChatGPT

### 2. Mục đích sử dụng

Tiếp tục hoàn thiện giao diện website thương mại điện tử từ Buổi 1 thông qua việc thực hành các kiến thức HTML5 và CSS3.

ChatGPT được sử dụng để hỗ trợ:
- Rà soát cấu trúc HTML5 và xác định nội dung cần cải thiện.
- Hướng dẫn tách CSS thành tệp riêng.
- Giải thích CSS Selector và Box Model.
- Thực hành căn chỉnh các thành phần bằng Flexbox.
- Thử nghiệm bố cục danh sách sản phẩm bằng CSS Grid.
- Bổ sung hiệu ứng hover và focus-visible.
- Hướng dẫn kiểm tra và điều chỉnh Responsive bằng Chrome DevTools.

### 3. Các prompt tiêu biểu đã sử dụng

#### Prompt 1 – Kiểm tra cấu trúc HTML5

Tôi đang học HTML5 và muốn cải thiện cấu trúc HTML của bài tập Buổi 1.

Hãy giúp tôi kiểm tra các phần tử HTML đang sử dụng, thứ bậc tiêu đề h1, h2, h3, thuộc tính alt của hình ảnh và các phần tử có ngữ nghĩa.

Phân biệt lỗi cần sửa và đề xuất cải thiện. Không viết lại toàn bộ website.

**Kết quả AI đề xuất:**

ChatGPT đề xuất bổ sung tiêu đề cho khu vực danh sách sản phẩm, điều chỉnh thứ bậc tiêu đề và cải thiện ngữ nghĩa của một số phần tử HTML.

Các phần tử đã được sử dụng phù hợp như header, main, section và article tiếp tục được giữ nguyên.

#### Prompt 2 – Thực hành CSS Selector và Box Model

Tôi muốn thực hành CSS Selector và Box Model trên thẻ sản phẩm trong website thương mại điện tử.

Hãy hướng dẫn cách sử dụng class selector, descendant selector, margin, padding, border và border-radius.

Giải thích tác dụng của từng thuộc tính và chỉ đề xuất những điều chỉnh CSS cần thiết.

**Kết quả AI đề xuất:**

ChatGPT đề xuất tăng khoảng đệm nội dung, điều chỉnh đường viền và độ bo góc của thẻ sản phẩm.

Các thuộc tính được áp dụng gồm:
- `border: 2px solid #91b5e8`
- `border-radius: 16px`
- `padding: 24px`
- `margin-bottom: 18px`

**Kiểm tra và điều chỉnh:**

Sau lần điều chỉnh đầu tiên, sự khác biệt giữa giao diện trước và sau chưa rõ ràng.

Em tiếp tục thử tăng padding, điều chỉnh margin và thay đổi màu đường viền để làm rõ hơn tác động của Box Model.

Sau đó, em đối chiếu hai phiên bản giao diện để đánh giá sự thay đổi về khoảng cách và hình thức của thẻ sản phẩm.

#### Prompt 3 – Thực hành Flexbox và CSS Grid

Tôi muốn thực hành Flexbox trên khu vực hiển thị giá sản phẩm và CSS Grid trên danh sách sản phẩm hiện có.

Hãy giải thích cách sử dụng display flex, justify-content, align-items, gap và grid-template-columns.

Hướng dẫn thử nghiệm các cách căn chỉnh và bố cục mà không thay đổi nội dung HTML.

**Kết quả AI đề xuất:**

Đối với Flexbox, ChatGPT đề xuất sử dụng `justify-content: space-between`, `align-items: center` và `gap` để điều chỉnh vị trí của giá bán hiện tại và giá gốc.

Đối với CSS Grid, ChatGPT hướng dẫn thử nghiệm hai cột và ba cột để quan sát tác động của số lượng cột đến cách sắp xếp sản phẩm.

**Kiểm tra và điều chỉnh:**

Em đã thực hành và chụp ảnh giao diện hai cột và ba cột.

Qua so sánh, bố cục hai cột tạo không gian rộng hơn cho mỗi thẻ nhưng tăng chiều cao danh sách, trong khi bố cục ba cột khiến sản phẩm thứ tư nằm riêng ở hàng tiếp theo.

Em lựa chọn duy trì bố cục bốn cột trên màn hình máy tính lớn.

#### Prompt 4 – Kiểm tra và cải thiện Responsive

Tôi đã hoàn thiện danh sách sản phẩm bằng HTML5 và CSS3.

Khi kiểm tra trên màn hình điện thoại, danh sách hiển thị hai cột nên mỗi thẻ có không gian tương đối hẹp.

Hãy giúp tôi xác định nguyên nhân, đề xuất cách sửa ít thay đổi nhất và hướng dẫn kiểm tra kết quả bằng Chrome DevTools.

**Kết quả AI đề xuất:**

ChatGPT đề xuất bổ sung Media Query:

```css
@media (max-width: 420px) {
    .product-grid {
        grid-template-columns: 1fr;
    }
}
```

Quy tắc này giúp chuyển danh sách sản phẩm thành một cột khi chiều rộng màn hình không vượt quá 420px.

### 4. Kiểm tra kết quả bằng Chrome DevTools

Sau khi bổ sung Media Query, em mở website bằng Google Chrome và sử dụng DevTools để kiểm tra giao diện.

Ở chiều rộng 390px, kết quả Console ghi nhận:

- `viewport = 390`
- `gridColumns = 366px`
- `mobileRuleActive = true`

Các giá trị trên xác nhận Media Query đã được kích hoạt và CSS Grid chuyển thành bố cục một cột.

Em tiếp tục quan sát giao diện ở chiều rộng 768px và 1366px.

Kết quả:
- 1366px: Danh sách hiển thị 4 cột.
- 768px: Danh sách hiển thị 2 cột.
- 390px: Danh sách hiển thị 1 cột.

Ngoài ra, em kiểm tra hiệu ứng hover bằng chuột và trạng thái focus-visible bằng phím Tab.

Kết quả quan sát cho thấy nút "Thêm vào giỏ" chuyển sang xanh đậm khi hover và xuất hiện đường viền cam khi nhận focus-visible.

### 5. Đề xuất AI đã được kiểm tra và điều chỉnh

Một đề xuất tiêu biểu được em kiểm tra là thay đổi bố cục CSS Grid trên điện thoại từ hai cột sang một cột.

Ban đầu, website sử dụng quy tắc:

```css
@media (max-width: 576px) {
    .product-grid {
        grid-template-columns: repeat(2, minmax(0, 1fr));
    }
}
```

Khi quan sát trên màn hình điện thoại, em nhận thấy bố cục hai cột giới hạn không gian hiển thị của tên sản phẩm và thông tin giá.

Sau khi tham khảo đề xuất từ ChatGPT, em bổ sung Media Query tại 420px để chuyển sang bố cục một cột.

Trong lần kiểm tra đầu tiên, giao diện vẫn hiển thị hai cột. Em tiếp tục đối chiếu mã CSS và sử dụng Chrome DevTools để kiểm tra trạng thái Media Query.

Kết quả kiểm tra sau đó xác nhận bố cục một cột đã hoạt động tại chiều rộng 390px.

Việc kiểm tra này giúp em nhận biết rằng mã CSS cần được xác minh trên trình duyệt thay vì chỉ dựa vào kết quả dự kiến.

### 6. Phần tôi hiểu và có thể giải thích

Sau khi hoàn thành Buổi 2, em có thể giải thích:

- Vai trò của các phần tử HTML5 có ngữ nghĩa.
- Sự khác nhau giữa margin và padding trong CSS Box Model.
- Cách sử dụng class selector và descendant selector.
- Cách Flexbox căn chỉnh các thành phần theo trục chính và trục vuông góc.
- Cách CSS Grid tổ chức danh sách sản phẩm theo hàng và cột.
- Vai trò của Media Query trong thiết kế Responsive.
- Sự khác biệt giữa hover và focus-visible.
- Cách sử dụng Chrome DevTools để kiểm tra CSS.

### 7. Kết luận

AI hỗ trợ quá trình tìm hiểu kiến thức, phân tích mã nguồn và đề xuất giải pháp kỹ thuật. Tuy nhiên, việc áp dụng cần dựa trên yêu cầu thực tế của bài tập và được kiểm tra trên trình duyệt.

Thông qua việc đối chiếu mã nguồn, thử nghiệm các phương án CSS và kiểm tra kết quả bằng Chrome DevTools, em hiểu rõ hơn cách HTML5 và CSS3 hoạt động, đồng thời rèn luyện khả năng tự phát hiện và điều chỉnh vấn đề trong quá trình phát triển giao diện website.

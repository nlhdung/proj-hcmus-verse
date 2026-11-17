# Xóm Ú · HCMUS Verse

Khuôn viên Trường Đại học Khoa học Tự nhiên, ĐHQG-HCM (cơ sở Linh Trung) dựng thành thế giới 3D để học lập trình. Sinh viên có thể:
- đi dạo quanh trường, gặp và trò chuyện với các bạn đang chơi cùng lúc;
- vào phòng học, bật màn chiếu xem video bài giảng;
- làm bài tập C++ và được chấm tự động;
- đọc đề thi cũ của các khoa và hỏi trợ lý giải đề ngay trong game.

Chơi ngay trên trình duyệt, hoặc cài ứng dụng Android. Repo này chỉ chứa **bản phát hành** để dùng: link chơi, link tải và ghi chú cập nhật. Không có mã nguồn.

## Chơi trên web

**https://ú.llms.vn**

Trình duyệt không mở được tên miền có dấu thì dùng https://xn--rda.llms.vn.

- **Máy tính:** Chrome, Edge hoặc Firefox bản mới, card đồ hoạ hỗ trợ WebGL 2.
- **Điện thoại, máy tính bảng:**
  - Safari (iPhone, iPad) hoặc Chrome (Android).
  - Có điều khiển cảm ứng; nên xoay ngang máy.
  - Điện thoại Android cài được ứng dụng (mục dưới).
- **Lần đầu mở:**
  - tải khoảng 270 MB (qua mạng được nén còn khoảng 170 MB);
  - trình duyệt cần thêm khoảng một phút để chuẩn bị đồ hoạ.
- **Lần sau:** vào nhanh, vì trình duyệt giữ lại phần đã tải.
- **Các nhóm sinh viên có sẵn trong khuôn viên** được tải dần sau khi bạn vào game (khoảng 25 MB, nhóm gần trước). Điện thoại tải 6 nhóm gần nhất.
- So với bản Windows, bản web không có xe chạy trên đường và còn thiếu vài mẫu đồ vật.

## Ứng dụng Android

**[Tải XomU.apk](https://github.com/nlhdung/proj-hcmus-verse/releases/latest/download/XomU.apk)** (khoảng 257 MB). Các bản cũ hơn có ở [Releases](https://github.com/nlhdung/proj-hcmus-verse/releases).

- **Máy cần:**
  - Android 7.0 trở lên, chip 64-bit (arm64), tức hầu hết điện thoại từ khoảng năm 2017;
  - còn trống khoảng 600 MB.
- **Cài đặt:**
  1. Mở link tải bằng Chrome trên điện thoại.
  2. Mở tệp `XomU.apk` vừa tải.
  3. Android hỏi về cài ứng dụng từ nguồn này thì bật **Cho phép** cho Chrome (hay trình quản lý tệp), rồi bấm **Cài đặt**.
  4. Ứng dụng có tên **Xóm Ú**.
- **Bản mới:** tải APK mới rồi cài đè lên bản cũ. Tài khoản và tiến độ nằm trên máy chủ nên không mất.
- **Cách chạy:**
  - Toàn bộ khuôn viên nằm sẵn trong ứng dụng, mở lên là vào, không phải tải thêm.
  - Cần mạng để đăng nhập, chơi cùng bạn bè và chấm bài.
  - Dùng chung tài khoản và tiến độ với bản web và bản Windows.
- **Hình và điều khiển:**
  - Đồ hoạ nhẹ như bản web trên điện thoại.
  - Có điều khiển cảm ứng; màn hình tự xoay ngang.
  - Video bài giảng: màn chiếu hiện hình của video, nút "Xem trên YouTube" mở video trong ứng dụng YouTube.

## Bản Windows

Một tệp `XomU.exe`, chạy được trên Windows 10 và 11. Link tải sẽ được cập nhật ở đây.

## Cách chơi

- **Phím (máy tính):**
  - WASD: đi; chuột: xoay camera; R: chạy;
  - E: mở bài tập, bật công tắc màn chiếu, mở bảng đề thi cũ;
  - Enter: trò chuyện (Tab đổi giữa Gần và Toàn trường);
  - I: kho đồ; M: bản đồ; T: tài khoản;
  - G: góp ý; Esc: đóng.
- **Điện thoại:** kéo vòng tròn bên trái để đi, vuốt phần còn lại của màn hình để xoay camera. Các nút: E, Chạy, Kho, Bản đồ, Tài khoản, Chat, Góp ý.
- **Tài khoản:**
  - Đăng nhập bằng MSSV, tên tài khoản hoặc email, hoặc tạo tài khoản mới (mã xác nhận gửi về email).
  - Chọn **Khám phá tự do** để dạo trường không cần tài khoản.
  - Mỗi tài khoản chỉ chơi trên một thiết bị: đăng nhập ở máy khác thì máy trước tự thoát.
- **Nhân vật và tên:**
  - Lần đầu vào, chọn nhân vật; đổi lại được trong Tài khoản (T).
  - Tên hiện trên đầu nhân vật là **tên hiển thị**: mặc định là một từ tiếng Anh ngẫu nhiên, đổi được trong Tài khoản (T). Họ tên thật không hiện cho người khác.
- **Trò chuyện:** kênh **Gần** tới các bạn đứng trong 5 m, kênh **Toàn trường** tới mọi người đang chơi. Lời nói hiện trong khung chat và thành bong bóng trên đầu người nói. Cần đăng nhập.
- **Đề thi cũ:**
  - Các bảng đề đặt quanh tháp hoa giữa hồ Túy Xuân, mỗi khoa một bảng.
  - Đến gần bảng, bấm E rồi trả lời đúng 3 câu hỏi để mở bảng của khoa đó.
  - Tìm đề theo môn, mã học phần, năm hoặc nội dung.
  - Cột **Trợ lý giải đề** bên cạnh đề:
    - hỏi bất cứ điều gì về đề, hoặc dùng các nút nhanh "Giải trang này", "Gợi ý", "Cần ôn gì?";
    - trợ lý là AI và có thể sai, nên tự kiểm tra lại.
- **Buổi tối** (từ 18:00 đến 05:00 theo giờ máy): trời tối, đèn đường, đèn quanh hồ, đèn cổng trường và quán Bon Bon sáng lên.
- **Góp ý cho tác giả:** chọn mục GÓP Ý ở màn hình chính hoặc bấm G khi đang chơi; gửi kèm được tối đa 2 hình.

## Cập nhật

### 17/11/2026: ứng dụng Android, đề thi cũ, trợ lý giải đề, đèn đêm

- **Ứng dụng Android** (`XomU.apk`): cài thẳng lên điện thoại, khuôn viên nằm sẵn trong ứng dụng, dùng chung tài khoản với bản web.
- **Đề thi cũ của các khoa:**
  - bảng đề quanh tháp hoa ở hồ Túy Xuân, gần 1.000 đề;
  - trả lời 3 câu hỏi để mở bảng của mỗi khoa;
  - đề hiện bằng chữ, đầy đủ ký hiệu toán; tìm được theo cả nội dung đề.
- **Trợ lý giải đề** ngay cạnh đề:
  - giải từng bước, gợi ý, chỉ ra phần cần ôn;
  - câu trả lời hiện dần khi trợ lý đang viết, công thức hiện thành ký hiệu toán.
- **Hồ Túy Xuân:** giữa hồ có tháp hoa, mặt hồ phản chiếu cây, nhà và tháp. Phản chiếu và bóng cây bật tắt được trong Cài đặt, kể cả trên web.
- **Đèn đêm:**
  - quanh hồ sáng nhất khuôn viên, có đèn lồng sân vườn quanh bờ;
  - cổng trường có đèn trên lối vào và đèn rọi bảng tên;
  - quán Bon Bon sáng bảng hiệu, mái hiên và trong quán.
- **Khuôn viên:**
  - căn tin thông nhau, có lầu trên ngồi được;
  - dãy C thấp hơn sân nửa tầng, có đường dốc xuống;
  - tầng hầm dưới dãy C đậu xe buýt, có ghế chờ.
- **Nhân vật:** chọn được mọi nhân vật, người khác thấy đúng nhân vật bạn chọn; tay nhân vật nữ buông tự nhiên hơn.

### 07/11/2026: chơi cùng nhau, trò chuyện, điện thoại

- **Nhiều người chơi cùng lúc:** thấy các bạn khác đi lại trong khuôn viên, và số sinh viên đang có mặt.
- **Trò chuyện** bằng chữ: kênh Gần (5 m) và Toàn trường, bong bóng lời trên đầu, lọc từ tục.
- **Tên hiển thị** trên đầu mỗi nhân vật, tự đặt trong Tài khoản.
- **Chọn nhân vật nam hoặc nữ**, giữ theo tài khoản. Dáng đứng tự nhiên; nhân vật nam có tỉ lệ chân dài hơn.
- **Chơi trên điện thoại và máy tính bảng** với joystick và nút cảm ứng.
- **Các nhóm sinh viên có sẵn** trong khuôn viên giờ có cả trên web (đôi bạn chờ xe buýt, các nhóm đứng trò chuyện, người mặc vest ở quán Bon Bon, hai tượng ở cổng), tải dần sau khi vào game.
- **Nhanh hơn khoảng ba lần** trên web.
- **Bản đồ nhỏ** hình tròn có viền vàng.
- **Một tài khoản một thiết bị.**
- **Sửa lỗi:** chuột biến mất khi chọn nhân vật ngay sau khi đăng nhập.

### 07/11/2026: bản web đầu tiên

- **Chơi ngay trên trình duyệt** tại https://ú.llms.vn, dùng chung tài khoản và tiến độ với bản Windows.
- **Màn chiếu trong phòng học** phát video bài giảng YouTube ngay trên màn, có tiếng.
  - Chọn khoa, môn, bài; ai cũng xem được, kể cả khi chưa đăng nhập.
  - Video tự dừng khi đi xa khỏi phòng.
  - Nút "Xem trên YouTube" mở video trong trình duyệt.
- **Hộp thoại góp ý:** viết chữ, kèm tối đa 2 hình, gửi thẳng cho tác giả.
- **Quên mật khẩu:** mã đặt lại gửi về email.
- **Camera** quay theo chuột chậm và dễ điều khiển hơn.
- **Khuôn viên:**
  - cầu nối có mái che từ dãy D sang dãy C ở tầng 2;
  - trạm xe bus và bảng tin bên lề đường, có đôi bạn đứng chờ xe;
  - bàn giáo viên dời vào góc phòng, không che màn chiếu.

## Giấy phép của phần mềm bên thứ ba

- Godot Engine (MIT), cùng các thư viện Android đi kèm bản Android của Godot (Apache 2.0)
- Godot WRY (MIT), chỉ trong bản Windows
- Phông Be Vietnam Pro và JetBrains Mono (SIL Open Font License), DejaVu Sans (giấy phép Bitstream Vera / DejaVu)
- Video bài giảng thuộc kênh YouTube của giảng viên

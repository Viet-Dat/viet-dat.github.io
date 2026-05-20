---
title: "Hướng dẫn toàn tập: Tạo Blog cá nhân miễn phí với GitHub Pages & Theme Chirpy"
date: 2026-05-20 11:30:00 +0700
categories: [Hướng dẫn, Khởi tạo Blog]
tags: [github pages, jekyll, chirpy, tutorial, git]
---

Chào mừng các bạn đến với bài viết hướng dẫn chi tiết cách tạo một trang blog cá nhân hoàn toàn miễn phí bằng GitHub Pages và sử dụng giao diện Chirpy tuyệt đẹp! Chúng ta cùng bắt đầu nhé. 🚀

## 1️⃣ Bước 1: Tạo tài khoản GitHub

**Đầu tiên, bạn cần có một tài khoản Github.**

![Tạo tài khoản Github](/imgs/Pasted%20image%2020260520090552.png)

Sau khi đã tạo xong tài khoản, giao diện của bạn sẽ trông như thế này:

![Giao diện Github](/imgs/Pasted%20image%2020260520090727.png)

---

## 2️⃣ Bước 2: Sử dụng Theme có sẵn

> **Link Theme:** [Click vào đây để chuyển sang Theme Chirpy Starter](https://github.com/cotes2020/chirpy-starter)

Đây là giao diện của Theme trên GitHub:

![Giao diện Theme Chirpy](/imgs/Pasted%20image%2020260520091725.png)

* Click vào nút màu xanh **Use this template**.

![Nút Use this template](/imgs/Pasted%20image%2020260520091847.png)

* Chọn **Create a new repository**.
* Đây là giao diện sau khi bạn đã click:

![Tạo Repository mới](/imgs/Pasted%20image%2020260520092055.png)

**Điền thông tin cho Repository:**
* **Repository name:** Hãy đặt tên theo đúng cú pháp sau:
    ```bash
    username.github.io
    ```
    *(Thay `username` bằng tên tài khoản GitHub của bạn)*
* **Description:** Có thể ghi chú thích ngắn gọn hoặc bỏ trống tùy bạn.
* Sau khi điền xong, hãy click vào **Create repository**.

🎉 **Và đây là thành quả của bạn:**

![Thành quả tạo Repo](/imgs/Pasted%20image%2020260520093226.png)

---

## 3️⃣ Bước 3: Cấu hình địa chỉ trang web

* Tìm và click vào file `_config.yml` (Nằm ở cột danh sách file bên trái).

![Mở file config](/imgs/Pasted%20image%2020260520093422.png)

* Click vào biểu tượng chiếc bút ✏️ **Edit this File**.

![Edit file](/imgs/Pasted%20image%2020260520093555.png)

* Tìm đến dòng code thứ 26 có nội dung `url: ""`.
* Chỉnh sửa thông tin bên trong thành đường link web của bạn *(Username là tên bạn đã đặt cho Repository lúc nãy)*:
    ```yaml
    url: "[https://Username.github.io](https://Username.github.io)"
    ```
* **Ví dụ thực tế:**

![Ví dụ cấu hình URL](/imgs/Pasted%20image%2020260520094120.png)

**Sau đó tiến hành Commit lại!**
> 💡 *Mẹo: Nội dung của ô commit không nhất thiết phải giống như trong ảnh, bạn có thể ghi bất cứ chú thích nào bạn muốn để dễ nhớ.*

![Ghi chú Commit](/imgs/Pasted%20image%2020260520094337.png)

**Sau khi commit xong:**
* Click vào tab **Actions**.

![Tab Actions](/imgs/Pasted%20image%2020260520094539.png)

* Click vào lần commit gần nhất của bạn (như trong ảnh ví dụ là `thisokbro`).

![Xem chi tiết Actions](/imgs/Pasted%20image%2020260520094643.png)

* Chờ một chút để tiến trình chạy. Khi thấy hiện tích xanh tức là đã **deploy lên web thành công**.

![Deploy thành công](/imgs/Pasted%20image%2020260520094742.png)

* Bây giờ, hãy mở tab mới và truy cập vào link: `https://Username.github.io`

**Bạn sẽ ra được blog của bạn như thế này:**

![Giao diện Blog](/imgs/Pasted%20image%2020260520094730.png)

> ⚠️ *Lưu ý: Đây mới chỉ là giao diện gốc xây từ theme có sẵn. Chúng ta cần phải tải source code về máy tính để đổi lại thông tin cá nhân và đăng thử một bài viết.*

---

## 4️⃣ Bước 4: Cài đặt phần mềm Git

* Mở trình duyệt, search từ khóa `Git Download` hoặc truy cập link: [Git - Install for Windows](https://git-scm.com/install/windows)

![Tìm kiếm Git](/imgs/Pasted%20image%2020260520100150.png)

* Download bản **64-bit Git for Windows Setup** (nếu máy bạn dùng Windows 64-bit).
* Sau khi tải xong, mở file cài đặt lên.

![Cài đặt Git 1](/imgs/Pasted%20image%2020260520100423.png)
* Cứ bấm **Next** liên tục ở các bước đầu.
![Cài đặt Git 2](/imgs/Pasted%20image%2020260520100508.png)
![Cài đặt Git 3](/imgs/Pasted%20image%2020260520100543.png)

* **Lựa chọn Trình soạn thảo (Editor):** Tại bước này, bạn có thể chọn ngôn ngữ/phần mềm bạn muốn dùng để edit. Ở đây, mình chọn sử dụng **Visual Studio Code**.
![Cài đặt Git 4](/imgs/Pasted%20image%2020260520100707.png)

* Tiếp tục bấm **Next**.
![Cài đặt Git 5](/imgs/Pasted%20image%2020260520100806.png)

* Tích chọn dòng **Override the default branch name...** và ấn Next.
![Cài đặt Git 6](/imgs/Pasted%20image%2020260520100932.png)

* Click vào lựa chọn thứ 2 *(Git from the command line and also from 3rd-party software)* và bấm Next.
![Cài đặt Git 7](/imgs/Pasted%20image%2020260520101056.png)

* Các bước tiếp theo bạn cứ giữ mặc định và bấm **Next** cho đến cuối.
![Cài đặt Git 8](/imgs/Pasted%20image%2020260520101139.png)
![Cài đặt Git 9](/imgs/Pasted%20image%2020260520101201.png)
![Cài đặt Git 10](/imgs/Pasted%20image%2020260520101230.png)
![Cài đặt Git 11](/imgs/Pasted%20image%2020260520101249.png)
![Cài đặt Git 12](/imgs/Pasted%20image%2020260520101313.png)

* Cuối cùng bấm **Install** để quá trình cài đặt diễn ra.

---

## 5️⃣ Bước 5: Kéo (Clone) mã nguồn Github về máy tính

* Đầu tiên, bạn vô lại trang Repo Github đã tạo và copy URL.

![Copy URL Repo](/imgs/Pasted%20image%2020260520102126.png)

* Sau đó, mở máy tính của bạn, chọn bất kỳ ổ đĩa/thư mục nào bạn muốn lưu trữ mã nguồn web (Ví dụ: `Documents`).

![Chọn thư mục lưu trữ](/imgs/Pasted%20image%2020260520102230.png)

* Click chuột phải ở khoảng trống trong thư mục, chọn **Open Git Bash Here**.
* Gõ lần lượt các lệnh sau vào bảng điều khiển (Bash) để đăng nhập:
    ```bash
    git config --global user.name "Tên-Github-của-bạn"
    git config --global user.email "Email-đăng-ký-Github-của-bạn@example.com"
    ```
* Sau đó, sử dụng lệnh `git clone` để tải web về máy:
    ```bash
    git clone "url-git-của-bạn"
    ```
    *Ví dụ cụ thể:*
    ```bash
    git clone [https://github.com/Viet-Dat/viet-dat.github.io.git](https://github.com/Viet-Dat/viet-dat.github.io.git)
    ```

* Sau khi chạy lệnh này xong, trong máy tính của bạn sẽ xuất hiện một folder mới chứa toàn bộ source code như ảnh dưới:

![Thư mục sau khi Clone](/imgs/Pasted%20image%2020260520102939.png)

---

## 6️⃣ Bước 6: Chỉnh sửa thông tin cá nhân của Blog

* Mở phần mềm **VS Code** lên và Open Folder mà bạn vừa clone về.

![Mở folder bằng VS Code](/imgs/Pasted%20image%2020260520103347.png)

* Mở file `_config.yml` ra để sửa Title và các thông tin khác thành tên của bạn.

![Đổi Title](/imgs/Pasted%20image%2020260520103844.png)

---

## 7️⃣ Bước 7: Viết và đăng tải bài Blog đầu tay

* Trong thư mục dự án, bạn tìm và mở thư mục `_posts`.

![Mở thư mục bài viết](/imgs/Pasted%20image%2020260520104119.png)

* Tạo một file mới với đuôi `.md` (Nhớ đặt tên file theo cấu trúc `YYYY-MM-DD-ten-bai.md`).

![Tạo file MD mới](/imgs/Pasted%20image%2020260520104333.png)

* Soạn thảo nội dung bài viết. Bạn bắt buộc phải có phần thẻ khai báo thông tin (Front Matter) ở đầu bài như sau:

    ```markdown
    ---
    title: "Hello World"
    date: 2026-05-19 00:00:00 +0700
    categories: [Nhật ký]
    tags: [hello world]
    ---
    
    # Hello World
    
    Chào mọi người, đây là bài blog cá nhân đầu tiên của mình!
    ```

* Sau khi viết xong, ấn **Ctrl + S** để lưu lại file.
* Nhìn sang cột menu bên trái của VS Code, click vào biểu tượng **Source Control** (hình nhánh cây).

![Source Control VS Code](/imgs/Pasted%20image%2020260520104642.png)

* Đây là lúc đẩy các file đã sửa lên GitHub. Hãy nhập một ghi chú bất kỳ vào ô Message.

![Nhập ghi chú Push](/imgs/Pasted%20image%2020260520104803.png)

* Bấm **Commit** (nếu hiện thông báo thì click 'Yes'), sau đó bấm **Sync Changes**.

![Sync Changes 1](/imgs/Pasted%20image%2020260520104826.png)
![Sync Changes 2](/imgs/Pasted%20image%2020260520104847.png)

* Click **OK** ở bảng thông báo xác nhận.

* Quá trình đồng bộ hoàn tất, giao diện sẽ gọn gàng lại như thế này:

![Đồng bộ hoàn tất](/imgs/Pasted%20image%2020260520104921.png)

* Đợi một lát để GitHub chạy build, sau đó mở web của bạn lên kiểm tra. **Đây là kết quả:**

![Kết quả bài đăng mới 1](/imgs/Pasted%20image%2020260520110145.png)
![Kết quả bài đăng mới 2](/imgs/Pasted%20image%2020260520110211.png)

### 🎉 Chúc các bạn thành công!
# Bước 1: Tạo tài khoản GitHub

**Hãy tạo 1 tài khoản Github**

![[Pasted image 20260520090552.png|697]]
**Sau khi đã tạo xong tài khoản, bạn sẽ có 1 trang như này:**

![[Pasted image 20260520090727.png]]
# Bước 2: Sử dụng Theme có sẵn

[Click vào dòng chữ này để chuyển sang Theme]([cotes2020/chirpy-starter: A starter template for Jekyll sites using the Chirpy theme.](https://github.com/cotes2020/chirpy-starter))

- **Đây là giao diện của Theme:**

![[Pasted image 20260520091725.png]]

- Click vào **Use this template**

![[Pasted image 20260520091847.png]]

- Chọn **Creat a new repository**

- **Đây là giao diện sau khi đã click**

![[Pasted image 20260520092055.png]]

Ngay dòng đầu tiên
- **Repository name**: Hãy chọn tên bạn muốn 

```
username.github.io
```

- **Description**: Có thể ghi hoặc không tùy vào bạn

- Sau khi xong hãy click vào **Creat repository**

--> **Đây là thành quả:**

![[Pasted image 20260520093226.png]]

# Bước 3:

- Tìm và click vào  **_config.yml**  ( Nằm ở góc bên trái của phần files)
![[Pasted image 20260520093422.png]]

- Click vào incon pen  **Edit this File**   
![[Pasted image 20260520093555.png]]

- Tìm đến dòng code thứ 26 nội dung `url=" "`
- Chỉnh sửa thông tin bên trong: ( Username là tên bạn đã đặt cho **Repository** hồi này)
```
url: "https://Username.github.io"
```
- **ví dụ:**

![[Pasted image 20260520094120.png]]

**Sau đó Commit lại**
Nội dung của commit không nhất thiết phải giống như trong ảnh
Bạn có thể ghi bất cứ một text nào bạn muốn 
![[Pasted image 20260520094337.png]]

**Sau khi commit**

**Click vào Action**
![[Pasted image 20260520094539.png]]

Click vào lần commit gần nhất của bạn ( như trong ảnh là **thisokbro**)

![[Pasted image 20260520094643.png]]
 Đã deploy lên được web
![[Pasted image 20260520094742.png]]
Click vào link: `https://Username.github.io`

**Bạn sẽ ra được blog của bạn**

![[Pasted image 20260520094730.png]]

**Đây chỉ mới là 1 blog được xây từ 1 theme có sẵn, ta cần phải đổi lại thông tin và đăng tải 1 blog thử nghiệm lên ( như trong ảnh mình đã đăng thử 1 blog lên trước còn khi bạn mới tạo thì sẽ không có)**

# Bước 4: Cài đặt Git

- Đầu tiên search ` Git Dowload`
[Git - Install for Windows](https://git-scm.com/install/windows)

![[Pasted image 20260520100150.png]]

- **Dowload bản x64 nếu máy bạn là Win**
- **Tùy chỉnh phiên bản phủ hợp với máy bạn để tải xuống**
- **Sau khi giải nén, chọn file để lưu trữ trên máy**
![[Pasted image 20260520100423.png]]
- **Bấm next**

![[Pasted image 20260520100508.png]]
-**Bấm next**
![[Pasted image 20260520100543.png]]
- **Ở đây tùy chọn ngôn ngữ bạn muốn edit**
- **Về phía mình, mình chọn sử dụng Visual Code**
![[Pasted image 20260520100707.png]]
**-Bấm next**
![[Pasted image 20260520100806.png]]
- click dòng dưới **Override the ........ và ấn Next 
![[Pasted image 20260520100932.png]]
- **Click vào cột thứ 2 và bấm Next**
 ![[Pasted image 20260520101056.png]]
 - **Bấm next**
 ![[Pasted image 20260520101139.png]]
 - **Bấm next**
 ![[Pasted image 20260520101201.png]]
 - **Bấm next**
 ![[Pasted image 20260520101230.png]]
 - **Bấm next**
 ![[Pasted image 20260520101249.png]]
 - **Bấm next**
 ![[Pasted image 20260520101313.png]]
- **Bấm Install**
# Bước 5: Dow github.io từ github về lap
- Đầu tiên: bạn vô lại trang git đã tạo và copy url
![[Pasted image 20260520102126.png]]
- Sau khi đã cop được, bạn vô desktop và vào bất kỳ chỗ nào có thể lưu file
- ( Mình thì mình chọn Document)
![[Pasted image 20260520102230.png]]
- Click vào **Open Git Bash Here**
-  Ghi lệnh này vào Bash
  ```console
git config --global user.name "John Doe"
git config --global user.email johndoe@example.com
  ```
  - **user name:** thay bằng tên github của bạn
  - **user mail:** thay bằng mail bạn login github

- **Sau đó tiếp tục với lệnh sau:** 
```
git clone "url git của bạn"
```
-  **Ví dụ:**
```
git clone https://github.com/Viet-Dat/viet-dat.github.io.git
```
- Sau khi chạy lệnh này, bạn sẽ có được 1 floder như trên ảnh:
![[Pasted image 20260520102939.png]]


# Bước 6: Chỉnh sửa thông tin của blog

- **Đầu tiên:** mở vscode lên và login vào folder github đó
![[Pasted image 20260520103347.png]]

- Sửa title:
- Đổi thành tên bạn muốn
![[Pasted image 20260520103844.png]]

- Chỉnh sửa 1 số thông tin lại thành của bạn


# Bước 7: Tạo 1 blog đầu tay
- click vào **Post**
![[Pasted image 20260520104119.png]]
- Tạo 1 file với đuôi .md
![[Pasted image 20260520104333.png]]

- Viết đoạn text sau:
- ```md
---

title: "Hello World"

date: 2026-05-19 00:00:00 +0800

categories: [Hello World]

tags: [Hello World]

---

# Hello World

  

Hello World is this my personal bolg.
  ```

-> Sau khi xong **Ctr+S** để lưu lại file

- Sau đó ngay chỗ incone file
![[Pasted image 20260520104642.png]]
- **Đây là lúc mình sẽ đẩy Change lên Git**
- Cái text ngay dưới Changes mình có thể điền bất cứ thông tin gì bởi nó không quan trọng
- ![[Pasted image 20260520104803.png]]
- **click 'yes'**
- **Syns changes**
![[Pasted image 20260520104826.png]]

![[Pasted image 20260520104847.png]]
- **click Ok**
- Như thế này là xong
![[Pasted image 20260520104921.png]]

- Đây sẽ là kết quả đã ok
![[Pasted image 20260520110145.png]]

![[Pasted image 20260520110211.png]]

# Chúc bạn thành công !

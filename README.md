# Code gian lận Quizizz - GiaKhanhVN

- Đây là code của một người Cộng Sản nên ai dùng cũng ok!
- Dùng script này để bonk một phát vào đầu nhà phát triển Quizizz (LMAO)

- [Khai thác API của Quizizz] (#fetching-quizizz-api)

## Cách hoạt động: Khai thác API của Quizizz

Hoạt đông tốt nhất ở chế độ Quizizz Classic
1. Tham gia bài test Quizizz Classic (Trắc nghiệm, Tự luận ngắn)
2. Khi đã vào phần làm bài, nhấn Ctrl + Shift + I (Windows) [Command + Shift + I (MacOS)]
3. Vào phần ```CONSOLE```
4. Dán code sau vào
```ts
fetch("https://raw.githubusercontent.com/KhanhVNMC/quizizzhackvn/master/dist/bundle.js")
.then((res) => res.text()
.then((t) => eval(t)))
```
5. Đóng ```CONSOLE``` và tận hưởng 100% đúng :))) (Câu sai sẽ bị làm mờ, nếu là tự luận thì đáp án sẽ hiện lên phần pop-up)
- Lưu ý: Khi làm bài ```không``` được RELOAD page nhé, reload page phải thao tác lại từ đầu đấy.

![screenshot](/examples/screenshot_1.png)
*Hình minh hoạ 1 [TRẮC NGHIỆM] (Test vào 23/2/2021)*

Made by GiaKhanhVN - Discord GiaKhanhVN#5187
Email: khanhcarlo@gmail.com

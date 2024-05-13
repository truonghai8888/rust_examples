# rust_examples
dùng để lưu trữ các ví dụ học tập về rust
# Điều kiện tiên quyết
1. Đã cài đặt rust
2. Cài đặt editor cùng các extentions liên quan. Trong dự án này mình sử dụng VS Code bạn có thể xem hướng dẫn tại 
[đây](https://code.visualstudio.com/docs/languages/rust)
3. biêt cách sử dụng terminal đơn giản
4. Tất cả ví dụ sẽ xem từ từ thư mục rust_examples bằng VScode

# Hello World
chạy bằng terminal
```shell
cargo new hello_world
cd hello_world
cargo run
```

# Các ví dụ tiếp theo
chạy bằng terminal
```shell
mkdir hello_world/examples
copy và đổi tên file main.rs ở thư mục src thành hello_world.rs trong thư mục examples
rustc .\hello_world\examples\hello_world.rs; .\hello_world
```
sau khi chạy lệnh trên bạn sẽ thấy có thêm 2 file mới ở thư mục rust_examples lần lượt là:
- hello_world.exe
- hello_world.pdb

Và kết quả dòng chữ Hello, world! cũng hiển thị tương tự như ví dụ trên. Các file thực thi nếu sinh ra như lệnh trên sẽ rất khó quản lý. Chính vì vậy mà mình khuyên các bạn hãy sử dụng cách làm bên dưới.

từ h đến các ví dụ tiếp bạn sẽ chỉ cần mở thư mục examples và code như bình thường giống với các ngôn ngữ khác VD
```shell
cd hello_world/examples
code .
rustc .\hello_world.rs; .\hello_world
```

bạn sẽ thấy được các file thực thi sẽ sinh ra trong thư mục examples. Về mặt cảm quan sẽ dễ quản lý hơn. khi rust-analyzer đã check ok, bạn có thể mở các thư mục con cũng được.

# hello cùng học Git nào!

# Giai đoạn đầu : cấu hình nó 
1. name:  $git config --global user.name "Tên người dùng"
2. email: $git config --global user.email tên địa chỉ emal
    // để xem $git config --global core.editor "code --wait"
                $git config --global -e 
    // để xem phiên bản 
                $git --version
3. cấu hình xử lý /n --> window và trên macos: $git config --global core.autoclf input


# Giai đoạn dùng: 
1. Tạo thư mục: 
    + Tạo thư mục --> right click --> git base here
    + $ mkdir <Tên thư mục>
2. Thêm file muốn theo dõi
    + Để kiểm:  $ ls
    + Xem status thêm vào môi trường dàn dựng chưa: $ git status [--short]: 
                                                ?? không theo dõi, 
                                                A các tập tin thêm vào, 
                                                M Đã thay đổi,
                                                D đã xóa
    // git staging Enviroment: khi làm việc có thể .thêm .sửa .xóa sau khi kết thúc bạn có thể thêm vào git staging Enviroment
    >> nếu chư thì thêm: $ git add <tên tệp> or $ git add --all
3. commit: $ git commit -m "massage" or $ git commit -a -m "massage" [tệp đã thay đổi]
    + Tạo 1 điểm lưu đó là một điểm trong dự án mà bạn có thể quay lại nếu tìm thấy lỗi hoặc thay đỗi nếu cần thiết   
4. Xem lịch sử các commit: $ git log

# Chú ý: 
    + ls , mkdir.


<Lệnh help>: $git help --all
<Lệnh help>: $git commit -help
<Lệnh tạo branch>: $git branch Tên nhánh
<Lệnh chuyển nhánh>: $git checkout tên nhánh cụ thể
<Lệnh tạo + chuyển>: $git checkout -b new branch tên nhánh



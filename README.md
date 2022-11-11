# Kali-Linux

Kali Lunix tutorial
Discovery: 
Iclentity services webserver:
Exploit: 
Elevate Privileses:   
+ Linux Shell: 
   - pwd hiển thị đường dẫn của thư mục hiện tại mà mình đang ở trong đó 
   - cd: chuyển hướng đường dẫn ( cd- lùi lại thư mục trước đó b ở)
   -  ls: hiển thị file trong thư mục đang ở hiện tại
       + ls -R liệt kê các file bao gồm các thư mục phụ bên trong
       + ls -a liệt kê những file ẩn
        + ls -al liệt kê tất cả các file và thư mục với thông tin chi tiết: phân quyền, kích thước ......
   - cat dùng để xem nội dung file 
	+ cat > filename tạo ra 1 file mới 
 	+ cat filename1 filename2 > filename3 : nhập 2 file để lưu kết quả và file3
   - cp nguon /đích: dùng để sao chép file vào thứ mục
   + cp –rv: sao chép đệ quy, sao chép tất cả lần thư mục con
   - mv: dùng dể di chuyển file vào thư mục.  Còn dùng để đổi tên file (mv tentruoc tensau) 
   - mkdir: dung để tạo thư mục 
	+ mkdir -p: dùng để tạo ra 1 thư mục giữa 2 thư mục đã tồn tại: mkdir -p home/newfile/anhphap -> mục newfile được tạo
	+ or: mkdir –p ap//tt . Tạo thư mục ap và tt là thư mục con của ap
    - rmdir: Xóa thư muc trống
-rm xóa file
	+ rm –r: xóa folder , đệ quy, hỏi khi xóa
	- rm –rf: khóa ko cần hỏi
    - chmod thay đổi quyền đọc ghi thực thi file và thư mục 
    chown thay đổi, chuyển quyền sở hữu file sang tên ng chỉ định.
Vi: 
- I: insert
- dd xóa dong
- u : undo
Quản lý user:
u-g-o
-rwx (r=4, w=2,x=1)		chmod g+x (group thêm quyề excute) 
Grep: lọc dữ liệu theo dòng
Cut: lọc dữ liệu theo cột 
Gnone-session-quit
Bin: để điều khiển folder, file, thao tác
Sbin: quản lý hdh
Var: chứa các thông tin  đến log, ứng dung, hệ thống, 
Cấp quyền: chmod u+x ten_file
Echo + [option] + chuoi/bien
Ex: let “z=$z+3
Nén: gzip <ten_file) || gzip –d <ten_file>
Gom: tar –cvf <tenfile.tar> <file1> <file2>
+ -c tạo 1 file mới
+ v (verbose): hiển thị quá trình gom file
Bung: tar –xvf <file.tar>


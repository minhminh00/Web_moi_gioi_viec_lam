# Phân tích trang web môi giới việc
## _Dự án_

## Đối tượng sử dụng
- Quản trị viên
- Nhà Tuyển dụng
- Ứng viên

## Chức năng từng đối tượng
A. Quản trị viên
- Quản lý trang thông tin: banner, giới thiệu, ...
- Quản lý người dùng
- Quản lý file: JD, CV
- Quản lý bài đăng công việc
- Quản lý báo cáo

B. Nhà tuyển dụng
- Quản lý bài tuyển dụng
- Tìm kiếm CV
- Chỉnh sửa thông tin cá nhân (thuộc công ty nào, thông tin liên hệ)

C. Ứng viên
- Tìm kiếm công việc (Công ty, vị trí, mức lương, địa điểm, ngôn ngữ, trình độ, yêu cầu bằng cấp - chứng chỉ, số lượng)
- Đăng CV
- Xem danh sách công việc ( sắp xếp ngẫu nhiên)
- Báo cáo vi phạm, công ty, cá nhân ( lừa đảo, spam, không liên hệ được, thông tin bài tuyển dụng sai)

### Phân tích chức năng

- Đăng bài tuyển dụng

| Các tác nhân | Nhà tuyển dụng |
| ------ | ------ |
| Mô tả | Đăng bài tuyển dụng |
| Kích hoạt | Người dùng ấn vào nút đăng bài tuyển dụng trên thanh menu |
| Đầu vào | Tên công ty <br> Tên công việc <br> Địa điểm: thành phố - quận(select2-load về local)<br>Remote | (checkbox) <br> Có cho Part time không ? (radio) <br> Mức lương (slidebar) <br> Ngôn ngữ ( multiple select 2 ) <br> Yêu cầu thêm (text) <br> File JD |
| Trình tự xử lý |  |
| Đầu ra | Đúng: Hiển thị trang người dùng và thông báo thành công <br> Sai: Hiển thị trang đăng nhập và thông báo thất bại |
| Lưu ý | Kiểm tra ô nhập không được để trống bằng Javascript |

   [dill]: <https://github.com/joemccann/dillinger>
   [git-repo-url]: <https://github.com/joemccann/dillinger.git>
   [john gruber]: <http://daringfireball.net>
   [df1]: <http://daringfireball.net/projects/markdown/>
   [markdown-it]: <https://github.com/markdown-it/markdown-it>
   [Ace Editor]: <http://ace.ajax.org>
   [node.js]: <http://nodejs.org>
   [Twitter Bootstrap]: <http://twitter.github.com/bootstrap/>
   [jQuery]: <http://jquery.com>
   [@tjholowaychuk]: <http://twitter.com/tjholowaychuk>
   [express]: <http://expressjs.com>
   [AngularJS]: <http://angularjs.org>
   [Gulp]: <http://gulpjs.com>

   [PlDb]: <https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md>
   [PlGh]: <https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md>
   [PlGd]: <https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md>
   [PlOd]: <https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md>
   [PlMe]: <https://github.com/joemccann/dillinger/tree/master/plugins/medium/README.md>
   [PlGa]: <https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md>

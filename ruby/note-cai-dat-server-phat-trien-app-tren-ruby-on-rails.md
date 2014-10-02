Chú ý khi cài đặt passenger với ruby 2.1.3 và rails 4.1.6 (sử dụng RVM)
--------------------------------

 1 - Chú ý này của RVM rồi, nên chạy dưới quyền người dùng không phải root, chỉ cấp quyền root khi nào RVM yêu cầu
 2 - Sau khi tạo app bằng rails cần để ý đến môi trường đã thiết lập chưa, mặc định passenger sẽ để là production, nên để môi trường là development thông qua cài đặt PasengerAppEnv

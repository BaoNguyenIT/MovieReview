Ghi chú: chương trình muốn sử dụng hết các chức năng như đăng nhập liên kết facebook, hoặc google thì cần có keyhash
Ngoài ra trong chương trình em có sử dụng một số API của firebase nhằm mục đích lưu trữ dữ liệu vì vậy cũng cần có SHA-1 key 
nhưng những key này chỉ năm trong source gốc khi copy source sang máy khác để chạy thì không có tác dụng.
Do mặc hạn chế như vậy nên em đã build sẵn file apk trên máy gốc, còn source mang tính chất tham khảo khi build vẫn chạy được 
nhưng không sử dụng được chức năng đăng nhập login vì vậy mong thầy thông cảm và sử dụng file apk đã buld sẵn.
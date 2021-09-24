# docker-seminar


### Giới thiệu (5-7 min)
- Giảng viên và buổi seminar (Tuannda3 && Tiennh21)
- Việc học lập trình và công việc phát triển phần mềm
- Cách thức phát triển phần mềm của 1 dự án
- Các công nghệ áp dụng
    - Với Java
    - Với PHP
    - Nhìn chung là 1 dự án sẽ cần môi trường cài đặt rất nhiều thứ cùng các phiên bản khác nhau

- Vấn đề: khi 1 thành viên mới vào team hoặc các thành viên cài đặt khác nhau sẽ cho ra kết quả khác nhau
- Cách giải quyết: cần 1 công cụ nào đó để quá trình này trở nên đơn giản hơn, tiết kiệm thời gian hơn và đồng nhất được môi trường phát triển cho toàn bộ thành viên dự án.


### Docker là gì? (5-7 min)


### Cần gì để có thể tiếp cận docker? (5-7 min)


### Docker hoạt động như thế nào? (5-7 min)


### Cài đặt docker (10-15 min)

Các thành viên trong team sẽ cùng cài đặt docker để sử dụng, tuy nhiên với mỗi HĐH sẽ có các cách cài đặt docker khác nhau.

- Windows
- Linux (Ubuntu)
- Macos

### Bắt đầu dựng docker (30 min)
- Với nhu cầu là có thể chạy 1 ứng dụng Java/PHP cơ bản:
    - Java:
        - SDK
        - SQL
        - ...
    - PHP:
        - PHP
        - nginx
        - MySQL
- Quy trình: Dựng Dockerfile -> image -> container
- Dockerfile
    - File cấu hình những thông tin của 1 image (giới thiệu vài cái cơ bản)
        - FROM
        - MAINTAINER
        - RUN
        - CMD
        - ENTRYPOINT
        - EXPOSE
        - ADD
        - COPY
        - WORKDIR
        - VOLUME
- Command bật tắt build...
- *Bật vscode demo dựng đơn giản sau đó chạy thử demo 1 project Hello world của 2 ngôn ngữ để sv hiểu cách hoạt động, run vào 1 vài container xem hoạt động ntn*
- Giới thiệu sv cách phát triển Dockerfile với những dự án lớn hơn để có định hướng


### Câu hỏi với sinh viên và giải đáp (5-10 min)

### Quản lý nhiều Dockerfile thấy mệt? docker-compose (35-40 min)


##### Vấn đề gì mà lại có thứ là docker-compose xuất hiện? (5-7 min)
- Dựng môi trường phức tạp
- Nhiều container chạy song song
- Cần cách thức phát triển và sử dụng cũng như maintain đơn giản hơn


##### So sánh docker vs docker-compose (5 min)


##### Cài đặt docker-compose và phát triển cho dự án đơn giản theo yêu cầu như ở docker (30 min)
- Quy trình: dựng file YAML -> image -> container
- *Bật vscode demo dựng đơn giản sau đó chạy thử demo 1 project Hello world của 2 ngôn ngữ để sv hiểu cách hoạt động, run vào 1 vài container xem hoạt động ntn*
- Giới thiệu sv cách phát triển file YAML với những dự án lớn hơn để có định hướng


### Kết lại quá trình tìm hiểu và sử dụng Docker và docker-compose (5-7 min)
- Hiểu được bản chất
- Cách thức hoạt động
- Cách xây dựng cơ bản và định hướng phát triển
- Cung cấp tài liệu trên github gồm slide và các file
- Đặt câu hỏi và trả lời câu hỏi của sv
- Kết thúc

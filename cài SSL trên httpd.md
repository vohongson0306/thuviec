# Hướng dẫn

Cài đặt mobaxterm

Bước 1:

![image](https://user-images.githubusercontent.com/105496635/192431789-3de4eee9-0078-4061-a485-19b8db7812ed.png)

Nhập thông tin của SSH và mật khẩu

Bước 2:

Kiểm tra hệ điều hành

          netstat -tupln

![image](https://user-images.githubusercontent.com/105496635/192432439-4c37e3cf-bd4c-42eb-b3b1-8a660ff5adea.png)

Đối với con này thì là hệ Apache

Bước 3:

Truy cập vào đường dẫn

      cd /var/www/domain/zone/ssl

![image](https://user-images.githubusercontent.com/105496635/192432663-152edc4a-1b33-45ad-870e-b45bc2ee1d74.png)

Để truy cập vào các domai


Bước 4: 

Sử dụng lệnh `ls` để tìm kiếm thông tin tên miền

![image](https://user-images.githubusercontent.com/105496635/192433141-6c13920b-d3ab-425c-85a5-c5b5f0379f20.png)


và truy cập vào tên miền

Bước 5

Sử dụng lệnh `ls` để hiện các file SSL và tiền hành cài đặt

![image](https://user-images.githubusercontent.com/105496635/192433347-042a7a1b-fc09-487c-bf59-d6f2fbad2831.png)

![image](https://user-images.githubusercontent.com/105496635/192433458-d62a8592-a6f3-4235-b18b-5b9c613dfc23.png)

Bước 6:

Sau khi cài xong tiến hành kiểm tra bằng lệnh

           httpd -t

nếu có chữ OK thì là được

![image](https://user-images.githubusercontent.com/105496635/192433567-4dada15e-1299-4f4e-8785-e0c4726a8cf8.png)

Bước 7:  Kiểm tra trạng thái


![image](https://user-images.githubusercontent.com/105496635/192433722-3ae27c19-780c-449d-ac76-fca8afe2c12f.png)





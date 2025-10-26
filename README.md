##  2.1
# dừng IIS
<img width="1112" height="563" alt="image" src="https://github.com/user-attachments/assets/7c3cf511-8ecf-406c-b306-a24a4b734944" />

#  tải bản apache win 64 cho window 
<img width="1543" height="872" alt="image" src="https://github.com/user-attachments/assets/43fd2a35-b2ac-43f6-b0b0-ddafc9978121" />

#  cấu hình httpd.conf
<img width="569" height="304" alt="image" src="https://github.com/user-attachments/assets/d61deee5-4e61-4037-a1d6-0292a4fb7fda" />

<img width="530" height="117" alt="image" src="https://github.com/user-attachments/assets/25ebf01f-62d5-4a4a-ad29-ff9678b9264e" />

#  cấu hình httpd-vhosts.conf

<img width="548" height="708" alt="image" src="https://github.com/user-attachments/assets/9273aa5d-e4ee-438d-a2b8-177f5a62bfff" />

#  fake 1 domain ảo
<img width="550" height="691" alt="image" src="https://github.com/user-attachments/assets/ac362744-c491-4f68-a12f-4e1cd64ab755" />

# cài apche qua CMD
<img width="1118" height="118" alt="image" src="https://github.com/user-attachments/assets/6c8cb000-4ed9-4328-83f5-05164d1f3d58" />

# sau quá trình setup ta có đường dẫn hoàn thiện 
<img width="1866" height="992" alt="image" src="https://github.com/user-attachments/assets/f709d071-e638-4f34-8470-39ab3264b3c2" />

## 2.2 
#  cài notejs qua link:    https://nodejs.org/dist/v20.19.5/node-v20.19.5-x64.msi
#  cài đặt vào ổ D:  D:\nodejs
<img width="617" height="478" alt="image" src="https://github.com/user-attachments/assets/ebb58e60-c5ac-4fff-95d5-5dc4060c2b99" />

# cài notred

<img width="727" height="347" alt="image" src="https://github.com/user-attachments/assets/16f95b05-15c5-4c6d-8f1d-38680326c293" />

#  với: --unsafe-perm → cho phép Node-RED cài đúng cách trên Windows
#       --prefix → cài vào thư mục cụ thể D:\nodejs\nodered
#  download file: https://nssm.cc/release/nssm-2.24.zip giải nén được file nssm.exe
<img width="1520" height="677" alt="image" src="https://github.com/user-attachments/assets/ce9e619f-c08a-4985-b4c6-8c331932fd49" />

#  tạo file run_nodered
<img width="527" height="693" alt="image" src="https://github.com/user-attachments/assets/27eaca80-353b-4755-8434-484136b75427" />
<img width="873" height="336" alt="image" src="https://github.com/user-attachments/assets/45a4dbb8-6b3c-4059-bad2-d6037d9948b9" />

#  Cài đặt NSSM qua link: https://nssm.cc/release/nssm-2.24.zip
#  nhận file giải nên lấy file nssm trong win64 rồi copy về nodered
<img width="830" height="378" alt="image" src="https://github.com/user-attachments/assets/c164391e-412d-4a68-b481-f2b87d7637b7" />

#  Tạo service Node-RED
<img width="857" height="165" alt="image" src="https://github.com/user-attachments/assets/cc44d5b8-3b39-4a9d-bdcb-eb6f9442f8e1" />

#  chạy service
<img width="614" height="75" alt="image" src="https://github.com/user-attachments/assets/7ba72c6f-0e1c-4517-bf6e-2563c6c88329" />

#  hiện như trên là thành công
#  chạy http://localhost:1880 hiện lên là thành công
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/f0b74ede-111b-4ac5-9330-6bf41cf67319" />

# tạo cơ sở dữ liệu đơn giản 

<img width="920" height="465" alt="image" src="https://github.com/user-attachments/assets/5bca9a98-89e5-485d-ae26-06265764165b" />

#  cài thư viện nodered :
node-red-contrib-mssql-plus, node-red-node-mysql, node-red-contrib-telegrambot, node-red-contrib-moment, node-red-contrib-influxdb, node-red-contrib-duckdns, node-red-contrib-cron-plus
<img width="1425" height="873" alt="image" src="https://github.com/user-attachments/assets/823f3e3d-b38f-47e3-b859-589b7a120ef1" />

# Sửa file settings.js để bật đăng nhập admin

<img width="883" height="275" alt="image" src="https://github.com/user-attachments/assets/dc5483de-b563-4480-8af5-a6a269beba42" />

#  sau đó khởi động lại nodered

## tạo api back-end bằng nodered:
<img width="689" height="862" alt="image" src="https://github.com/user-attachments/assets/445dcbd0-1a53-49c2-ad13-00cfcd7e3f63" />

<img width="1097" height="455" alt="image" src="https://github.com/user-attachments/assets/71f5bf14-5ae6-4b10-825d-dc2ea71cd2e4" />

#  tạo frontend: 
<img width="1016" height="327" alt="image" src="https://github.com/user-attachments/assets/4335d7dd-73ae-4fce-a0cb-c63f45e57b74" />

## sau quá trình làm bài e rút ra đc : 
# việc thực hiện khá là đơn giản nhưng để chính xác và hoàn hảo là rất là khó
# các bước phức tạp và dễ lỗi nhất là các phần liên kết phần nodered tạo backend và frontend việc làm này dẫn dễ sai lệch và dến đên skhông chạy được
# việc các phần liên kết với nhau qua notered thông qua các cổng liên kết khá đơn giản và không mất thời gian nhưng cần sự cẩn trọng vì rất dễ lỗi
#






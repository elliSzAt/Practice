Đầu tiên ta thử nhập tài khoản và mật khẩu thông dụng như:  

    admin - admin  
    
    username - password  
    
Và nó không thành công, tiếp theo chúng ta sẽ chiếu trang web này lên Burpsuite tại proxy, sau đó send to repeater.  
  <img width="638" alt="image" src="https://user-images.githubusercontent.com/125866921/220987867-8a73009e-2e6d-4f10-b276-4afbd82b1e5f.png">  

Ta nhận thấy ở phần request chưa có header nào để xác định IP cả, do đó ta thêm phần X-Foward-For vào, tại đây khi nhìn vào phần response thì nó cần chúng ta cung cấp cho 1 IP của mạng LAN. Ta cùng thử với địa chỉ IP sau  192.168.1.17.  
  <img width="638" alt="image" src="https://user-images.githubusercontent.com/125866921/220989375-0c390a09-d61f-4dce-a033-a401c2aa28cc.png">  


password: Ip_$po0Fing

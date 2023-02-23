Tương tự ta cũng chiếu trang web lên Burpsuite ở phần proxy, sau đó send to repeater.  
  <img width="638" alt="image" src="https://user-images.githubusercontent.com/125866921/220974306-c72e781a-d1b2-4afc-b3df-93fb78762871.png">  

    Tại đây ta thấy phần Header-RootMe-Admin: none ở phần respone, do đó nếu muốn tìm ra password ta phải thêm nó vào phần request.  
   
Khi thêm phần Header-RootMe-Admin: vào phần request ta cần cấp cho nó 1 giá trị, ở đây ta thử cấp cho nó 1 giá trị là true.  
  <img width="640" alt="image" src="https://user-images.githubusercontent.com/125866921/220975099-de8709ad-b621-452c-acc4-af0c2a4a4375.png">  
    
    Ta thấy tại phần response đã có sự thay đổi.  
    
password: HeadersMayBeUseful

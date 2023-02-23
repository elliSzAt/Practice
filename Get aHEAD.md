Nhìn vào source-code ta thấy:  
  <img width="665" alt="image" src="https://user-images.githubusercontent.com/125866921/220954104-f75cd453-09e0-4300-8bf3-b8317aad0555.png">  

    Hai phương pháp khác nhau được sử dụng là GET và POST, và trong phần gợi ý có nhắc đến phương thức khác mà ta có thể thấy chính là HEAD. Hãy thử dùng phương thức HEAD để xem kết quả.  
    
Theo gợi ý thì ta sẽ chiếu trang web này lên phần mềm Burpsuite ở phần Proxy, sau đó send to Repeater, tại đây ta chỉ việc thay đổi từ phương thức GET sang HEAD.  
  <img width="1140" alt="image" src="https://user-images.githubusercontent.com/125866921/220959355-df17cdc2-4cb7-443d-96e4-8abd0b6de83a.png">  

    flag: picoCTF{r3j3ct_th3_du4l1ty_6ef27873}

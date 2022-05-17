# WEB:
### NO BACKEND.
   - Vừa đọc tên đề mình đã nghĩ ngay đến vấn đề ở đây là nằm ở Frontend (HTML,CSS,JS,..). 
   - Để đọc code một cách chính xác nhất mình dùng lệnh ```wget``` để lấy hết tệp trên web về.
   
         $ wget -i http://103.245.250.31:32323/#/auth/login
   - Sau khi tải xong ta được một thư mục như sau: 
        ![image](https://user-images.githubusercontent.com/89735990/168854176-3cd983eb-3403-42a6-b5de-ad3dd568c13d.png)
   - Lúc này mình dùng ```$ grep -r "HCMUS" *``` để tìm flag:

        ![image](https://user-images.githubusercontent.com/89735990/168855262-9f0db343-8fad-44eb-94f3-4c613a725dcf.png)
   - Vậy là chúng ta đã có flag ```HCMU{w0w_4uth3ntication_bYP4ss_s000_h4rd}```

# MISC:
### SUPER SECRET.
   - Đọc đề xong mình để ý thấy tên anh Author nên mình check tên anh trên discord và đúng là có link lạ: ```https://pastebin.com/LsNtJMke```
        ![image](https://user-images.githubusercontent.com/89735990/168856972-679a568f-b09a-40fc-b0a4-a6aac915ce25.png)
         
   - Thử Click vào  thì mình tìm được Flag nhưng nó là Rick Roll =)))
   - Quá cay cú vì bị Rick Roll, mình đọc lại đề thì nhận ra là phải tìm kiếm trên Discord.
   - Qua vài lần thử thì mình đã thử với từ ```secret``` trên kênh General: 
   - 
        ![image](https://user-images.githubusercontent.com/89735990/168859094-01d312f4-c6f5-439e-a56a-75b398a9652a.png)

   - Thử dowload tấm ảnh trên Tin Nhắn về và WOW tấm ảnh chính là Secret:
        ![image](https://user-images.githubusercontent.com/89735990/168858469-7658453d-429b-4522-90d3-6089204b6a8d.png)
   - Flag : ```HCMUS-CTF{c291872ada763ed9a480eca240552890}```   

# PWN:
### PRINTME.
![image](https://user-images.githubusercontent.com/89735990/168860364-3e6c4647-70be-47e7-8392-2a360cd68938.png)



   
 


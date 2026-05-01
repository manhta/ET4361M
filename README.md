# ET4361M
https://www.youtube.com/watch?v=56ugUSdDWzw

1. Thay đổi cấu hình HTTP
  idf terminal -> truy cập folder test -> chạy lệnh idf.py menuconfig -> Component config/ESP HTTPS OTA/Allow HTTP for OTA 
2. Server HTTP
   Truy cập folder bất kỳ, chạy python -m http.server 8080
   Để file firmware .bin trong folder này
3. Thay đổi url
   Trong file main/simple_ota_example.c thay đổi .url = "http://[IP_MÁY_TÍNH]:8080/firmware.bin"
   

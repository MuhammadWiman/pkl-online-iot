# PKL ONLINE 

**Materi pkl online untuk microcontroller IOT**

Dalam materi ini akan membahas panduan perakitan soil moisture dan pompa air.
Ada dua tahap yang akan dilakukan dalam merakit soil moisture dan pompa air yaitu: 
- Menampilkan data value dari soil moisture dan pompa air melalui serial monitor
- Mengirimkan data value dari soil moisture dan pompa air melalui serial monitor dan mengirimkan data ke MQTT agar bisa di pantau melalui aplikasi mobile, dan pada materi ini poimpa akan di kontrol secara otomatis.
 
 
 # 1. MATERI 1
 
 **PANDUAN MERAKIT SOIL MOISTURE**
 1. Komponen yang dibutuhkan:
    - Sensor soil moisture FC-28
    
    ![image](https://user-images.githubusercontent.com/18458955/94101022-38fef980-fe59-11ea-9c25-cd27c81c8872.png)

    - Wemos D1 Mini (ESP8266)
    
    ![](https://grobotronics.com/images/detailed/112/wemos-d1-mini-esp8266-wifi-development-board-0_grobo.jpg)
    
    - PCB Bolong jika ingin wiring dengan skema sendiri atau menggunakan PCB Khusus Soil Moisture
    - Kabel Jumper Female-Female jika tidak menggunakan PCB 
    
    ![](https://s1.bukalapak.com/img/134621537/w-1000/Kabel_Jumper_Female___Female_Breadboard_Arduino_Wire_Sensor_.jpg)

    - Box (Opsional)
    
    ![](https://ecs7.tokopedia.net/img/cache/700/product-1/2020/7/19/1060408/1060408_6cbbff5d-9f36-4815-8747-6aa81a5d4fe5_700_700)
    
    - Kabel data usb micro (Kabel harus bisa mengirimkan data bukan hanya power)
    - Adaptor usb 5v 1-2A 
    
    ![](https://www.jakartanotebook.com/images/products/14/63/7501/3/travel-adapter-charge-5v-20a-for-samsung-galaxy-note-ii-white-2.jpg)
   
   
  2. Langkah-langkah merakit:
  
     - Wiring komponen seperi berikut :
     
     ![sooil moisture](https://user-images.githubusercontent.com/18458955/94108775-1c1ef200-fe6a-11ea-9abd-34e59751b45c.png)

     - Lakukan Kalibrasi
       Setelah melakukan perakitan pada senssor moisture dan wemos , sebbaiknya dilakukan kalibrasi terlebih dahulu pada komponen untuk mencegah penggunaan komponen yang rusak serta memudahkan untuk melakukan annallissa jika tejadi kesalahan.
       - Kalibrasi pada wemooss D1 Mini
            Langkah-langkah yang harus dilakukan ketika akan melakukan kalibrasi pada wemos adalah sebagai berikut:
            - Pastikan pin male  telah terpasang dan tidak saling terhubung nat pinnya.
            - Siapkan avometer , analog / digital.
            - Seiapkan kabel adapter / kabel usb yanng akan digunakan sebagai sumbber tegangan wemos dan sebagai uploader program wemos.
            - Setelah semua komponen siap, maka hubungkan kabel charger pada wemos board, lalu hubungkan probe (+) pada avometer ke pin tegangan(yangg 5V atau 3V) kemudian nprboe negatif (-) pada avometer ke pin ground.
            - Setelah tepasang, nyalakan avometer, pasang ke posisi teggangann , pastikan sebelum digunakan, avometer pun sudah dilakukan kalibrasi.
            - Lalu perrhatikan nilai yang ditunjukan avometer, jika ppada teganggan 3V, maka jarum avometer (analog) akan berada di angka 2 hingga 3, jika pada avometer digital akann menunjukan angka 2,5 hingga 3,3V.
            
       - Kalibrasi pada komponen soil moisture
            Langkah-langkah  yang harus dilakukan ketika akan melakukan kalibrasi pada soil moisture adalah sebagai berkut:
            - 

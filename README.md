Dalam menginput perintah ke sistem, penulis menggunakan Software Arduino IDE untuk menulis kode program sistem kipas otomatis.
Mikrokontroller ESP-32 menggunakan Drive USB, Software Arduino IDE, ESP-32 dan kabel USB agar program dapat di upload dan berjalan di dalam mikrokontroller ESP-32. 
Berikut adalah kode program berupa bahasa C yang fungsinya berjalan sesuai flowchart berikut adalah program kipas angin otomatis:program lek
Sistem kipas angin otomatis bekerja berdasarkan 2 kontrol yaitu kontrol manual dan kontrol otomatis berdasarkan suhu. 
Kontrol Manual bekerja dengan input dari button yang ada di Blynk lalu akan diproses mikrokontroller, selanjutnya mikro akan mengirim trigger ke relay berupa output HIGH maka relay akan bekerja lalu arus akan mengalir ke kipas dan menggerakan motor kipas.
Kontrol Otomatis bekerja dengan cara memberikan batasan berupa suhu, untuk menyalakan mode otomatis, maka mikro menerima input dari button yang ada di Blynk lalu akan diproses mikrokontroller lalu batasan suhu akan dibandingkan dengan suhu terbaru. 
Jika memenuhi syarat maka mikro akan mengirim trigger ke relay berupa output HIGH sehingga relay akan bekerja lalu arus akan mengalir ke kipas dan menggerakan motor kipas. 
Jika tidak memenuhi syarat maka mikro akan mengirim trigger ke relay berupa output LOW sehingga relay akan bekerja lalu arus diputus menyebabkan kipas akan berhenti, ketika mode otomatis bekerja maka mode manual tidak bisa di aktifkan. 

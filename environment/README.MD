# LAB PEMROGRAMAN JARINGAN

Dalam MK pemrograman jaringan, disediakan 4 buah mesin dengan IP address sebagai berikut.

Mesin-mesin tersebut berupa docker container. tiap-tiap mesin dapat diakses dengan mengakses url melalui web browser

- mesin1 : 172.16.16.101 http://172.16.16.101:8888
- mesin2 : 172.16.16.102 http://172.16.16.102:8888
- mesin3 : 172.16.16.103 http://172.16.16.103:8888
- mesin4 : 172.16.16.104 http://172.16.16.104:8888

## LANGKAH-LANGKAH

*untuk windows, gunakan wsl2*

- install docker dan docker-compose
- jalankan `docker-compose up -d`
- cek dengan perintah : `docker-compose ps`
  
  <img width="358" alt="image" src="https://user-images.githubusercontent.com/68428942/161257673-7c6b0ad0-91c3-4f17-882e-8358140035c2.png">

Download/clone materi untuk pemrograman jaringan di https://github.com/rm77/progjar dengan cara

- akses ke salah satu mesin
- buka terminal (di bagian launcher)
- akseslah layar terminal, ketiklah command berikut ini
  * cd work
  * git clone  https://github.com/rm77/progjar
  * akan menghasilkan direktori "progjar", untuk menjalankan gunakan command `python3 <namaprogram.py>`
  







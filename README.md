## Responsi Syaiful Mustafa (175410158)
1. Materi Praktikum 1: Git

URL: [https://github.com/sfmusta/tcc/tree/master/minggu-01](https://github.com/sfmusta/tcc/tree/master/minggu-01)

Ringkasan: Pertemuan pertama adalah tentang penggunaan dasar Git. Dari melihat versi git yang terinstall, melakukan pembuatan repository pada Github, melakukan clone repository, dan menambahkan file/ directory ke repository.

2. Materi Praktikum 2: Git (lanjutan)

URL: [https://github.com/sfmusta/tcc/tree/master/minggu-02](https://github.com/sfmusta/tcc/tree/master/minggu-02)

Ringkasan: Praktikum 2 melanjutkan praktikum pada pertemuan 1.

3. Materi Praktikum 3: Saas

URL: [https://github.com/sfmusta/tcc/tree/master/minggu-03](https://github.com/sfmusta/tcc/tree/master/minggu-03)

Ringkasan: Pada pertemuan ini belajar tentang definisi, sejarah, dan contoh dari SaaS (Software as a Service).

4. Materi Praktikum 4: BPaaS

URL: [https://github.com/sfmusta/tcc/tree/master/minggu-04](https://github.com/sfmusta/tcc/tree/master/minggu-04)

Ringkasan: Pertemuan ini membahas tentang BPaaS (Business Process as a Service). 

5. Materi Praktikum 5: CockroachDB

URL: [https://github.com/sfmusta/tcc/tree/master/minggu-05](https://github.com/sfmusta/tcc/tree/master/minggu-05)

Ringkasan: Pertemuan ini belajar tentang CockroachDb. Banyak cara untuk melakukan instalasi, pada pertemuan ini melakukan instalasi CockroachDb menggunakan Docker. 

6. Materi Praktikum 6: Docker

URL: [https://github.com/sfmusta/tcc/tree/master/minggu-06](https://github.com/sfmusta/tcc/tree/master/minggu-06)

Ringkasan: Pada pertemuan ini belajar tentang Docker melalui online course. Praktik pertama adalah menjalankan image Redis menjadi sebuah container. Pada praktik 2 membuat Dockerfile untuk membuah sebuah layanan web menggunakan image nginx. Praktik ke 3 membuah membuat container menggunakan base image nginx.

7. Materi Praktikum 7: Zeit Now

URL: [https://github.com/sfmusta/tcc/tree/master/minggu-07](https://github.com/sfmusta/tcc/tree/master/minggu-07)

Ringkasan: Pertemuan ini belajar tentang Zeit Now, yaitu sebuah platform untuk mendeploy berbagai bahasa pemrograman. Pada praktik ini menggunakan Node.js.

8. Materi Praktikum 8: Python Flask

URL: [https://github.com/sfmusta/tcc/tree/master/minggu-08](https://github.com/sfmusta/tcc/tree/master/minggu-08)

Ringkasan: Flask merupakan salah satu Framework yang menggunakan bahasa pemrograman python. Flask diinstal menggunakan Docker. Agar lebih mudah maka menggunakan Dockerfile. Flask listen pada port 5000.

9. Materi Praktikum 9: Python Flask (lanjutan)

URL: [https://github.com/sfmusta/tcc/tree/master/minggu-09](https://github.com/sfmusta/tcc/tree/master/minggu-09)

Ringkasan: Pertemuan ini melanjutkan pertemuan 08 bagi yang belum menyelesaikan.

10. Materi Praktikum 10: Git Colaboration

URL: [https://github.com/sfmusta/tcc/tree/master/minggu-10](https://github.com/sfmusta/tcc/tree/master/minggu-10)

Ringkasan: Mencoba kolaborasi menggunakan git. Dilakukan skenario penulisan sebuah file oleh banyak user. Ini akan menimbulkan terjadinya conflict. Conflict dapat ditangani oleh owner repository, atau user yang memiliki hak akses lebih.

11. Materi Praktikum 11: IaaS (Infrastructur as a Service)

URL: [https://github.com/sfmusta/tcc/tree/master/minggu-11](https://github.com/sfmusta/tcc/tree/master/minggu-11)

Ringkasan: Pada pertemuan ini belajar tentang IaaS. dari Konsep Dasar, Software IaaS, Arsitektur dan Konsep Deployment IaaS, danpenggunaan IaaS.

12. Materi Praktikum 12: Docker Compose Drupal

URL: [https://github.com/sfmusta/tcc/tree/master/minggu-12](https://github.com/sfmusta/tcc/tree/master/minggu-12)

Ringkasan: Pertemuan ini belajar tentang docker compose. yaitu sebuah software yang dapat digunakan untuk menjalankan banyak container dalam sebuah perintah. Pada pertemuan ini menjalankan sebuah layanan Web dengan CMS Drupal menggunakan Docker-compose. Service yang digunakan adalah Drupal sebagai Web Interface dan Postgres untuk database.

13. Materi Praktikum 13: Docker Swarm

URL: [https://github.com/sfmusta/tcc/tree/master/minggu-13](https://github.com/sfmusta/tcc/tree/master/minggu-1)

Ringkasan: Docker Swarm adalah membuat layanan Docker yang terdiri dari banyak PC (nodes). Nodes tadi memiliki perannya masing-masing, ada yang sebagai Manager ada juga yang sebagai Worker. Pada praktikum terdapat 2 Node, Node1 berperan sebagai Manager (melakukan advertise melalui IP 10.55.1.1),  dan Node2 dihubungkan ke node1 menggunakan `docker swarm join`. Untuk melihat daftar node yang terhubung dapat menggunakan `docker node ls`.  Untuk menjalankan sebuah layanan dari docker-compose, dapat menggunakan perintah `
docker stack deploy --compose-file docker-compose.yml <nama-stack>. 
`
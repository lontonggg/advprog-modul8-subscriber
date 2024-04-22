## Reyhan Zada Virgiwibowo
## 2206081723
## Advanced Programming - C
## Modul 8 - Subscriber

## a. What is ampq?

AMQP adalah singkatan dari Advanced Message Queuing Protocol, sebuah protokol lapisan aplikasi yang terbuka untuk message-oriented middleware. Protokol ini digunakan untuk pertukaran pesan antara aplikasi, terutama dalam skenario di mana ada kebutuhan untuk komunikasi yang asinkron. AMQP menyediakan cara bagi sistem perangkat lunak yang berbeda untuk berkomunikasi satu sama lain menggunakan bahasa yang umum. AMQP mendefinisikan format dan aturan untuk mengirim dan menerima pesan antara sistem, termasuk fitur seperti antrian pesan, routing, dan keamanan.

## b. What it means? guest:guest@localhost:5672 , what is the first quest, and what is the second guest, and what is localhost:5672 is for?

Guest yang pertama menandakan username pengguna yang dipakai untuk authentication di RabbitMQ server yang by default memiliki username "guest". Guest kedua mewakili passwordnya. Di RabbitMQ, by default passwordnya adalah "guest" juga. localhost:5672 adalah hostname dan port number broker AMQP. Dalam kasus ini, localhost broker berjalan pada mesin yang sama di mana kode dijalankan, dan 5672 adalah default port untuk komunikasi AMQP.
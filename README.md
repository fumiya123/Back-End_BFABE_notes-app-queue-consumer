# Back-End_BFABE_notes-app-queue-consumer
Project Latihan dari Kelas Belajar Fundamental Aplikasi Back-End — Dicoding Indonesia

Lanjutan dari proyek **notes-app-back-end**, membuat Program Consumer untuk menerima pesan yang masih berada di queue.

Install package dependencies yang di butuhkan:

`npm install amqplib pg dotenv nodemailer`

- amqplib : untuk berinteraksi dengan protokol AMQP dalam menerima pesan dari queue.
- pg : untuk berinteraksi dengan Postgres Database.
- dotenv : untuk mengelola environment variable di Node.js proyek.
- nodemailer : untuk mengirimkan email melalui Node.js.


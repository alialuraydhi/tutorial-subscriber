a. Apa itu AMQP?
AMQP (Advanced Message Queuing Protocol) adalah protokol standar terbuka yang dirancang untuk middleware berbasis pesan. Protokol ini memungkinkan sistem atau aplikasi untuk saling berkomunikasi melalui pesan dengan cara yang andal, aman, dan asynchronous (tidak langsung). AMQP sangat cocok digunakan untuk berbagai kebutuhan seperti aplikasi chat real-time, sistem terdistribusi, hingga solusi Internet of Things (IoT). Salah satu implementasi AMQP yang paling populer adalah RabbitMQ, yang akan digunakan pada bagian tutorial berikutnya.

b. Apa arti dari guest:guest@localhost:5672?
`guest:guest@localhost:5672` adalah URI (Uniform Resource Identifier) yang mengarah ke server AMQP. Format umum dari URI ini adalah:

`amqp://<username>:<password>@<hostname>:<port>`

Berdasarkan format tersebut, kita bisa mengartikan:

```html
Protokol: amqp

Username: guest

Password: guest

Host: localhost (mengacu pada komputer lokal)

Port: 5672 (port standar/default untuk komunikasi AMQP)
```

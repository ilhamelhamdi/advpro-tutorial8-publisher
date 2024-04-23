# Tutorial 8 - Publisher

Nama : Ilham Abdillah Alhamdi <br>
NPM : 2206081194 <br>
Kelas : Advance Programming A <br>

1. How many data your publisher program will send to the message broker in one run?
   Terdapat 5 publisher program yang akan dijalankan secara bersamaan karena terdapat 5 buah pemanggilan `p.publish_event`.

2. The url of: `amqp://guest:guest@localhost:5672` is the same as in the subscriber
program, what does it mean?
    Kedua url sama saja karena keduanya mengirim request ke server rabbitMQ. Hanya saja, publisher mengirim pesan ke queue sementara subscriber akan mendapatkan data dari queue.

3. RabbitMQ Overview
    ![Rabbit MQ's Overview](./assets/images/rabbitmq-overview.png)

4. Publisher mengirim messages ke RabbitMQ. Subscriber membaca messages dari RabbitMQ
    ![Publishing & Reading message](./assets/images/rabbitmq-console-running.png)
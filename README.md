[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/mRmkZGKe)
# Network Programming - Assignment G01

## Anggota Kelompok
|            Nama          | NRP        | Kelas     |
| ---                      | ---        | ----------|
| Rafael Mulia Wiratama S. | 5025241196 | C          |


## Link Youtube (Unlisted)
Link ditaruh di bawah ini
```

```

## Penjelasan Program
Program ini merupakan implementasi TCP File Server dengan multi-client support.

Terdapat 4 jenis server:
1. server-sync.py → hanya melayani 1 client
2. server-thread.py → menggunakan threading
3. server-select.py → menggunakan select
4. server-poll.py → menggunakan poll

Fitur:
- Broadcast message
- /list → melihat file di server
- /upload → upload file ke server
- /download → download file dari server

Client dapat terhubung ke server dan mengirim command melalui terminal.

## Screenshot Hasil
### Server Berjalan dan Dua Client terhubung (Multi Client Connect)
<img width="1919" height="1053" alt="image" src="https://github.com/user-attachments/assets/d840f55f-b633-4fd2-8ff8-dea5ee96e86c" />

### Broadcast Message
<img width="1363" height="405" alt="image" src="https://github.com/user-attachments/assets/2242a47f-69ec-48f1-96a4-d548bcfaeda9" />

### Command /upload, /list, dan /download
<img width="1380" height="391" alt="image" src="https://github.com/user-attachments/assets/f3a00b87-0813-424b-ab6b-164cf69b076a" />
Dari Terminal lain kita jalankan dulu :

      echo "test upload" > test.txt
Untuk membuat file yang digunakan sebagai tes command-command yang tersedia dari program.


- /upload
<img width="1378" height="404" alt="image" src="https://github.com/user-attachments/assets/ee6a08f1-7798-49ad-8637-242d6dfb0be5" />
<img width="302" height="649" alt="image" src="https://github.com/user-attachments/assets/3ee7f215-7f9b-4148-9f3f-673a64e9883b" />

Seperti yang dilihat file test.txt sudah di upload ke dalam folder /files. 

- /list
<img width="1391" height="397" alt="image" src="https://github.com/user-attachments/assets/bb3b6777-83d3-42ba-ae95-f553b72d3204" />

Sesuai pada gambar berikut, command /list menunjukkan isi dari folder /files yang sekarang terdapat file test.txt setelah di upload.

- /download
<img width="1383" height="400" alt="image" src="https://github.com/user-attachments/assets/81692969-6a3e-4ae0-9e8e-402c574bec49" />
<img width="282" height="315" alt="image" src="https://github.com/user-attachments/assets/677e9225-7b25-4c3a-88bf-594706b64749" />



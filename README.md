## Eksperimen: Membangun Aplikasi Chat Real-Time dengan Node.js

## Setup Lingkungan Pengujian
1. Node.js 18.x untuk backend dan manajemen paket (npm)
   
2. Express.js dan ws (WebSocket) sebagai pustaka server

3. HTML dan JavaScript murni untuk antarmuka pengguna

4. Visual Studio Code (opsional) untuk pengembangan

5. Terminal atau Command Prompt untuk menjalankan server

## Langkah instalasi dan konfigurasi:

## 1. Unduh dan instal Node.js dari https://nodejs.org

## 2. Melakukan inisialisasi proyek dan pasang dependensi yang dibutuhkan menggunakan command prompt dengan perintah berikut :
   
           npm init -y
   
           npm install express ws

Perintah pertama (npm init -y) akan membuat file package.json secara otomatis, sedangkan perintah kedua menginstal Express.js untuk server HTTP dan ws sebagai pustaka WebSocket.
   
## 3. Membuat struktur folder proyek

   ![strukturfolderproyek](https://github.com/user-attachments/assets/f414480e-f4a6-40e1-9f14-aeeb827bbdd0)

   • node_modules/: Sebagai Direktori dependensi.
   
   • package.json: Sebagai Konfigurasi proyek.
   
   •	server.js: Server utama digunakan untuk membuat server WebSocket dan HTTP.
   
   •	public/index.html: Antarmuka pengguna menjadi tampilan pengguna aplikasi chat.
   
## 4. Membuat server WebSocket dan HTTP (server.js)
   
   ![js](https://github.com/user-attachments/assets/92b13ff8-6210-435e-9d6c-a6ad13f14530)

## 5. Membuat tampilan HTML (Frontend) File ini disimpan di  (public/index.html)

   ![indexhtml](https://github.com/user-attachments/assets/8d0c62c2-c7f0-4897-8632-d43ee58e2577)
   
## 6. Menjalankan aplikasi chat dua arah ini menggunakan command prompt dengan perintah node server.js, jika sudah terhubung maka akan muncul Server berjalan di http://localhost:3000 seperti digambar ini :

   ![CMD](https://github.com/user-attachments/assets/6e94e3fa-0765-4b8b-939b-dd023046bbed)
   
## 7. Buka dua tab browser di alamat http://localhost:3000. Jika sudah, Kirim pesan dari salah satu tab, lalu lihat apakah pesan yang dikirim dari tab pertama muncul secara langsung di tab kedua.

## Tampilan pada tab pertama sebagai Server :
   
• Isi username terlebih dahulu , untuk username penulisan nama yang ingin dipakai opsional, kalau disini menggunakan nama (Server) seperti digambar ini:
   
   ![SERVERR](https://github.com/user-attachments/assets/e23043a4-8456-4dc0-a68c-d74656a47313)

   ![NAME](https://github.com/user-attachments/assets/e6d4cbfd-86d2-45f2-b563-7b04a846958e)

• Maka akan muncul tampilan untuk mengirim pesannya, seperti ini :

   ![TAMPILAN](https://github.com/user-attachments/assets/29791e45-a3e9-4bc7-bc30-3ff529d3f1a6)

## Tampilan tab kedua sebagai client :
   
   • Untuk tampilan awalnya masih sama seperti tampilan di tab pertama tadi, yang dibedakan hanya username-nya saja. Disini username-nya sebagai Client seperti digambar ini :

   ![NAMA](https://github.com/user-attachments/assets/ff92ba77-e24e-4e92-bcc7-b42dbe2008e0)
     
   ![CLIENT](https://github.com/user-attachments/assets/d5f4fd19-82e0-4caa-83a1-61383cb40c6c)
   
## Setelah itu, akan  muncul tampilan sama seperti tab pertama :

   ![client awal](https://github.com/user-attachments/assets/c6083bcf-015e-45b9-a6aa-bb3f19862f7d)

## 8. Mengirim chat dari Server ke Client
   
   ![chat](https://github.com/user-attachments/assets/1444ac46-302a-4baa-b7eb-e603d89f58d5)
   
   ![server hallo](https://github.com/user-attachments/assets/f351640e-3cdb-4a52-8c92-2d2e3759bb4d)
   
## 9. Tampilan pada halaman Client jika pesan sudah terkirim dari Server :
   
   ![HASILCHAT](https://github.com/user-attachments/assets/9a4467b2-dfbc-47df-ba78-b73d1212b4f3)
   
## 10. Mencoba membalas pesan dari Client ke Server :

   ![gantianchat](https://github.com/user-attachments/assets/9a5c952c-7783-49d5-b4d4-3005a7674a81)

## Tampilan Server jika Client membalas pesannya :

   ![BALESANSERVER](https://github.com/user-attachments/assets/51d5b46d-68bc-4f12-953a-e521e6c88215)

## SELESAI

    




   



   













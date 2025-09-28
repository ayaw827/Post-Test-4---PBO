# Post Test 4 PBO

Nurhidayah
2409116002

## Penjelasan Kode Program

### 1. Abstraction (Getter dan Setter)

Enkapsulasi dipakai untuk menjaga agar data produk tidak bisa diakses sembarangan dari luar class. Misalnya, atribut id, nama, kategori, harga di dalam class Produk dibuat private. Supaya tetap bisa diakses maka dibuatlah getter dan setter agar nanti ada aturan tambahan, contohnya harga tidak boleh negatif dan cukup ditaruh di setHarga() dan tidak perlu menghambur logika di tempat lain, jadi data lebih aman dan rapi.

<img width="1111" height="282" alt="image" src="https://github.com/user-attachments/assets/1051e700-2606-4f85-a945-92bd9fe931fc" />

### 2. Polymorphism (Warisan)

Program ini juga menggunakan inheritance supaya jenis produk bisa berbeda tapi tetap punya struktur dasar yang sama. Class Produk dijadikan superclass, sedangkan Pakaian, Selimut, dan CelanaJeans dijadikan subclass. Semua subclass otomatis mewarisi atribut id, nama, kategori, harga dari Produk. Tapi yang membedakan subclass itu karena ada tambahan atribut masing-masing, misalnya Pakaian punya atribut ukuran, Selimut punya atribut bahan, dan CelanaJeans punya atribut warna.

<img width="1264" height="745" alt="image" src="https://github.com/user-attachments/assets/d7fc4e04-71cc-4edd-9196-22426a4fe61f" />

<img width="1292" height="748" alt="image" src="https://github.com/user-attachments/assets/123c57dd-7109-4017-a333-d70f482cb64d" />

<img width="710" height="176" alt="image" src="https://github.com/user-attachments/assets/9de7cb0e-41ba-4949-b370-7f106ccad160" />

### 3. Overridinng (Override)
Overriding adalah kemampuan subclass untuk menimpa (override) method yang sudah ada di superclass dengan implementasi yang berbeda. Ciri-cirinya adalah mempunyai nama method sama dan parameter sama.

<img width="710" height="176" alt="image" src="https://github.com/user-attachments/assets/09ee87a1-f542-46ea-822f-27da3b1cae57" />

<img width="751" height="206" alt="image" src="https://github.com/user-attachments/assets/4d884c90-af1b-4f61-bf71-6f6ef1c4fc55" />

<img width="738" height="225" alt="image" src="https://github.com/user-attachments/assets/74a68844-7c8d-4090-ac90-c4cdcdc9e50e" />

## Penjelasan Alur Program

# Post Test 4 PBO

Nurhidayah
2409116002

## Penjelasan Kode Program

### 1. Abstraction (Getter dan Setter)

#### Abstract pada Class Produk

lass abstract Produk sebagai cetakan umum semua produk. Di dalamnya disimpan data dasar seperti id, nama, kategori, dan harga, serta method abstract infoProduk() yang belum memiliki isi. Setiap subclass seperti Pakaian atau Selimut wajib mengisi cara menampilkan informasi produknya masing-masing. 

<img width="1071" height="403" alt="image" src="https://github.com/user-attachments/assets/c64e3891-3359-4c5b-9121-4051e0cb5304" />

<img width="487" height="720" alt="image" src="https://github.com/user-attachments/assets/d3a00667-e310-4e0f-b79e-a92e61ee35fd" />

<img width="365" height="66" alt="image" src="https://github.com/user-attachments/assets/81b77915-13bd-4d8e-a7e9-9157f22f50ef" />

#### Interface Diskon

Interface Diskon yang bertindak seperti kontrak, sehingga setiap produk yang mengimplementasikannya harus menyediakan perhitungan diskon sendiri. Dengan abstraction ini, data produk lebih teratur dan mudah dikembangkan tanpa harus mengubah struktur utama.

<img width="368" height="115" alt="image" src="https://github.com/user-attachments/assets/952d1d93-0b71-4d0e-846a-2c5aed038917" />

### 2. Polymorphism

Pada method hitungDiskon, yang memiliki beberapa versi: satu hanya memakai parameter persentase, dan satu lagi memakai persentase sekaligus batas maksimum potongan. Kedua method memiliki nama sama tapi parameter berbeda, sehingga cara pemanggilannya bisa menyesuaikan kebutuhan.

<img width="819" height="461" alt="image" src="https://github.com/user-attachments/assets/d3428aef-aca8-4193-80be-9afc02b0c6c5" />

Overriding erjadi saat subclass menimpa method abstract infoProduk() dari Produk. Meskipun nama method sama, tiap produk menampilkan format informasi yang berbeda sesuai jenisnya. Dengan polymorphism ini, program dapat memanggil method yang sama tetapi menghasilkan perilaku yang sesuai dengan objek yang sedang digunakan.

<img width="831" height="155" alt="image" src="https://github.com/user-attachments/assets/53fdea68-bbab-4d79-8053-123a5d758485" />

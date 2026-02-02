# JavaScript Standard Library – Contoh Dasar

Repositori ini berisi kumpulan file **HTML + JavaScript** yang berfungsi sebagai **contoh penggunaan JavaScript Standard Library**. Setiap file berdiri sendiri dan fokus pada satu topik utama.

---

## 📁 Daftar File & Penjelasan

Bagian ini menjelaskan **fungsi, tujuan, dan konsep utama** dari setiap file. Semua contoh menggunakan **JavaScript standar (tanpa framework)** dan ditulis untuk pemula.

---

### 1. `array.html`
**Array** digunakan untuk menyimpan banyak nilai dalam satu variabel.

Dipakai untuk:
- Menyimpan daftar data (nama, angka, objek)
- Melakukan iterasi data

Konsep utama:
- Index array dimulai dari 0
- Array bersifat dinamis

---

### 2. `bigint.html`
**BigInt** adalah tipe data untuk bilangan bulat yang melebihi batas aman `Number`.

Dipakai untuk:
- Perhitungan angka sangat besar
- Kriptografi, ID besar, data finansial

Catatan:
- Ditandai dengan akhiran `n`
- Tidak bisa dicampur langsung dengan `Number`

---

### 3. `boolean.html`
**Boolean** hanya memiliki dua nilai: `true` dan `false`.

Dipakai untuk:
- Logika program
- Percabangan (`if`, `while`)

Sumber nilai Boolean:
- Hasil perbandingan
- Konversi nilai (truthy / falsy)

---

### 4. `date.html`
Objek **Date** digunakan untuk mengelola waktu dan tanggal.

Dipakai untuk:
- Menampilkan tanggal sekarang
- Menghitung umur, waktu, deadline

Catatan:
- Bulan dimulai dari 0 (Januari = 0)

---

### 5. `encode.html`
Digunakan untuk **mengamankan URL**.

Dipakai untuk:
- Parameter URL
- Data query string

Fungsi utama:
- `encodeURI()`
- `decodeURI()`

---

### 6. `eval.html`
`eval()` menjalankan kode JavaScript dari string.

Dipakai untuk:
- Contoh konsep evaluasi kode

⚠️ **Tidak disarankan untuk produksi** karena risiko keamanan.

---

### 7. `json.html`
**JSON** adalah format pertukaran data paling umum di web.

Dipakai untuk:
- API
- Penyimpanan dan transfer data

Fungsi utama:
- `JSON.parse()` → string ke object
- `JSON.stringify()` → object ke string

---

### 8. `map.html`
**Map** menyimpan pasangan key–value seperti Object, tapi lebih fleksibel.

Kelebihan Map:
- Key bisa tipe apa saja
- Urutan data terjaga

---

### 9. `math.html`
Objek **Math** menyediakan fungsi matematika.

Dipakai untuk:
- Pembulatan angka
- Angka acak
- Operasi matematika umum

---

### 10. `number.html`
**Number** adalah tipe data numerik utama di JavaScript.

Dipakai untuk:
- Perhitungan
- Representasi angka

Catatan:
- JavaScript menggunakan floating point

---

### 11. `object.html`
**Object** adalah struktur data paling dasar di JavaScript.

Dipakai untuk:
- Representasi entitas (user, produk)
- Struktur data kompleks

---

### 12. `proxy.html`
**Proxy** memungkinkan intersepsi operasi pada object.

Dipakai untuk:
- Validasi
- Logging
- Kontrol akses

---

### 13. `reflect.html`
**Reflect** menyediakan method standar untuk operasi object.

Dipakai bersama Proxy untuk:
- Operasi aman
- Meta programming

---

### 14. `regexp.html`
**Regular Expression** digunakan untuk pencocokan pola teks.

Dipakai untuk:
- Validasi input
- Pencarian teks

---

### 15. `sample.json`
File JSON statis sebagai **sumber data contoh**.

Dipakai oleh:
- `sample.html`
- Latihan fetch dan parsing JSON

---

### 16. `set.html`
**Set** menyimpan nilai unik.

Dipakai untuk:
- Menghapus duplikasi
- Koleksi data unik

---

### 17. `string.html`
**String** digunakan untuk teks.

Dipakai untuk:
- Manipulasi teks
- Format output

---

### 18. `symbol.html`
**Symbol** adalah identifier unik.

Dipakai untuk:
- Key tersembunyi pada object
- Menghindari konflik properti
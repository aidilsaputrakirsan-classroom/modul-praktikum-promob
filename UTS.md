# UTS Pemrograman Mobile
## Ujian Tengah Semester - Teori & Praktik

**Mata Kuliah:** Pemrograman Mobile  
**Durasi Total:** 3 jam (1 jam teori + 2 jam praktik)  
**Bobot:** Teori 40% + Praktik 60%  
**Tools yang Diizinkan:** AI Assistant (ChatGPT, Claude, DeepSeek), Dokumentasi, Internet

---

## 📋 Gambaran Umum UTS

### **Struktur Ujian:**
- **Teori (40%):** 1 jam - Pilihan ganda + Esai
- **Praktik (60%):** 2 jam - Membuat aplikasi mobile lengkap
- **Penggunaan AI:** Diperbolehkan dengan batasan tertentu
- **Repository:** Proyek baru terpisah dari HelloWorld

### **Cakupan Materi:**
- Week 1: Dasar-dasar Mobile Development
- Week 2: Komponen Inti React Native 
- Week 3: Manajemen State & Input Pengguna
- Week 4: Navigasi & Multiple Screen
- Week 6: Penyimpanan Data Lokal (AsyncStorage)

**Catatan:** *Materi Week 5 (API) dan Week 7 (Animasi) tidak diujikan di UTS*

---

## 📖 BAGIAN 1: TEORI (40% - 60 menit)

### **Format Ujian Teori:**
- **Pilihan Ganda:** 15 soal (30 poin)
- **Esai Pendek:** 4 soal (30 poin)
- **Total:** 60 poin
- **Waktu:** 60 menit
- **Catatan:** Tidak diperbolehkan menggunakan AI untuk bagian teori

---

### **A. PILIHAN GANDA (15 soal - 30 poin)**

**Petunjuk:** Pilih jawaban yang paling tepat (2 poin per soal)

**1. Apa perbedaan utama antara React Native dan pengembangan web React?**
a) React Native menggunakan JavaScript, React web menggunakan HTML
b) React Native menggunakan komponen native, React web menggunakan elemen DOM
c) React Native lebih lambat dari React web
d) Tidak ada perbedaan signifikan

**2. Komponen manakah yang TIDAK tersedia di React Native?**
a) View
b) Text
c) div
d) TouchableOpacity

**3. Untuk styling di React Native, property mana yang TIDAK valid?**
a) backgroundColor
b) margin-top (dengan tanda strip)
c) fontSize
d) borderRadius

**4. Bagaimana cara yang benar untuk mengelola state di functional component React Native?**
a) this.setState()
b) useState hook
c) componentDidMount()
d) menggunakan variabel biasa

**5. Komponen mana yang digunakan untuk input teks di React Native?**
a) Input
b) TextInput
c) TextField
d) InputField

**6. Dalam Expo Router, bagaimana cara membuat navigasi tab?**
a) Membuat folder bernama (tabs) di dalam app/
b) Menggunakan createBottomTabNavigator
c) Membuat file tabs.js
d) Menggunakan TabView component

**7. Hook mana yang digunakan untuk efek samping seperti loading data?**
a) useState
b) useEffect
c) useContext
d) useCallback

**8. Untuk menyimpan data secara permanen di React Native, library apa yang digunakan?**
a) localStorage
b) sessionStorage
c) AsyncStorage
d) FileStorage

**9. Apa fungsi dari StyleSheet.create() di React Native?**
a) Membuat animasi
b) Mengoptimalkan performa styling
c) Membuat komponen baru
d) Mengelola state

**10. Dalam navigasi Stack, apa yang terjadi ketika memanggil router.push()?**
a) Mengganti screen saat ini
b) Menambah screen baru ke stack
c) Kembali ke screen sebelumnya
d) Menutup aplikasi

**11. Untuk menampilkan daftar data yang panjang, komponen mana yang paling efisien?**
a) ScrollView dengan map()
b) FlatList
c) View dengan map()
d) Text dengan map()

**12. Apa perbedaan utama antara View dan ScrollView?**
a) View untuk teks, ScrollView untuk gambar
b) View tidak bisa di-scroll, ScrollView bisa di-scroll
c) Tidak ada perbedaan
d) ScrollView lebih lambat

**13. Bagaimana cara yang benar untuk handle tombol di React Native?**
a) Menggunakan button HTML
b) Menggunakan TouchableOpacity dengan onPress
c) Menggunakan onClick seperti di web
d) Menggunakan tap gesture

**14. Untuk validasi form, kapan biasanya validasi dilakukan?**
a) Hanya saat submit
b) Saat onChangeText dan onSubmit
c) Hanya saat aplikasi dimulai
d) Tidak perlu validasi

**15. Apa kegunaan dari key prop dalam rendering list di React Native?**
a) Untuk styling
b) Untuk optimasi re-rendering
c) Untuk navigasi
d) Tidak ada kegunaan khusus

---

### **B. ESAI PENDEK (4 soal - 30 poin)**

**Petunjuk:** Jawab dengan jelas dan singkat (7.5 poin per soal)

**1. Jelaskan perbedaan antara Flexbox di React Native dan CSS web! Berikan contoh penggunaan yang berbeda! (7.5 poin)**

**2. Mengapa AsyncStorage diperlukan di aplikasi mobile? Sebutkan 3 contoh kasus penggunaan yang tepat! (7.5 poin)**

**3. Jelaskan alur kerja useState dan useEffect dalam functional component! Berikan contoh sederhana! (7.5 poin)**

**4. Apa saja yang perlu diperhatikan saat membuat form input di mobile? Sebutkan minimal 3 aspek penting! (7.5 poin)**

---

## 💻 BAGIAN 2: PRAKTIK (60% - 120 menit)

### **Skenario Ujian Praktik:**

**Tugas:** Membuat aplikasi **"Katalog Toko Online"** 

**Deskripsi:** Aplikasi untuk mengelola katalog produk toko, di mana pemilik toko dapat menambah, mengedit, dan menghapus produk, serta mengkategorikan produk-produk tersebut.

**Durasi:** 120 menit  
**Penggunaan AI:** Diperbolehkan dengan pembatasan  
**Repository:** Buat proyek baru bernama `UTS_NIM_Nama`

---

### **📱 Spesifikasi Aplikasi**

#### **Fitur Inti (Wajib - 70 poin):**

**1. Halaman Autentikasi (10 poin)**
- Login sederhana dengan nama toko (validasi minimal)
- Halaman welcome dengan nama toko
- Fungsi logout

**2. Struktur Navigasi (10 poin)**
- Tab Navigation dengan 3 tab:
  - 🏪 **Beranda** - Ringkasan dan tombol cepat
  - 📦 **Produk** - Manajemen produk
  - 📂 **Kategori** - Manajemen kategori

**3. Manajemen Produk (25 poin)**
- Tambah produk baru (nama, harga, kategori, deskripsi)
- Edit produk yang sudah ada
- Hapus produk
- Tampilkan daftar produk dalam bentuk kartu
- Penyimpanan data dengan AsyncStorage

**4. Manajemen Kategori (15 poin)**
- Tambah kategori baru
- Hapus kategori (cek apakah masih digunakan produk)
- Tampilkan daftar kategori
- Penyimpanan data dengan AsyncStorage

**5. Halaman Beranda (10 poin)**
- Tampilkan statistik (total produk, total kategori)
- Tombol cepat untuk tambah produk dan kategori
- Pesan selamat datang dengan nama toko

#### **Fitur Tambahan (Bonus - 30 poin):**

**6. Pencarian dan Filter (10 poin)**
- Pencarian produk berdasarkan nama
- Filter produk berdasarkan kategori
- Tampilkan hasil pencarian/filter

**7. Validasi dan Error Handling (10 poin)**
- Validasi form input (nama tidak boleh kosong, harga harus angka)
- Tampilkan pesan error yang jelas
- Loading state saat menyimpan data

**8. UI/UX Enhancement (10 poin)**
- Styling yang konsisten dan menarik
- Responsive design untuk berbagai ukuran layar
- Konfirmasi sebelum menghapus data
- Feedback visual untuk aksi user

---

### **🎯 Persyaratan Teknis**

**Tech Stack Wajib:**
- ✅ React Native dengan Expo
- ✅ Expo Router untuk navigasi
- ✅ AsyncStorage untuk penyimpanan data
- ✅ JavaScript atau TypeScript
- ✅ Functional components dengan hooks

**Struktur Data yang Disarankan:**
```javascript
// Produk
{
  id: string,
  nama: string,
  harga: number,
  kategori: string,
  deskripsi: string,
  tanggalDibuat: string
}

// Kategori
{
  id: string,
  nama: string,
  warna: string (opsional)
}
```

---

### **📋 Setup Proyek Awal**

**Langkah 1: Buat Proyek Baru**
```bash
# Buat proyek Expo baru
npx create-expo-app UTS_[NIM]_[Nama]
cd UTS_[NIM]_[Nama]

# Install dependencies yang diperlukan
npx expo install @react-native-async-storage/async-storage
npx expo install expo-router
```

**Langkah 2: Struktur File Awal**
```
UTS_[NIM]_[Nama]/
├── app/
│   ├── _layout.tsx          # Layout utama
│   ├── login.tsx           # Halaman login
│   └── (tabs)/             # Tab navigation
│       ├── _layout.tsx     # Konfigurasi tab
│       ├── index.tsx       # Beranda
│       ├── produk.tsx      # Manajemen produk
│       └── kategori.tsx    # Manajemen kategori
├── components/             # Komponen yang dapat digunakan ulang
├── services/               # Service untuk data
├── types/                  # TypeScript types (jika pakai TS)
└── utils/                  # Fungsi helper
```

**Langkah 3: Template Kode Dasar**

Template dasar akan disediakan untuk:
- Setup navigasi tab
- Konstanta styling dasar
- Template service AsyncStorage
- Interface TypeScript untuk model data

---

### **🤖 Panduan Penggunaan AI**

**Yang Diperbolehkan:**
- ✅ Meminta bantuan debugging error
- ✅ Menanyakan best practice untuk implementasi
- ✅ Bantuan dengan syntax dan referensi API
- ✅ Saran untuk optimasi kode
- ✅ Bantuan styling dan layout

**Yang Tidak Diperbolehkan:**
- ❌ Copy-paste solusi lengkap tanpa memahami
- ❌ Meminta AI membuat seluruh aplikasi
- ❌ Berbagi kode antar mahasiswa melalui AI
- ❌ Menggunakan AI untuk keputusan desain tanpa justifikasi

**Pola Penggunaan AI yang Disarankan:**
1. **Mulai dengan implementasi sendiri** - Coba dulu implementasi mandiri
2. **Gunakan AI untuk debugging** - Pakai AI ketika stuck dengan error
3. **Tanya hal spesifik** - Tanyakan hal spesifik, bukan solusi umum
4. **Pahami sebelum implementasi** - Pastikan paham sebelum pakai saran AI

---

### **📊 Rubrik Penilaian Praktik**

#### **Fungsionalitas (40 poin)**
- **Autentikasi (5 poin):** Login/logout berfungsi dengan baik
- **Navigasi (5 poin):** Tab navigation bekerja lancar
- **CRUD Produk (20 poin):** Create, read, update, delete produk
- **CRUD Kategori (8 poin):** Create, read, delete kategori
- **Penyimpanan Data (2 poin):** Data tersimpan dan termuat dengan benar

#### **Kualitas Kode (30 poin)**
- **Struktur Kode (12 poin):** Kode bersih, terorganisir, mudah dibaca
- **Error Handling (8 poin):** Penanganan error dan validasi yang tepat
- **Desain Komponen (6 poin):** Komponen yang dapat digunakan ulang
- **Manajemen State (4 poin):** Pengelolaan state yang efisien

#### **UI/UX (20 poin)**
- **Konsistensi Desain (8 poin):** Styling dan tema yang konsisten
- **Pengalaman Pengguna (7 poin):** Navigasi intuitif dan interaksi yang baik
- **Responsive Design (5 poin):** Tampil baik di berbagai ukuran layar

#### **Inovasi & Bonus (10 poin)**
- **Fitur Tambahan (5 poin):** Pencarian, filter, validasi advanced
- **Solusi Kreatif (3 poin):** Pendekatan unik untuk menyelesaikan masalah
- **Optimasi Performa (2 poin):** Rendering efisien dan pengelolaan data

---

### **📝 Persyaratan Pengumpulan**

**Yang Harus Dikumpulkan:**
1. **Source Code:** Folder proyek lengkap dalam format ZIP
2. **Video Demo:** Demo fungsionalitas 2-3 menit (format MP4)
3. **Dokumentasi:** File README.md berisi:
   - Instruksi setup dan menjalankan aplikasi
   - Fitur yang berhasil diimplementasikan
   - Tools AI yang digunakan dan bagaimana membantu
   - Kendala yang dihadapi dan solusinya
   - Waktu yang dihabiskan untuk setiap fitur

**Format Pengumpulan:**
- **Nama File:** `UTS_[NIM]_[Nama].zip`
- **Upload ke:** [Platform LMS yang digunakan]
- **Deadline:** [Sesuai jadwal UTS]

**Template Dokumentasi:**
```markdown
# UTS Praktikum - Aplikasi Katalog Toko

**Nama:** [Nama Lengkap]
**NIM:** [NIM]
**Kelas:** [Kelas]

## Fitur yang Berhasil Diimplementasikan
- [ ] Autentikasi (Login/Logout)
- [ ] Tab Navigation
- [ ] Manajemen Produk (CRUD)
- [ ] Manajemen Kategori (CRUD)
- [ ] Halaman Beranda dengan Statistik
- [ ] Penyimpanan Data dengan AsyncStorage
- [ ] [Fitur bonus lainnya...]

## Tools AI yang Digunakan
- **ChatGPT/Claude/DeepSeek:** Digunakan untuk [tujuan spesifik]
- **Bantuan Spesifik:** [Jelaskan apa yang dibantu AI]

## Pembagian Waktu
- Setup & Navigasi: [X] menit
- Fitur Produk: [X] menit
- Fitur Kategori: [X] menit
- Styling & UI: [X] menit
- Testing & Debug: [X] menit

## Kendala yang Dihadapi
- [Daftar kendala dan bagaimana mengatasinya]

## Cara Menjalankan Aplikasi
1. npm install
2. npx expo start
3. [Langkah tambahan jika ada...]
```

---

### **⏰ Strategi Manajemen Waktu**

**Alokasi Waktu yang Disarankan:**

**30 menit pertama:**
- ✅ Setup proyek dan struktur navigasi
- ✅ Navigasi tab dasar berfungsi
- ✅ Autentikasi sederhana

**45 menit berikutnya:**
- ✅ Manajemen produk (CRUD) lengkap
- ✅ Integrasi AsyncStorage untuk produk
- ✅ UI dasar untuk halaman produk

**30 menit berikutnya:**
- ✅ Manajemen kategori (CRUD)
- ✅ Integrasi AsyncStorage untuk kategori
- ✅ UI dasar untuk halaman kategori

**15 menit terakhir:**
- ✅ Halaman beranda dengan statistik
- ✅ Testing akhir dan perbaikan bug
- ✅ Dokumentasi dan persiapan pengumpulan

---

### **🎯 Tips Sukses**

**Sebelum Ujian:**
1. **Review materi Week 1-4 dan 6** - Pastikan familiar dengan konsep inti
2. **Latihan dengan AI tools** - Biasakan dengan workflow AI
3. **Setup environment** - Pastikan tools sudah siap
4. **Review pola AsyncStorage** - Penyimpanan data adalah kebutuhan inti

**Selama Ujian:**
1. **Mulai dari yang sederhana** - Implementasi fungsionalitas dasar dulu
2. **Test secara berkala** - Verifikasi setiap fitur bekerja sebelum lanjut
3. **Gunakan AI secara strategis** - Jangan bergantung sepenuhnya pada AI
4. **Kelola waktu dengan baik** - Jangan habiskan terlalu banyak waktu di satu fitur
5. **Dokumentasi sambil jalan** - Catat untuk dokumentasi akhir

**Tips Kolaborasi dengan AI:**
1. **Spesifik dalam pertanyaan** - "Bagaimana implementasi swipe to delete di FlatList"
2. **Pahami kodenya** - Jangan hanya copy-paste, pahami cara kerjanya
3. **Debug bertahap** - Perbaiki satu masalah dalam satu waktu
4. **Minta penjelasan** - "Jelaskan mengapa kode ini bekerja"

---

## 🎓 Ringkasan Penilaian

### **Total Poin: 100**

**Teori (40 poin):**
- Pilihan Ganda: 30 poin
- Esai: 30 poin
- **Subtotal:** 60 poin → skala ke 40 poin (40%)

**Praktik (60 poin):**
- Fungsionalitas: 40 poin
- Kualitas Kode: 30 poin  
- UI/UX: 20 poin
- Inovasi & Bonus: 10 poin
- **Subtotal:** 100 poin → skala ke 60 poin (60%)

### **Skala Nilai:**
- **A (85-100):** Pekerjaan luar biasa, semua fitur terimplementasi dengan kualitas kode excellent
- **B (70-84):** Pekerjaan baik, sebagian besar fitur terimplementasi dengan kualitas kode baik
- **C (60-69):** Pekerjaan memuaskan, fitur inti terimplementasi
- **D (50-59):** Di bawah ekspektasi, fitur kunci hilang atau kualitas kode buruk
- **E (<50):** Tidak lulus, fitur utama hilang atau tidak berfungsi

---

## 📚 Sumber Belajar

### **Materi Review yang Disarankan:**
- Modul praktikum Week 1-4 dan 6 beserta proyek yang telah diselesaikan
- [Dokumentasi React Native](https://reactnative.dev/docs/getting-started)
- [Dokumentasi Expo Router](https://docs.expo.dev/router/introduction/)
- [Panduan AsyncStorage](https://react-native-async-storage.github.io/async-storage/)

### **Proyek Latihan:**
- Buat ulang versi sederhana dari proyek Week 3-4
- Bangun aplikasi CRUD kecil dengan AsyncStorage
- Latihan pola navigasi dengan Expo Router

### **Latihan Kolaborasi AI:**
- Latihan debugging error React Native umum dengan AI
- Belajar mengajukan pertanyaan spesifik daripada pertanyaan umum
- Latihan memahami penjelasan kode yang dihasilkan AI

---

*Semoga sukses untuk UTS! Ingat: Tujuannya adalah menunjukkan pemahaman Anda tentang dasar-dasar pengembangan mobile, bukan hanya mendapatkan kode yang berfungsi. Gunakan AI sebagai alat belajar, bukan pengganti pemahaman. 🚀*
# PRD Katalog Laundry

**Panduan pertanyaan dan contoh jawaban**

PRD adalah dokumen yang menjelaskan apa yang perlu dibangun, untuk siapa, dan bagaimana kita tahu hasilnya sudah sesuai. Panduan ini mengadaptasi struktur PRD Katalog Kopi Rani (CHAT Online) untuk usaha laundry.

**Gambaran aplikasi**
Katalog layanan laundry dengan pemesanan melalui WhatsApp. Pelanggan melihat daftar layanan, harga, dan estimasi waktu selesai terbaru. Pemilik memperbarui layanan dan harga melalui HP. Konfirmasi pesanan, penjemputan, dan pembayaran tetap melalui percakapan dengan pemilik.

**Cara menggunakan panduan**
Bahas pertanyaan per kategori. Baca alasan singkatnya, lalu periksa contoh jawaban. Ganti jawaban dan catat keputusan ketika melakukan wawancara dengan pemilik laundry yang sebenarnya.

**Isi panduan**

| Kategori | Topik |
|---|---|
| A | Mengenal usaha |
| B | Pelanggan dan masalah |
| C | Tujuan dan batas aplikasi |
| D | Pengalaman pelanggan |
| E | Pengelolaan oleh pemilik |
| F | Data dan kenyamanan pakai |
| G | Pengujian dan tanda selesai |
| H | Konfirmasi dan langkah berikutnya |

Status contoh: simulasi pembelajaran dengan nama usaha fiktif "Laundry Sari". Belum hasil wawancara atau persetujuan usaha nyata.

---

## KATEGORI A — Mengenal usaha

Sepakati nama, layanan, dan identitas yang akan mewakili usaha laundry di aplikasi.

### 01 Apa nama usaha laundry dan layanan apa yang ditawarkan?

**Mengapa ditanyakan** Nama dan jenis layanan menjaga isi aplikasi tetap sesuai dengan usaha yang dilayani. Laundry kiloan, satuan, dan khusus (sepatu, karpet) punya cara penawaran yang berbeda.

> **Contoh jawaban**
> Nama usaha: Laundry Sari. Pemilik dalam cerita: Bu Sari.
> Usaha melayani cuci kiloan dan cuci satuan untuk warga sekitar, dengan opsi antar-jemput. Pemesanan berlangsung melalui WhatsApp; konfirmasi jadwal jemput, berat cucian, dan pembayaran tetap melalui percakapan dengan pemilik.

### 02 Layanan apa saja yang perlu tampil di katalog?

**Mengapa ditanyakan** Daftar awal menjadi pegangan untuk menyiapkan foto, satuan harga (per kg atau per item), durasi pengerjaan, dan pengujian.

> **Contoh data layanan**
> Cuci Kering Lipat — per kg, selesai 2 hari.
> Cuci Setrika — per kg, selesai 3 hari.
> Setrika Saja — per kg, selesai 1 hari.
> Cuci Express (6 jam) — per kg, selesai hari yang sama.
> Bedcover / Selimut — per item, selesai 3 hari.
> Sepatu — per pasang, selesai 3 hari.
> Harga, foto, minimal order, dan deskripsi final: menunggu konfirmasi pemilik.

### 03 Seperti apa identitas visual yang ingin dipakai?

**Mengapa ditanyakan** Identitas yang konsisten membantu pelanggan mengenali usaha ketika membuka tautannya, termasuk saat tautan disebar lewat grup warga atau status WhatsApp.

> **Usulan identitas**
> Konsep logo memakai ikon gelembung sabun atau pakaian terlipat dengan tulisan Laundry Sari. Warna biru muda dipadukan dengan aksen putih bersih.
> Logo dipasang di bagian atas aplikasi. Identitas ini masih usulan, belum persetujuan pemilik.

---

## KATEGORI B — Pelanggan dan masalah

Pahami pengalaman pemilik saat ini. Pisahkan kejadian yang diceritakan dari dugaan kita.

### 04 Siapa yang akan memakai aplikasi ini?

**Mengapa ditanyakan** Pelanggan dan pemilik memiliki kebutuhan berbeda serta batas akses yang perlu dijelaskan. Laundry sering punya karyawan yang ikut menjawab chat.

> **Contoh jawaban**
> Calon pelanggan (warga kos, keluarga sekitar) ingin tahu jenis layanan, harga per kg, lama pengerjaan, dan apakah ada antar-jemput sebelum menghubungi laundry.
> Bu Sari sebagai pengelola ingin memperbarui harga dan status layanan dari HP. Pelanggan boleh membaca tanpa akun; hanya admin yang berwenang mengubah data. Apakah karyawan perlu akses admin masih perlu ditanyakan.

### 05 Apa yang terjadi saat pelanggan memesan sekarang?

**Mengapa ditanyakan** Kejadian konkret menunjukkan bagian yang merepotkan sebelum kita menawarkan fitur.

> **Cerita dalam simulasi**
> Pelanggan mendapat nomor dari spanduk, tetangga, atau status WhatsApp lama, lalu bertanya "Berapa per kilo? Bisa jemput? Berapa hari jadi?".
> Dalam contoh kejadian, Bu Sari mengetik ulang daftar harga yang sama berkali-kali setiap hari, dan kadang harga yang dikirim sudah tidak berlaku karena daftar lama masih beredar di grup.

### 06 Masalah utama apa yang ingin kita selesaikan?

**Mengapa ditanyakan** Rumusan masalah memberi pegangan saat menentukan fitur dan menilai manfaatnya.

> **Rumusan masalah**
> Calon pelanggan Laundry Sari, saat ingin mencuci sebelum menghubungi laundry, kesulitan menemukan daftar layanan, harga, dan lama pengerjaan terbaru, sehingga pemilik mengirim informasi yang sama berulang kali melalui WhatsApp.
> Frekuensi chat belum dihitung. Belum ada data tentang pelanggan yang batal karena lambat dijawab atau dampak terhadap omzet.

---

## KATEGORI C — Tujuan dan batas aplikasi

Sepakati manfaat yang dituju dan batas pekerjaan pada versi pertama.

### 07 Perubahan apa yang diharapkan setelah aplikasi ada?

**Mengapa ditanyakan** Tujuan menjelaskan manfaat bagi pengguna, bukan sekadar daftar halaman aplikasi.

> **Hasil yang diharapkan**
> Pelanggan dapat menemukan layanan, harga, dan lama pengerjaan terbaru melalui satu tautan yang mudah dibagikan.
> Pemilik dapat memperbarui harga dan menandai layanan yang sedang tidak tersedia dari HP. Pelanggan membawa konteks layanan yang jelas saat memulai percakapan WhatsApp.
> Berkurangnya pertanyaan berulang masih perlu diukur; belum menjadi hasil yang terbukti.

### 08 Fitur apa yang masuk versi pertama?

**Mengapa ditanyakan** Batas pekerjaan menyamakan harapan pemilik dan pengembang untuk versi pertama.

> **Usulan lingkup awal**
> Untuk pelanggan: katalog layanan, detail layanan, dan tombol pesan melalui WhatsApp.
> Untuk pemilik: login, keluar, ganti password, daftar layanan, dan ubah informasi layanan dari HP.
> Tambah dan hapus layanan, serta tanda "sedang tidak tersedia", adalah usulan operasional yang perlu dikonfirmasi. Semua akses perubahan data harus terlindungi.

### 09 Fitur apa yang belum akan dibuat?

**Mengapa ditanyakan** Daftar yang ditunda mencegah tambahan pekerjaan sebelum kebutuhannya dipahami.

> **Di luar lingkup awal**
> Pelacakan status cucian (diterima, dicuci, siap diambil), pembayaran otomatis, program poin atau member, dan penjadwalan kurir otomatis ditunda.
> Nota digital, akun pelanggan, riwayat pesanan, penimbangan atau kalkulator harga, dan notifikasi cucian selesai belum masuk usulan ini.
> Ketentuan fitur wajib program tetap mengikuti arahan kelas, terpisah dari contoh lingkup usaha ini.

---

## KATEGORI D — Pengalaman pelanggan

Bayangkan pelanggan membuka aplikasi dari HP, memilih layanan, lalu mulai memesan.

### 10 Apa yang harus terlihat saat katalog dibuka?

**Mengapa ditanyakan** Halaman pertama perlu memberi informasi yang cukup untuk memilih layanan dan memperkirakan biaya.

> **Kebutuhan katalog**
> Pelanggan dapat membuka katalog tanpa login.
> Setiap layanan menampilkan foto atau ikon, nama, harga rupiah, satuan (per kg atau per item), dan lama pengerjaan.
> Data berasal dari informasi yang dikelola admin. Menekan layanan membuka detail yang sesuai. Layanan yang ditandai tidak tersedia tetap tampil dengan keterangan, atau disembunyikan sesuai keputusan pemilik.
> Jika belum ada data, tampilkan "Belum ada layanan". Jika gagal dimuat, beri penjelasan dan pilihan mencoba kembali.

### 11 Informasi apa yang dibutuhkan pada detail layanan?

**Mengapa ditanyakan** Detail membantu pelanggan memastikan jenis layanan, satuan harga, dan ketentuan sebelum bertanya.

> **Kebutuhan detail layanan**
> Tampilkan nama, foto, harga, satuan, lama pengerjaan, deskripsi, minimal order, dan catatan (misalnya "tidak termasuk noda berat") sesuai data tersimpan.
> Informasi pada katalog dan detail harus sama. Cuci Setrika tertulis per kg; Bedcover tertulis per item.
> Sediakan tombol WhatsApp dan jalan kembali ke katalog. Tautan layanan yang tidak tersedia memberi penjelasan, bukan halaman kosong.

### 12 Apa yang terjadi ketika tombol WhatsApp ditekan?

**Mengapa ditanyakan** Pelanggan perlu tiba pada nomor laundry yang benar dengan konteks layanan yang jelas, termasuk apakah ia ingin antar sendiri atau dijemput.

> **Kebutuhan pemesanan**
> Buka WhatsApp atau WhatsApp Web menuju nomor usaha yang telah dikonfirmasi.
> Siapkan pesan berisi nama layanan, harga, satuan, dan lama pengerjaan yang sama dengan detail. Pelanggan menambahkan sendiri perkiraan berat atau jumlah dan pilihan antar sendiri atau dijemput, lalu mengirim pesan.
> Jika nomor belum valid, tampilkan penjelasan. Membuka WhatsApp tidak berarti pesanan, penjemputan, atau pembayaran sudah berhasil.

---

## KATEGORI E — Pengelolaan oleh pemilik

Pastikan pemilik dapat memperbarui informasi dengan mudah dan aman.

### 13 Siapa yang mengelola dan bagaimana cara masuknya?

**Mengapa ditanyakan** Akun pengelola membatasi perubahan informasi tanpa menyulitkan pelanggan melihat katalog. Perlu jelas apakah hanya pemilik atau juga karyawan yang masuk.

> **Kebutuhan akun admin**
> Dalam simulasi, Bu Sari mengelola informasi sendiri melalui HP. Akun admin disiapkan pengelola proyek sesuai alur kelas. Satu akun dipakai bersama atau akun terpisah untuk karyawan masih perlu dikonfirmasi.
> Login yang benar membuka pengelolaan. Login gagal menampilkan pesan yang jelas. Password tidak tampil sebagai teks biasa.
> Admin dapat keluar. Setelah keluar, membuka pengelolaan atau menyimpan perubahan memerlukan login lagi.

### 14 Bagaimana pemilik memperbarui informasi layanan?

**Mengapa ditanyakan** Pemilik perlu mengubah harga, lama pengerjaan, atau menandai layanan tidak tersedia tanpa meminta pengembang mengedit aplikasi setiap kali.

> **Kebutuhan pengelolaan layanan**
> Admin membuka daftar layanan, memilih layanan, mengubah isian, lalu menyimpan. Formulir menampilkan data lama sebelum diubah.
> Tolak nama kosong, harga kosong, harga bukan angka atau negatif, satuan tidak dipilih, dan lama pengerjaan yang belum diisi. Jelaskan isian yang perlu diperbaiki.
> Jika berhasil, data baru tampil di katalog dan detail setelah dimuat ulang. Jika gagal, isian tetap ada dan aplikasi tidak menampilkan pesan sukses.

### 15 Bagaimana akun dan perubahan data dilindungi?

**Mengapa ditanyakan** Sistem harus menolak perubahan tanpa izin, termasuk saat halaman admin dilewati.

> **Kebutuhan perlindungan**
> Halaman dan permintaan perubahan data hanya menerima admin yang berwenang. Pengujian tanpa login harus ditolak tanpa mengubah layanan.
> Admin dapat mengganti password. Password kosong atau konfirmasi yang tidak cocok ditolak. Setelah berhasil, login baru menerima password baru dan menolak password lama.
> Kunci rahasia tetap di server; tidak dikirim ke browser, dibagikan di chat, atau dimasukkan ke repo kode.

---

## KATEGORI F — Data dan kenyamanan pakai

Siapkan isi layanan dan tentukan cara aplikasi menangani keadaan yang berbeda.

### 16 Data apa yang perlu disiapkan untuk setiap layanan?

**Mengapa ditanyakan** Data lengkap mengurangi tebakan dan menjaga isi katalog sesuai layanan yang benar-benar dijual.

> **Daftar informasi layanan**
> Identitas layanan, nama, harga rupiah, satuan (kg, item, pasang), lama pengerjaan, minimal order, deskripsi, catatan ketentuan, foto atau ikon, dan status tersedia.
> Enam contoh awal memakai satuan kg dan item. Harga dan aset final menunggu konfirmasi pemilik.
> Apakah ada harga berbeda untuk express, paket langganan, atau pelanggan kos masih perlu ditanyakan. Cara menyimpan satuan dibahas saat validasi teknis.

### 17 Materi usaha apa yang boleh tampil di aplikasi?

**Mengapa ditanyakan** Pemilik perlu menyetujui materi yang mewakili usahanya sebelum aplikasi dibagikan.

> **Konten yang perlu dikonfirmasi**
> Pemilik mengesahkan nama usaha, logo, foto, deskripsi, harga, dan nomor WhatsApp yang ditampilkan.
> Jam buka, alamat, area antar-jemput, dan biaya jemput ditambahkan bila terbukti dibutuhkan pelanggan.
> Minta izin penggunaan data usaha di aplikasi dan portofolio. Contoh logo merupakan konsep yang masih dapat diganti.

### 18 Bagaimana aplikasi tetap nyaman dipakai dari HP?

**Mengapa ditanyakan** Sebagian besar pelanggan laundry membuka tautan dari HP dengan koneksi seadanya. Tampilan yang rapi di laptop belum tentu nyaman di layar kecil.

> **Kebutuhan kenyamanan**
> Usulan uji: pada lebar layar 390 px, teks terbaca tanpa zoom dan tidak ada gulir horizontal. Tombol WhatsApp mudah dijangkau ibu jari.
> Tunjukkan keadaan sedang memuat, data kosong, dan gagal memuat atau menyimpan dengan pesan yang sesuai.
> Kontrol punya label jelas, fokus keyboard terlihat, dan foto punya teks alternatif. Harga, satuan, dan lama pengerjaan konsisten di seluruh alur.

---

## KATEGORI G — Pengujian dan tanda selesai

Tentukan bukti yang dapat dilihat ketika pelanggan dan pemilik mencoba aplikasi.

### 19 Apa yang perlu dicoba sebagai pelanggan?

**Mengapa ditanyakan** Uji mengikuti kegiatan pelanggan agar aplikasi membantu pemesanan, bukan sekadar bisa dibuka.

> **Skenario uji pelanggan**
> Buka katalog tanpa login dan periksa keenam layanan: nama, foto, harga, satuan, dan lama pengerjaan.
> Buka Cuci Setrika dan Bedcover. Cocokkan detail dan pesan WhatsApp, termasuk nomor tujuan, nama layanan, harga, satuan, dan lama pengerjaan.
> Buka tautan layanan tidak tersedia dan coba keadaan data kosong atau gagal dimuat. Aplikasi harus memberi penjelasan serta cara melanjutkan.

### 20 Apa yang perlu dicoba sebagai admin?

**Mengapa ditanyakan** Pemilik perlu memastikan pembaruan tersimpan dan akses pengelolaan benar-benar terlindungi.

> **Skenario uji admin**
> Dari HP, login dan ubah satu harga per kg. Periksa harga baru pada katalog, detail, serta pesan WhatsApp setelah dimuat ulang. Tandai satu layanan tidak tersedia dan periksa tampilannya di katalog.
> Kirim nama kosong atau harga negatif; penyimpanan harus ditolak dan data lama tetap utuh. Coba kegagalan simpan; jangan sampai muncul sukses palsu.
> Ganti password lalu uji login baru. Setelah keluar, uji halaman admin dan permintaan ubah langsung; keduanya harus menolak akses tanpa izin.

### 21 Kapan aplikasi dapat dinyatakan siap digunakan?

**Mengapa ditanyakan** Kriteria selesai menyamakan harapan dan membedakan target dari hasil yang sudah diukur.

> **Kriteria penerimaan**
> Isi usaha dan lingkup telah dikonfirmasi. Seluruh alur yang disetujui lulus pengujian pada HP.
> Pemilik dapat mengubah satu harga dan menandai layanan tidak tersedia tanpa dibimbing langkah demi langkah. Akun, panduan singkat, dan cara melaporkan masalah sudah diserahkan.
> Usulan target: dari katalog ke WhatsApp paling banyak 3 ketukan. Penurunan chat "berapa per kilo" belum punya baseline atau target persentase; ukur sebelum dan setelah pemakaian.

---

## KATEGORI H — Konfirmasi dan langkah berikutnya

Catat hal yang belum diketahui, pihak yang mengonfirmasi, dan langkah berikutnya.

### 22 Apa yang masih perlu ditanyakan kepada pemilik?

**Mengapa ditanyakan** Pertanyaan terbuka menjaga dugaan tetap tercatat dan memberi arah wawancara berikutnya.

> **Pertanyaan yang masih terbuka**
> Berapa harga tiap layanan, dan foto serta deskripsi mana yang disetujui? Nomor WhatsApp mana yang akan dipakai?
> Apakah ada minimal order per kg? Apakah antar-jemput gratis, berbayar, atau hanya untuk area tertentu? Berapa biaya tambahan express?
> Apakah pemilik perlu menambah atau menghapus layanan sendiri? Apakah karyawan perlu akses admin? Seberapa sering info harga dikirim ulang? Perlukah jam buka dan alamat? Perangkat serta cara pemulihan akun apa yang digunakan?

### 23 Siapa yang mengonfirmasi kebutuhan dan keputusan?

**Mengapa ditanyakan** Kebutuhan bisnis dan kelayakan teknis perlu dikonfirmasi oleh pihak yang memahaminya.

> **Pembagian peran**
> Pemilik laundry mengonfirmasi masalah, data layanan, dan lingkup yang benar-benar dibutuhkan.
> Peserta mencatat keputusan dan tanggalnya. Pendamping program membantu meninjau kejelasan kebutuhan dan memvalidasi kelayakan teknis.
> Status contoh Laundry Sari: simulasi pembelajaran, belum wawancara atau persetujuan usaha nyata. Catat koreksi sebelum implementasi.

### 24 Apa langkah setelah PRD ini dibahas?

**Mengapa ditanyakan** Kesepakatan diterjemahkan menjadi pekerjaan dan pengujian, lalu diperbarui bila bukti berubah.

> **Urutan tindak lanjut**
> Wawancara dan konfirmasi masalah. Sepakati isi serta lingkup. Susun desain dan daftar pekerjaan, lalu bangun alur utama.
> Uji bersama pemilik, perbaiki kegagalan, lalu serahkan aplikasi. Tanggal rilis ditetapkan setelah lingkup dan kelayakan disepakati.
> Teknologi mengikuti kelas: Next.js untuk aplikasi web, Supabase untuk data dan akun, serta Vercel untuk publikasi. Rincian teknis mengikuti pendampingan.

# ArkCad

Perancang pabrik AIC Arknights: Endfield buatan penggemar. Susun mesin, sabuk, dan pipa di browser, lalu lihat hasil simulasinya sebelum membangun di game.

**Buka di sini: https://nielsan110.github.io/ArkCad/**

Tidak perlu akun dan tidak perlu dipasang.

## Yang bisa dilakukan

- Menyusun denah dengan mesin, sabuk, pipa, Splitter, Converger, dan jembatan.
- Mensimulasikan pabrik: laju tiap barang, persen kerja tiap mesin, dan pemakaian daya.
- Memeriksa jalur putus, bangunan bertumpuk, dan mesin yang belum tersambung.
- Menghitung Stock Bill per menit, kapan depot penuh, dan apakah bahan cukup.
- Merancang kebun di lahan tanam dengan petak, Sprinkler, pompa, dan Auto-Farmer, lalu menghitung hasil panennya.
- Mengunduh hasil sebagai gambar, laporan, tabel, atau berkas rancangan.

## Cara pakai

1. **Pilih titik awal.** Klik **Baru**, lalu pilih kisi kosong atau salah satu denah yang sudah jadi.
2. **Taruh mesin.** Klik mesin di daftar kiri, lalu klik kanvas. Tombol `R` memutar, `Esc` selesai.
3. **Pilih resep.** Klik mesin di kanvas, lalu pilih resepnya di tab **Properti**.
4. **Sambungkan jalur.** Tekan `E` untuk sabuk atau `Q` untuk pipa. Klik port keluar, klik titik-titik belokannya, lalu klik port masuk untuk menyelesaikan.
5. **Cek hasilnya.** Lihat tab di panel kanan, lalu betulkan yang masih bermasalah.
6. **Bangun di game.** Unduh gambarnya lewat **Unduh dan bagikan**, lalu bangun ulang sambil melihat gambar itu.

### Panel kanan

| Tab | Isinya |
|---|---|
| **Properti** | Pengaturan rancangan dan detail mesin atau jalur yang dipilih |
| **Periksa** | Bisa dibangun atau tidak, daftar masalah, dan cara membetulkannya |
| **Neraca** | Produk, pendapatan, pos depan, bahan, pompa, dan kerja mesin |
| **Rantai** | Mesin dan bahan yang dibutuhkan untuk membuat suatu barang |
| **Jalur** | Semua ruas sabuk dan pipa, termasuk yang terpanjang dan yang putus |

Di tab **Neraca**, isi hasil tambangmu per menit dan level pos depan supaya perhitungannya sesuai akunmu.

### Kebun

Klik **Kebun** di bilah atas untuk merancang lahan tanam di Agricultural Test Site, Eco-Farm, atau Si's Painting. Lahan ini terpisah dari pabrik, jadi tidak memakai Unit Penanam dan Unit Petik Benih.

1. Taruh petak dari daftar kiri. Tiap petak 4×4 dan harus di dalam area.
2. Pasang Sprinkler menghadap petak, lalu sambungkan pipa dari pompa. Kotak biru menunjukkan jangkauannya.
3. Lihat tab **Panen** untuk hasil per hari dan barang yang perlu disiapkan.

Waktu tumbuh, hasil per petak, jangkauan Sprinkler, dan luas lahan masih anggapan, jadi samakan dengan yang kamu lihat di game.

### Tombol

| Perintah | Tombol |
|---|---|
| Pilih dan pindah | `V` |
| Sabuk, pipa | `E`, `Q` |
| Splitter, Converger, jembatan | `S`, `G`, `B` |
| Control Port | `F` |
| Hapus dengan seret | `H` |
| Putar, pindah | `R`, `M` |
| Cari di daftar mesin | `A` |
| Salin, tempel | `Ctrl+C`, `Ctrl+V` |
| Urung, ulang | `Ctrl+Z`, `Ctrl+Y` |
| Pas layar | `Home` |

## Menyimpan dan berbagi

Rancangan tersimpan otomatis di browser yang kamu pakai. Rancangan terakhir, zoom, dan tab yang terbuka kembali saat halaman dibuka lagi.

**Rancangan bisa hilang kalau data browser dibersihkan, dan tidak ikut pindah ke perangkat lain.** Simpan cadangannya lewat **Unduh dan bagikan**:

| Pilihan | Kegunaan |
|---|---|
| Gambar PNG | Acuan saat membangun di game |
| Laporan HTML | Denah dan semua tabel, bisa dibuka tanpa ArkCad |
| Tabel CSV | Dibuka di Excel |
| Berkas JSON | Cadangan rancangan, bisa dibuka dan diubah lagi |
| Tautan atau kode bagi | Dikirim ke teman supaya denahnya langsung terbuka |

Untuk membuka kiriman, klik tautannya, atau pilih **Buka** lalu tempel kodenya atau pilih berkasnya. Kalau tautannya terpotong di aplikasi chat, kirim berkas JSON saja.

## Yang perlu diperhatikan

- Angka berasal dari simulator dan belum tentu sama persis dengan game.
- Kode cetak biru game tidak bisa diimpor atau diekspor, karena formatnya tertutup. Denah harus dibangun ulang di game.
- Beberapa nilai masih anggapan, misalnya jangkauan tiang dan batas laju Protocol Stash. Tab **Periksa** mencantumkan yang perlu dicek di game.
- Satu lahan hanya bisa punya satu PAC.

## Sumber dan hak

ArkCad adalah alat buatan penggemar dan tidak berafiliasi dengan Hypergryph atau GRYPHLINE. Nama, ikon barang, dan gambar bangunan milik pemegang hak Arknights: Endfield.

- Data mesin dan resep: [endfield-calc](https://github.com/JamboChen/endfield-calc) oleh JamboChen, lisensi MIT (lihat [LICENSE-endfield-calc.txt](LICENSE-endfield-calc.txt)).
- Harga jual: [endfield.wiki.gg](https://endfield.wiki.gg).
- Ikon dan gambar dimuat dari endfield-calc dan endfield.wiki.gg saat halaman dibuka, dan tidak disimpan di repositori ini.

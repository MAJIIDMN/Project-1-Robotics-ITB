# Mini Game CLI: Gunting Batu Kertas & Tebak Angka

Proyek ini berisi skrip Python sederhana (`Tugas_1.py`) yang menawarkan dua mini game berbasis terminal: **Gunting Batu Kertas** dan **Tebak Angka**. Dokumentasi ini ditulis dalam Bahasa Indonesia.

## Fitur
- Menu interaktif untuk memilih salah satu dari dua mini game.
- Permainan Gunting Batu Kertas dengan aturan standar.
- Permainan Tebak Angka dengan rentang angka yang dapat ditentukan pemain.
- Opsi untuk mengulang permainan setelah setiap sesi.

## Persyaratan
- Python 3.x
- Sistem operasi yang mendukung perintah `cls` untuk membersihkan layar (Windows). Jika Anda menggunakan Linux/macOS, ganti `cls` dengan `clear` di skrip atau jalankan tanpa pembersihan layar.

## Cara Menjalankan
1. Pastikan Python sudah terpasang.
2. Buka terminal di direktori proyek.
3. Jalankan perintah berikut:
   ```bash
   python Tugas_1.py
   ```
4. Pilih mini game (1 atau 2) lalu ikuti instruksi di layar.

## Aturan Singkat
### Gunting Batu Kertas
- Masukkan `r` untuk **batu**, `p` untuk **kertas**, atau `s` untuk **gunting**.
- Batu kalah melawan kertas, kertas kalah melawan gunting, gunting kalah melawan batu.
- Jika pilihan sama, hasilnya seri.

### Tebak Angka
- Tentukan rentang angka positif (misal 10 berarti komputer memilih angka 1–10).
- Masukkan tebakan Anda; sistem memberi petunjuk “lebih besar lagi” atau “lebih kecil lagi” hingga benar.

## Struktur Berkas
- `Tugas_1.py`: Implementasi dua mini game dan menu utama.
- `README.md`: Dokumentasi proyek dalam Bahasa Indonesia.
- `README.txt`: Cuplikan kode awal (tidak diperlukan untuk menjalankan).
- `Flowchart.png`: Diagram alur permainan.

## Catatan
- Jika Anda ingin membersihkan layar secara lintas platform, Anda bisa mengganti pemanggilan `os.system('cls')` dengan logika yang menyesuaikan sistem operasi, misalnya menggunakan `os.name`.
- Proyek ini dirancang untuk penggunaan belajar dan demonstrasi sederhana di terminal.

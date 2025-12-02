# tic-tac-toe-python

Game Tic-Tac-Toe sederhana menggunakan Python. Project ini adalah implementasi permainan X dan O klasik.

## Deskripsi

Program ini adalah game Tic-Tac-Toe berbasis console dimana pemain melawan komputer. Pemain menggunakan simbol 'O' dan komputer menggunakan simbol 'X'.

## Cara Menjalankan

### Prasyarat
- Python 3.x terinstall di komputer
- Terminal/Command Prompt

### Langkah-langkah:

1. **Clone atau download repository ini**
   ```bash
   git clone https://github.com/razwahsb/tic-tac-toe-python.git
   cd tic-tac-toe-python
   ```

2. **Jalankan program**
   ```bash
   python main.py
   ```

3. **Cara bermain**
   - Papan permainan memiliki 9 posisi bernomor 1-9
   - Masukkan nomor posisi (1-9) saat giliran Anda
   - Komputer akan otomatis memilih posisinya
   - Permainan berakhir ketika ada yang menang atau seri

## Fitur

- Papan permainan 3x3 yang mudah dibaca
- Validasi input pemain
- Komputer dengan gerakan random
- Deteksi kemenangan otomatis
- Deteksi kondisi tie/seri

## Contoh Tampilan

```
+-----------------------+
|       |       |       |
|   1   |   2   |   3   |
|       |       |       |
+-----------------------+
|       |       |       |
|   4   |   X   |   6   |
|       |       |       |
+-----------------------+
|       |       |       |
|   7   |   8   |   9   |
|       |       |       |
+-----------------------+
Enter your move:
```

## Struktur Kode

- `displayboard()` - Menampilkan papan permainan
- `entermove()` - Menangani input pemain
- `makelistoffreefields()` - Membuat daftar posisi kosong
- `victoryfor()` - Mengecek kondisi kemenangan
- `drawmove()` - Komputer memilih posisi

## Lisensi

Project ini bebas digunakan untuk pembelajaran.

## Kontributor

Razwa Hafidz Hasibuan - UIN Jakarta

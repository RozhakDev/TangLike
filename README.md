# 🚀 TangLike - Free Facebook Likes Tool

![TangLike Logo](https://github.com/user-attachments/assets/70ff31f7-0abf-4258-84aa-e3d05fcc85bb)
✨ **Alat Gratis untuk Mendapatkan Like/Likes Permanen di Postingan Facebook dengan Mudah dan Cepat!** ✨

## 📜 Deskripsi

**TangLike** adalah alat keren yang dirancang untuk membantu kamu mendapatkan **suka/like** di postingan Facebook dengan **aman**, **permanen**, dan **mudah**! Alat ini memanfaatkan layanan bypass recaptcha sehingga proses mendapatkan like menjadi cepat dan efisien. 🚀✨

## 🔗 **Fitur Unggulan**:

- 🛡️ **Bypass reCAPTCHA**: Integrasi dengan API Multibot untuk melewati verifikasi otomatis.
- 🌟 **Aman & Permanen**: Menggunakan metode yang stabil dan terpercaya.
- ⚡ **Cepat & Efisien**: Dukung hingga 100 likes per permintaan.
- 📊 **Pelacakan Real-Time**: Pantau jumlah sukses/gagal secara langsung.

## 🛠️ Prasyarat

- 🍪 **Cookies Akun Facebook** (direkomendasikan akun palsu untuk menghindari risiko).
- 🔑 **API Key Multibot.in** (untuk bypass reCAPTCHA, [daftar di sini](https://multibot.in/dashboard/signup.php)).
- 🐍 **Python 3.8+** terinstal di perangkat.

## 📥 Instalasi

```bash
$ apt update -y && apt upgrade -y
$ pkg install git python-pip
$ git clone https://github.com/RozhakLabs/TangLike.git
$ cd "TangLike"
$ pip install -r requirements.txt
$ python Run.py
```

## 🖥️ Cara Penggunaan

1. **Masukkan Cookies Facebook**:
   - ⚠️ **Gunakan akun palsu untuk menghindari checkpoint!**
   - Salin cookies dari browser dan tempelkan saat diminta.
2. **Input ID Postingan**:
   - Masukkan ID postingan Facebook yang ingin Anda dapatkan likes-nya (contoh: `123456789`).
3. **Tunggu Proses**:
   - Tools akan otomatis mengirim likes dan menampilkan status real-time.

## ⚙️ Konfigurasi API Key Multibot

Daftarkan diri Anda di [Multibot.in](https://multibot.in/dashboard/signup.php). Setelah itu, buka file `Run.py` dan cari baris ke-152. Gantilah `YOUR KEY!` dengan API key Anda menggunakan format berikut:  

```python
self.key = ("API_KEY_ANDA")
```

## 📌 Catatan Penting

- 🚫 **Jangan gunakan akun Facebook utama!** Risiko checkpoint/akun terkunci mungkin terjadi.
- ⏳ Batas penggunaan harian: 100 likes per akun.
- 🔄 Jika gagal, tunggu 15 menit sebelum mencoba ulang.

## ⚠️ Peringatan

> TangLike dibuat semata-mata untuk tujuan edukasi dan pembelajaran teknis. Segala risiko, termasuk pelanggaran kebijakan Facebook atau hukum yang berlaku, sepenuhnya menjadi tanggung jawab pengguna. Gunakan hanya dengan akun uji/dummy dan hindari penyalahgunaan untuk aktivitas ilegal.

## 📜 Lisensi

Proyek ini dilisensikan di bawah **MIT License**. Lihat [LICENSE](LICENSE) untuk detail.
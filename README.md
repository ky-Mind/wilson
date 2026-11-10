# Wilson

Kamera di browser yang menempelkan cap hari, tanggal, jam, dan lokasi ke foto atau video. Hasilnya bisa langsung dikirim ke WhatsApp, disimpan ke Google Drive, atau dijadwalkan kirimnya.

Live: https://wilson-lilac.vercel.app

## Fitur

- Foto dan video dari kamera, atau unggah foto
- Cap waktu dan lokasi yang bisa diatur (posisi atas/bawah, nama lokasi, catatan)
- Kirim lewat bot WhatsApp atau simpan ke Google Drive
- Antrean dan jadwal kirim
- Login Google atau email

## Teknologi

Satu halaman HTML + JavaScript, Firebase Auth dan Firestore, Google Drive API, dan bot WhatsApp terpisah (alamatnya di `config.js`).

## Jalankan lokal

```bash
python3 -m http.server 8080
```

Isi konfigurasi Firebase di `config.js` sebelum dipakai.

# Bug Blaster

Game tembak bug untuk latihan Computational Thinking (Scratch). Tembak bug dengan Spasi, gerak dengan tombol panah. Peluru terbatas, jawab soal coding untuk mengisi ulang. Ada tombol terjemahan ID/EN.

## Isi folder
- `index.html` : seluruh game (HTML, CSS, JavaScript dalam satu file)
- `assets/mascot.png` : karakter pemain

## Cara pasang di GitHub Pages
1. Buat repository baru di GitHub (Public), misalnya `bug-blaster`.
2. Klik **Add file > Upload files**, lalu tarik `index.html` dan folder `assets` ke halaman itu. Klik **Commit changes**.
3. Buka **Settings > Pages**. Pada **Build and deployment**, pilih **Deploy from a branch**, branch `main`, folder `/ (root)`, lalu **Save**.
4. Tunggu 1 sampai 2 menit. Game bisa dibuka di `https://USERNAME.github.io/bug-blaster/`.

## Mengubah soal
Soal ada di array `Q` di dalam `index.html`. Setiap soal punya teks Inggris dan Indonesia dalam pasangan `['English','Indonesia']`. Jawaban benar selalu ditulis paling pertama pada daftar `a`.

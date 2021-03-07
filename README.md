# Instant Video Compressor
Skrip untuk mengompres video dengan mudah menggunakan Termux.
Dengan skrip ini, dapat membuat size videomu berkurang sampai ±50% tanpa mengurangi kualitas video.
Skrip ini memudahkan kalian untuk menjalankan command ffmpeg tanpa harus menulis command yang panjang.
Skrip ini merupakan simplified dari <a href="https://github.com/tfkhdyt/uvc">Ultra Video Compressor</a>
<p align=center>
<a href="https://tfkhdyt.web.app"><img src="https://img.shields.io/badge/Created%20by-tfkhdyt-blue?style=for-the-badge&logo=github" loading="lazy"/></a><br>
<a href="Https://facebook.com/tfkhdyt142"><img height="30" src="https://www.pinclipart.com/picdir/big/2-21918_download-transparent-background-facebook-logo-clipart-facebook-logo.png" loading="lazy"/></a>&nbsp;
<a href="https://twitter.com/tfkhdyt"><img height="30" src="https://www.pinclipart.com/picdir/big/64-649167_the-pairings-twitter-icon-rounded-square-clipart.png" loading="lazy"/></a>&nbsp;
<a href="https://instagram.com/_tfkhdyt_"><img height="30" src="https://camo.githubusercontent.com/5cf2a148d1763dca531d1d43bdf234b4e57ee2e00f613589e6d307ccd1077a9f/68747470733a2f2f7777772e70696e636c69706172742e636f6d2f7069636469722f6269672f3130392d313039393330315f696e7374616772616d2d696e7374616772616d2d6c6f676f2d6e6f2d626f726465722d636c69706172742e706e67" loading="lazy"/></a>&nbsp;
<a href="https://youtube.com/tfkhdyt"><img height="30" src="https://www.pinclipart.com/picdir/big/530-5305952_youtube-computer-icons-portable-network-graphics-logo-logo.png" loading="lazy"/></a>&nbsp;
<a href="https://t.me/tfkhdyt"><img height="30" src="https://cdn4.iconfinder.com/data/icons/social-media-2146/512/37_social-512.png" loading="lazy"/></a>&nbsp;
<a href="https://open.spotify.com/playlist/4JR5wqcnuOQw6ppF38Vpu9?si=zHMKBfCiRrGVamKsL8LXqQ"><img height="30" src="https://cdn2.iconfinder.com/data/icons/social-icons-33/128/Spotify-512.png" loading="lazy"/></a>
</p>

## Disclaimer
Saya tidak menjamin video yang kalian kompres ukurannya akan menjadi lebih kecil, karena hasil akhir akan sangat berpengaruh dari video asli. Jadi jangan heran jika suatu saat size hasil kompres malah lebih besar dari size video asli 

## Requirements
- `Termux`
- `git (pkg install git)`
- `Koneksi internet (Hanya untuk instalasi dependencies, proses kompres tetap dilakukan secara offline)`

## Instalasi
``````
# mengizinkan termux mengakses storage
termux-setup-storage
# kemudian pilih y

# cloning source code
git clone https://github.com/tfkhdyt/ivc.git && cd ivc && ./install

# Compress: 
ivc [namaFile.mp4]
# Contoh  :
ivc sample.mp4

# Trim  : 
ivc -t [Waktu awal] [Waktu akhir] [namaFile.mp4]
# Contoh: 
ivc -t 00:01:00 00:02:30 sample.mp4
``````
## Informasi lebih lanjut
Apabila ada yang mau ditanyakan soal skrip ini, bisa langsung pm saya:
<p align=center>
<a href="https://linktr.ee/tfkhdyt" target="_blank"><img src="https://img.shields.io/badge/Contact-me-green?style=for-the-badge" loading="lazy"/></a>
</p>

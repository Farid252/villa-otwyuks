WEBSITE VILLA + PANEL ADMIN UNTUK GITHUB PAGES (github.io)

1. Buat repository GitHub (Public), misalnya "villa-otwyuks".
2. Upload SEMUA isi folder ini ke repository (index.html, admin/, data/, foto/).
3. Buka admin/config.yml di GitHub, ubah baris:  repo: USERNAME/NAMA-REPO
   menjadi username dan nama repository Anda. Lalu Commit.
4. Settings > Pages > Deploy from a branch > main > / (root) > Save.
5. Website:  https://USERNAME.github.io/NAMA-REPO/
   Panel admin:  https://USERNAME.github.io/NAMA-REPO/admin/

Login panel admin (tanpa server):
- GitHub > Settings > Developer settings > Personal access tokens > Fine-grained tokens > Generate new token.
- Repository access: pilih hanya repository ini. Permissions > Contents: Read and write.
- Di halaman /admin/ pilih "Sign In with GitHub using Token", tempel token.
Setiap kali Anda menyimpan di panel, perubahan masuk ke repository dan tampil di website setelah sekitar 1 menit.

Catatan:
- Jangan bagikan token. Hanya pemilik token (dan kolaborator repository) yang bisa mengubah isi.
- Website harus dibuka lewat alamat web, bukan dengan klik dua kali index.html.

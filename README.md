# backend-nrp

Repo tugas mata kuliah **Pengembangan Backend Dasar**, dibuat dari template [`webdev-if-its/backend-template`](https://github.com/webdev-if-its/backend-template). Ganti judul di atas jadi nama repo kalian sendiri (`backend-nrp`, contoh: `backend-5025201012`).

## Aturan Umum

- Tugas tiap pertemuan disimpan di folder `pertemuan-XX/` pada repo ini.
- Commit message wajib menyebut level yang dicapai: `pertemuan-XX: level N selesai`.
- Deadline push: sebelum pertemuan berikutnya dimulai.
- Semua level dicek otomatis lewat `go test` — baca `pertemuan-XX/SOAL.md` tiap minggu untuk detail levelnya.

## Mengambil Pertemuan Baru Tiap Minggu

Repo ini **tidak otomatis sinkron** dengan template dosen. Begitu ada pertemuan baru, jalankan (ganti `pertemuan-02` sesuai minggu berjalan):

```bash
git fetch https://github.com/webdev-if-its/backend-template.git main
git checkout FETCH_HEAD -- pertemuan-02
```

Perintah ini **aman dijalankan kapan pun** — tidak akan menimpa folder pertemuan lain yang sudah kalian kerjakan, karena hanya mengambil folder yang disebutkan. Setelah itu, commit folder barunya seperti biasa.

Kalau dosen memperbaiki sesuatu di pertemuan yang sudah dirilis (mis. ada bug di test), biasanya cukup ambil ulang file yang diperbaiki saja, bukan seluruh folder — akan diumumkan file mana yang berubah.

---

Bagian di bawah ini **isi bertahap** sesuai level yang sedang kalian kerjakan (lihat `pertemuan-01/SOAL.md`) — heading-nya dicek otomatis, jangan diganti namanya.

## Identitas
- Nama: Alhaura Rahmatunnisa Harsanto
- NRP: 5053241016
- Kelas: Backend RPL (M)

## Commit vs Push
Commit adalah proses menyimpan perubahan yang telah dibuat ke repository lokal Git. Sedangkan push adalah mengirim commit dari repository lokal ke repository remote, seperti GitHub. Perbedaan ini perlu dipahami dengan baik supaya tidak ada miskonsepsi dan kesalahan.

## Reproducibility
Reproducibility dalam perangkat lunak adalah kondisi dimana project dapat dijalankan atau dikembangkan kembali dengan hasil dan lingkungan yang konsisten sehingga anggota tim lain dapat menjalankan project yang sama tanpa mengalami perbedaan konfigurasi. Git sangat membantu reproducibility karena riwayat perubahan kode disimpan dan dapat diakses melalui repository.

## Catatan Merge Conflict
Merge conflict dapat terjadi saat Git menemukan perubahan yang bertabrakan, contohnya dua orang mengubah bagian yang sama dalam sebuah file. Merge conflict harus diselesaikan secara manual dengan memilih atau menggabung perubahan yang sesuai. Untuk menghindari ini, anggota tim perlu sering melakukan pull.

## Kenapa .gitignore Penting
file .gitignore digunakan untuk menentukan file mana yang tidak perlu dimasukkan ke dalam repository Git. Contohnya file dependency, temporary, dan data sensitif seperti password atau API key. Repository akan menjadi lebih aman dan hanya berisi file yang diperlukan.

## Refleksi
Saya semangat dalam menjalankan mata kuliah ini karena banyak sekali ilmu yang belum saya miliki. Semoga dengan komitmen ini saya bisa selalu konsisten di setiap pertemuannya.

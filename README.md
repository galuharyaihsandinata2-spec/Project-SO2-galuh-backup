# Project-SO2-galuh-backup

Gambar : https://drive.google.com/file/d/1SJxCpVg15bczUWAhFYcAbwpw6hWfaG6J/view?usp=sharing

**Perintah 1:**

`galuh@ubuntu01:~/Desktops cd` 

**Penjelasan:** Ini sepertinya perintah `cd` (change directory) yang mungkin salah ketik atau prompt yang tidak lengkap. Prompt menunjukkan direktori `~/Desktops` (mungkin dimaksudkan sebagai `~/Desktop`), dan `cd` tanpa argumen biasanya membawa ke direktori home pengguna. Namun, ini bisa jadi kesalahan ketik, dan perintah ini mungkin dimaksudkan untuk berpindah direktori.

**Perintah 2:**

`galuh@ubuntu01:~$ mkdir -p /home/galuh/documents/project_file_manajement`  

**Penjelasan:** Perintah `mkdir -p` membuat direktori baru secara rekursif. Di sini, ia membuat direktori `/home/galuh/documents/project_file_manajement`. (Catatan: Ada typo "manajement" yang mungkin dimaksudkan sebagai "management".)

**Perintah 3:**

`galuh@ubuntu01:~$ mkdir -p /home/galuh/backups`  

**Penjelasan:** Sama seperti di atas, `mkdir -p` membuat direktori `/home/galuh/backups` untuk menyimpan file backup.

**Perintah 4:**

`galuh@ubuntu01:~$ mkdir -p /home/galuh/logs`  

**Penjelasan:** Membuat direktori `/home/galuh/logs` untuk menyimpan file log.

**Perintah 5:** 

`galuh@ubuntu01:~$ touch /home/galuh/logs/backup_log.txt`  

**Penjelasan:** Perintah `touch` membuat file kosong baru bernama `backup_log.txt` di direktori `/home/galuh/logs`. Jika file sudah ada, ia akan memperbarui timestamp-nya.

**Perintah 6:** 

`galuh@ubuntu01:~$ nano backup.sh` 

**Penjelasan:** Membuka editor teks `nano` untuk mengedit atau membuat file script `backup.sh`. Pengguna kemungkinan menulis kode script di dalamnya.

**Perintah 7:** 

`galuh@ubuntu01:~s chmod +x backup.sh`  

**Penjelasan:** Perintah `chmod +x` menambahkan izin eksekusi ke file `backup.sh`, sehingga bisa dijalankan sebagai program. (Catatan: Ada typo di prompt "~s" yang mungkin dimaksudkan sebagai "~$".)

**Perintah 8:**

`galuh@ubuntu@1:~$./backup.sh`  

**Penjelasan:** Menjalankan script `backup.sh` dari direktori saat ini. (Catatan: Ada typo di prompt "galuh@ubuntu@1" yang mungkin dimaksudkan sebagai "galuh@ubuntu01", dan "./backup.sh" tanpa spasi setelah titik mungkin kesalahan ketik.)

**Output 9:** 

`Files to be backed up:`  

**Penjelasan:** Ini adalah output dari script `backup.sh`, menunjukkan bahwa script sedang memproses file yang akan di-backup.

**Output 10:** 

`Compressing files into backup_20251123115010.tar.gz...`  

**Penjelasan:** Output dari script, menunjukkan proses kompresi file ke dalam arsip tar.gz dengan nama yang mencakup timestamp.

**Output 11:**

`Backup berhasil: backup_20251123115010.tar.gz`  

**Penjelasan:** Output konfirmasi bahwa backup berhasil dan file arsip telah dibuat.

**Perintah 12:** 

`galuh@ubuntu01:~$ cd /home/galuh/backups/` 

**Penjelasan:** Perintah `cd` berpindah ke direktori `/home/galuh/backups/`.

**Perintah 13:**

`galuh@ubuntu01:~/backups$ ls -lh`  

**Penjelasan:** Perintah `ls -lh` menampilkan daftar file di direktori saat ini dengan detail lengkap (izin, ukuran, dll.) dalam format yang mudah dibaca.

**Output 14:** 

`total 8.0K`  

**Penjelasan:** Output dari `ls -lh`, menunjukkan total ukuran semua file di direktori (8.0 KB).

**Output 15:** 

`-rw-rw-r-- 1 galuh galuh 45 Nov 23 10:03 backup_20251123100350.tar.gz`  

**Penjelasan:** Output dari `ls -lh`, menampilkan detail file backup lama (dari sesi sebelumnya).

**Output 16:**

`-rw-rw-r-- 1 galuh galuh 45 Nov 23 11:50 backup_20251123115010.tar.gz`  

**Penjelasan:** Output dari `ls -lh`, menampilkan detail file backup baru yang baru dibuat.

**Perintah 17:** 

`galuh@ubuntu01:~/backups$ cat /home/galuh/logs/backup_log.txt`  

**Penjelasan:** Perintah `cat` menampilkan isi file `/home/galuh/logs/backup_log.txt`.

**Output 18:**

`2025-11-23 10:03:50 - Backup berhasil: backup_20251123100350.tar.gz`  

**Penjelasan:** Isi file log, menunjukkan entri backup pertama.

**Output 19:**

`2025-11-23 11:13:45 - Backup berhasil: backup_20251123111345.tar.gz`  

**Penjelasan:** Isi file log, menunjukkan entri backup kedua (meskipun file ini tidak terlihat di daftar `ls`, mungkin dari sesi sebelumnya).

**Output 20:**

`2025-11-23 11:50:10 - Backup berhasil: backup_20251123115010.tar.gz`  

**Penjelasan:** Isi file log, menunjukkan entri backup ketiga (yang baru saja dibuat).

**Prompt 21:**

`galuh@ubuntu01:~/backupss`  

**Penjelasan:** Ini sepertinya prompt terminal yang tidak lengkap atau salah ketik (mungkin dimaksudkan sebagai `galuh@ubuntu01:~/backups$`), menunjukkan pengguna berada di direktori backups. (Catatan: Ada typo "backupss" yang mungkin dimaksudkan sebagai "backups".)

Secara keseluruhan, log ini menunjukkan proses backup yang berhasil dengan beberapa file backup yang tersimpan, dan log yang mencatat aktivitas. Jika ada bagian yang perlu diperbaiki atau detail lebih lanjut tentang script, beri tahu saya!

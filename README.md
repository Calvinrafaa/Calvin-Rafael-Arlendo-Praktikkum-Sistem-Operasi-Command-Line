# Praktikum Sistem Operasi
## 50 Command Line Ubuntu

Berikut merupakan 50 command line yang digunakan dalam praktikum Sistem Operasi menggunakan Ubuntu 26.06.

| No. | Command | Penjelasan |
|---|---|---|
| 1 | `pwd` | Menampilkan lokasi directory yang sedang digunakan. |
| 2 | `ls` | Menampilkan daftar file dan directory pada lokasi saat ini. |
| 3 | `ls -1` | Menampilkan daftar file dan directory dengan satu item pada setiap baris. |
| 4 | `ls -a` | Menampilkan seluruh file dan directory, termasuk file tersembunyi. |
| 5 | `ls -lh` | Menampilkan daftar file secara detail dengan ukuran file dalam format yang mudah dibaca. |
| 6 | `whoami` | Menampilkan username dari pengguna yang sedang aktif. |
| 7 | `id` | Menampilkan user ID, group ID, dan grup pengguna yang sedang aktif. |
| 8 | `hostname` | Menampilkan nama host atau nama komputer. |
| 9 | `hostname -I` | Menampilkan alamat IP yang dimiliki oleh komputer. |
| 10 | `date` | Menampilkan tanggal dan waktu sistem saat ini. |
| 11 | `uname -a` | Menampilkan informasi lengkap mengenai sistem operasi dan kernel. |
| 12 | `uname -r` | Menampilkan versi kernel Linux yang sedang digunakan. |
| 13 | `uptime` | Menampilkan berapa lama sistem telah berjalan sejak dinyalakan. |
| 14 | `which bash` | Menampilkan lokasi executable dari program Bash. |
| 15 | `whereis bash` | Mencari lokasi binary, source, dan manual dari Bash. |
| 16 | `echo` | Menampilkan teks atau nilai tertentu pada Terminal. |
| 17 | `printf` | Menampilkan teks dengan format yang dapat ditentukan oleh pengguna. |
| 18 | `cat /etc/os-release` | Menampilkan informasi distribusi dan versi sistem operasi Ubuntu. |
| 19 | `cat /proc/cpuinfo` | Menampilkan informasi mengenai CPU yang terdeteksi oleh sistem. |
| 20 | `cat /proc/meminfo` | Menampilkan informasi mengenai memory atau RAM sistem. |
| 21 | `lscpu` | Menampilkan informasi detail mengenai CPU dan arsitektur sistem. |
| 22 | `lsblk` | Menampilkan informasi mengenai block device seperti hard disk dan partisi. |
| 23 | `free -h` | Menampilkan penggunaan RAM dan swap dalam format yang mudah dibaca. |
| 24 | `df -h` | Menampilkan informasi penggunaan kapasitas penyimpanan pada filesystem. |
| 25 | `du -sh ~` | Menampilkan total ukuran directory home pengguna. |
| 26 | `ps` | Menampilkan proses yang sedang berjalan pada shell saat ini. |
| 27 | `ps aux` | Menampilkan daftar proses yang sedang berjalan secara lebih lengkap. |
| 28 | `top -b -n 1` | Menampilkan informasi proses dan penggunaan resource sistem dalam satu kali pengambilan data. |
| 29 | `pgrep bash` | Mencari Process ID (PID) dari proses Bash yang sedang berjalan. |
| 30 | `free` | Menampilkan informasi penggunaan memory RAM dan swap. |
| 31 | `ip addr` | Menampilkan informasi network interface dan alamat IP pada sistem. |
| 32 | `ip route` | Menampilkan tabel routing jaringan yang digunakan sistem. |
| 33 | `ping -c 4 8.8.8.8` | Menguji konektivitas jaringan ke alamat IP 8.8.8.8 sebanyak empat kali. |
| 34 | `ss -tuln` | Menampilkan koneksi atau socket jaringan yang sedang listening menggunakan TCP dan UDP. |
| 35 | `ip link` | Menampilkan informasi mengenai network interface yang tersedia pada sistem. |
| 36 | `lsusb` | Menampilkan perangkat USB yang terdeteksi oleh sistem. |
| 37 | `lspci` | Menampilkan perangkat yang terhubung melalui PCI atau PCI Express. |
| 38 | `getent hosts google.com` | Mencari informasi alamat IP yang terkait dengan hostname google.com. |
| 39 | `cat /etc/hostname` | Menampilkan hostname yang tersimpan pada sistem. |
| 40 | `cat /etc/hosts` | Menampilkan konfigurasi pemetaan hostname dan alamat IP pada sistem. |
| 41 | `grep "root" /etc/passwd` | Mencari baris yang mengandung kata "root" pada file daftar akun pengguna. |
| 42 | `getent passwd` | Menampilkan informasi akun pengguna yang tersedia pada sistem. |
| 43 | `sort /etc/passwd` | Mengurutkan isi file `/etc/passwd` berdasarkan urutan teks. |
| 44 | `env` | Menampilkan seluruh environment variable yang sedang aktif. |
| 45 | `printenv HOME` | Menampilkan nilai dari environment variable `HOME`. |
| 46 | `echo $SHELL` | Menampilkan jenis shell yang sedang digunakan oleh pengguna. |
| 47 | `groups` | Menampilkan grup yang dimiliki oleh pengguna yang sedang aktif. |
| 48 | `basename /home/$USER` | Mengambil nama terakhir dari sebuah path. |
| 49 | `dirname /home/$USER/Documents` | Mengambil bagian directory dari sebuah path. |
| 50 | `man ls` | Menampilkan manual atau dokumentasi penggunaan command `ls`. |

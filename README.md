# Instalasi OS debian 10 minimal di virtual box

## Yang dibutuhkan
1. Aplikasi Oracle VM Virtual Box Versi 6 ke atas
2. File ISO Debian versi 10.11.xx 32 bit

## Membuat Virtual Machine baru
1. Buka Aplikasi Virtual box
2. Pilih icon warna biru "New"
3. Ubah:
   - Name : debian_nama
   - Type : Linux
   - Version : Debian(32bit)
   - Next
4. Memory Size : 1024 MB, Next
5. Create a Virtual Hard disk, next
6. pilih VHD, next
7. pilih cinamically allocated, next
8. biarkan 8.00 GB, next

## Setting virtual Machine
1. pilih virtual machine yang sudah jadi
2. klik, tombol setting
3. menu sistem
   - hilangkan checklist untuk floppy
   - optical harus ada di urutan pertama
   - harddisk ada di urutan kedua

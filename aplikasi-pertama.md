---
description: >-
  Yang akan dipelajari: Pembuatan Project, Menjalankan Aplikasi Flutter ke
  Device.
---

# Aplikasi Pertama



## Membuat Project

Untuk membuat project flutter siapkan direktory kosong terlebih dahulu.

```bash
cd ~
mkdir flutter_playground
cd flutter_playground
```

Kemudian buat project baru dengan nama `app_pertama` dengan menggunakan perintah:

```bash
flutter create app_pertama
```

Nama project harus menggunakan huruf kecil dan tidak boleh terpisah spasi.

![Membuat Project Baru.](.gitbook/assets/image.png)

  
Tunggu hingga proses pembuatan project selesai, dan jika di list pada direktori tersebut, maka akan ada tambahan satu direktori yakni direktori `app_pertama`.

![](.gitbook/assets/image%20%281%29.png)

  
Masuk ke direktory project, kemudian test jalankan dengan menggunakan perintah `flutter run`. Tapi sebelumnya pastikan Emulator sudah dijalankan atau HP yang sudah di enable developer modenya terhubung dengan komputer anda.

```bash
cd app_pertama
flutter run
```

![Contoh hasil run.](.gitbook/assets/screen.png)

## Mengimport Project ke Visual Code Studio

Buka Visual code studio, kemudian pilih menu **File &gt; Add Folder to Workspace**

![](.gitbook/assets/image%20%282%29.png)

Cari dimana lokasi project dibuat, kemudian click folder project, kemudian import.

![](.gitbook/assets/image%20%283%29.png)

![](.gitbook/assets/image%20%284%29.png)

## Menjalankan Project via Visual Code Studio

Cara paling mudah adalah dengan menggunakan plugin terminal untuk VCS. Install plugin kemudian jalankan perintah `flutter run` melalu terminal.

![](.gitbook/assets/image%20%285%29.png)




# CalculatorApp

Kalkulator scientific atau kalkulator ilmiah digunakan secara luas dalam situasi yang memerlukan akses cepat ke fungsi matematika tertentu, 
terutama yang pernah dicari di tabel matematika. Mereka juga digunakan untuk perhitungan bilangan yang sangat besar atau sangat kecil.

## Layout Aplikasi
Pada layout aplikasi kalkulator, kita akan menggunakan view grub yaitu LinearLayout. LinearLayout adalah sekelompok tampilan yang menyejajarkan 
semua anak dalam satu arah, secara vertikal atau horizontal. Anda bisa menetapkan arah layout dengan atribut. [ Baca Selengkapnya...](https://developer.android.com/guide/topics/ui/layout/linear?hl=id)

Dari syntax terlihat dalam tag Button terdapat atribut yang di isi dengan nilai @dimen dan @drawable yang telah kita buat sebelumnya, 
di setiap Button juga terdapat atribut onClick yang berisi fungsi fungsional dari kalkulator seperti hasil perhitungan, menghapus data yang telah di hitung, 
dan digit angka yang akan di hitung.

## Fungsionalitas kalkulator
Pembuatan logika yang akan kita gunakan di balik layar dari aplikasi kalkulator kita, sebelum masuk MainActivity.kt kita terlebih dahulu membuat 
sebuah Interface.Interface adalah tampilan antarmuka yang digunakan pada ponsel Android. Berbeda dengan iOS yang sudah terintegrasi langsung dengan produk Apple, 
Android harus menggunakan UI pada berbagai merek smartphone yang berbeda. [ Baca Selengkapnya...](https://developer.android.com/training/basics/firstapp/building-ui?hl=id)
Tujuan membuat interface adalah menampung seluruh fungsi yang akan kita buat di MainActivity, (esuaikan nama fungsi dengan yang ada pada atribut onClick di layout activity_main.xml.)

Analisis Button Onclick:
1. Operator

   Berisi barisan kode untuk menggabungkan text_result yang sudah berisi data sesuai yang di hasilkan saat memanggil fungsi onDigit, kemudian data tersebut di gabungkan
   dengan method engan operator hitung (+,-,*,/).
2. btnClick_aquals

    Berfungsi untuk mencegah terjadinya force close ketika terjadi error saat runtime sehingga aplikasi bisa tetap berjalan.
3. btnClick_clear

   Ketika menekan Button clear(C) makan nilai dari text_result kembali menjadi “0”.
4. btnClick_delete

   Digunaan unutk mengatur berapa banyak karakter yang mau di hapus.
5. dll...


## Tampilan
- Halaman Utama

![WhatsApp Image 2020-10-23 at 20 07 10 (1)](https://user-images.githubusercontent.com/60412314/97019026-05a7ab80-157a-11eb-8643-fed251ca6897.jpeg)

- Nilai dari sin 90 __ Benar

![WhatsApp Image 2020-10-23 at 21 02 24](https://user-images.githubusercontent.com/60412314/97019252-50292800-157a-11eb-9ae2-a4522dc1cdb2.jpeg)

![WhatsApp Image 2020-10-23 at 21 02 24](https://user-images.githubusercontent.com/60412314/97019252-50292800-157a-11eb-9ae2-a4522dc1cdb2.jpeg)

- Nilai dai akar 4 __ Benar

![WhatsApp Image 2020-10-23 at 21 02 23](https://user-images.githubusercontent.com/60412314/97019021-03dde800-157a-11eb-972c-d018fd7f311c.jpeg)

![WhatsApp Image 2020-10-23 at 21 02 23 (1)](https://user-images.githubusercontent.com/60412314/97019029-06404200-157a-11eb-8d16-8f3b5dc3a283.jpeg)


# Terimakasih :)

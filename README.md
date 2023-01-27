# Image Segmentation Using HSV Color Space
2006043 - Ade Iskandar Zulkarnaen<br/>
1906062 - Dzikri Nursyaban

Program ini merupakan implementasi dari journal internasional dengan judul yang sama yang dapat diakses pada tautan [berikut ini](https://s.id/image-segmentation-journal).

Program ini mengimplementasikan image segmentation berdasarkan ruang warna HSV. Untuk referensi penggunaan ruang warna HSV, dapat dilihat pada tautan [berikut ini](https://stackoverflow.com/questions/10948589/choosing-the-correct-upper-and-lower-hsv-boundaries-for-color-detection-withcv).
Dengan menggunakan ruang warna HSV, kita dapat mengekstraksi bagian gambar berdasarkan warna objek nya. Kekurangannya adalah, kita harus menyesuaikan secara manual warna objek yang hendak diekstrak dan hal ini bergantung pada kualitas gambar, apakah memiliki noise atau tidak, terdapat banyak objek atau tidak.  

File [berikut ini](https://github.com/mrdzick/image-segmentation-hsv-color-space/blob/master/Image_Segmentation_using_HSV_Color_Space.ipynb) merupakan proses yang dilakukan berdasarkan paper. Proses yang dilakukan pada file ini memiliki kekurangan yaitu hanya bisa mengekstraksi objek pada gambar yang tidak terlalu rumit.
Kemudian, kami melakukan improvisasi untuk dapat mengekstraksi objek pada gambar yang lebih rumit seperti gambar-gambar pada file `images.zip`. Cara yang kami terapkan yaitu melakukan ekstraksi warna-warna pada objek yang hendak diekstrak secara satu per satu. Setelah itu, dilakukan penggabungan menjadi satu objek yang utuh. File [berikut ini](https://github.com/mrdzick/image-segmentation-hsv-color-space/blob/master/Image%20Segmentation%20using%20HSV%20Color%20Space_Improved.ipynb) merupakan hasil improvisasi nya.

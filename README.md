# Otomasi Prediksi Water Quality

Otomasi prediksi Water Quality Testing (pengujian kualitas air) berasal dari kebutuhan untuk mempercepat dan mempermudah proses pengujian kualitas air. Pengujian kualitas air adalah suatu langkah penting dalam menjaga kebersihan dan keamanan sumber air, baik itu untuk kebutuhan minum, industri, atau lingkungan.
Secara tradisional, pengujian kualitas air dilakukan secara manual oleh tenaga ahli laboratorium yang melakukan pengambilan sampel air dan menganalisisnya menggunakan metode kimia dan fisika yang rumit. Proses ini memakan waktu dan tenaga, dan seringkali menghasilkan data yang tidak segera tersedia. Selain itu, faktor manusia, seperti kesalahan pengambilan sampel atau kesalahan interpretasi hasil, dapat mempengaruhi keakuratan dan keandalan hasil pengujian.
Otomasi prediksi Water Quality Testing melibatkan penerapan teknologi dan metode otomatisasi untuk memprediksi kualitas air berdasarkan data yang tersedia. Berikut adalah beberapa latar belakang penting yang mendorong otomasi dalam prediksi kualitas air:
1.	Efisiensi dan Kecepatan: Dengan otomasi, proses pengujian dapat dipercepat sehingga data kualitas air dapat diperoleh dengan cepat dan tepat waktu. Dengan demikian, tindakan perbaikan atau mitigasi dapat diambil dengan lebih efisien dan cepat, mengurangi risiko paparan terhadap air yang tidak layak.
2.	Akurasi dan Keandalan: Otomasi mengurangi ketergantungan pada faktor manusia dalam pengambilan sampel dan analisis. Ini membantu mengurangi kesalahan manusia dan meningkatkan akurasi serta keandalan hasil pengujian kualitas air.
3.	Penghematan Biaya: Dalam jangka panjang, otomasi dapat mengurangi biaya yang terkait dengan pengujian kualitas air. Dengan mengurangi waktu, tenaga, dan penggunaan bahan kimia yang diperlukan dalam proses manual, biaya operasional dapat dikurangi.
4.	Monitor dan Peringatan Dini: Otomasi memungkinkan pengawasan dan pemantauan kualitas air secara terus-menerus. Dengan menggunakan sensor dan teknologi pemantauan jarak jauh, perubahan yang tidak diinginkan dalam kualitas air dapat dideteksi lebih awal, memungkinkan tindakan preventif atau perbaikan yang cepat.
 
**AutoAI** adalah sebuah alat grafis yang disediakan dalam *Watson Studio*, yang memiliki kemampuan untuk menganalisis kumpulan data, menghasilkan beberapa alur model, dan memeringkatnya berdasarkan metrik yang telah dipilih sesuai dengan permasalahan yang ada. Dalam contoh ini, kita akan menjelajahi kemampuan yang lebih lanjut dari AutoAI dengan menggunakan set data yang sama melalui pipeline model Pembelajaran Mesin Hasilkan untuk memilih model terbaik dalam rangka penyelesaian artikel masalah yang sedang dihadapi.
Kualitas air mengacu pada sifat kimia, fisik, dan biologi air berdasarkan standar penggunaanya. Ini paling sering digunakan dengan merujuk pada seperangkat standar yang kepatuhannya, umumnya dicapai melalui pengolahan air, dapat dinilai.
Berdasarkan hal – hal di atas maka penulis membuat sebuah projek yang dapat merencanakan dan menghitung melalui artificial intelligence (AI) dengan platform IBM Cloud dengan service  Watson Machine Learning, Watson Storage, dan Watson Studio untuk membuat sebuah Machine Learning kita dapat menggunakan tiga service tersebut untuk membuat sebuah prediksi mengenai water quality di suatu sumber air.
Langkah pertama yang dilakukan adalah menjalankan eksperimen AutoAI dengan memasukkan data ke dalam alat tersebut. AutoAI akan secara otomatis menganalisis data yang diberikan dan menghasilkan beberapa alur model yang berbeda. Setiap alur model akan dinilai berdasarkan metrik yang sebelumnya telah dipilih untuk menentukan model terbaik yang sesuai.
Setelah eksperimen selesai, kita akan dapat menghasilkan dan menyimpan buku catatan Python yang berisi hasil analisis dari AutoAI. Buku catatan ini dapat dijalankan dan hasilnya dapat dianalisis secara mendalam.
 
Apabila terdapat kebutuhan untuk melakukan perubahan pada model atau melakukan pelatihan ulang, kita dapat menggunakan Watson Machine Learning SDK. Dengan menggunakan SDK ini, kita dapat memodifikasi parameter model, melatih ulang model, dan menyimpan model yang telah diperbarui.
Terakhir, jika kita ingin menyebarkan model yang telah dilatih, kita dapat menggunakan Watson Machine Learning untuk melakukannya langsung dari dalam buku catatan. Hal ini memungkinkan kita untuk mengintegrasikan model dengan sistem lain atau membuat layanan prediksi yang dapat langsung digunakan oleh pengguna.
Dengan mengikuti pola kode ini, kita akan memahami cara menjalankan eksperimen AutoAI, menghasilkan dan menyimpan buku catatan Python, menjalankan buku catatan tersebut dan menganalisis hasilnya, melakukan perubahan dan pelatihan ulang model menggunakan Watson Machine Learning SDK, serta menyebarkan model yang telah dilatih menggunakan Watson Machine Learning dari dalam buku catatan. Dengan demikian, kita dapat memanfaatkan AutoAI dan Watson Machine Learning untuk memecahkan masalah dan mengimplementasikan solusi yang cerdas dengan tingkat kesamaan konten rendah.
Komponen yang disertakan dalam konteks yang Anda berikan adalah sebagai berikut:
1.	IBM [*Watson Studio*](https://cloud.ibm.com/catalog/services/watson-studio): IBM Watson Studio adalah platform yang membantu ilmuwan data dan analis dalam menyiapkan data, membangun, dan mengelola model dalam skala besar di berbagai lingkungan cloud. Watson Studio menyediakan berbagai alat dan lingkungan yang memungkinkan kolaborasi tim, eksplorasi data, pemodelan, dan penyebaran model.
2.	IBM [*Watson Machine Learning*](https://cloud.ibm.com/catalog/services/watson-machine-learning): IBM Watson Machine Learning merupakan layanan yang membantu ilmuwan data dan pengembang untuk mempercepat proses penyebaran kecerdasan buatan (AI) dan pembelajaran mesin. Watson Machine Learning memungkinkan pengguna untuk melatih, menyimpan, dan mendeploy model machine learning dengan mudah di lingkungan yang fleksibel.

## Teknologi Unggulan yang disebutkan meliputi:

1.	Machine Learning: Merupakan bidang ilmu yang berkaitan dengan penggunaan algoritma dan model statistik untuk menganalisis data historis dan memprediksi nilai atau perilaku masa depan.
2.	Python: Python adalah bahasa pemrograman tingkat tinggi yang sering digunakan dalam bidang ilmu data dan pembelajaran mesin. Python menyediakan sintaksis yang mudah dipahami dan beragam pustaka yang kuat untuk pengembangan model dan analisis data.
3.	Jupyter Notebook: Jupyter Notebook adalah aplikasi web sumber terbuka yang memungkinkan pengguna untuk membuat dan berbagi dokumen yang mengandung kode interaktif, visualisasi, dan narasi. Notebook Jupyter sering digunakan dalam eksplorasi data, prototyping model, dan berbagi hasil analisis.
4.	scikit-learn: scikit-learn adalah library pembelajaran mesin berbasis Python yang populer. Pustaka ini menyediakan berbagai algoritma dan fungsi untuk melakukan tugas seperti pemrosesan data, pemilihan fitur, klasifikasi, regresi, pengelompokan, dan evaluasi model.
5.	lale: lale adalah library Python yang kompatibel dengan scikit-learn. Library ini digunakan dalam AutoAI SDK untuk mendukung pengembangan model dan penyebaran yang semi-otomatis dalam ilmu data.

### Service yang di butuhkan :

1.	Akun [*IBM Cloud*](https://cloud.ibm.com/): Anda perlu memiliki akun IBM Cloud untuk menggunakan layanan-layanan yang disebutkan. Anda dapat mendaftar untuk akun percobaan yang tidak memerlukan biaya atau kartu kredit. 
2.	Instance layanan [*Cloud Object Storage*](https://cloud.ibm.com/objectstorage/create): Anda perlu membuat instance layanan Cloud Object Storage di IBM Cloud, yang digunakan untuk menyimpan data dan objek terkait proyek Anda.
3.	Instance layanan [*Watson Studio*](https://cloud.ibm.com/catalog/services/watson-studio): Anda perlu membuat instance layanan Watson Studio di IBM Cloud. Watson Studio memberikan lingkungan untuk bekerja dengan data, mengembangkan model, dan berkolaborasi dalam tim.
4.	Instance layanan [*Watson Machine Learning*](https://cloud.ibm.com/catalog/services/watson-machine-learning): Anda perlu membuat instance layanan Watson Machine Learning di IBM Cloud. Watson Machine Learning memungkinkan pelatihan, penyimpanan, dan penyebaran model machine learning.
5.	Membuat proyek Watson Studio dan memuat data dengan tingkat plagiat rendah: Anda perlu membuat proyek di Watson Studio dan memuat data dengan tingkat plagiat rendah ke dalam proyek tersebut. Hal ini mungkin berkaitan dengan tujuan atau tugas yang ingin Anda lakukan dalam lingkungan Watson Studio.

Langkah – Langkah pengerjaan otomasi untuk prediksi water quality :

## 1.	Jalankan AutoAI experiment
 
![image](https://github.com/MRTnsWD/HCAI_MartinusWidiyanto_AutoAI/assets/86089281/cbfcbd6f-3914-41b8-8043-8bebe9ea1e2b)
 

Penjelasan :
1.	Buka proyek yang telah dibuat di Watson Studio. Klik tombol Add to Project + di pojok kanan atas, lalu klik AutoAI experiment.
2.	Berikan nama eksperimen (ProvJabarWater), pilih layanan Watson Machine Learning dari dropdown, dan klik Create.
3.	Pada layar Add data source, klik Select from project dan centang Water Quality Testing.csv, lalu klik Select Asset.
4.	Pada bagian Konfigurasi detail, klik pada dropdown What do you want to predict? dan pilih Result from the list. Jika Anda menggunakan dataset yang berbeda, pilih kolom yang ingin AutoAI gunakan untuk melakukan prediksi. Klik Run experiment di pojok kanan bawah.

Setelah berhasil melakukan Langkah diatas maka anda akan melihat pemberitahuan yang menunjukkan bahwa eksperimen AutoAI telah dimulai. Tergantung pada ukuran dataset, langkah ini akan membutuhkan beberapa menit untuk diselesaikan.
 
## 2.	Buat experiment level notebook
 
![image](https://github.com/MRTnsWD/HCAI_MartinusWidiyanto_AutoAI/assets/86089281/6d7f6f7d-75d0-4444-a2d9-b01e8469a7dc)


** Experiment Notebook menyediakan kode yang dijelaskan secara detail sehingga Anda dapat: **
1.	Berinteraksi dengan pipeline model yang telah dilatih
2.	Mengakses detail model secara programatik, termasuk pentingnya fitur dan metrik pembelajaran mesin
3.	Visualisasikan setiap pipeline sebagai grafik dengan setiap node yang didokumentasikan untuk memberikan transparansi
4.	Unduh pipeline yang dipilih dan lakukan pengujian secara lokal
5.	Membuat deployment dan melakukan scoring terhadap model
6.	Mendapatkan konfigurasi eksperimen yang dapat digunakan untuk otomatisasi atau integrasi dengan aplikasi lainnya.

** Untuk membuat experiment notebook, lakukan Langkah – Langkah berikut : **

1.	Setelah eksperimen AutoAI selesai, klik tombol Save Experiment Code yang ditandai dengan ikon penyimpanan (floppy disk)
2.	Pada prompt Save Experiment Code, jika diperlukan, ubah default Name dan klik Save. Sebuah pop-up akan muncul yang menunjukkan bahwa notebook berhasil disimpan. Sekarang Anda akan melihat notebook ini dalam bagian Notebook di tab Assets.
 
a.	Load and execute notebook
Jelajahi bagian – bagian notebook untuk mendapatkan gambaran umum. Sebuah notebook terdiri dari sel - sel teks (markdown atau heading) dan sel-sel kode. Sel - sel markdown menyediakan komentar mengenai tujuan dari kode yang disusun.
Jalankan setiap sel secara individu dengan menyorot setiap sel, lalu klik tombol Run di bagian atas notebook atau menggunakan pintasan keyboard untuk menjalankan sel (Shift + Enter, namun bisa bervariasi tergantung pada platform). Saat sel sedang dieksekusi, sebuah tanda asterisk ([*]) akan muncul di sebelah kiri sel. Setelah sel selesai dieksekusi, akan muncul sebuah nomor urutan.
Buku catatan yang dihasilkan sudah diisi sebelumnya dengan kode Python dan dibagi menjadi 5 bagian utama sebagai berikut :
 
Gambar 15 package yang di butuhkan
b.	Setup
Bagian ini berisi informasi kredensial untuk mengakses Cloud Object Storage yang digunakan untuk mengambil pipeline AutoAI yang sedang digunakan. Sel ini berisi kode yang sudah disiapkan sebelumnya untuk mengekstrak data pelatihan yang digunakan dalam pembuatan pipeline serta hasil dari pipeline tersebut. 
 
Gambar 16 meta data experiment
Bagian ini berisi metadata pipeline yang digunakan untuk menjalankan eksperimen.
 
Gambar 17 metadata pipeline
api_key
Untuk dapat mengakses WML instance, pengguna perlu menghasilkan kunci API melalui akun cloud dan menyalinnya ke sel seperti yang ditunjukkan dalam sel di bawah ini. Instruksi untuk mendapatkan kunci API cloud dijelaskan dalam bagian markdown pada tangkapan layar yang ditampilkan di bawah ini.
 
Gambar 18 contoh integrasi Machine  Learning 

c.	Perbandingan Pipelines
Untuk membandingkan semua pipeline yang dihasilkan, panggil method summary() pada objek pipeline. Model dengan performa terbaik disimpan dalam variabel best_pipeline_name.
 
Gambar 19 baris pipeline yang terpilih
d.	Memeriksa Pipeline
Dalam bagian ini dari notebook, terdapat kode untuk memvisualisasikan tahapan-tahapan dalam model sebagai grafik menggunakan API AutoAI Watson Machine Learning.
 
Gambar 20 visualisasi pipeline 

Bagian ini juga berisi kode yang mengekstrak model saat ini dan mencetaknya sebagai kode Python.
 
Gambar 3 baris kode untuk mengekstrak model
e.	Deploy and score as web service using WML instance
Bagian dari notebook ini berisi kode yang dapat mendeploy model pipeline sebagai layanan web menggunakan Watson Machine Learning. Bagian ini membutuhkan pengguna untuk memasukkan kredensial agar dapat mengidentifikasi instansi WML yang tepat dan ruang deployment.
 
Gambar 4 deployments mode
 
Langkah deploy :
1.	Klik hamburger menu di sudut kiri atas halaman utama Watson Studio.
2.	Klik pada Deployment Spaces dari daftar dan pilih View All Spaces.
3.	Klik New Deployment Space, pilih opsi Create An Empty Space.
4.	Provide a name, pilih layanan machine learning yang telah dibuat sebelumnya, dan klik Create.
5.	Klik View New Space dan beralih ke tab Settings dan salin ID space tersebut.
Dapatkan target_space_id seperti yang dijelaskan dalam Langkah – Langkah di atas, lalu tempelkan dalam bagian create deployment. Penggunaan API Watson Machine Learning memerlukan wml_credentials dan target_space_id untuk mendeploy model pembelajaran mesin sebagai layanan web.
 
Gambar 5 deployments creation 

Setelah sel – sel dieksekusi, model akan dipromosikan ke ruang deployment dan sekarang tersedia sebagai layanan web. Anda dapat memverifikasinya melalui antarmuka pengguna seperti yang ditunjukkan di bawah ini.
 
Gambar 6 pipeline untuk webservice
III.3	Hasil Pengolahan Data dari AutoAI
Uraikan berbagai hasil yang diperoleh selama menjalankan project MSIB di organisasi Mitra MSIB, rinciannya mengacu pada lampiran dokumen teknik jika ada. Hasil selama mengikuti MSIB dikaitkan juga dengan tujuan MSIB di sub bab I.3.
Jadi hasil dari pemrosesan data di Watson studio dengan AutoAI mendapatkan beberapa hasil tes sebagai berikut :
1.	Relationship map
Di sini saya memantau pergerakan pH berdasarkan pengambilan test sebelumnya terdapat sedikit perbedaan data berdasarkan jumlah yang ada sebelumnya.
Pada AutoAI terdapat beberapa pipeline yang paling di rekomendasikan dari AutoAI seperti pada gambar : 

 
Gambar 7 hasil prediksi dari AutoAI
Di sini terdapat tiga rekomendasi pipeline dari AutoAI dengan beberapa hasil yang  berbeda selain hasil yang di dapat, AutoAI juga dapat memberikan peningkatan prediksi.
Berikut untuk hasil prediksi pH yang terbaik dari data set yang telah penulis dapat sebelumnya : 

 
Gambar 8 forecasting result
Di sini penulis mencoba analisis dari pH, karena pH merupakan salah satu indikator dari tingkat keasaman suatu air dan menjadi tingkat apakah air di suatu tempat dapat dikonsumsi, atau hanya di gunakan untuk mandi, mencuci dan lain – lain. 
Selain dari forecasting result di atas terdapat dua pengolahan data yang telah di olah oleh AutoAI  
 
Gambar 9 Prediction Over Time
"Prediction over time" mengacu pada kemampuan model prediksi untuk menghasilkan prediksi atau perkiraan terhadap suatu variabel atau fenomena seiring berjalannya waktu.
Karena sebelumnya penulis membuat  prediksi data berdasarkan waktu maka di sini terdapat hasil pengolahan data berdasarkan waktu ke waktu.
Selain beberapa hasil di atas autoAI juga memberikan data error dari backtest yang telah di lakukan seperti halnya gambar di bawah.
 
Gambar 10 Mean absolute error by Backfest

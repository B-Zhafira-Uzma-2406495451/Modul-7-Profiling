# Modul-7-Profiling
screenshot untuk test plan endpoint /all-student di JMeter
![Commit 2 screen capture](/assets/images/test_plan_1.png)
screenshot untuk test plan endpoint /all-student-name di JMeter
![Commit 2 screen capture](/assets/images/test_plan_2.png)
screenshot untuk test plan endpoint /highest-gpa di JMeter
![Commit 2 screen capture](/assets/images/test_plan_3.png)
screenshot untuk test plan endpoint /all-student di log
![Commit 2 screen capture](/assets/images/testplanlog1.png)
screenshot untuk test plan endpoint /all-student-name di log
![Commit 2 screen capture](/assets/images/testplanlog2.png)
screenshot untuk test plan endpoint /highest-gpa di log
![Commit 2 screen capture](/assets/images/testplanlog3.png)

## Reflection Module 7
1. Perbedaan utama antara JMeter dan IntelliJ Profiler terletak pada sudut pandang pengukuran performa aplikasi. JMeter
berfokus pada evaluasi eksternal dengan mensimulasikan beban kerja untuk mengukur waktu respons dari perspektif pengguna
akhir pada tingkat makro. Sementara itu, IntelliJ Profiler bekerja pada tingkat mikro dengan membedah eksekusi program
secara internal untuk mengidentifikasi penggunaan sumber daya CPU pada setiap method melalui visualisasi seperti flame
graph. Secara keseluruhan, JMeter berfungsi sebagai alat untuk membuktikan keberhasilan optimasi secara umum, sedangkan
profiler berperan sebagai instrumen diagnosis untuk menemukan penyebab teknis keterlambatan di dalam struktur kode.

2. Proses profiling membantu saya untuk mengidentifikasi titik lemah aplikasi saya melalui visualisasi rincian eksekusi
baris kode yang tidak terlihat dari sisi luar. Dengan menggunakan flame graph, saya dapat melihat method mana yang 
menghabiskan waktu proses paling tinggi dan membebani CPU. Metrik objektif seperti CPU Time dan persentase beban kerja
memberikan saya pemahaman yang mendalam untuk mendeteksi masalah teknis seperti kueri basis data berulang atau
inefisiensi memori. Dengan demikian, profiling memungkinkan saya melakukan perbaikan yang tepat pada bagian kode yang
paling bermasalah untuk meningkatkan kinerja sistem secara menyeluruh.

3. Iya. saya merasa IntelliJ Profiler membantu saya untuk menganalisis dan mengidentifikasi hambatan performa karena
merupakan fitur bawaan yang sudah terintegrasi di dalam lingkungan developers. Fitur ini menyediakan data visual berupa
grafik api yang menunjukkan method apa saja yang paling banyak mengonsumsi waktu proses dan sumber daya sistem secara
spesifik. Melalui  ini, saya dapat dengan mudah menemukan bagian kode yang menjadi penyebab lambatnya aplikasi saya 
seperti masalah kueri basis data yang berulang atau penggunaan memori yang tidak efisien. Keberhasilan optimasi juga
dapat saya pantau secara langsung melalui penurunan angka waktu proses dan persentase beban kerja setelah kode
diperbaiki.

4. Tantangan utama yang saya dihadapi saat melakukan pengujian performa dan profiling adalah hal yang berkaitan dengan
pengaturan teknis dan lingkungan pengujian di perangkat lokal. Salah Beberapa di antaranya meliputi grafik profil yang
terlihat kosong akibat aktivitas yang direkam kurang signifikan atau proses eksekusi yang terlalu cepat pada jumlah data
yang kecil. Masalah lainnya adalah kesalahan navigasi folder pada terminal saat menjalankan perintah pengujian.
Tantangan tersebut diatasi dengan melakukan akses berulang pada endpoint aplikasi agar terekam oleh sistem serta
menggunakan fitur bantuan otomatis untuk memperbaiki struktur kode. Pengaturan jalur file yang tepat serta pemindahan
file ke direktori yang sesuai juga menjadi solusi kunci dalam menyelesaikan kendala operasional tersebut.

5. Manfaat yang saya dapatkan dari penggunaan IntelliJ Profiler adalah kemampuan untuk melakukan bedah jalannya
eksekusi program dari sisi internal untuk mendapatkan data objektif di tingkat mikro. Saya dapat memperoleh rincian
konsumsi sumber daya untuk setiap metode secara akurat melalui tampilan grafik api yang informatif. Hal ini memudahkan
proses diagnosis saya terhadap masalah teknis seperti kueri basis data yang berlebihan atau pengelolaan teks yang kurang
optimal di dalam perulangan kode. Selain itu, tersedianya metrik seperti waktu proses serta persentase beban memberikan
tanda yang jelas untuk mengukur peningkatan efisiensi setiap fungsi.

6. Situasi ketika hasil profiling tidak sepenuhnya konsisten dengan temuan pengujian JMeter ditangani dengan memahami
perbedaan cakupan pengukuran antara tingkat makro dan mikro. JMeter digunakan untuk mengevaluasi perilaku aplikasi dari
sisi eksternal berdasarkan perspektif pengguna akhir, sedangkan profiler fokus pada efisiensi eksekusi di dalam struktur
kode. Dalam proses optimasi, JMeter berperan sebagai instrumen untuk membuktikan peningkatan kecepatan respons secara
utuh, sementara profiler digunakan untuk memperbaiki titik lemah yang spesifik di tingkat internal. Dengan memadukan
kedua data tersebut, pengembang dapat memastikan bahwa perbaikan teknis yang dilakukan benar-benar memberikan dampak
nyata pada performa aplikasi secara keseluruhan.

7. Strategi yang saya terapkan dalam mengoptimasi kode aplikasi mencakup penggunaan teknik pemuatan data secara
menyeluruh untuk menghindari masalah kueri berulang dan penggunaan alat pembangun teks yang lebih efisien. Selain itu,
pemanfaatan fitur pengurutan data langsung di sisi basis data juga dilakukan untuk mengurangi beban pemrosesan pada
memori aplikasi. Verifikasi akhir dilakukan dengan memantau pesan sukses di terminal dan memeriksa jumlah baris data di
dalam basis data untuk memastikan konsistensi informasi tetap terjaga.
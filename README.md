# PSD

## Materi:

- Pertemuan 1: Pengenalan Mata Kuliah Proyek Sains Data.
- Pertemuan 2: Pengenalan pada aplikasi power BI.
- Pertemuan 3: Membahas materi bagaimana cara menghubungkan Power BI dengan Database kita menggunakan python
- Pertemuan 4: Membahas tentang bagaimana cara mencari outliers dari suatu data dengan beberapa algoritma yaitu: knn, ABOD, clustering
- Pertemuan 5: Membahas mengani data yang mempunyai data oversampling dan metode yang digunakan untuk dataset oversampling. metode ADASYN akan membangkitkan data sintetis jika ada disekita mayoritas dan minoritas. sedangkan metode SMOTE akan membangkitkan data sintetis jika disekitar minor saja
- Pertemuan 6: Materi baru Ensemble learning metode yang digunakan adalah bagging classifier dan random forrest. Teorinya adalah dengan kita menggunakan metode ini diibaratkan kita
- Pertemuan 7: -
- Pertemuan 8: Melakukan Ujian Tengah Semester
- Pertemuan 9: Belajar bagaimana cara mengambil data dari website Copernicus. sekaligus uji coba website tersebut dengan menggunakan jupyterlab. 
- Pertemuan 10: Review Ulang(Penjelasan mengenai bagaimana normalisasi bekerja dan setelah selesai di denormalisasi. mencari korelasi target dengan setiap fitur pada superviced di timeseries.) Menganalisis Audio dan menambahkan 20 fitur statistika 


## Tugas:

- Tugas 1: Menginstall aplikasi yang nantinya akan dipakai selama mata kuliah berlangsung serta tak lupa juga membuat web statis dengan menggunakan colab
- Tugas 2: Mencari dataset mengenai bisnis lalu membuat database menggunakan postgres sql. Dataset yang sudah mahasiswa cari lalu dimasukkan ke dalam database postgres yang sudah dibuat. selanjutnya adalah menganalisis datasetnya dengan menggunakan power BI. Analisisnya berupa apa tipe datanya, bagaimana konsistensi datanya, mendeteksi adanya outliers, missing value dan lain lain.
- Tugas 3: Menambahkan dataset kedalam 2 jenis database yang berbeda, lalu hubungkan dataset tadi menjadi 1 table kembali dengan menggunakan python dan power BI. 
- Tugas 4: Mencari data outliers kemudian menghapusnya. algoritma yang digunakan adalah knn, ABOD, LOF(Local Outliers Factor).
- Tugas 5: Membuat data sintetis dengan menggunakan algoritma SMOTE
- Tugas 6: 
- Tugas 7: Mencoba menganalisis data dengan menggunakan aplikasi KNIME 
- Tugas UTS
- Tugas 9: Dengan menggunakan website Copernicus, Cari data NO2 dari daerah masing masing lalu lakukan pemrosesan data dari dataset tersebut.
- Tugas 10: Memperbaiki bab project timeseries. Outliers detection, Auto korelasi, evaluasi MAPE, membuat model untuk implementasi, menghasilkan kualitas udara. Membuat interface seperti berikut ini : Input data --> Model Normalisasi --> Model KNN --> Model Denormalisasi --> Output data --> Memunculkan Kualitas Udara!!. Tambahan membuat model untuk mendeteksi suara 100 buka dan 100 tutup. 



### Run code ini menjalankan Virtual Environment

        .venv\Scripts\activate

### Run code ini untuk mengeskpor Package python

        pip freeze > requirements.txt

### Run code dibawah ini untuk menginstall Package di versi python lain

        pip install -r requirements.txt

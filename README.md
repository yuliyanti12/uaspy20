# Project UAS Bahasa Pemrograman
silakan tuliskan langkah-langkah disertai screenshotnya
1. Clone repository tersebut ke local komputer (gunakan PyCharm agar lebih mudah)
2. Lakukan perbaikan pada code program yang ada sehingga aplikasi dapat berjalan dengan
semestinya. 3. Lengkapi README.md dengan penjelasannya. 4. Commit dan Push kembali pada repository masing-masing.
Ketentuan dan Alur Program:
Pada class MainApp, lakukan overriding terhadap method:
a. list_book(): buat instance class ViewBook() dan call method list()
b. add_book(): buat instance class InputBook() dan call method input(), lalu hasilnya tambahkan
pada attribute books
c. search_book(): buat instance class InputBook() dan call method search(), kemudian buat
instance class SearchHelper() dan call method search_title(), kemudian buat instance class
ViewBook dengan parameter books dari search_title() dan panggil method list()
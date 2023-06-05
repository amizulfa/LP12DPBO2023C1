# LP12DPBO2023C1

## JANJI
> Saya Amida Zulfa Laila dengan NIM 2101147 mengerjakan Latihan Praktikum 12 dalam mata kuliah Desain Pemrograman Berorientasi Objek untuk keberkahan-Nya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Aamiin.

## ALASAN
Saya menggunakan struktur ```MVVM``` (Model-View-ViewModel) karena keterpisahannya jelas yaitu memisahkan tugas-tugas yang berbeda menjadi komponen yang terpisah. ```Model``` bertanggung jawab untuk menyimpan data, ```view``` bertanggung jawab untuk menampilkan tampilan, dan ```viewmodel``` bertindak sebagai penghubung antara keduanya. ```view``` tidak ada keterikatan terhadap ```model```. 

Dalam struktur program ini, File ```gameObjek``` dan ```player``` digunakan untuk menyimpan data dan secara otomatis masuk ke dalam ```model```. Selain itu, ```gameInterface```, yang merupakan interface dari ```gameObject``` dan ```player```, juga masuk ke dalam ```model```. File ```display``` dan ```synchronization``` termasuk ke dalam ```view``` karena mereka berfungsi untuk mengatur tampilan. File ```controller```, ```game```, dan ```handler``` masuk ke dalam ```viewmodel``` karena mereka bertanggung jawab untuk menghubungkan antara data yang ada di ```model``` dengan tampilan permainan di file ```display``` yang berada di ```view```.


# Nama:AqshalFakhri Eka Surya Saputra NIM:362358302071 Kelas:2A TRPL

# Tugas Praktikum 1
**1. Maksud dari Langkah 4 pada Praktikum**
Langkah 4 melibatkan pembuatan file data_layer.dart untuk menggabungkan ekspor dari model plan.dart dan task.dart, dengan tujuan mempermudah proses impor model-model tersebut di bagian lain aplikasi. Dengan menggabungkan ekspor ini dalam satu file, Anda hanya perlu mengimpor data_layer.dart untuk mengakses semua model yang diperlukan, sehingga membuat proses impor lebih sederhana, struktur proyek lebih terorganisir, dan kode lebih efisien serta mudah untuk dipelihara.


**2. Pentingnya Variabel plan pada Langkah 6**
Variabel plan pada Langkah 6 digunakan untuk menyimpan data rencana yang berisi daftar tugas dalam aplikasi, yang kemudian dapat dimanipulasi dan diperbarui, seperti menambahkan tugas baru atau mengubah status tugas. Variabel ini dibuat sebagai konstanta karena saat objek Plan dibuat, nilai-nilai default seperti nama dan daftar tugas ditetapkan melalui konstruktor, dan menggunakan konstanta memastikan bahwa nilai awal objek tidak dapat diubah setelah objek dibuat, membantu menjaga integritas data dan mencegah perubahan yang tidak diinginkan.

**HASIL**

![Screenshot 2024-11-11 100234](https://github.com/user-attachments/assets/cc88ae43-c395-4c55-a7bf-0acd7d0be4cc)


![Screenshot 2024-11-11 100445](https://github.com/user-attachments/assets/1ff6a7ac-cd71-4fb8-b554-fb5b10f34f79)



**3.**
Pada Langkah 11, initState() digunakan untuk menginisialisasi variabel seperti scrollController dan menambahkan listener untuk menangani peristiwa scroll saat State pertama kali dibuat, sedangkan pada Langkah 13, dispose() digunakan untuk membersihkan scrollController dan membebaskan sumber daya yang digunakan ketika State tidak lagi diperlukan, sehingga memastikan pengelolaan siklus hidup objek yang tepat.

# Tugas Praktikum 2
Pada Langkah 1, InheritedWidget adalah widget yang memungkinkan data dapat diteruskan ke widget anak tanpa perlu meneruskannya secara manual. InheritedNotifier adalah subclass dari InheritedWidget yang lebih khusus digunakan untuk menangani perubahan data dengan menghubungkan ValueNotifier untuk mengelola state yang berubah. Hal ini memungkinkan widget yang bergantung padanya untuk secara otomatis memperbarui UI saat data berubah, sehingga pengelolaan state menjadi lebih efisien dan mudah.

Pada Langkah 3, metode yang ditambahkan bertujuan untuk mempermudah perhitungan dan penampilan status progres dari task yang ada pada Plan. Dengan menambahkan dua metode ini, kita dapat dengan mudah menampilkan jumlah task yang selesai dan progres keseluruhan tanpa harus menghitungnya berulang-ulang di tempat lain dalam kode, sehingga logika aplikasi menjadi lebih terstruktur dan efisien.


# Tugas Praktikum 3

![Screenshot 2024-11-11 111629](https://github.com/user-attachments/assets/ebeb296b-252d-4ab6-a22a-d06ae39eac69)

**Diagram tersebut menggambarkan dua hierarki widget dalam aplikasi Flutter sebelum dan sesudah navigasi.**

Sebelum navigasi (kiri):

MaterialApp mencakup PlanProvider, yang kemudian memuat PlanCreatorScreen.
PlanCreatorScreen terdiri dari Column yang berisi TextField dan Expanded, dengan ListView di dalamnya.
Setelah navigasi (kanan):

MaterialApp menavigasi ke PlanScreen menggunakan Navigator Push.
PlanScreen terdiri dari Scaffold, yang di dalamnya terdapat Column.
Column ini berisi Expanded dengan ListView di dalamnya, serta SafeArea yang berisi Text.
Diagram ini menunjukkan perpindahan dari satu layar ke layar lain dalam aplikasi, dengan perubahan struktur widget yang menampilkan elemen UI yang berbeda.


**HASIL**


![Screenshot 2024-11-11 104040](https://github.com/user-attachments/assets/970a8e4a-4ca3-4813-bc70-321d856f969b)



![Screenshot 2024-11-11 104204](https://github.com/user-attachments/assets/d7f2b713-bb49-494c-ad09-95c0b27030d4)




https://github.com/user-attachments/assets/8584b0a7-336b-4916-95f1-169dba00dd58


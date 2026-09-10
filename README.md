# pemrograman-dasar-2
Repository pembelajaran mata kuliah Pemrograman Dasar 2, mencakup konsep memori, struktur data, pemrograman berorientasi objek (OOP), hingga pengembangan aplikasi berbasis MFC (Microsoft Foundation Classes) dan Database.

# 📚 Pemrograman Dasar 2 (Advanced Programming Concepts)

Repository ini berisi kumpulan materi, modul, dan kode sumber (source code) untuk pembelajaran mata kuliah **Pemrograman Dasar 2**. Materi dirancang secara bertahap mulai dari manajemen memori tingkat lanjut, struktur data dinamis, konsep Pemrograman Berorientasi Objek (POP/OOP), hingga pengembangan aplikasi desktop menggunakan *Microsoft Foundation Classes* (MFC) dan integrasi basis data.

---

## 🗂️ Daftar Isi Materi

Berikut adalah cakupan materi yang tersedia pada struktur folder repository ini:

1. **Konsep Dasar Pointer** (`01-Pointer`)
   * Pengenalan alamat memori, dereference, dan operasi aritmatika pointer.
   * Pointer ke pointer dan penggunaannya dalam fungsi (*pass by reference*).

2. **Memori Dinamis** (`02-Dynamic-Memory`)
   * Alokasi dandealokasi memori secara dinamis menggunakan `new` dan `delete` (atau `malloc` dan `free`).
   * Pencegahan *memory leak* dan penanganan *dangling pointer*.

3. **Struktur Data** (`03-Data-Structures`)
   * Penggunaan `struct` untuk mendefinisikan tipe data kustom.
   * Penggabungan struktur data dengan array dan pointer.

4. **Singly Linked List** (`04-Singly-Linked-List`)
   * Implementasi struktur data rantai tunggal.
   * Operasi dasar: *Insertion* (di awal, akhir, tertentu), *Deletion*, dan *Traversal*.

5. **Doubly Linked List** (`05-Doubly-Linked-List`)
   * Implementasi struktur data rantai ganda dengan *pointer next* dan *prev*.
   * Navigasi dua arah pada elemen data.

6. **Konsep Class** (`06-Class-and-Object`)
   * Dasar-dasar Pemrograman Berorientasi Objek (PBO/OOP).
   * Implementasi *Class*, *Object*, *Encapsulation* (Access Modifiers: `public`, `private`, `protected`), serta Constructor & Destructor.

7. **Inheritance (Pewarisan)** (`09-Inheritance`)
   * Konsep pewarisan sifat antar class (*Base class* dan *Derived class*).
   * *Method overriding* dan penggunaan polimorfisme dasar.

8. **MFC (Microsoft Foundation Classes)** (`10-MFC-Introduction`)
   * Pengenalan framework MFC untuk pengembangan aplikasi desktop berbasis Windows.
   * Pemahaman arsitektur *Document-View* dan komponen dasar GUI.

9. **Combo Box** (`11-MFC-Combo-Box`)
   * Implementasi kontrol *Combo Box* pada antarmuka MFC.
   * Pengelolaan data pilihan (*list items*) dan event handling interaksi pengguna.

10. **File Handling** (`12-File-Handling`)
    * Operasi pembacaan (*reading*) dan penulisan (*writing*) file eksternal (teks/biner).
    * Penyimpanan data persisten menggunakan C++ stream (`ifstream`, `ofstream`).

11. **MFC App Database** (`13-MFC-Database`)
    * Integrasi aplikasi desktop MFC dengan sistem basis data.
    * Implementasi operasi CRUD (Create, Read, Update, Delete) melalui koneksi database pada antarmuka MFC.

---

## 🛠️ Prasyarat & Tools
* **Bahasa Pemrograman:** C++
* **IDE / Editor:** Visual Studio / Code::Blocks / Dev-C++
* **Environment:** Windows (untuk modul MFC)

---

## 👨‍💻 Cara Penggunaan
1. Clone repository ini ke perangkat Anda:
   ```bash
   git clone [https://github.com/faturoraturu/pemrograman-dasar-2.git](https://github.com/faturoraturu/pemrograman-dasar-2.git)

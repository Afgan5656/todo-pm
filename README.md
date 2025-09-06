# todo-pm

Todo App
## Deskripsi Aplikasi
Aplikasi Todo ini dibuat menggunakan Flutter untuk membantu pengguna mengelola daftar tugas harian mereka. Pengguna dapat menambahkan, menandai selesai, dan menghapus tugas dengan mudah. Aplikasi ini menggunakan arsitektur sederhana dengan pemisahan antara model, provider untuk state management, dan widget UI.

## Diagram Singkat Widget Tree
MaterialApp
 └── TodoApp
      └── Scaffold
           ├── AppBar
           ├── Body: TodoList (ListView menampilkan todo items)
           └── FloatingActionButton (Untuk menambah todo baru)

## Pendekatan State Management yang Dipilih + Alasan
Aplikasi ini menggunakan Provider sebagai state management yang diimplementasikan dalam todo_provider.dart.

## Alasan memilih Provider:
Mudah digunakan dan diintegrasikan dengan Flutter.
Memisahkan logika bisnis dari UI, sehingga kode lebih terstruktur dan mudah dipelihara.
Efisien dalam pembaruan UI, hanya widget yang membutuhkan data akan rebuild saat terjadi perubahan.
Skalabilitas yang baik untuk pengembangan aplikasi lebih lanjut.

## demo
<img width="758" height="413" alt="Screenshot 2025-09-06 082018" src="https://github.com/user-attachments/assets/09afc421-4545-493b-bef9-9aad0d21311c" />
<img width="952" height="444" alt="Screenshot 2025-09-06 082005" src="https://github.com/user-attachments/assets/171859d9-1884-4cc2-b07d-fff807d7e383" />
<img width="945" height="302" alt="Screenshot 2025-09-06 082150" src="https://github.com/user-attachments/assets/03168c58-8535-43a2-ac44-8132b8824844" />
<img width="380" height="257" alt="Screenshot 2025-09-06 082046" src="https://github.com/user-attachments/assets/c636f1fd-d2b6-4f02-b997-1512bd889d39" />



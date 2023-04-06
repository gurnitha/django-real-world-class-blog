# Membangun a real-world class proyek blog 
Aplikasi ini dibangun sebagai kenangan ultah saya yg ke-65

[Github repo](https://github.com/gurnitha/django-real-world-class-blog)


## 1. Setup

        Aktivitas:

        1. Menginstal python
        2. Membuat repositori di Github
        3. modified:   README.md
        4. push file ke Github


#### [1.1 Pra-syarat](https://github.com/gurnitha/django-real-world-class-blog/commit/35a530d41d8113da2a43d5485b95a120c597f522)

        Aktivitas:

        1. Membuat saran

        Kelas ini adalah kelas 'intermediate', dan oleh karenanya, And diasumsikan telah mempelari dasar-dasar:

        1. HTML,
        2. CSS,
        3. JavaScript,
        4. Python, dan
        5. Framework Django.
        6. Memiliki keinginan yang kuat untuk bisa dan berdisiplin diri untuk mengikuti dan menyelesaikan setiap tahapan kelas ini sampai tuntas.

        Namun demikian, Anda tidak diwajibkan sudah menguasai semua hal di atas. Paling tidak Anda memiliki sedikit pengalaman menggunakan bahasa-bahasa di atas.

        Bila tidak sama sekali, maka Anda akan mengalami kesulitan dalam mengikuti kelas ini.

        Saran:

        Anda bisa mempelajari ke-5 hal di atas di youtube.com. Ada banyak materi atau tutorial tingkat dasar di youtube tentang HTML, CSS, JavaScript, Python, dan Django.

        Setelah itu, Anda dapat kembali lagi ke sini untuk mengikuti kelas ini. 

        2. modified:   README.md
        3. push file ke Github


## 2. Membuat django proyek dan app

        Aktivitas:

        1. modified:   README.md


#### [2.1 Membuat virtualenv](https://github.com/gurnitha/django-real-world-class-blog/commit/79078c1ec9735aa85a61a3ea7c6955d5adc18e8d)
        
        Aktivitas:

        1. Tentang virtualenv    

        Lingkungan virtual atau virtualenv dapat digambarkan sebagai direktori instalasi terisolasi. 
        Isolasi ini memungkinkan Anda untuk melokalkan instalasi dependensi proyek Anda, tanpa memaksa Anda untuk menginstalnya di seluruh sistem.

        Virtualenv digunakan untuk mengelola paket Python untuk proyek yang berbeda. 

        Menggunakan virtualenv memungkinkan Anda untuk menghindari menginstal paket Python secara global yang dapat merusak alat sistem atau proyek lain. Anda dapat menginstal virtualenv menggunakan pip.

        Berikut adalah langkah-langkah membuat virtualenv:

        2. Memastikan python sudah diinstal dan memastikan versinya. Dalam proyek ini kita akan menggunakan Python versi 3.5 atau yang lebih atas. Saya akan menggunakan Python versi 3.9.5.

        > Perintahnya: python --version

        3. Memastikan versi pip yang sudah terinstal. Biasa pip terinstal dengan sendirinya saat Anda menginstal Python.

        > Perintahnya: pip --version

        4. Memastikan virtualenv sudah terinstal. Biasa virtualenv juga terinstal dengan sendirinya saat Anda menginstal Python.

        > Perintahnya: virtualenv --version

        5. Membuat virtualenv dengan nama venv3941

        > Perintahnya:  python -m venv venv3941

        6. Memodifikasi file .gitignore dengan menambahkan venv3941 di dalamnya. Hal ini dimaksudkan agar venv3941 dan semua file yang ada di dalamnya tidak disimpan ke dalam repositori.

        7. Membuat git commit dan push file ke Github


#### [2.2 Menginstal django](https://github.com/gurnitha/django-real-world-class-blog/commit/cf0b3025111fd407e0f2ecb3e6d8f74d54c656c3)
        
        Aktivitas:

        1. Mengaktifkan venv3941

        Untuk mengistal django, kita perlu mengakifkan virtualenv atau venv3941 yang telah kita buat.

        > Perintahnya: 
        F:\_ingafter65\KAMU_BISA_APA\django-real-world-class-blog (main)
        λ venv3941\Scripts\activate

        NOTE:

        1.1 Pastikan code editor Anda menunjukkan bahwa Anda ada dalam root direktori proyek Anda. Dalam hal ini, root direktorinya dalah 'django-real-world-class-blog'.

        1.2 venv3941 ada di dalam root direktori 'django-real-world-class-blog'

        2. Menginstal django

        Setelah venv3941 aktif, maka sekarang kita bisa menginstal django.

        Dalam proyek ini kita akan menggunakan Framework Django versi 4.1. Cara menginstalnya adalah seperti dibawah ini.

        > Perintahnya: pip install django==4.1

        3. Meng-update pip

        Setiap kali menginstal django, kita selalu diminta untuk meng-update pip. Agar venv3941 kita updated, maka kita akan mengupdate pip.

        > Perintahnya: python.exe -m pip install --upgrade pip

        4. Memeriksa hasil instalasi

        Setelah berhasil membuat venv3941, selanjutnya saya akan sebut venv saja, dan berhasil menginstal django, maka kita perlu memeriksanya untuk memastikan semua terinstal dengan sempurna.

        > Perintahnya: pip list

        5. Modifikasi README.md file


#### [2.3 Membuat proyek django](https://github.com/gurnitha/django-real-world-class-blog/commit/e739b5f4bb9be956555fcf068022c84c6b153171)
        
        Aktivitas:

        Langkah-langkah membuat proyek django:

        1. Me-non-aktifkan venv3941

        Sebagai latihan, saya akan mendemokan cara me-non-aktifkan venv3941.

        Perintahnya:

        F:\_ingafter65\KAMU_BISA_APA\django-real-world-class-blog (main)
        (venv3941) λ deactivate

        Kemudian akan menjadi seperti ini:
        F:\_ingafter65\KAMU_BISA_APA\django-real-world-class-blog (main)

        2. Memastikan venv3941 sedang aktif. Kalau venv3941 sedang tidak aktif, maka Anda harus mengaktifkannya terlebih dahulu sebelum membuat proyek django.

        > Perintahnya: 
        F:\_ingafter65\KAMU_BISA_APA\django-real-world-class-blog (main)
        λ venv3941\Scripts\activate

        Setelah itu, maka akan terlihat seperti ini pada code editor Anda:

        F:\_ingafter65\KAMU_BISA_APA\django-real-world-class-blog (main)
        (venv3941) λ

        NOTE: Jika pada code editor Anda terlihat hal seperti di bawah ini, maka hal itu menandai bahwa venv3941 sedang aktif.

        (venv3941) λ

        Jika tidak terlihat seperti itu, maka:

        2.1 Pastikan code editor Anda menunjukkan bahwa Anda ada dalam root direktori proyek Anda. Dalam hal ini, root direktorinya dalah 'django-real-world-class-blog'.

        2.2 venv3941 ada di dalam root direktori 'django-real-world-class-blog'

        3. Mencari perintah untuk membuat proyek django

        Agar bisa membuat proyek, maka hal pertama yang harus kita ketahui adalah perintah untuk membuat proyek itu. Perintah itu tersembunyi di dalam venv3941 yang kita buat. Untuk mengeluarkannya, kita perlu menggukan perintah seperti di bawah ini:

        > Perintahnya: django-admin

        4. Membuat proyek django

        Sekarang kita sudah tahu perintah untuk membuat proyek django, yakni seperti ini di bawah ini:

        > Perintahnya: django-admin startproject config .

        Dengan menggunakan perintah itu, maka proyek django dengan nama 'config' dapat di buat.

        Perhatikan tanda (.) atau titik setelah kata config. Titik (.) itu menandai bahwa proyek dengan nama config itu diletakkan di dalam root direktori atau di dalam folder'django-real-world-class-blog'.

        Lihatlah gambar dibawah ini.

        5. File yang ada di dalam proyek django 'config'

        modified:   README.md
        new file:   config/__init__.py
        new file:   config/asgi.py
        new file:   config/settings.py
        new file:   config/urls.py
        new file:   config/wsgi.py
        new file:   manage.py


#### 2.4 Menjalankan proyek django untuk kali pertama
        
        Aktivitas:

        Langkah-langkah menjalankan proyek django:

        1. Jalankan server lokal

        Untuk menjalankan proyek django, Anda perlu melakukan hal-hal seperti di bawah ini:

        1.1 Buka code editor Anda dan aktifkan venv3941.
        
        2.2 Setelah itu, jalankan server lokal.
        > Perintahnya: python manage.py runserver

        2.3 Buka browser Anda (saya menggunakan Chrome)

        2.4 Copy file: http://127.0.0.1:8000/

        2.5 Paste http://127.0.0.1:8000/ pada browser Anda.

        2.6 Jika Anda melihat hal seperti gambar di bawah ini, maka Anda telah berhasil membuat proyek django.

        SELAMAT!












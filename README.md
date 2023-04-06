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


#### 2.1 Membuat virtualenv
        
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





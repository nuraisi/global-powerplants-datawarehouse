# Analisis Data Pembangkit Listrik Dunia Melalui Teknik Query pada Data Warehouse

Proyek ini bertujuan untuk menganalisis data pembangkit listrik dunia menggunakan pendekatan Data Warehouse dengan teknik query untuk mendapatkan insight yang mendalam terkait distribusi dan kapasitas energi global. Dengan memanfaatkan library Atoti sebagai alat analisis OLAP interaktif, proyek ini dirancang untuk menampilkan data dalam bentuk multidimensi yang memudahkan eksplorasi data secara menyeluruh dan efisien. Proyek ini dibuat sebagai bentuk implementasi praktis pemanfaatan Data Warehouse dalam mendukung pengambilan keputusan berbasis data, khususnya di sektor energi.

Melalui pemodelan data dan visualisasi interaktif, dilakukan sejumlah insight penting seperti: total energi yang dihasilkan per tahun, rata-rata dan total kapasitas per jenis pembangkit, kapasitas berdasarkan lokasi, serta total energi yang dihasilkan menurut jenis pembangkit. Selain itu, analisis juga mencakup identifikasi negara dengan total energi terbesar, bahan bakar yang paling sering digunakan di seluruh negara, dan jenis bahan bakar yang paling banyak digunakan di masing-masing negara. Seluruh eksplorasi dan visualisasi dilakukan menggunakan Atoti session widget untuk mendukung interaksi yang fleksibel dan intuitif dalam proses analisis.

Dataset ini berisi informasi seperti:

- negara
- nama Pembangkit
- bahan Bakar
- kapasitas

Pendekatan dan langkah-langkah utama:
1. Import dan pembersihan dataset pembangkit listrik dunia.
2. Pemodelan data multidimensi menggunakan Atoti.
3. Pembuatan hierarki, agregasi, dan metrik OLAP.
4. Implementasi query untuk mengeksplor insight berikut: 
    - Total energi yang dihasilkan per tahun  
    - Rata-rata kapasitas per jenis pembangkit  
    - Total kapasitas per jenis pembangkit  
    - Kapasitas pembangkit berdasarkan lokasi  
    - Total energi per jenis pembangkit  
    - Negara dengan total energi terbesar  
    - Bahan bakar paling sering digunakan di seluruh negara  
    - Jenis bahan bakar dengan jumlah pembangkit terbanyak di setiap negara

5. Visualisasi dan interaksi data menggunakan Atoti session widget.
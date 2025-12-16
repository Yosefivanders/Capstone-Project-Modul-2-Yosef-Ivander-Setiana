# Capstone-Project-Modul-2-Yosef-Ivander-Setiana
| Analisis Efektivitas Promosi terhadap Transaksi, Repeat Purchase, dan Omset |


Dalam industri ritel supermarket, promosi sering digunakan sebagai strategi utama untuk meningkatkan jumlah transaksi, nilai belanja pelanggan, serta mendorong pembelian ulang. Namun, tidak semua program promosi memberikan dampak yang sama terhadap kinerja bisnis.

Oleh karena itu, diperlukan analisis berbasis data untuk mengevaluasi efektivitas promosi yang telah dijalankan, sehingga perusahaan dapat mengambil keputusan yang lebih tepat dan efisien.

Analisis ini bertujuan untuk :
- Menganalisis pengaruh promosi terhadap jumlah transaksi dan nilai pendapatan per transaksi.
- Mengetahui hubungan antara pembelian saat promo dengan kemungkinan pembelian ulang (repeat purchase).
- Mengidentifikasi efektivitas promosi dalam meningkatkan total omset.


Nama Dataset: Supermarket Customers
Jumlah Data: 2.240 baris
Jumlah Kolom: 29 kolom

Isi Data :
Data demografi pelanggan
Riwayat dan frekuensi pembelian
Nilai pengeluaran per kategori produk
Respons pelanggan terhadap promosi

Analisis dilakukan menggunakan Python dengan library berikut :
Pandas – manipulasi dan analisis data
NumPy – komputasi numerik
Matplotlib – visualisasi data
Seaborn – visualisasi statistik

Beberapa tahapan data preparation yang dilakukan:
Pemeriksaan struktur dan tipe data
Deteksi missing values

Penanganan missing values :
Data numerik diisi dengan median
Data kategorikal diisi dengan modus

Pembentukan variabel baru :
Promotion → diturunkan dari kolom Response
TotalAmount → total pengeluaran pelanggan
RepeatPurchase → indikator pembelian ulang

Exploratory Data Analysis (EDA)
Analisis eksplorasi meliputi :
Perbandingan jumlah transaksi antara promo dan non promo
Perbandingan rata-rata nilai transaksi (AOV)
Aalisis perilaku repeat purchase
Kontribusi promo terhadap total omzet

Beberapa temuan penting dari analisis :
Jumlah transaksi non promo lebih tinggi karena mayoritas transaksi harian terjadi di luar periode promo.
Transaksi saat promo memiliki nilai rata-rata lebih tinggi dibandingkan non promo.
Pelanggan yang membeli saat promo memiliki kecenderungan lebih tinggi untuk melakukan pembelian ulang.
Promo berkontribusi signifikan terhadap omzet meskipun volumenya lebih kecil.


Kesimpulan :
Promosi tidak selalu meningkatkan jumlah transaksi secara keseluruhan, namun terbukti:
Meningkatkan kualitas transaksi (nilai belanja per transaksi)
Mendorong loyalitas pelanggan melalui repeat purchase
Memberikan kontribusi yang relevan terhadap total omzet

Evaluasi promosi sebaiknya tidak hanya berdasarkan jumlah transaksi, tetapi juga mempertimbangkan nilai transaksi, omzet, dan perilaku pelanggan.

Catatan :
Proyek ini dibuat sebagai bagian dari Capstone Project Modul 2 (Data Analysis) dan bertujuan untuk menunjukkan kemampuan analisis data, eksplorasi data, serta penyampaian insight berbasis bisnis.

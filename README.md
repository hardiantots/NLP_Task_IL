<h1 align="center"> NLP With HuggingFace Transformers </h1>
<p align="center"> Berisi tentang pipeline dari HuggingFace Transformers untuk keperluan NLP (Natural Language Processing)</p>

<div align="center">

<img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54">
<img src="https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white">

</div>

<h2 align="center"> Analisis </h2> 

1. Zero-Shot Classification
Manfaat: Mengklasifikasikan teks ke dalam kategori tertentu tanpa pelatihan ulang atau pengaturan khusus. Model ini hanya membutuhkan daftar label (kelas) yang relevan, dan model akan mencoba mencocokkan teks dengan label yang paling sesuai.
Kegunaan: Berguna untuk klasifikasi teks di berbagai industri, terutama dalam skenario di mana data label baru atau kustom perlu dievaluasi tanpa dataset pelatihan. Contohnya, di media sosial atau analisis sentimen di mana kategori mungkin berubah dengan cepat.
2. Text Generation
Manfaat: Menghasilkan teks secara otomatis yang dilanjutkan dari teks masukan (prompt). Model ini berguna untuk membuat konten yang koheren berdasarkan prompt tertentu.
Kegunaan: Berguna untuk membuat konten kreatif seperti artikel, cerita pendek, atau teks pemasaran. Selain itu, dapat dipakai untuk pembelajaran atau penulisan otomatis dalam chatbot dan asisten virtual.
3. Fill-Mask
Manfaat: Mengisi kata yang hilang dalam kalimat dengan menggunakan token [MASK]. Model akan memprediksi kata yang paling cocok untuk melengkapi kalimat berdasarkan konteks yang ada.
Kegunaan: Sangat berguna untuk tugas-tugas seperti penyelesaian kalimat, pemeriksaan grammar, atau membuat pilihan kata yang tepat dalam penyusunan kalimat. Berguna juga untuk pengisian otomatis dalam platform belajar bahasa atau proofreading.
4. Named Entity Recognition (NER)
Manfaat: Mengidentifikasi dan menandai entitas penting dalam teks, seperti nama orang, organisasi, lokasi, tanggal, dll.
Kegunaan: Digunakan dalam ekstraksi informasi, seperti analisis data pelanggan, manajemen basis data, dan analisis tren. Sangat berguna untuk menyusun profil pengguna atau mengidentifikasi entitas penting dalam teks media sosial dan berita.
5. Question Answering
Manfaat: Menjawab pertanyaan berbasis konteks dengan membaca dan memahami teks yang relevan.
Kegunaan: Cocok untuk membangun sistem tanya jawab otomatis pada situs web, dokumentasi, atau aplikasi bantuan pelanggan. Misalnya, untuk memudahkan pencarian jawaban dari dokumen yang panjang atau memahami dokumen yang kompleks.
6. Sentiment Analysis
Manfaat: Menentukan sentimen atau emosi dalam sebuah teks, seperti positif, negatif, atau netral.
Kegunaan: Sangat berguna untuk analisis media sosial, survei pelanggan, dan analisis umpan balik. Perusahaan dapat menggunakannya untuk memahami pandangan pelanggan tentang produk atau layanan mereka.
7. Summarization
Manfaat: Membuat ringkasan otomatis dari teks yang panjang. Pipeline ini menganalisis teks dan mengidentifikasi informasi utama untuk merangkum keseluruhan konten.
Kegunaan: Ideal untuk artikel berita, laporan, atau dokumen panjang yang perlu diringkas untuk mendapatkan pemahaman yang cepat. Bermanfaat untuk riset, penulisan konten, atau aplikasi pembelajaran.
8. Translation (translation_id_to_en)
Manfaat: Menerjemahkan teks dari bahasa Indonesia ke bahasa Inggris, memudahkan pemahaman lintas bahasa.
Kegunaan: Digunakan untuk menerjemahkan dokumen, email, atau teks lainnya. Berguna di perusahaan yang beroperasi di pasar global atau dalam konteks kolaborasi internasional, memungkinkan komunikasi lebih lancar di berbagai bahasa.

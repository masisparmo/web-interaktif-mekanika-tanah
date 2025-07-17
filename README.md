Web Pembelajaran Interaktif Mekanika Tanah
===========================================================

Deskripsi Umum
--------------

Aplikasi ini adalah sebuah platform pembelajaran interaktif yang dirancang untuk membantu pengguna mempelajari dan menguji pemahaman mereka tentang konsep-konsep dalam Mekanika Tanah I & II. Aplikasi ini memanfaatkan kekuatan AI Google Gemini untuk secara dinamis menghasilkan ringkasan materi dan soal-soal kuis berdasarkan bab yang dipilih oleh pengguna.

Akses aplikasi di [https://webmektan.isparmo.com/](https://webmektan.isparmo.com/)

Fitur Utama
-----------

1.  **Pemilihan Bab Fleksibel**: Pengguna dapat memilih satu atau beberapa bab dari daftar isi buku Mekanika Tanah I dan Mekanika Tanah II untuk dipelajari.
    
2.  **Ringkasan Materi Otomatis (AI-Powered)**: Setelah memilih bab, aplikasi akan secara otomatis membuat ringkasan materi yang komprehensif. Ringkasan ini mencakup definisi kunci, konsep utama, rumus-rumus yang relevan, dan contoh perhitungan sederhana.
    
3.  **Kuis Interaktif**: Aplikasi menghasilkan 10 soal kuis pilihan ganda yang relevan dengan materi yang dipilih. Setiap jawaban akan diberikan umpan balik langsung (benar atau salah) beserta penjelasannya.
    
4.  **Penilaian dan Skor Akhir**: Di akhir kuis, pengguna akan melihat skor akhir mereka dalam persentase.
    
5.  **Fitur "Tanya Ahli"**: Sebuah tombol mengambang memungkinkan pengguna untuk membuka jendela obrolan (chat) dan mengajukan pertanyaan spesifik terkait materi yang sedang dipelajari. Jawaban akan diberikan oleh AI yang bertindak sebagai ahli geoteknik.
    
6.  **Identitas Peserta**: Sebelum memulai kuis, pengguna diminta untuk mengisi data diri (Nama, ID, No. Telp) yang akan digunakan pada laporan hasil.
    
7.  **Cetak Hasil Kuis**: Pengguna dapat mencetak laporan hasil kuis yang terperinci, lengkap dengan informasi peserta, skor, waktu pengerjaan, dan rincian setiap jawaban.
    

Cara Penggunaan
---------------

1.  **Halaman Awal (Pemilihan Bab)**:
    
    *   Anda akan disambut dengan daftar isi dari buku Mekanika Tanah I dan II.
        
2.  **Masukkan Kunci API (PENTING)**:
    
    *   Sebelum memulai, Anda **wajib** memasukkan Kunci API Google Gemini Anda pada kolom yang tersedia.
        
    *   **Cara Mendapatkan Kunci API**:
        
        1.  Kunjungi situs [Google AI Studio](https://aistudio.google.com/).
            
        2.  Masuk dengan akun Google Anda.
            
        3.  Klik tombol **"Get API key"** atau **"Create API key"**.
            
        4.  Salin kunci yang muncul dan tempelkan ke dalam aplikasi.
            
    *   Tombol "Mulai Belajar" tidak akan aktif sebelum Anda memasukkan kunci API dan memilih minimal satu bab.
        
3.  **Pilih Bab**:
    
    *   Beri tanda centang (✓) pada satu atau lebih bab yang ingin Anda pelajari.
        
4.  **Mulai Belajar**:
    
    *   Klik tombol **"Mulai Belajar"**. Aplikasi akan mulai memproses permintaan Anda.
        
5.  **Melihat Ringkasan**:
    
    *   Tunggu beberapa saat hingga AI selesai membuat ringkasan.
        
    *   Baca dan pelajari materi yang disajikan. Anda dapat menggulir ke bawah untuk melihat keseluruhan ringkasan.
        
6.  **Memulai Kuis**:
    
    *   Setelah siap, klik tombol **"Mulai Kuis"** di bagian bawah ringkasan.
        
    *   Isi formulir **Informasi Peserta**, lalu klik "Lanjutkan ke Kuis".
        
7.  **Mengerjakan Kuis**:
    
    *   Jawab setiap pertanyaan dengan mengklik salah satu pilihan.
        
    *   Jawaban Anda akan langsung dinilai (hijau untuk benar, merah untuk salah).
        
    *   Penjelasan untuk setiap soal akan muncul di bawah.
        
    *   Klik tombol **"Lanjut"** untuk ke soal berikutnya.
        
8.  **Melihat Hasil**:
    
    *   Setelah 10 soal selesai, Anda akan diarahkan ke halaman hasil yang menampilkan skor akhir Anda.
        
9.  **Opsi Lanjutan**:
    
    *   **Cetak Hasil**: Mencetak laporan kuis ke format PDF atau printer.
        
    *   **Ulangi Kuis**: Mengulang kuis dengan soal yang sama.
        
    *   **Pilih Bab Lain**: Kembali ke halaman awal untuk memilih materi baru.
        
10.  **Menggunakan "Tanya Ahli"**:
    
    *   Selama di halaman ringkasan atau hasil, klik ikon chat di pojok kanan bawah.
        
    *   Ketik pertanyaan Anda di jendela chat dan tekan kirim. AI akan memberikan jawaban berdasarkan konteks bab yang telah Anda pilih.
        

Catatan Teknis
--------------

*   Aplikasi ini sepenuhnya berjalan di sisi klien (browser Anda).
    
*   Koneksi internet aktif diperlukan untuk berkomunikasi dengan Google Gemini API.
    
*   Kunci API Anda hanya digunakan untuk sesi ini dan tidak disimpan di mana pun.
    
*   Kualitas ringkasan dan kuis bergantung pada kemampuan model AI Gemini dalam memahami teks sumber yang disediakan dalam kode.

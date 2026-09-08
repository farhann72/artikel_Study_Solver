# Artikel AI STUDY SOLVER

Project : 

https://studysolver-ai-dpxvwg0dbamz.edgeone.dev/

Assalamualaikum Wr.Wb

Pada kali ini saya akan mencoba memanfaat fitur yang ada di Tencecnt Cloud EdgeOne dari Tencent. Hal ini juga termasuk pemenuhan syarat untuk untuk tugas ke2 dari codepolitan.com untuk event dev 2026. Bismilah min hadiahnya wkwkw, untuk itu saya membuat 1 project yaitu AI STUDY SOLVER, yang memanfaat fitur dari cloud edgeone.

# Apasih AI STUDY SOlVER?

AI STUDY SOLVER adalah AI yang dapat membantu para pelajar atau siswa untuk memahami masalah belajar mereka dan mendapatkan rekomendasi belajar yang lebih terarah, yaa intinya project saya kali ini hanya sekadar mencoba membuat website AI sederhana yang dapat di akses internet, 

# Konsep AI / Cara Kerja Sistem

┌─────────────────────┐

│       User          │

│ Menulis masalah     │

│ belajar             │

└──────────┬──────────┘

           │
           
           ▼
┌─────────────────────┐

│   React Frontend    │

│   StudySolver AI    │

└──────────┬──────────┘

           │
           
           │ POST /api/analyze
           
           ▼

┌─────────────────────┐

│ EdgeOne Function    │

│       Backend       │

└──────────┬──────────┘

           │
           
           ▼

┌─────────────────────┐

│ EdgeOne Makers      │

│      Models         │

│        AI           │

└──────────┬──────────┘

           │
           
           │ AI Response
           
           ▼

┌─────────────────────┐

│ EdgeOne Function    │

└──────────┬──────────┘

           │
           
           ▼


┌─────────────────────┐

│   React Frontend    │

│ Menampilkan hasil   │

│ analisis AI         │

└─────────────────────┘

1. Problem Solver

Pengguna dapat memasukkan masalah belajar mereka melalui text.

Contoh:

Saya tidak mengerti persamaan kuadrat.

Saya sudah belajar dari YouTube tetapi masih bingung.


3. AI Analysis

Masalah belajar dikirim ke backend dan diproses menggunakan AI.

AI kemudian menganalisis masalah tersebut dan menghasilkan rekomendasi pembelajaran.


4. Personalized Learning Recommendation

Hasil analisis AI digunakan untuk memberikan rekomendasi belajar berdasarkan masalah yang diberikan pengguna.


5. Loading State

Saat AI sedang memproses permintaan, tombol berubah menjadi:

🤖 AI sedang menganalisis...

Hal ini memberikan feedback kepada pengguna bahwa sistem sedang bekerja.


6. Error Handling

Jika terjadi masalah ketika menghubungi backend atau AI, aplikasi akan menampilkan pesan error kepada pengguna.

# Pemanfaat EdgeOne

1. React : untuk membangun interface aplikasi

2. Vite : Development dan buld frontend

3. Java Script : Bahasa Pemrograman utama

4. CSS : Stylinng/Memperindah website

5. EdgeOne Makers : Platform Deploment dan backend

6. EdgeOne Functions : Menjalankan API/Backend

7. Makers Models : Menghubungkan aplikasi dengan AI

8. Github : Untuk repository dan control

# Arsitektur 

Arsitektur aplikasi dibuat dengan memisahkan frontend dan backend.

Frontend
   │
   
   │ HTTP Request
   
   ▼

/api/analyze

   │
   
   ▼

EdgeOne Function

   │
   
   │ API Request
   
   ▼

Makers Models

   │
   
   ▼

AI Model

   │
   
   │ Response
   
   ▼

EdgeOne Function

   │
   
   ▼

Frontend

Pendekatan ini membuat API Key tidak perlu disimpan di frontend.

# Keamanan API Key

API Key untuk AI tidak disimpan di dalam kode frontend.

API Key disimpan sebagai environment variable:

MAKERS_MODELS_KEY

Frontend hanya mengakses endpoint backend:

/api/analyze

Dengan demikian, API Key tidak langsung dikirim ke browser pengguna.

Jangan pernah memasukkan API Key ke dalam App.jsx, GitHub repository, atau file frontend lainnya.

# Materi

Untuk teman-teman yang penasaran dengan cara pembuatannya bisa teman-teman liat script/kode yang ada pada github saya sendiri, pada https://github.com/farhann72/StudySolver_AI

Gratis dan monggo untuk refernsi

# Testing Sendiri

Saya rasa kurang afdol kalo tidak saya testing sendiri malukan kalau sudah di buat tapi tidak bekerja kan :v wkwkwk

<img width="1366" height="768" alt="Screenshot 2026-09-08 204848" src="https://github.com/user-attachments/assets/342cf27b-8047-449d-93e5-ba67e2cac18f" />

sukses yaa, jika teman-teman ingin menggunakan AI sederhana ini, bisa memasukan perintah dengan detail dan jelas serta masukan mata[elajaran apa yang akan di hadapi agar AI dapat membaca dan mengeluarkan respon :)

# Kesimpulan 

Menurut saya pemanfaatan EdgeOne ini sangat-sangat berguna sekali, sebetulnya project bukan hanya sekedar Ai sederhana yang saya buat, tetapi dapat dibuatkan project yang lain yang lebih jos dan lebih menarik dari AI STUDY SOLVER saya, dan dapat dipake media belajar terutama jurusan yang berkaitan dengan teknologi. Dan juga faktanya pada saat ini AI memang betul-betul sedang trend dan banyak perusahaan yang mau membuat AI-nya masing-masing, dan ini juga bisa menjadi titik awal kesempatan emas untuk bekerja di perusahaan-nya. 

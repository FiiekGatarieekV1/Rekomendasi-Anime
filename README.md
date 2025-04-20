# Rekomendasi-Anime
Codingan dari skripsi saya

🎌 Sistem Rekomendasi Anime

Proyek ini merupakan sistem rekomendasi anime yang dibangun menggunakan pendekatan Content-Based Filtering dengan algoritma Cosine Similarity. Sistem ini bertujuan untuk membantu pengguna menemukan anime yang sesuai dengan preferensi mereka berdasarkan kemiripan konten seperti genre, sinopsis, dan rating.
📌 Tujuan Proyek

    Memberikan rekomendasi anime yang relevan berdasarkan preferensi pengguna.

    Meningkatkan pengalaman menonton dengan menyarankan anime yang sesuai dengan selera pengguna.

    Menerapkan algoritma Content-Based Filtering untuk sistem rekomendasi.

🧠 Pendekatan yang Digunakan
Content-Based Filtering

Pendekatan ini merekomendasikan anime kepada pengguna berdasarkan kemiripan atribut dari anime yang disukai sebelumnya. Atribut yang digunakan meliputi:

    Genre: Kategori atau jenis anime.

    Sinopsis: Ringkasan cerita dari anime.

    Rating: Penilaian atau skor yang diberikan oleh pengguna lain.

Cosine Similarity

Algoritma ini digunakan untuk mengukur tingkat kemiripan antara dua anime berdasarkan representasi vektor dari atribut-atribut tersebut. Nilai kemiripan dihitung menggunakan rumus:

cos(θ) = (A · B) / (||A|| * ||B||)

Dimana:

    A dan B adalah vektor fitur dari dua anime.

    · adalah operasi dot product.

    ||A|| dan ||B|| adalah norma dari vektor A dan B.

🗂️ Dataset

Dataset yang digunakan dalam proyek ini berasal dari MyAnimeList dan mencakup informasi berikut:

    Judul Anime: Nama dari anime.

    Genre: Daftar genre yang terkait dengan anime.

    Sinopsis: Deskripsi singkat tentang alur cerita anime.

    Rating: Skor penilaian dari pengguna.

Dataset telah diproses untuk menghilangkan data duplikat dan menangani nilai yang hilang.

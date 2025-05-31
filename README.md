# AI Text Summarizer Frontend

Frontend aplikasi web untuk AI Text Summarizer yang memungkinkan pengguna mendaftarkan akun, login, dan membuat ringkasan teks menggunakan model AI dari OpenRouter.

---

## Fitur Utama
- **Autentikasi Pengguna**: Register, Login, Logout dengan proteksi halaman menggunakan context API.
- **Ringkasan Teks Otomatis**: Input teks, pilih model AI, dan dapatkan ringkasan teks secara real-time.
- **Riwayat Ringkasan**: Menampilkan daftar riwayat ringkasan yang pernah dibuat oleh pengguna.
- **Loading Indicator** saat memproses ringkasan.
- Responsive dan mudah digunakan.

---

## Teknologi yang Digunakan
- React.js dengan Hooks (`useState`, `useEffect`)
- React Router DOM untuk routing halaman
- Context API untuk manajemen autentikasi (`AuthContext`)
- Fetch API untuk komunikasi backend dan API eksternal
- Tailwind CSS untuk styling komponen
- React Markdown untuk render hasil ringkasan dengan format Markdown

---

## Struktur Folder Utama

# Mission-2---Resolving-Git-Merge-Conflict-
Resolving Git Merge Conflict 
# 📌 Deskripsi Mission

Mission ini bertujuan untuk memahami proses analisis perubahan kode, pemilihan perubahan saat terjadi konflik (merge conflict), serta penyelesaian konflik menggunakan Git pada proyek berbasis e-commerce.

# 🧩 Analisis Masalah

Website yang dikembangkan merupakan sistem e-commerce, sehingga penamaan fitur harus selaras dengan proses bisnis. Oleh karena itu, penggunaan istilah search-product dianggap lebih relevan dan kontekstual.

# 🔀 Choose Change

Pada tahap ini dilakukan pemilihan perubahan ketika terjadi konflik merge.
Perintah berikut digunakan untuk memilih perubahan dari branch developer (branch dev):

```bash
git checkout --theirs index.html
```

# ✅ Resolve Merge

Setelah konflik dipilih dan disesuaikan, langkah selanjutnya adalah menyimpan perubahan dan memastikan repository dalam kondisi stabil:

```bash
git add index.html
git commit -m "resolve merge conflict"
git status
```

# 🎯 Tujuan Pembelajaran

Memahami konsep merge conflict pada Git

Menentukan perubahan yang paling sesuai dengan kebutuhan sistem

Menyelesaikan konflik dan menjaga konsistensi repository

# 👤 Author

Hamdan Arif Darojat
Full Stack Developer Student

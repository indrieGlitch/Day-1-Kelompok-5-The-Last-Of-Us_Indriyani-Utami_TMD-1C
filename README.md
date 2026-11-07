# Day-1-Kelompok-5-The-Last-Of-Us_Indriyani-Utami_TMD-1C
Repository ini merupakan rangkuman kegiatan Day 1 Proyek Workshop atau Sosialisasi. Berisi catatan materi, poin pembelajaran penting, dan refleksi pribadi.

## Informasi Peserta
- Nama Lengkap: Indriyani Utami
- Kelas: TMD-1C
- Kelompok: Kelompok 5-The Last Of Us
- Kegiatan: Day 1 Proyek Workshop/Sosialisasi

## Deskripsi Repository
Repository ini merupakan rangkuman kegiatan Day 1 Proyek Workshop atau Sosialisasi. Berisi catatan materi, poin pembelajaran penting, dan refleksi pribadi.

## Tujuan Repository
1. Prompt AI: Dapat menjelaskan bagaimana prompt AI yang lebih spesifik menghasilkan hasil yang lebih baik.
2. Git vs GitHub: Dapat membedakan apa itu Git dan GitHub.
3. Istilah GitHub: Dapat mengidentifikasi repository, commit, branch, dan pull request.
4. Version Control: Dapat melakukan version controlling dan mendokumentasikannya di GitHub.

## Dokumentasi Kegiatan Workshop (Day 1)
<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/70f9e504-87f5-4c89-9b1d-899adfc935f5" />


### 1. Rangkuman Materi
**a. Prompt Engineering**
- Prompt adalah instruksi atau masukan yang diberikan kepada model AI untuk mendapatkan hasil tertentu. Bentuknya bisa pertanyaan sederhana, kata kunci, instruksi rumit, atau potongan kode.
- Prompt Engineering adalah cara merancang instruksi agar AI memberikan jawaban yang tepat, relevan, dan layak digunakan.
- **Context is key:** prompt yang disertai konteks (misalnya tujuan, kebutuhan, dan batasan) menghasilkan jawaban jauh lebih baik dibanding prompt singkat tanpa konteks.
- **Struktur prompt yang baik:** Role, Task, Context, dan Format.
- Contoh taktik prompt: gunakan kata kerja yang jelas, tentukan panjang dan format output, tentukan target audiens, sertakan fakta dan data yang relevan, rujuk dokumen atau sumber tertentu, serta definisikan istilah kunci.
- Keuntungan prompt engineering: meningkatkan performa model AI, mengurangi bias dan respons yang ofensif, meningkatkan kontrol dan prediktabilitas, serta memberikan pengalaman yang lebih baik.

**b. Git dan GitHub**
- **Git** adalah version control system terdistribusi (DVCS) untuk melacak siapa, kapan, dan apa saja yang berubah dalam suatu file secara lokal. Git diciptakan oleh Linus Torvalds pada tahun 2005.
- **GitHub** adalah platform berbasis web untuk menyimpan repository Git secara online dan mendukung kolaborasi.
- **Git Workflow:**
  - *Working directory:* salinan satu versi proyek yang sedang dikerjakan.
  - *Staging area (index):* menyimpan informasi perubahan yang akan masuk ke commit berikutnya.
  - *Git directory (repository):* tempat Git menyimpan metadata dan object database proyek.

**c. Perintah Dasar Git**
- `git init` : memulai repository baru
- `git add .` : memindahkan file ke staging area
- `git commit -m 'message'` : menyimpan perubahan ke repository
- `git remote add <name> <url>` : menghubungkan repository lokal dengan remote
- `git push origin main` : mengirim perubahan ke GitHub
- `git pull origin main` : mengambil dan menggabungkan perubahan dari GitHub
- `git clone "url"` : menyalin repository dari GitHub ke komputer

**d. Setup Git, VS Code, dan SSH Key**
- Install Git, lalu cek dengan `git --version`.
- Atur identitas Git dengan `git config --global user.name` dan `git config --global user.email`.
- Install VS Code dan cek dengan `code --version`.
- Membuat SSH key dengan `ssh-keygen -t ed25519 -C "email"`, menambahkannya ke ssh-agent, lalu mendaftarkan public key di pengaturan SSH keys GitHub.
- Verifikasi koneksi dengan `ssh -T git@github.com`.

**e. Praktik: Student Task Planner**
Alur praktik: install platform AI, tulis prompt untuk membuat web/aplikasi, tambahkan ke Git dengan `git init`, commit dan push ke GitHub, lakukan perubahan, lalu commit dan push kembali.

### 2. Poin-Poin Penting & Pengetahuan Baru
- Prompt yang spesifik dan terstruktur (Role, Task, Context, Format) menghasilkan output AI yang lebih baik.
- Git dan GitHub itu berbeda: Git adalah alat version control di komputer lokal, sedangkan GitHub adalah platform online untuk menyimpan repository dan berkolaborasi.
- Alur dasar bekerja dengan Git: working directory → staging area (`git add`) → repository (`git commit`) → GitHub (`git push`).
- Setiap perubahan tercatat lewat commit, sehingga riwayat dan siapa yang mengubah bisa dilacak.

### 3. Pendapat Pribadi tentang Day 1 Proyek Workshop
- Materi workshop ini bermanfaat karena mengenalkan cara memakai AI dengan prompt yang terstruktur dan dasar version control dengan Git dan GitHub, yang berguna untuk tugas dan proyek nantinya. Praktik membuat repository sendiri juga membantu memahami alurnya secara langsung dan dapat dipelajari secara mandiri.

1. Silahkan buat branch sesuai nama panggilan masing-masing
2. Pada masing-masing branch silahkan buat file .txt dengan nama panggilan masing-masing
3. Silahkan isi file txt dengan text berikut: ``Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.``
4. Push perubahan pada branch masing-masing dan lakukan Pull Request di Github dengan target branch develop.

Cara buat branch develop dari main:
1. Pastikan sedang ada di branch main
2. git checkout -b develop

Cara buat branch feature dari develop:
1. Pastikan sedang ada di branch develop
2. git checkot -b nama_branch_feature

Cara pull request dari branch feature ke branch develop:
1. Add perubahan: git add nama_file
2. Commit: git commit -m "tulis pesan commit di sini"
3. Push ke github: git push origin nama_branch_feature
4. Masuk ke github silahkan pull request

Cara sinkronisasi repositori lokal agar sama dengan github
1. Masuk ke branch main: git checkout main
2. Pull branch main remote: git pull origin main

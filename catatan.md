GIT dan Github, bedanya apa sih?

Git = Alat

- Alat mesin waktu (`version control system / vcs`)
- File filenya kita
  
- laporan_final.docx
  - laporan_final_v2.docx
    - laporan_final_revisi.docx
      - laporan_final_FIX.docx
        - laporan_final_BENERAN_FIX.docx

Github = Provider = Tempat Penyimpanannya <-- Microsoft

- Alternatif: Gitlab, Atlassian, GCR

- git init
- git add .
- git commit -m "message yang dideskripsikan"

> Terjadi error

Karena belum memasukkan identitasnya kalian

git init
git add .
git config --global user.name "Masukkin Nama Kalian" <ENTER>
git config --global user.email "email githubnya kalian" <ENTER>
git commit -m "message yang dideskripsikan" <ENTER>

# Install Github CLI

# Config Github CLI <--- lamanya di sini

`brew install gh` (macos) / download exe -> next next next finish (windows)
`gh auth login`

# Push Repository

git remote add origin blablabla <--- kita kasih tau kalau tempatnya itu di github
git branch -M main <--- kita kasih tau oi nama branchnya (nama percabangannya) adalah "main", ubah yah ke "main"
git push -u origin main <--- kita "dorong" file kita yang ada di lokal (komputer kita) ke github (origin)

# Selanjutnya tinggal seperti ini

git add .
git commit -m "message selanjutnya apa"
git push -u origin main <--- kita "dorong" file kita yang ada di lokal (komputer kita) ke github (origin)

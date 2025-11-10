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

`brew install gh` (macos) / download exe -> next next next finish (windows)

`gh auth login`

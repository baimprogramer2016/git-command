# Syntax basic GIT
SYNTAX GIT

inisialisasi

git init

setting global

git config --global user.name 'Anhari' 

git config --global user.email 'email@gmail.com' 

Work
git status => melihat file2 yang untrack dan commit

git add -A => untuk add dan masih untrack

git commit -m "This Message" => commit yang untrack dan beri pesan

git log => melihat history yang sudah di commit

git restore nama_file => mengembalikan ke posisi sebelum perubahan

gti diff => melihat perubahan apa yang dilakukan

git checkout Isi_path_nya => untuk rollback sebelum di add

branch

git branch => mellihat daftar branch, dan tanda * adalah yang sedang aktif

git branch nama_branch => menambahkan branch baru

git checkout -b nama_branch => langusng buat branch baru dan switch

git checkout nama_branch_tujuan => pindah branch

git merge branch_yang_digabung => saat merge kita harus berada di branch tujuan

git branch -D nama_branch => menghapus branch

bisa membuat branch di bawah branch lain cara sama

Pull and push

git remote add origin https://github.com/USER/REPO>.git => membuat nama remte baru (origin itu bebas)

git push origin nama_branch => cara ngepush 

git pull origin nama_branch

.gitignore 

untuk mengabaikan file2 yng tidak mau di track

isi nama2 file ke dalam file .gitignore

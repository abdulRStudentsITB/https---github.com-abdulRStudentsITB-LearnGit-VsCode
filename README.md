# Demo Git Repository

This is the first repository

command git -add : add stage (tambah perubahan bukan file)
command git commit -m "comment" : utk commit apapun yg sudah disave
command git commit -am "comment" : shortcut biar gak add modified file dulu

command git add . : utk add semua file
command git checkout -- file : utk restore versi sebelumnya

command git checkout : waktu dicoba gak bisa utk restore
command git restore --staged file : utk unstaged
command git restore file : utk restore file versi sebelumnya

command git log --oneline --graph --decorate --color : utk menampilkan log history yg lebih menarik
command git revert id : utk mengembalikan ke id commit tersebut, tapi harus menambahkan comment dulu kalo di vscode

### kalo mau menambahkan ke github di-pull dulu baru di-push biar tidak terjadi konflik dengan developer lain

command git pull origin master
command git push origin master : catatan aja origin itu bisa diganti dengan ssh sedangkan master bisa diganti dengan branch yg lain
command git remote add origin ssh/url : buat alias agar lbh mudah ssh, nama origin itu default bisa diubah

command git branch name : utk membuat branch baru, harus dikasih nama
command git checkout name : utk pindah ke branch tersebut, bisa dicek pake command git branch -a

command git branch -D name : utk delete branch
command git merge name-yg-mau-dimerge : kalo mau merge pindah dulu ke master, kalo misal konflik krn sama2 ngubah bagian file yg sama maka kontak dulu developer yg lain. Tinggal fix terus commit

Tips : buat kalimat perintah utk comment git - sesuai dengan pedoman komunitas

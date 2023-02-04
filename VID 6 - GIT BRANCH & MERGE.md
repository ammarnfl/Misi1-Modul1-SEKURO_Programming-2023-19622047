# #6 GIT BRANCH & MERGE

## PENGERTIAN BRANCH
Branch adalah situasi ketika kita membuat cabang bebas dari commit-commit. Branch sering digunakan ketika kita bekerja secara tim atau berkelompok.

## Command yang perlu diperhatikan saat membuat branch
- Melihat branch yang ada
```
$ git branch
```

- Membuat branch baru
```
$ git branch <nama_branch>
```
- Menampilkan visualisasi branch dalam bentuk graph
```
$ git log --all --decorate --online --graph
```
- Membuat nama lain
```
$ alias <nama_alias> = "<isi_yang_diinginkan>"
```
- Pindah branch
```
$ git checkout <nama_branch>
```
### PENGERTIAN MERGE

Merge adalah menggabungkan branch yang telah dibuat ke dalam master branch (cabang utama)

### Jenis Merge
1. Fast Forward, terjadi ketika branch yang kita inginkan berada dalam jalur langsung (direct path)
2. Three-way Merge, menggabungkan 2 branch menjadi commit baru sendiri

## Command yang perlu diperhatikan saat melakukan merge

- Menggabung branch
```
$ git merge <nama_branch>
```
- Mengetahui branch yang telah di merged
```
$ git branch --merged
```
- Menghapus branch yang telah di merged
```
$ git branch -d <nama_branch>
```
- Menghapus langsung branch yang belum di merged
```
$ git branch -D <nama_file>

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
```

### DOKUMENTASI
![Screenshot_20230204_153421](https://user-images.githubusercontent.com/117100501/216757588-6fba41ad-3fa8-434b-99bd-b6f6088fd91b.png)
![Screenshot_20230204_153744](https://user-images.githubusercontent.com/117100501/216757723-f325bc77-708f-4bc9-b669-089a0d9dde50.png)
![Screenshot_20230204_153843](https://user-images.githubusercontent.com/117100501/216757766-44d73255-8d87-4c49-b286-d08fe6a997c6.png)
![Screenshot_20230204_154137](https://user-images.githubusercontent.com/117100501/216757899-39a9d22c-c028-4923-8637-8db3821fd76b.png)
![Screenshot_20230204_154438](https://user-images.githubusercontent.com/117100501/216757996-06d79274-0c2e-4caf-be53-263b0dc5ec85.png)
![Screenshot_20230204_154353](https://user-images.githubusercontent.com/117100501/216758003-73bee7c6-4feb-409a-9a8d-a37f1c5489dc.png)
![Screenshot_20230204_154620](https://user-images.githubusercontent.com/117100501/216758070-a9ca5b04-ea53-4c5d-bf28-13136e0a23f2.png)

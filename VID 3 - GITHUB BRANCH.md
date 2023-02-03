# #3 GITHUB : BRANCH

### Branch adalah cabang yang dapat dibuat pada suatu repo yang di luar dari master branch (jalur utama) dengan tujuan melakukan perubahan terhadap file tersebut.


### Tujuan branching :
1.	Membuat Git Branch
2.	Membuat snapshot tanpa menganggu jalur utama (master branch)
3.	Fitur experimental
4.	2 orang mengerjakan repo yang sama


Cabang yang telah dibuat dapat bergabung lagi ke master branch melalui proses merging. Tidak semua commit file bisa di merge, system github akan mendeteksi apakah file tersebut able to merge or not. Jika tidak, system akan menunjukkan apa conflict yang menyebabkan file tidak bisa di merge.
Meskipun kita sendiri yang punya repository tersebut, untuk melakukan merging perlu pull request ke pemilik repo terlebih dahulu.
Dan juga, pemilik repo dapat melihat terlebih dahulu apa yang ingin di merge sehingga tidak bisa sembarang orang merubah repository kita.

### Istilah
- Checkout : berpindah ke branch /  commit yang lain
- Pull request : meminta pemilik repo untuk ‘mengambil’ perubahan yang telah dilakukan
- Merge : menggabungkan 2 branch
- Merge conflict : baris yang sama diubah oleh 2 branch yang berbeda

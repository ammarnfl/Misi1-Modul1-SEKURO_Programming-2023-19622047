# #5 BEKERJA DENGAN GIT

Untuk mengoperasikan git gunakan link https://git-scm.com/ untuk melakukan download.

Untuk mengecek apakah git udah ter-download, ketik ‘git’ di command prompt. Lalu, jika sudah ter-download akan muncul tampilan seperti help mengenai git.

![Screenshot_20230204_063521](https://user-images.githubusercontent.com/117100501/216730380-14a414c6-79ff-4c84-905e-b498a1d70eb0.png)

### Git command (local)
- git init : untuk menginisialisasi repo git di computer
- git add <file(s)> : untuk menambahkan file di staging area
- git status : untuk mengecek status terbaru pada repo kita
- git commit : untuk melakukan commit (perubahan)
- git config : untuk memasukkan konfigurasi ke dalam git
- git branch : untuk membuat branch
- git help : untuk mengetahui cara perintah git dengan cepat

Perbedaan dengan github adalah kita melakukan git command ini langsung di terminal computer kita. 

### Setelah mendownload git, computer akan mengenali 3 area pada repo git
-	Working tree : folder tempat bekerja
-	Staging area : memberitahu git bahwa kita telah melakukan perubahan
-	History : penentuan apakah perubahan akan menjadi commit atau tidak

Staging area dan history akan tersimpan dalam sebuah folder ‘.git’ 

#### Mengetahui directory aktif
![Screenshot_20230204_060836](https://user-images.githubusercontent.com/117100501/216731223-9ad7cd36-5a54-4c23-9294-f643f6f0b3a0.png)

#### Membuat folder ke dalam repo git
Untuk memembuat folder ke dalam repo git, kita harus masuk dulu ke dalam foldernya dengan melakukan change directory

![Screenshot_20230204_060950](https://user-images.githubusercontent.com/117100501/216731498-8822f7f8-89d7-4eab-8f9b-817b791bef7f.png)

#### Meminta git mengawasi folder
![Screenshot_20230204_061024](https://user-images.githubusercontent.com/117100501/216731526-95df6149-1c0c-48f9-858a-9dc84ddfd8cd.png)

Sehingga di file explorer akan muncul seperti ini

![Screenshot_20230204_061153](https://user-images.githubusercontent.com/117100501/216731631-ece48223-a5be-40c2-baa0-8642ed8d441b.png)

Lalu, coba kita membuat file

![Screenshot_20230204_061550](https://user-images.githubusercontent.com/117100501/216731686-953f4277-431a-424c-8986-9d9ec49fb0e0.png)

#### Untuk mengecek status git (git status)
![Screenshot_20230204_061609](https://user-images.githubusercontent.com/117100501/216731783-19248c60-c977-4aa0-8c6d-17eeb2f8607c.png)

#### Untuk menambahkan file dalam pengawasan git (git add)
![Screenshot_20230204_061716](https://user-images.githubusercontent.com/117100501/216731849-e140b351-c3b7-45fc-9ae6-c1eb5f6a326d.png)

#### Tiap perubahan tidak hanya di save tetapi harus di commit (git commit)
![Screenshot_20230204_062159](https://user-images.githubusercontent.com/117100501/216731992-adc372d6-a9df-4557-8f16-fcaab78ce5d1.png)

Lalu, coba kita memodifikasi dan menambahkan file

![Screenshot_20230204_062257](https://user-images.githubusercontent.com/117100501/216732050-7395d9af-4690-4fca-a3a0-60866ccbf967.png)

![Screenshot_20230204_062422](https://user-images.githubusercontent.com/117100501/216732059-05af1c6a-1bb5-404d-a506-bb05d5ffd999.png)

Status git akan seperti ini

![Screenshot_20230204_062511](https://user-images.githubusercontent.com/117100501/216732098-755f0c5a-cf56-4842-9591-268134e61993.png)

Sehingga kita perlu add file tersebut ke dalam git dengan cara "git add." (menyimpan semua perubahan)

Lalu, kita lakukan commit lagi
![Screenshot_20230204_062710](https://user-images.githubusercontent.com/117100501/216732329-aa378c9d-2107-4e72-9e40-360332fada15.png)

#### Mengetahui perubahan
![Screenshot_20230204_062752](https://user-images.githubusercontent.com/117100501/216732360-5941c698-f071-400e-85ab-ec7d8d9af77f.png)

#### Mengembalikan file sebelum di commit
Dengan cara memasukan 5 kode bash awal
![Screenshot_20230204_063135](https://user-images.githubusercontent.com/117100501/216732465-928e0b66-8159-4934-aa8f-0c2769d01db8.png)

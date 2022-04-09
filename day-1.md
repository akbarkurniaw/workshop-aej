# GIT Version Control System

## Practice 1: Operasi Dasar GIT
> Dengan Practice pertama ini kita akan belajar operasi dari git, kita akan mempelajari operasi dasar seperti membuat repository, menambahkan remote/cloud repository, melihat status perubahan dan lain sebagainya. 
> Operasi dasar akan sangat dibutuhkan di practice practice berikutnya, jadi kita akan focus disini dalam beberapa waktu kedepan.
***
1. Digunakan untuk membuat directory menjadi repository
```
git init .
```
2. Membuat repository kita memiliki tempat di cloud repository
```
git remote add origin
```
3. Melihat status perubahan yang ada di repository
```
git status
```
4. Menambahkan perubahan yang dari working area to staging area
```
git add [namafile] / --all / .
```
5. Menyimpan perubahan yang ada di staging ke repository
```
git commit –m “message”
```
6. Upload perubahan repository local ke cloud
```
git push origin master
```
7. Download perubahan repository dari cloud ke local
```
git pull origin master
```
***
## Practice 2: Branch operasional
> branch merupakan virtual environment yang dapat membedakan antara environment satu dengan environment lainnya, tetapi tetap dalam satu tempat, biasanya branch digunakan untuk membedakan versi seperti versi _beta_, _alpha_, _latest_ dan lain sebagainya,
> branch akan membantu kita dalam pengembangan aplikasi, karena ketika menggunakan branch maka tidak akan mengganggu branch yang lain, sehingga branch cocok untuk kolaborasi.
***
1. Melihat branch yang ada di repository kita
```
git branch -a
```
2. Membuat branch dari branch saat ini
```
git branch [namabranch]
```
3. Pindah branch
```
git checkout [namabranchtujuan]
```
4. Menggabungkan branch
```
git merge [namabranch]
```
5. Mengatasi conflict
```
git status
```





# Program Data Mahasiswa
## INPUT
![3](https://user-images.githubusercontent.com/56240386/72039234-d1a71680-32d6-11ea-9f40-83d2ee193d70.png)
## ALGORITMA
1. Pertama kita membuat variable List dan juga Variable True:untuk perulanganya
```
nilai = []
ulang = True
```
2.Buatlah Kondisi Perulangan yang sekarang.
```
while ulangi:
    nama = input("Masukan Nama: ")
    nim = input("Masukan NIM: ")
    tugas = int(input("Masukan Nilai Tugas: "))
    uts = int(input("Masukan Nilai UTS: "))
    uas = int(input("Masukan Nilai UAS: "))
    akhir = (tugas * 30/100) + (uts * 35/100) + (uas * 35/100)
```
3.Lalu kita akan membuat statement dimana program akan berhenti jika kita menlis kata 'T'.
```
if (input("Tambah data (y/t)?") == 't'):
        ulang = False
```
4.Terakhir adalah menyamakan sebuah tabel pada program yang akan di cetak,dengan menggunakan d,s,f dan juga mengurutkan variable dengan menggunakan format dan disambung dengan item agar mereka berurutan sehingga menjadi tabel yg sempurna.
```
print("\n                      Daftar Nilai Mahasiswa")
print("==================================================================")
print("|No. |     Nama     |    NIM    | Tugas |  UTS  |  UAS  |  Akhir |")
print("==================================================================")
i = 0
for item in nilai:
    i += 1
    print("| {no:2d} | {nama:12s} | {nim:9s} | {tugas:5d} | {uts:5d} | {uas:5d} | {akhir:6.2f} |"
          .format(no=i, nama=item[0], nim=item[1], tugas=item[2], uts=item[3], uas=item[4], akhir=item[5]))
print("==================================================================")
```
## OUTPUT
![4](https://user-images.githubusercontent.com/56240386/72039262-e84d6d80-32d6-11ea-9f9a-74e47bf8fe2c.png)

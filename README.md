## Latihan 1 ##

Menjalan <b>Python Console</b>
* Menampilkan tulisan "Hello" dilayar
* Menampilkan tulisan "Saya sedang belajar python" dilayar

```python
print("Hello")
```
```python
print("Saya sedang belajar python")
```
![1](https://user-images.githubusercontent.com/123666514/215308415-9fc049af-e79c-4cf9-936f-6eb92bc5b081.PNG)

## Latihan 2 ##

Menjumlahkan dua buah bilangan menggunakan variable a dan b.
* Mendefinisikan variable a dengan nilai 8
* Mendefinisikan Variable b denhan nilai 6
* Mencetak nilai variable a dan b
* Mencetak hasil penjumlahan a+b

```python
a = 8
b = 6
print("Variable a=",a)
print("Variable b=",b)
print("Hasil dari penjumlahan a+b=",a+b)
```

![2](https://user-images.githubusercontent.com/123666514/215308691-dab8556d-d758-471b-98b7-f1119f9c09f7.PNG)

## Latihan 3 ##

Menjalankan <b>IDLE</b>
* Membuat file baru dengan nama latihan3.py
* Menggunakan fungsi input untuk mengambil nilai variable dari keyboard

```python
# input nilai variable
a = input("Masukan nilai a : ")
b = input("Masukan nilai b : ")

# cetak nilai variable
print("Variable a = ",a)
print("Variable b = ",b)

# cetak hasil operasi kedua variable dengan String Format
print("Hasil penggabungan {l}&{0}=d%".format(a,b) %(a+b))

# konversi nilai variable
a = int(a)
b = int(b)
print("Hasil penjumlahan {l}+{0}=d%".format(a,b) %(a+b))
print("Hasil pembagian {l}/{0}=d%".format(a,b) %(a/b))
```

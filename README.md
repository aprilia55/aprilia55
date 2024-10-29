# praktikum 3 - tipe data,variable, dan operator

Nama : Alfarizki Aprilia Putri 

Kelas : TI.24.A5

NIM : 312410455

Mata Kuliah : Bahasa pemrograman 


## Mencari Bilangan Terbesar dari bilangan yang di inputkan 
program ini menetukan bilangan terbesar dari bilangan yang di inputkan hingga input '0' . program ini menggunakan loop 'while' dan kondisi 'if' untuk memperbarui nilai terbesar yang di temukan.

# Flowchart Program 
![foto](https://github.com/aprilia55/photo/blob/6df3c206047bcad362d898f5aa53dfc97d3816aa/README.md)

## Kode program 
''' python 

#inisialisasi variabel max
max_value = float ('-inf')
while True:
    # Meminta input bilangan dari pengguna
    number = int(input("Masukkan bilangan (0 untuk berhenti): "))
    
    # Jika bilangan adalah 0, keluar dari loop
    if number == 0:
        break
    
    # Cek apakah bilangan lebih besar dari max_value
    if number > max_value:
        max_value = number

# Memeriksa apakah ada bilangan yang dimasukkan
if max_value == float('-inf'):
    print("Tidak ada bilangan yang dimasukkan.")
else:
    print(f"Bilangan terbesar adalah: {max_value}")

else:
    print(f"Bilangan terbesar adalah: {max_value}")
```
## Penjelasan Kode Program

```python
#Inisiasi variabel max
max_value = float(' -inf')
```
`max_value`diinisiasi dengan nilai `-inf` (negatif tak hingga).Ini berguna karena  kita ingin memastikan bilangan pertama yang dimasukan oleh pengguna akan selalu lebih besar dari nilai  ini.

```
```python
while True:
```
Loop ini akan terus berjalan tanpa batas sampai ada kondisi yang menghentikan nya (dalam hal bilangan ini `0` dimasukan) bertujuan untuk mengizinkan penggunaa untuk memasukan bilangan hingga mereka memutuskan berhenti

```python
if number == 0:
   break
```
```python
if number > max_value:
   max_value = number
```
program membandingkan bilangan yang baru saja memasukan (`number`) dengan nilai terbesar saat ini (`max_value`).Jika bilangan yang baru besar, maka (`max_value`) diperbarui dengan nilai tersebut.Bertujuan untuk melacak bilangan terbesar yang pernah dimasukkan selama program berjalan.

```python
if max_value == float(`-inf`):
   print("Tidak ada bilangan yang dimasukan")
else:
   print(f"bilangan terbesar adalah:{max_value}")
```
Setelah penggunaan menghetikan input,program memeriksa apalah `max_value` masih bernilai `-inf`,yang berarti tidak ada bilangan yang dimaksudkan (selain `0`).Jika demikian,Pesan "Tidak ada bilangan yang dimaksukkan." akan ditampilkan.Jika ada bilangan yang dimaksudkan,program akan mencetak bilangan terbesar yang ditemukan. 





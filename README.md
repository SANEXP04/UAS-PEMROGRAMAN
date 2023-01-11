# UAS-PEMROGRAMAN
# UAS
## Nama  : Ihsan Hadimulya
## NIM   : 312210047
## Kelas : TI22A1
### Membuat Package dan module

![Screenshot (718)](https://user-images.githubusercontent.com/115686359/210766307-7c0963ba-ea6b-4a3c-8e6c-36b0a571366c.png)

### Sudah dibuat Package dan Module seperti diatas

![image](https://user-images.githubusercontent.com/115678077/211916666-73795eaa-6b62-461d-9234-4d3e974475c4.png)


### ```daftar_nilai.py``` Berisi modul untuk :

- tambah_data

- ubah_data

- hapus_data

- cari_data

### ```view_nilai.py``` Berisi modul untuk :

- cetak_daftar_nilai

- cetak_hasil_pencarian

### ```input_nilai.py``` Berisi modul untuk :

- input_data (Meminta pengguna untuk memasukkan data)

### ```main.py``` Berisi Program Utama

- Memanggil semua menu yang yang ada

#### 1. Kemudian saya telah menyatukan syntax yang nanti akan menghasilkan semua modul dari ```daftar_nilai``` yang diantaranya adalah (tambah data, ubah data, lihat data, hapus data, dan cari data)

```

from view.input_nilai import *
data={}
class daftarnilai():
    def tambah_data(self):
        tambah_nama = nama()
        tambah_nim = nim()
        tambah_tugas = tugas()
        tambah_uts = uts()
        tambah_uas = uas()
        tambah_akhir = akhir()
        data[tambah_nama]= tambah_nim,tambah_tugas,tambah_uts,tambah_uas,tambah_akhir

    def ubah_data(self):
        ubah_nama = nama()
        if ubah_nama in data.keys():
           
            tambah_nim = nim()
            tambah_tugas = tugas()
            tambah_uts = uts()
            tambah_uas = uas()
            tambah_akhir = akhir()
            data[ubah_nama]= tambah_nim,tambah_tugas,tambah_uts,tambah_uas,tambah_akhir
        else:
            print('data tidak ditemukan !!!')

    def hapus_data(self):
        hapus_nama = nama()
        if hapus_nama in data.keys():
            del data[hapus_nama]
            print('data berhasil di hapus')
        else:
            print('data tidak ditemukan !!!')

    def keluar(self):
    
```     

### Output Tambah_data :

![image](https://user-images.githubusercontent.com/115678077/211919617-ff8502d2-b081-41dd-891e-f4aeb7de2a39.png)


### Output Daftar_nilai :
![image](https://user-images.githubusercontent.com/115678077/211918470-2ff90e37-79c0-4bcd-a1d1-52e48b8b024a.png)

### Output Ubah_data :

![image](https://user-images.githubusercontent.com/115678077/211918814-18b86ff0-4690-4c21-9ace-ffbab3c38232.png)


### Output Cari_data :
![image](https://user-images.githubusercontent.com/115678077/211919067-8000cde4-0348-4806-afb2-97c38bc431b0.png)


### Output Hapus_data :
![image](https://user-images.githubusercontent.com/115678077/211919253-1ee7bac3-9ef3-4216-a4c5-74b347f66f07.png)



## SELESAI


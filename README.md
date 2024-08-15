**Mengubah data hasil export DecibleX ke dalam bentuk tabel**

1. Kumpulkan semua data yang ingin diubah ke dalam suatu folder
2. Ubah ```data``` dalam ```os.listdir('data')``` sesuai dengan nama folder yang digunakan, menyesuaikan alamat folder
3. Ubah ```data/hari1_pagi_bengkel_titik3.txt``` sesuai dengan alamat file dan bentuk file (txt atau csv)
4. Apabila header nilai desibel adalah ```Recorded Value (dBA)```, ubah ```Leq (dB-A)``` dan sesuaikan
5. Ubah ```df.to_csv('output/test.csv')``` menjadi alamat folder dan file yang diharapkan menjadi output
6. Run

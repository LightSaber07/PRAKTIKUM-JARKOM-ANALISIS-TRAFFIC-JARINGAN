# PRAKTIKUM-JARKOM-ANALISIS-TRAFFIC-JARINGAN
| Nama        | Tamam Rifky Aqila |
|--------------|------------|
| NIM        | 09030282327016 |
| Program Studi | Teknik Komputer |

## Judul Praktikum
## Analisis Traffic Jaringan
----------

## Langkah Kerja


<div>
  <br>
  <div class="item">
    <p>1. Buka wireshark dan pastikan terhubung ke internet</p>
    <p>2.Pilih wifi</p>
    <img src="https://github.com/user-attachments/assets/7a3b6022-18f9-4748-bb72-2650fe1c1ece" width="300">
    <p>3.Jalankan untuk mencari capture paket</p>
    <img src="https://github.com/user-attachments/assets/ae8c792a-9f2a-471d-afe3-50af5dcb25c6" width=300">
    <p>4.Selanjutnya melakukan kegiatan seperti nonton youtube selama kurang lebih 5 menit</p>
    <p>5.Setelah selesai klik ikon merah seperti pada gambar</p>
    <img src="https://github.com/user-attachments/assets/1167232a-c4ec-4c6d-bfbd-f1e33e54e7b1" width=300">
    <p>6.Pilih capture file pada statistics, untuk melihat properties pada packet capture yang dijalankan</p>
    <img src="https://github.com/user-attachments/assets/7e1badff-102c-43d7-81f7-5bf7f94316d9" width=300">
    <p>7.Melihat paket lost dengan mengetik tcp.analysis.lost_segment</p>
    <img src="https://github.com/user-attachments/assets/61ea5470-5601-4045-9eab-ec08305b9081" width=300">
    <p>8.Perhatikan bagian statics pada Properties untuk melakukan perhitungan Throughput, Packet Loss, Delay, dan Jitter.</p>
    <img src="https://github.com/user-attachments/assets/21038f6b-019f-4c48-81c1-cfeeaa209413" width=300">
    <p>9.Perhitungan Throughput, Packet Loss, Delay, dan Jitter.</p>
    <img src="https://github.com/user-attachments/assets/6709c93f-7978-4cb9-a4e9-bfb7ad2ad552" width=300">
    <P>7417641 = bytes
16.890 = time span
7417641 : 16.890 = hasil bytes (439.1735346358792) x 8 = 3,513.388277087034
(throughput)

packet loss
((paket dikrim - paket diterima) : paket dikirim) x 100
=(6783 - 6781) : 6783) x 100
=(2 : 6783) x 100
=0.0294854784018871

delay
total delay = 15224531 s
rata rata delay = 2284.250713 s x 1000 = 2,284250 ms

jitter
total jiter = -1520157 s
rata rata jiter = -228.0805701 s x 1000 = 228,080.5701 ms


</P>
     <p>10.Setelah mendapatkan hasil perhitungan, selanjutnya ialah mengisi tabel indeks yang didapatkandari pengukuran QoS.</p>
     <img src="https://github.com/user-attachments/assets/5052a2f5-6f16-4219-95bf-fdb38e0b48bf" width=300">
     
</div>

-------

## Kesimpulan
<p>Pada perhitungan QoS ini, hasil Throughput, Packet Loss, dan Delay tergolong dalam kategori Sangat Bagus, yang mengindikasikan bahwa jaringan memiliki kecepatan tinggi dan stabil dalam pengiriman data. Namun, Jitter berada dalam kategori Sedang, menunjukkan variasi waktu antar paket yang sangat besar, yang berpotensi mengganggu komunikasi real-time. Dengan demikian, jaringan ini sangat optimal dalam hal kecepatan dan kestabilan latensi, tetapi jitter yang tinggi dapat menjadi kendala bagi aplikasi real time.</p>

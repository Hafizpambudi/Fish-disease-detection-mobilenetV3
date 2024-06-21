
# Fresh Water Fish Disease Detection

## Teams 
- Hafiz Pambudi - ML engineer 
- Naufal Kanz - Design Researcher 
- Muhammad Daffa Ramadhan - Data Engineer
- Yerico Marchel Bernadus - ML Ops 

## Idea Background 

### 1. Theme 
tema : Aquakultur

### 2. Problem 

Masalah : Para pembudidaya dan newbie dalam budidaya seringkali merasa bingung ketika ikan yang dibudidaya mengalami sakit. perlu adanya suatu teknologi yang bisa mendeteksi penyakit ikan dan memberikan solusi praktis yang langsung. 
### 3. Solution
Solusi : Membuat deteksi penyakit ikan berbasis artificial Intelligence dengan menggunakan image recognition. 

## Dataset 
Untuk melakukan pelatihan deteksi penyakit ikan, digunakan dataset dari 
kaggle. Kemudian ditambah kembali dari berbagai situs untuk difokuskan 
kepada 5 ikan yaitu ikan lele, ikan bawal, ikan gurame, ikan mujair dan ikan 
nila. Dataset ini memiliki 7 label yang salah satu labelnya adalah ikan sehat. 
Dataset yang dipakai memiliki batasan hanya dapat memprediksi 6 penyakit 
yang sering terjadi pada 5 ikan yang telah disebutkan, yaitu : 
- Penyakit Aeromoniasis 
- Penyakit Bacterial gill 
- Penyakit Bacterial Red 
- Penyakit Jamur
- Penyakit Parasit 
- Penyakit virus ekor putih
## Algorithm
Algoritma yang digunakan berbasis CNN. dipadukan dengan menggunakan 
pre-trained model dari mobilenetV3 yang dilakukan fine tuning. Algoritma ini 
piilih karena project ini akan menganalisan gambar sehingga digunakan CNN 
dan mobilenetV3 dipilih karena pre - trained model ini ringan dan memiliki 
akurasi yang lumayan tinggi.




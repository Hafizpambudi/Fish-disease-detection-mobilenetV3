
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


## Prototype
![image](https://github.com/Hafizpambudi/Fish-disease-detection-mobilenetV3/assets/154437965/f3ff44a6-23b9-41d9-be2e-e02a2ae76974)


## Integration 
\Model ini akan diintegrasikan ke dalam platform mobile. Sehingga untuk mempermudah integrasi, Model yang telah dikembangan disimpan dan dibuatkan menjadi API. API akan dibuangkus menjadi container menggunakan docker dan deploy secara public menggunakan service dari ibm code engine.

## Deployment 
Setelah proses developing dan training model selesai dilakukan, model deteksi penyakit ikan akan dibuatkan menjadi API. Tujuan dibuatkannya api agar pihak developer mobile dimana fitur ini akan diimplementasikan, akan merasa dimudahkan. Pembuatan API menggunakan framework FAST Api. Ketika API selesai di develop, dilakukan kontainerisasi menggunakan docker dan dilakukan deployment ke dalam servide IBM code engine. Deployment ini akan menghasilkan public endpoint url yang siap di konsumsi oleh pihak developer mobile. 

## Result 
![WhatsApp Image 2024-06-21 at 14 51 46](https://github.com/Hafizpambudi/Fish-disease-detection-mobilenetV3/assets/154437965/508d0e20-0c14-4356-819d-cbf1065c0127)
Model ini dapat mengenali penyakit pada ikan dan memberikan solusi pengobatan praktisnya 

## Conclusion 
model deteksi penyakit ikan berjalan sesuai target awal. 



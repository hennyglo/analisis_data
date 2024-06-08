# Bike Share Dashboard :sparkles:

## Deskripsi Proyek
Proyek ini adalah dashboard interaktif yang menampilkan analisis dan visualisasi data sewa sepeda berdasarkan dataset. Dashboard ini dibuat menggunakan Streamlit dan visualisasi data dilakukan dengan bantuan pustaka pandas, matplotlib, dan seaborn.

## Fitur Utama
- **Rentang Waktu Seleksi**: Pengguna dapat memilih rentang waktu untuk analisis data.
- **Visualisasi Musim dan Cuaca**: Menampilkan rata-rata jumlah sewa sepeda berdasarkan musim dan kondisi cuaca.
- **Visualisasi Suhu dan Suhu Terasa**: Menampilkan rata-rata jumlah sewa sepeda berdasarkan suhu dan suhu terasa.
- **Korelasi Suhu, Kelembaban, dan Kecepatan Angin**: Menampilkan hubungan antara jumlah sewa sepeda dengan suhu, kelembaban, dan kecepatan angin.
- **Jumlah Sewa Sepeda Selama Dua Tahun Terakhir**: Menampilkan rata-rata jumlah sewa sepeda per hari dan per bulan serta tren jumlah sewa sepeda tiap bulan dalam dua tahun terakhir.

## Instalasi
1. Clone repositori ini:
   ```bash
   git clone https://github.com/hennyglo/analisis_data
   cd analisis_data

## Setup Environment - Anaconda
1. Buat environment baru dengan Anaconda:
conda create --name bike-share-dashboard python=3.9
conda activate bike-share-dashboard

2. Instal dependensi:
pip install -r requirements.txt

## Setup Environment - Shell/Terminal
1. Buat direktori proyek dan masuk ke dalamnya:
mkdir proyek_analisis_data
cd proyek_analisis_data

2. Instal pipenv jika belum terinstal:
pip install pipenv

3. Instal dependensi dan aktifkan environment:
pipenv install
pipenv shell
pip install -r requirements.txt

## Menjalankan Aplikasi
# Untuk menjalankan aplikasi Streamlit:
streamlit run dashboard_bike_sharing.py

## Dependensi
# Pastikan Anda memiliki pustaka berikut terinstal dalam environment Anda:
numpy==1.24.2
pandas==2.1.1
matplotlib==3.7.2
seaborn==0.12.2
plotly==5.7.0
scipy==1.10.1
streamlit==1.23.0
babel==2.11.0
warnings==3.11.5

## Struktur Proyek
analisis_data/
├── README.md
├── requirements.txt
├── dashboard_bike_sharing.py
├── bike_sharing.ipynb
├── recruitment.txt
├── url.txt
├── dataset/
│   ├── hour.csv
│   ├── day.csv
│   └── readme
└── env/

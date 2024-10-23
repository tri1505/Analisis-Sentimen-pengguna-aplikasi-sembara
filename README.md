# ANALISIS SENTIMEN PENGGUNA APLIKASI SEMBARA 
## Overview
Penelitian ini bertujuan untuk menganalisis sentimen pengguna terhadap aplikasi Sembara, sebuah aplikasi yang dirancang untuk memudahkan pembayaran pajak kendaraan bermotor di Jawa Barat. Dengan menggunakan metode analisis sentimen, ulasan pengguna di Google Play Store dikategorikan menjadi tiga kelompok: positif, negatif, dan netral.  Metode yang digunakan dalam penelitian ini adalah  Support Vector Machine (SVM) dengan tingkat akurasi diatas 85% Hasil analisis ini diharapkan dapat memberikan wawasan yang berharga bagi pengembang aplikasi untuk meningkatkan kualitas layanan dan kepuasan pengguna.
## Project Structure
- `sembara.csv`:berisi file data mentah dalam format CSV.
- `TRI_RAMDHANY_APLIKASI_SEMBARA.ipynb`: Direktori yang berisi notebook Jupyter untuk analisis data.
- `scraping_aplikasi_sembara.ipynb`: Skrip melakukan scraping data ulasan aplikasi SEMBARA di google playstore.
- `requirements.txt`: Daftar dependensi Python yang diperlukan untuk menjalankan proyek.
- `README.md`: Dokumentasi proyek ini
## Installation
1. Clone repositori ini ke mesin lokal Anda:
   ```bash
   git clone https://github.com/tri1505/Analisis-Sentimen-pengguna-aplikasi-sembara.git
   
'Instal dependensi yang diperlukan:'
pip install -r requirements.txt

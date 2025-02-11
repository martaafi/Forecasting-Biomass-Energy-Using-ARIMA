# Forecasting-Biomass-Energy Using ARIMA
## Pendahuluan
Energi biomassa telah menjadi salah satu sumber energi terbarukan yang semakin penting dalam upaya global untuk mengurangi emisi karbon dan ketergantungan pada bahan bakar
fosil. Energi biomassa berasal dari bahan organik seperti kayu, limbah pertanian, dan sisa makanan yang dapat diubah menjadi energi melalui berbagai proses seperti pembakaran langsung, fermentasi, dan gasifikasi. Dengan semakin meningkatnya kebutuhan akan sumber energi yang berkelanjutan, energi biomassa menawarkan solusi yang signifikan untuk masa depan energi dunia. Sehingga diharapkan jumlah produksi energi biomassa yang tersedia akan semakin bertambah setiap tahunnya untuk menjamin ketersediaan energi terbarukan yang ramah lingkungan. Dalam kurun waktu dari Januari 2011 hingga Februari 2023, terdapat data bulanan mengenai produksi energi biomassa yang dapat dianalisis untuk memahami pola dan tren penggunaannya. Data ini mencakup berbagai fluktuasi musiman serta perubahan tren yang mungkin dipengaruhi oleh faktor eksternal seperti kebijakan energi, perkembangan teknologi, dan kondisi ekonomi.

## Tujuan
- Memahami pola dan tren produksi energi biamassa.
- Memprediksi produksi energi biomassa pada bulan Maret-Mei 2023.

## Langkah Analisis
- Preprocessing Data
- Exploratory Data Analysis
- Penentuan orde ARIMA (p,d,q)
- Underfitting
- Diagnostic Checking: uji autokorelasi, uji homoskedastisitas, uji normalitas
- Pemilihan model terbaik dengan memilih model yang memiliki `Loglikelihood` terbesar, `AIC` terkecil, dan `BIC` terkecil.
- Prediksi produksi energi biomassa dalam 3 periode ke depan (Maret-Mei 2023).

## Tools
- R

## Pola dan Tren Produksi Energi Biomassa
![image](https://github.com/user-attachments/assets/715b4fe2-5bc7-40fa-b21b-c385a500671b)

Produksi energi biomassa dari 2011-2023 cenderung fluktuatif dari waktu ke waktu. Jika dilakukan segmentasi dari tahun 2011 hingga 2017, produksi energi biomassa cenderung mengalami tren kenaikan, sedangkan pada tahun 2017 hingga 2023 cenderung mengalami tren penurunan.

## Model terbaik
![image](https://github.com/user-attachments/assets/327885b2-2112-41ea-9642-bd9d654fc740)

Model ARIMA(4,1,1) tanpa konstanta paling banyak memenuhi kriteria model terbaik (2 dari 3 kriteria), yaitu memiliki Log Likelihood terbesar dan AIC terkecil. Oleh karena itu, model ARIMA(4,1,1) tanpa konstanta dipilih sebagai model terbaik.

## Prediksi 3 Periode ke depan
![image](https://github.com/user-attachments/assets/4163a6d2-753e-46c4-b97d-bc8a4897b212)

Hasil prediksi menunjukkan bahwa pada bulan Maret-Mei 2023, produksi energi biomassa juga cenderung fluktuatif. Diperkirakan produksi energi biomassa pada bulan Maret sebesar 186,1932, April sebesar 183,2442, dan Mei sebesar 187,3345.

## Kesimpulan
- Produksi energi biomassa dari 2011 hingga 2023 menunjukkan pola fluktuatif dan belum mengalami tren kenaikan yang signifikan. Salah satu faktor yang mungkin berkontribusi adalah rendahnya kesadaran terhadap pemanfaatan energi biomassa.
- Hasil prediksi produksi energi biomassa untuk periode Maret–Mei juga menunjukkan pola yang serupa, yaitu masih fluktuatif. Diperkirakan produksi pada bulan Maret mencapai 186,1932, April 183,2442, dan Mei 187,3345.

## Rekomendasi
Untuk mendorong transisi menuju energi terbarukan guna mengurangi emisi karbon dan ketergantungan terhadap bahan bakar fosil, pemerintah perlu meningkatkan upaya sosialisasi dan edukasi mengenai manfaat serta potensi energi biomassa. Langkah ini dapat mencakup kampanye kesadaran publik, insentif bagi industri yang beralih ke energi biomassa, serta peningkatan riset dan inovasi di sektor ini. Selain itu, menjaga stabilitas dan meningkatkan produksi energi biomassa juga menjadi aspek penting agar penggunaannya lebih berkelanjutan dan dapat diandalkan sebagai sumber energi alternatif di masa depan.

# predict-water-content
Decision Tree, Support Vector Regression, and Random Forest Regression

Alat yang digunakan:
- Microsoft Excel
- Visual Basic for Applications (VBA)
- Python
- Numpy
- Panda
- Matplotlib
- Scikit-learn
- Google Colab

Dataset yang digunakan merupakan data sebuah greenhouse cabai rawit yang dilengkapi berbagai sensor. Kolom data yang digunakan adalah:
Suhu Lingkungan (°C) -> S;
Kelembapan Relatif Udara (%) -> K;
Suhu Tanah (°C) -> ST;
Kadar Air Tanah (%) -> KA; dan
Kadar Air Tanah Satu Jam Setelahnya (%) -> KASJS.

Pengolahan dataset mentah di Microsoft Excel menggunakan **VBA**. 
Dataset dibagi menjadi dua. Dataset pertama adalah dataset 3 bulan (Agustus-Oktober), digunakan untuk melatih model machine learning (data uji).
                            Dataset kedua adalah dataset bulan November, digunakan untuk validasi prediksi dari model machine learning yang sudah dilatih (data baru).

Tiga model machine learning yang dibuat antara lain Decision Tree Regression, Support Vector Regression, dan Random Forest Regression.
Batas akurasi yang ditetapkan adalah 81%, di mana ketiga model mampu melewati batas akurasi tersebut.
Model terbaik adalah model Support Vector Regression, dengan nilai akurasi tertinggi sebesar 93.8% pada data uji dan 95.8% pada data baru.

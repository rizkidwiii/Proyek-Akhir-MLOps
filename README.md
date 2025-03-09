# Submission 1: Churn Prediction for Netflix: Leveraging Machine Learning for Customer Retention
Nama: Rizki Dwi Sya'bana Nugraha

Username dicoding: rizkidwi07

| | Deskripsi |
| ----------- | ----------- |
| Dataset | [Netflix Engagement Dataset](https://www.kaggle.com/datasets/honeybearugly/netflix-engagment-dataset) |
| Masalah | Churn atau pelanggan yang berhenti berlangganan merupakan tantangan besar bagi layanan berbasis langganan seperti Netflix. Memahami pola perilaku pelanggan yang dapat mengarah pada churn sangat penting untuk meningkatkan retensi pelanggan. Dengan menggunakan dataset ini, tujuan utama adalah memprediksi apakah pelanggan akan berhenti berlangganan berdasarkan keterlibatan mereka, kebiasaan menonton, dan faktor lainnya. |
| Solusi machine learning | Untuk mengatasi masalah ini, diterapkan model machine learning yang dapat mengklasifikasikan pelanggan apakah mereka akan churn atau tidak. Model ini akan menganalisis berbagai faktor seperti riwayat pembayaran, durasi langganan, keterlibatan pengguna, serta promosi yang digunakan untuk memberikan prediksi yang akurat. |
| Metode pengolahan | Melakukan encoding pada fitur kategorikal, dan normalisasi data numerik, memilih fitur yang paling relevan untuk meningkatkan performa model, dan memisahkan dataset menjadi data training dan testing dengan rasio 80:20. |
| Arsitektur model | Model yang digunakan adalah neural network dengan beberapa layer: Input Layer: Berisi fitur kategorikal dan numerik yang telah diproses. Hidden Layers: Terdiri dari 3 lapisan dense dengan aktivasi ReLU untuk menangkap pola kompleks dalam data. Output Layer: Menggunakan aktivasi sigmoid untuk menghasilkan probabilitas churn. |
| Metrik evaluasi | Model dievaluasi menggunakan metrik Binary Accuracy. |
| Performa model | Model ini memiliki performa yang cukup baik dalam memberikan sebuah prediksi dan dari pelatihan yang dilakukan menghasilkan binary accuracy sebesar 100%, val binary accuracy sebesar 99%. |
| Opsi deployment | Proyek machine learning ini di deploy menggunakan salah satu layanan yaitu Railway. |
| Web app | [cc-model](https://proyek-akhir-mlops-production.up.railway.app/v1/models/cc-model/metadata)|
| Monitoring | Monitoring pada proyek ini dilakukan dengan menggunakan layanan open-source yaitu prometheus. Contohnya setiap perubahan jumlah request yang dilakukan dapat dimonitoring dengan baik dan dapat menampilkan status dari setiap request yang diterima. |


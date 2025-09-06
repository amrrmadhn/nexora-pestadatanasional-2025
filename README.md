# 🚗 Time Series Forecasting untuk Prediksi Penjualan Mobil

## Tim NEXORA Universitas Pembangunan Jaya

**Ketua Tim:**
- Maria Rachel Kesya Makarena

**Anggota Tim:**
- Ammar Ramadhan

**Asal Universitas:** Universitas Pembangunan Jaya

**Kompetisi:** Pesta Data Nasional 2025

---

## 📋 Deskripsi Proyek

Repository ini berisi implementasi berbagai model time series forecasting untuk memprediksi penjualan mobil bulanan. Proyek ini dikembangkan sebagai bagian dari partisipasi Tim NEXORA dalam **Pesta Data Nasional 2025**.

## 🎯 Tujuan

- Menganalisis dan memprediksi penjualan mobil menggunakan berbagai metode time series
- Membandingkan performa model SARIMAX, Prophet, Holt-Winters, dan Darts
- Menentukan model terbaik berdasarkan metrik evaluasi SMAPE (Symmetric Mean Absolute Percentage Error)
- Memberikan prediksi penjualan untuk periode mendatang

## 🔧 Model yang Diimplementasikan

1. **SARIMAX (Seasonal AutoRegressive Integrated Moving Average with eXogenous regressors)**
   - Menggunakan auto_arima untuk mencari parameter optimal
   - Mempertimbangkan komponen seasonal dengan periode 12 bulan

2. **Prophet**
   - Model forecasting yang dikembangkan oleh Facebook
   - Mampu menangani trend dan seasonality dengan baik

3. **Holt-Winters (Exponential Smoothing)**
   - Model tradisional untuk data dengan trend dan seasonality
   - Implementasi additive seasonal component

4. **Darts**
   - AutoARIMA dan Exponential Smoothing dari library Darts
   - Modern time series forecasting library

## 📊 Metrik Evaluasi

Model dievaluasi menggunakan beberapa metrik:
- **MAE (Mean Absolute Error)**
- **RMSE (Root Mean Square Error)**
- **SMAPE (Symmetric Mean Absolute Percentage Error)** - *Metrik utama untuk pemilihan model terbaik*
- **MSE (Mean Square Error)**

## 🗂 Struktur Data

Dataset sampel yang digunakan mencakup:
- **Periode:** Januari 2021 - Juli 2025 (data bulanan)
- **Merek Mobil:** DAIHATSU, HONDA, MITSUBISHI, SUZUKI, TOYOTA
- **Format:** Time series dengan komponen trend dan seasonality

### Output yang Dihasilkan
1. **Pencarian Parameter Optimal** untuk setiap model
2. **Evaluasi Model** dengan berbagai metrik
3. **Perbandingan Performa** antar model
4. **Pemilihan Model Terbaik** berdasarkan SMAPE
5. **Prediksi Masa Depan** menggunakan model terbaik

## 📈 Fitur Utama

- ✅ **Automated Parameter Tuning** untuk SARIMAX
- ✅ **Multiple Model Comparison** dalam satu framework
- ✅ **Comprehensive Evaluation Metrics**
- ✅ **Future Forecasting** dengan model terbaik
- ✅ **Structured Output** untuk analisis mudah

## 👥 Kontributor

### Maria Rachel Kesya Makarena
- Universitas Pembangunan Jaya

### Ammar Ramadhan
- Universitas Pembangunan Jaya


---

## 📞 Kontak

Untuk pertanyaan atau kolaborasi, silakan hubungi tim melalui:
LinkedIn:
- **Maria Rachel:** [Maria Rachel on LinkedIn](https://www.linkedin.com/in/maria-rachel-kesya-makarena-b43979287/)
- **Ammar Ramadhan:** [Ammar Ramadhan on LinkedIn](https://www.linkedin.com/in/amrrmadhn/)

## 📄 Lisensi

Proyek ini dikembangkan untuk keperluan kompetisi **Pesta Data Nasional 2025**.

---

**© 2025 Tim NEXORA - Universitas Pembangunan Jaya**

*"Innovating through Data, Forecasting the Future"*

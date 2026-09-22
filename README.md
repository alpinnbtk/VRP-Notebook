# Garbage Collection Vehicle Routing Problem (VRP) with Google OR-Tools

Repositori ini berisi notebook Google Colab yang dirancang untuk menyelesaikan permasalahan **Capacitated Vehicle Routing Problem (CVRP)** pada studi kasus optimasi rute pengangkutan sampah di wilayah Surabaya.

> **Catatan Penulis & Disclaimer AI:**
> Seluruh kode, struktur penjelasan, dan logika di dalam notebook ini **sepenuhnya dibuat oleh AI**. Notebook ini digunakan sebagai materi pembelajaran mandiri (*prerequisite study*) untuk memahami konsep dasar optimasi rute, formulasi VRP, dan penggunaan Google OR-Tools sebelum melangkah ke pengerjaan **Tugas Akhir (TA)**.

---

## 📌 Fitur & Cakupan Notebook

* **Pengenalan VRP & Setup**: Penjelasan dasar landasan VRP pada pengangkutan sampah serta instalasi *dependencies* tanpa konfigurasi rumit.
* **Simulasi Data Realistis**: Menggunakan titik koordinat riil wilayah Surabaya (1 Depot/TPA dan 10 TPS) lengkap dengan data *demand* (muatan sampah) serta kapasitas truk.
* **Matrix Jarak (Haversine)**: Perhitungan jarak riil antar koordinat geografis dalam satuan meter.
* **Solver OR-Tools**: Penggunaan `pywrapcp` dari Google OR-Tools untuk menyelesaikan VRP dengan batasan kapasitas (*Capacity Constraint*).
* **Visualisasi Ganda**:
  * **Matplotlib**: Visualisasi skema rute 2D secara ringkas.
  * **Folium**: Peta interaktif berbasis koordinat geografis Surabaya.
* **Analisis Kinerja & Sensitivitas**: Evaluasi tingkat utilisasi armada dan eksperimen dampak variasi jumlah kendaraan terhadap total jarak tempuh.

---

## 🚀 Cara Menggunakan

1. Unggah dan buka file notebook `.ipynb` di **Google Colab**.
2. Jalankan sel secara berurutan (*End-to-End Execution*) dari **Cell 1** hingga **Cell 9**.
3. Seluruh *dependencies* akan diinstal secara otomatis pada sel pertama.

---

## 🛠️ Stack & Pustaka Utama

* **Python 3.x**
* **Google OR-Tools** (`ortools.constraint_solver.pywrapcp`) - Engine Optimasi
* **Folium** - Visualisasi Peta Interaktif
* **Matplotlib & Pandas** - Analisis Data & Visualisasi Grafik 2D

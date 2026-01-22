# Well-Log-Data-Analysis-Facies-Classification-for-Reservoir-Characterization
This project focuses on well log data analysis and rock facies classification modeling to support reservoir characterization in petroleum engineering. Utilizing Python and machine learning techniques, this project integrates various rock physical parameters to automatically identify potential hydrocarbon zones.

Berikut adalah draf lengkap untuk file README.md Anda dalam dua bahasa (Bahasa Indonesia dan Bahasa Inggris). Anda bisa menyalin teks ini langsung ke repository GitHub Anda.

## Well Log Analysis & Reservoir Identification 🛢️

### Project Overview
This project is a computational petrophysics workflow designed to analyze well log data and identify potential hydrocarbon-bearing zones. Using Python, the notebook processes geological data (Gamma Ray, Resistivity, Porosity, etc.) to evaluate reservoir quality and distinguish between different facies.

The core of this analysis relies on the "Golden Rule" of petrophysics to pinpoint economic oil reserves.

### Key Features
Data Processing: Loads and cleans well log datasets (e.g., facies_data2.csv) containing key metrics like Depth, GR, ILD_log10, PE, and PHIND.

Statistical Analysis: Provides descriptive statistics to understand the distribution of geological properties across different formations.

Visualization: visualizing well logs to observe trends in formation properties.

Reservoir Interpretation: Applies petrophysical logic to identify "Pay Zones".

 ## The "Golden Rule" 💡
The analysis focuses on identifying zones that meet specific criteria for economic potential:

"Look for zones where Gamma Ray is low (Clean Sand), Resistivity is high (Hydrocarbon indication), and Porosity is high (Storage capacity). That is where we are most likely to find economic oil reserves."

Technologies Used
Python 3

Pandas: For data manipulation and dataframe management.

NumPy: For numerical computations.

Matplotlib & Seaborn: For static plotting and data visualization.

### How to Use
Clone this repository.

Open Faisal_Well_Log_Analysis.ipynb in Jupyter Notebook or Google Colab.

Upload your dataset (e.g., facies_data2.csv) when prompted or ensure it is in the same directory.

Run the cells sequentially to perform the analysis.


## Gambaran Proyek
Proyek ini adalah alur kerja petrofisika komputasi yang dirancang untuk menganalisis data well log (log sumur) dan mengidentifikasi zona yang berpotensi mengandung hidrokarbon. Menggunakan Python, notebook ini memproses data geologi (Gamma Ray, Resistivitas, Porositas, dll) untuk mengevaluasi kualitas reservoir dan membedakan berbagai fasies batuan.

Inti dari analisis ini berpegang pada "Golden Rule" (Aturan Emas) petrofisika untuk menemukan cadangan minyak yang ekonomis.

### Fitur Utama
Pemrosesan Data: Memuat dan membersihkan dataset well log (contoh: facies_data2.csv) yang berisi metrik kunci seperti Depth (Kedalaman), GR (Gamma Ray), ILD_log10 (Resistivitas), PE, dan PHIND (Porositas).

Analisis Statistik: Menyediakan statistik deskriptif untuk memahami distribusi properti geologi di berbagai formasi.

Visualisasi: Menampilkan grafik well logs untuk mengamati tren properti formasi.

Interpretasi Reservoir: Menerapkan logika petrofisika untuk mengidentifikasi "Pay Zones".

## The "Golden Rule" (Aturan Emas)💡
Analisis ini berfokus pada pencarian zona yang memenuhi kriteria potensi ekonomi:

"Cari zona di mana Gamma Ray rendah (Pasir Bersih/Clean Sand), Resistivitas tinggi (Indikasi Hidrokarbon), dan Porositas juga tinggi (Kapasitas Penyimpanan). Itulah titik di mana kita kemungkinan besar menemukan cadangan minyak yang ekonomis."

Teknologi yang Digunakan
Python 3

Pandas: Untuk manipulasi data dan manajemen dataframe.

NumPy: Untuk komputasi numerik.

Matplotlib & Seaborn: Untuk pembuatan plot statis dan visualisasi data.

### Cara Penggunaan
Clone repository ini.

Buka Faisal_Well_Log_Analysis.ipynb di Jupyter Notebook atau Google Colab.

Unggah dataset Anda (misalnya facies_data2.csv) saat diminta atau pastikan file berada di direktori yang sama.

Jalankan sel secara berurutan untuk melakukan analisis.

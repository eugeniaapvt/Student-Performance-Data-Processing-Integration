# Student Performance Data Cleaning & Integration

Pengolahan dan integrasi data siswa, kehadiran, dan performa akademik menggunakan Python dan Pandas.

## Dataset

Project menggunakan tiga dataset:

- Students dataset
- Attendance dataset
- Performance dataset

Ketiga dataset digunakan untuk mengolah informasi mengenai siswa, kehadiran, dan performa akademik.

## Data Processing

Tahapan pengolahan data meliputi:

- Data inspection
- Data cleaning
- Data standardization
- Data transformation
- Data manipulation
- Data merging and integration

Beberapa proses yang dilakukan meliputi standardisasi status kehadiran dan nama siswa serta penggabungan dataset berdasarkan `Student_ID` dan `Subject`.

## Data Integration

Dataset attendance dan performance diintegrasikan menggunakan `left join` berdasarkan:

- `Student_ID`
- `Subject`

Hasilnya berupa dataset yang menggabungkan informasi kehadiran dan performa akademik siswa.

## Tools

- Python
- Pandas
- NumPy
- Google Colab

## Usage

Notebook utama:

`Manajemen_Big_Data.ipynb`

Notebook berisi proses data cleaning, transformation, manipulation, dan integration dari tiga dataset.

## Results

Menghasilkan dataset terintegrasi yang menggabungkan informasi siswa, attendance, dan academic performance.

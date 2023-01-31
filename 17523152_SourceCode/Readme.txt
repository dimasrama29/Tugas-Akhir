Folder ini berisi file kode seleksi fitur bersama prediksi data NIRS mangga
Dataset dapat diunduh di https://data.mendeley.com/datasets/b9d6s7hr33/1
Code dijalankan pada Jupyter Notebook (.ipynb).

File dataset NIRS mangga berjudul "Dataset_RawSpectrum_NIRS_for_Intact_Mangoes.csv".
Panduan source code berjalan"
1. Import Libraries yang dibutuhkan + install libraries yang belum di install
2. Import dan split Dataset
3. Proses Seleksi Fitur
4. Proses Prediksi regresi dan pengujian model 

Terdapat beberapa file:
- 9 file seleksi fitur bersama prediksinya. 9 seleksi fitur tersebut yaitu Anova, Mutual Information, Fisher Score
Pearson correlation, Sequential Forward Selection, Backward Elimination, Recursive Feature Elimination, LASSO, ELastic net
- Fitur terbanyak yang muncul

Untuk menjalankannya, jalankan setiap cell secara berurutan.
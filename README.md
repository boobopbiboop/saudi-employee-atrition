# Prediksi Employee Attrition dengan Metode Single Learning dan Ensemble Learning

| Nama                  | NRP        |
|-----------------------|------------|
| Azizah Elok Harvianti          | 5025221243     |
| Nadya Saraswati Putri      | 5025221246     |
| Adelia Putri Kamaski  | 5025221320|

## Deskripsi Final Project

Final project ini bertujuan untuk membangun model prediksi **_employee attrition_**, yaitu memprediksi apakah seorang karyawan akan bertahan atau keluar dari perusahaan berdasarkan berbagai faktor demografis, pekerjaan, kepuasan kerja, dan karakteristik organisasi. Dataset yang digunakan pada project ini, yaitu 'Saudi Employee Attrition' Dataset yang dipublikasikan oleh Alqahtani, Almagrabi, dan Alharbi pada Maret 2025 melalui repositori Mendeley Data (Alqahtani et al., 2025).

Adapun tujuan akhir yang ingin dicapai dari final project ini, yaitu: 
1. Membandingkan model _Single Learning_ dan _Ensemble Learning_ untuk mencari model terbaik yang mampu memprediksi resiko attrition.
2. Mengidentifikasi fitur mana yang paling berpengaruh.
3. Memberikan insight yang dapat membantu pengambil keputusan dalam mengurangi turnover

---

## Dataset

* **Link:** [Saudi Employee Attrition Dataset](https://data.mendeley.com/datasets/6z2hty8php/1)
* **Original Data**  (`Original Dataset of Employee Attrition.xlsx`): data mentah hasil survei sebelum dilakukan preprocessing atau encoding pada fitur-fiturnya. 
* **Tree-Based Data** (`Employee attrition dataset for tree-based models.xlsx`): data yang sudah melalui tahapan preprocessing dan encoding. Data ini disesuaikan untuk model decision tree dan model ensemble berbasis tree, seperti Random Forest atau Gradient Boosting.
* * **Non-Tree Data** (`Employee attrition dataset for non-tree-based models`): data yang sudah melalui tahapan preprocessing, encoding, dan semua data telah dikonversikan ke dalam bentuk numerikal. Data ini disesuaikan untuk model non-tree, seperti SVM, Logistic Regression, dan KNN. 
* **Target Variable(Y):** **`Attrition`**

**Catatan:** Pemilik dataset mencantumkan dua file yang sudah di-preprocessing khusus untuk melatih model tree-based dan model non-tree. Namun, kami tetap melakukan tahapan preprocessing. 

| **Aspek**              | **Deskripsi**      |
|-----------------------|-----------------|
| Nama Dataset          | Saudi Employee Attrition Dataset         |
| Tahun Publikasi       | 2025   |
| Publisher             | Mendeley |
| DOI                   | 10.17632/6z2hty8php.1 |
| Kontributor           | Haya Alqahtani, Hana Almagrabi, Amal Alharbi               |
| Jumlah responden      | 1.200 karyawan    |
| Jumlah fitur          | 34 variabel + 1 target variabel (attrition) |
| Jenis fitur           | Demografis, pekerjaan, kepuasan kerja, kondisi organisasi,  faktor motivasi |
| Tipe Target           | Biner ('Yes' / 'No') |


---

## Model yang Digunakan
- **Single Learning:** Regresi Logistik, K-Nearest Neighbors, Support Vector Machine, dan Decision Tree.

- **Ensemble Learning:** Random Forest, Gradient Boosting, AdaBoost, XGBoost, dan CatBoost

## Skenario Pengujian

### A. Komparasi Performa Single Learning vs Ensemble Learning

### B. Pengujian Dampak Penanganan Imbalanced Data

### C. Analisis Determinan Atrisi (Feature Importance)

---

##  Output

### 1. Prediksi employee attrition

--- 

## Link Demo

---

## Referensi

Alqahtani, H., Almagrabi, H., & Alharbi, A. (2025). Saudi Employee Attrition Dataset (Version 1) [Data set]. Mendeley Data. https://doi.org/10.17632/6z2hty8php.1 

Fauziah, D. A., Muliawan, A., & Dimyati, M. (2024). Implementation of Machine Learning on Employee Attrition Based on Performance Parameters Using Particle Swarm Optimization and Ensemble Classifier Methods. Jurnal Teknik Informatika (JUTIF), 5(6), 1823-1831. https://doi.org/10.52436/1.jutif.2024.5.6.3442 

Glassbox Medicine. (2019, February 17). Measuring performance: The confusion matrix. Glassbox Medicine. https://glassboxmedicine.com/2019/02/17/measuring-performance-the-confusion-matrix/  

Govindarajan, R., Kumara, N. K., Reddy, S. P., Pravallika, S. E., Dhatri, B., & Kumar, P. (2025). Predicting Employee Attrition: A Comparative Analysis of Machine Learning Models Using the IBM Human Resource Analytics Dataset. Procedia Computer Science, 258, 4084-4093. https://doi.org/10.1016/j.procs.2025.04.659 

Jamroni, A. R. B., Hadikristanto, W., & Fatchan, M. (2025). Analisis Faktor dan Prediksi Atrisi untuk Optimalisasi Retensi Karyawan Menggunakan Machine Learning. Bit-Tech (Binary Digital - Technology), 7(3), 1057-1067. https://doi.org/10.32877/bt.v7i3.2301 

Varkiani, S. M., Pattarin, F., Fabbri, T., & Fantoni, G. (2025). Predicting Employee Attrition and Explaining Its Determinants. Expert Systems With Applications, 272, 126575. https://doi.org/10.1016/j.eswa.2025.126575 

Wardhani, F. H., & Lhaksmana, K. M. (2022). Predicting Employee Attrition Using Logistic Regression with Feature Selection. Sinkron: Jurnal dan Penelitian Teknik Informatika, 6(4), 2214-2222. https://doi.org/10.33395/sinkron.v7i4.11783 

## Deteksi Tumor Otak dengan Metode Convolutional Neural Network

Proyek ini bertujuan untuk mengembangkan sistem deteksi tumor otak menggunakan Convolutional Neural Network (CNN) berdasarkan citra MRI (Magnetic Resonance Imaging). Model ini dirancang untuk mengklasifikasikan apakah citra MRI menunjukkan keberadaan tumor otak atau tidak, dan mengklasifikasikan jenis tumor yang dapat membantu dalam diagnosis awal yang cepat dan akurat.

### Anggota Kelompok

Proyek ini dikerjakan oleh Kelompok 4 dari IT 05-01:

* **Maharani Febhi Atha Ningrum** (1202220006)
* **Adinda Mariasti Dewi** (1202220041)
* **Wahyuning Ajeng Arfiatin** (1202220045)
* **Adina Fadillah Balqis** (1202222012)

### Latar Belakang

Tumor otak adalah salah satu penyakit paling mematikan di dunia dengan prevalensi yang signifikan. Deteksi dini dan diagnosis yang akurat sangat krusial untuk penanganan yang efektif. Meskipun MRI scan adalah alat diagnostik utama, interpretasi manual oleh dokter bisa memakan waktu. Penerapan CNN dalam pengolahan citra medis menawarkan potensi besar untuk otomasi dan peningkatan efisiensi proses diagnosis.

### Struktur Repositori

* `Tubes_PCD_kelompok.ipynb`: Notebook Jupyter yang berisi seluruh kode sumber untuk pelatihan, evaluasi, dan implementasi model CNN.
* `[nama_model_anda].h5`: File model CNN yang telah dilatih (misalnya, `brain_tumor_model.h5` atau `model_cnn_final.h5`).
* `README.md`: File ini.
* `image_166f62.png`: Gambar ilustrasi terkait proyek.

### Dataset

Dataset yang digunakan dalam proyek ini bersumber dari Kaggle, yang berisi citra MRI otak yang telah diklasifikasikan sebagai tumor atau non-tumor.

**Link Dataset:** [https://www.kaggle.com/datasets/adirahman123/kanker](https://www.kaggle.com/datasets/adirahman123/kanker)

Pastikan untuk mengunduh atau mengakses dataset ini terlebih dahulu jika Anda ingin menjalankan ulang notebook.

### Persyaratan Sistem (Dependencies)

Untuk menjalankan kode ini, Anda memerlukan lingkungan Python dengan pustaka-pustaka berikut:

* Python 3.x
* TensorFlow
* Keras
* NumPy
* Pillow (PIL)
* Matplotlib
* Scikit-learn
* OpenCV (cv2)

Anda dapat menginstal semua dependensi ini menggunakan `pip`:

```bash
pip install tensorflow keras numpy pillow matplotlib scikit-learn opencv-python
````

### Cara Menjalankan Kode

1.  **Klon Repositori:**
    ```bash
    git clone [https://github.com/](https://github.com/)[Your_Username]/Brain-Tumor-Detection-CNN.git
    cd Brain-Tumor-Detection-CNN
    ```
2.  **Unduh Dataset:**
    Akses dataset dari link Kaggle yang disediakan di atas dan simpan di lokasi yang sesuai (atau sesuaikan path di notebook Anda). Jika Anda menggunakan Google Colab, Anda bisa langsung mengunduhnya di sana.
3.  **Buka Notebook:**
    Buka `Tubes_PCD_kelompok.ipynb` menggunakan Jupyter Notebook, JupyterLab, atau Google Colab.
4.  **Jalankan Sel-sel Kode:**
    Ikuti instruksi di dalam notebook untuk menjalankan sel-sel kode secara berurutan. Ini akan mencakup pemrosesan data, pembangunan model, pelatihan, dan evaluasi.

### Hasil dan Diskusi

Model CNN yang dikembangkan menunjukkan performa yang menjanjikan dalam mengklasifikasikan citra MRI untuk deteksi tumor otak. Detail lebih lanjut mengenai arsitektur model, metrik evaluasi (akurasi, presisi, recall, F1-score), dan visualisasi hasil dapat ditemukan di dalam notebook `Tubes_PCD_kelompok.ipynb`.

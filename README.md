# Submission Dicoding "Belajar Data Analytics dengan Python"✨

Repository ini berisi proyek data analytics yang telah saya deploy di **Streamlit** 

## Deskripsi

Proyek ini bertujuan untuk menganalisis data pada E-Commerce Public Dataset. Tujuan akhirnya adalah untuk menghasilkan wawasan dan informasi yang berguna dari data yang dianalisis.

## Struktur Direktori

- **/dashboard**: Direktori ini berisi main_data yang digunakan untuk membuat dashboard hasil analisis data dan data yang digunakan dalam proyek, dalam format .csv 
- **/data**: Direktori ini berisi dataset yang digunakan dalam analisis data.
- **notebook**: File ini yang digunakan untuk melakukan analisis data (format file:ipynb).
- **requirements**: File ini mencantumkan berbagai library yang digunakan selama proses analisis data.
- **url**: File ini berisi tautan untuk mengakses dashboard.
- **README.md**: File ini berisi petunjuk tentang cara menjalankan dashboard streamlit.

## Instalasi

1. Clone repository ini ke komputer lokal Anda menggunakan perintah berikut:

   ```shell
   git clone https://github.com/siskakhnnisa/proyek-analisis-submission.git
   ```

2. Pastikan Anda memiliki lingkungan Python yang sesuai dan pustaka-pustaka yang diperlukan. Anda dapat menginstal pustaka-pustaka tersebut dengan menjalankan perintah berikut:

    ```shell
    pip install streamlit
    pip install -r requirements.txt
    ```

## Penggunaan
1. Masuk ke direktori proyek (Local):

    ```shell
    cd proyek-analisis-submission/dashboard/
    streamlit run dashboard.py
    ```

**Atau melalui cara berikut:**

## Setup Environment - Anaconda
```
conda create --name main-ds python=3.10
conda activate main-ds
pip install -r requirements.txt
```

## Setup Environment - Shell/Terminal
```
mkdir proyek_analisis_data
cd proyek_analisis_data
pipenv install
pipenv shell
pip install -r requirements.txt
```

## Run steamlit app
```
streamlit run dashboard.py
```
**Atau dapat akses link berikut: https://kyccugeedpkqyp8ukckmgk.streamlit.app/**

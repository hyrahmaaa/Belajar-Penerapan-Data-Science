# Proyek Akhir: Menyelesaikan Permasalahan Perusahaan Edutech

## Business Understanding

Jaya Jaya Maju adalah perusahaan multinasional yang telah beroperasi sejak tahun 2000 dan memiliki lebih dari 1.000 karyawan yang tersebar di seluruh Indonesia. Sebagai perusahaan yang cukup besar, Jaya Jaya Maju menghadapi tantangan dalam mengelola karyawan, yang tercermin dalam tingkat attrition rate yang tinggi, melebihi 10%. Situasi ini berpotensi mengganggu stabilitas operasional, meningkatkan biaya, dan mengurangi efektivitas organisasi. Manajemen departemen HR menyadari perlunya tindakan proaktif berbasis data untuk memahami dan mengatasi akar permasalahan ini.

### Permasalahan Bisnis

Permasalahan bisnis utama yang akan diselesaikan adalah:
- Tingginya Tingkat Attrition Karyawan: Rasio karyawan yang keluar dari perusahaan (lebih dari 10%) dianggap tidak sehat dan perlu diturunkan.
- Kurangnya Pemahaman Faktor Penyebab Attrition: Departemen HR belum memiliki pemahaman yang mendalam mengenai faktor-faktor spesifik yang secara signifikan berkontribusi terhadap tingginya tingkat attrition.
- Kebutuhan akan Sistem Monitoring Berkelanjutan: Belum adanya alat atau sistem yang efektif untuk memonitor tren attrition dan faktor-faktor terkait secara berkelanjutan, sehingga pengambilan keputusan strategis menjadi kurang optimal.
  
### Cakupan Proyek

Cakupan proyek ini meliputi:
- Analisis Data Karyawan: Menganalisis dataset yang disediakan oleh Jaya Jaya Maju untuk mengidentifikasi pola, korelasi, dan faktor-faktor yang mempengaruhi attrition karyawan.
- Pengembangan Model Machine Learning: Membangun model machine learning yang mampu memprediksi potensi attrition karyawan berdasarkan data yang ada.
- Pembuatan Dashboard Visualisasi: Merancang dan mengembangkan dashboard interaktif yang memungkinkan departemen HR untuk memonitor tingkat attrition, mengidentifikasi faktor-faktor kunci, dan melacak tren dari waktu ke waktu.

### Persiapan

Sumber data: https://github.com/dicodingacademy/dicoding_dataset/tree/main/employee

Setup environment (Google Colab):
Persiapan

Sumber data: https://github.com/dicodingacademy/dicoding_dataset/tree/main/employee

### Setup Environment

Proyek ini dikembangkan menggunakan Python dan disarankan untuk dijalankan dalam lingkungan virtual (virtual environment) untuk mengelola dependensi secara terisolasi.

1.  **Membuat dan Mengaktifkan Virtual Environment (venv)**
    Buka terminal atau command prompt Anda, lalu ikuti langkah-langkah berikut:
    ```bash
    # Membuat virtual environment baru bernama 'venv_attrition'
    python3 -m venv venv_attrition

    # Mengaktifkan virtual environment:
    # Untuk macOS/Linux:
    source venv_attrition/bin/activate
    # Untuk Windows (Command Prompt):
    venv_attrition\Scripts\activate.bat
    # Untuk Windows (PowerShell):
    venv_attrition\Scripts\Activate.ps1
    ```
    Setelah diaktifkan, Anda akan melihat `(venv_attrition)` di awal baris perintah Anda, menandakan bahwa Anda berada di lingkungan virtual.

2.  **Menginstal Dependensi dari `requirements.txt`**
    Pastikan Anda telah mengaktifkan virtual environment Anda (langkah 1). Kemudian, instal semua pustaka Python yang dibutuhkan dari berkas `requirements.txt` (yang harus Anda sediakan di root proyek Anda) menggunakan pip:
    ```bash
    pip install -r requirements.txt
    ```
    Ini akan menginstal semua *library* yang diperlukan seperti `pandas`, `scikit-learn`, `matplotlib`, `seaborn`, dll.

3.  **Akses Data**
    * **Untuk Lingkungan Lokal:** Pastikan Anda telah mengunduh dataset dari [tautan sumber data](https://github.com/dicodingacademy/dicoding_dataset/tree/main/employee) dan meletakkannya di lokasi yang sesuai dengan path yang digunakan dalam skrip Python.
    * **Untuk Google Colab:** Jika Anda menjalankan proyek di Google Colab, Anda perlu mengunggah file dataset ke Google Drive Anda dan melakukan *mount* Google Drive di Colab untuk mengaksesnya. Instruksi *mounting* dapat ditemukan di notebook Colab Anda (misalnya: `from google.colab import drive; drive.mount('/content/gdrive/')`).

4.  **Cara Menjalankan Skrip Python (.py)**
    Setelah virtual environment diaktifkan dan semua dependensi terinstal, Anda dapat menjalankan skrip utama proyek. Asumsikan skrip utama Anda adalah `main.py` (Anda bisa mengganti nama ini sesuai dengan nama file skrip Anda, misalnya `train_model.py` atau `analyze_data.py`).
    ```bash
    # Contoh menjalankan skrip utama tanpa parameter tambahan
    python main.py

    # Jika skrip Anda membutuhkan parameter (misalnya, path ke data atau mode operasi):
    # python main.py --data_path ./data/employee_data.csv --mode predict
    # Pastikan untuk merujuk pada dokumentasi internal skrip Anda untuk detail parameter.
    ```
    Hasil analisis, model yang disimpan, atau output lainnya akan dihasilkan sesuai dengan logika skrip Anda.

## Business Dashboard

Dashboard ini dirancang untuk memberikan pemahaman yang mendalam tentang attrition karyawan dengan menampilkan metrik utama, tren, dan perbandingan berdasarkan berbagai faktor. Tujuannya adalah untuk membantu departemen HR mengidentifikasi area fokus untuk meningkatkan retensi karyawan. Adapun yang ditampilkan adalah faktor-faktor yang mempengaruhi attration berdasarkan analisis pada notebook.

🔗 URL : https://lookerstudio.google.com/reporting/1df393fd-e55c-43c5-a287-7e2feee0fa0d

## Conclusion

Proyek ini berhasil melakukan analisis mendalam terhadap data karyawan Jaya Jaya Maju untuk mengidentifikasi berbagai faktor yang berpotensi mempengaruhi tingginya tingkat attrition karyawan. Melalui eksplorasi data dan analisis statistik (seperti uji Chi-square dan t-test), korelasi dan perbedaan signifikan antara berbagai fitur karyawan  dengan status attrition berhasil diungkap.

Conclusion

Proyek ini berhasil melakukan analisis mendalam terhadap data karyawan Jaya Jaya Maju untuk mengidentifikasi berbagai faktor yang berpotensi mempengaruhi tingginya tingkat attrition karyawan. Melalui eksplorasi data dan analisis statistik (seperti uji Chi-square dan t-test), korelasi dan perbedaan signifikan antara berbagai fitur karyawan dengan status attrition berhasil diungkap.

Adapu karakteristik umum karyawan yang melakukan attrition:
- Masa Kerja dengan Manajer yang Lebih Singkat: Karyawan dengan rata-rata masa kerja yang lebih singkat dengan manajer saat ini memiliki kecenderungan lebih tinggi untuk keluar.
- Tingkat Kepuasan Kerja Rendah: Karyawan yang menunjukkan tingkat kepuasan kerja yang lebih rendah cenderung memiliki probabilitas attrition yang lebih tinggi.
- Tingkat Keterlibatan Kerja Rendah: Rendahnya tingkat keterlibatan dalam pekerjaan juga merupakan indikator kuat potensi attrition.
- Keseimbangan Kerja dan Hidup yang Buruk: Karyawan yang melaporkan keseimbangan kerja dan hidup yang tidak optimal lebih rentan untuk meninggalkan perusahaan.
- Tingkat Opsi Saham yang Rendah: Ada korelasi antara tingkat opsi saham yang lebih rendah dengan peningkatan attrition.
- Tingkat Jabatan (Job Level) Tertentu: Tingkat jabatan tertentu mungkin menunjukkan risiko attrition yang lebih tinggi, mengindikasikan isu pada struktur karir atau kompensasi di level tersebut.
- Bidang Pendidikan Spesifik: Karyawan dari bidang pendidikan tertentu menunjukkan kecenderungan lebih tinggi untuk melakukan attrition, memerlukan investigasi lebih lanjut terkait relevansi atau prospek karir.

Untuk memfasilitasi pemantauan berkelanjutan dan pemahaman yang lebih baik oleh departemen HR, sebuah dashboard visualisasi yang komprehensif telah dirancang dan dikembangkan. Dashboard ini menyajikan metrik kunci terkait attrition, tren dari waktu ke waktu, dan perbandingan attrition berdasarkan berbagai faktor demografis dan terkait pekerjaan. Visualisasi ini bertujuan untuk memberikan wawasan yang actionable bagi HR untuk memahami pola attrition dan mengidentifikasi area fokus untuk upaya retensi karyawan.

Secara keseluruhan, proyek ini telah berhasil mengidentifikasi faktor-faktor penting yang terkait dengan attrition karyawan di Jaya Jaya Maju dan menyediakan alat visualisasi yang berharga bagi departemen HR untuk memonitor dan memahami fenomena ini. Hasil analisis dan dashboard ini dapat menjadi dasar yang kuat bagi perusahaan dalam merumuskan strategi retensi karyawan yang lebih efektif dan tepat sasaran.

Untuk memfasilitasi pemantauan berkelanjutan dan pemahaman yang lebih baik oleh departemen HR, sebuah dashboard visualisasi yang komprehensif telah dirancang dan dikembangkan. Dashboard ini menyajikan metrik kunci terkait attrition, tren dari waktu ke waktu, dan perbandingan attrition berdasarkan berbagai faktor demografis dan terkait pekerjaan, seperti departemen, jabatan, usia, tingkat kepuasan, keterlibatan kerja, masa kerja, dan lainnya. Visualisasi ini bertujuan untuk memberikan wawasan yang actionable bagi HR untuk memahami pola attrition dan mengidentifikasi area fokus untuk upaya retensi karyawan.

Secara keseluruhan, proyek ini telah berhasil mengidentifikasi faktor-faktor penting yang terkait dengan attrition karyawan di Jaya Jaya Maju dan menyediakan alat visualisasi yang berharga bagi departemen HR untuk memonitor dan memahami fenomena ini. Hasil analisis dan dashboard ini dapat menjadi dasar yang kuat bagi perusahaan dalam merumuskan strategi retensi karyawan yang lebih efektif dan tepat sasaran.

### Rekomendasi Action Items (Optional)

- Rata-rata Masa Kerja dengan Manajer (Average Years With Current Manager): dapat melakukan survei untuk memahami gaya kepemimpinan para manajer dan dampak pada tim, pelatihan kepemimpinan, rotasi manajer terstruktur.
- Tingkat Kepuasan Kerja (Job Satisfaction Rate): melakukan survei kepuasan kerja secara anonim secara berkala dan menindaklanjuti hasil surveinya.
- Tingkat Keterlibatan Kerja (Job Involvement Rate): memberikan karyawan lebih banyak otonomi dalam pekerjaan mereka dan libatkan mereka dalam pengambilan keputusan yang relevan, menawarkan pengembangan keterampilan dan promosi internal.
- Keseimbangan Kerja dan Hidup (Attrition by Work Life Balance): mempertimbangkan opsi kerja fleksibel seperti jam kerja yang disesuaikan atau mendorong karyawan untuk mengambil cuti dan istirahat yang cukup, mawarkan program yang mendukung kesehatan fisik dan mental karyawan.
- Tingkat Opsi Saham (Attrition by Stock Option Level): meninjau kembali program opsi saham perusahaan, mekankan nilai jangka panjang dari kepemilikan saham perusahaan kepada karyawan.
- Tingkat Jabatan (Job Level Rate): memaastikan struktur jabatan yang jelas dan kompensasi yang kompetitif untuk setiap level, menyediakan jalur karir yang jelas bagi karyawan untuk naik level dalam organisasi.
- Bidang Pendidikan (Attrition by Education Field): menyelidiki lebih lanjut latar belakang pendidikan tertentu yang lebih cenderung meninggalkan perusahaan dan melakukan survei, mempertimbangkan strategi rekrutmen atau program pengembangan karir untuk kelompok pendidikan tertentu.

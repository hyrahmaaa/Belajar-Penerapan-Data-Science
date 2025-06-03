# Proyek Akhir: Menyelesaikan Permasalahan Perusahaan Edutech

## Business Understanding

Jaya Jaya Maju adalah perusahaan multinasional yang telah beroperasi sejak tahun 2000 dan memiliki lebih dari 1000 karyawan yang tersebar di seluruh Indonesia. Sebagai perusahaan yang cukup besar, Jaya Jaya Maju menghadapi tantangan dalam mengelola karyawan, yang tercermin dalam tingkat attrition rate yang tinggi, melebihi 10%. Situasi ini berpotensi mengganggu stabilitas operasional, meningkatkan biaya, dan mengurangi efektivitas organisasi. Manajemen departemen HR menyadari perlunya tindakan proaktif berbasis data untuk memahami dan mengatasi akar permasalahan ini.

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
- Bahasa Pemrograman: Python sudah terinstal secara default di Google Colab.
- Library yang digunakan seperti pada berkas requirement.txt.
- Konfigurasi: Konfigurasi biasanya dilakukan langsung dalam kode notebook.
- Akses Data: upload File menggunakan drive.mount() untuk mengakses file dari Google Drive.

## Business Dashboard

Dashboard ini dirancang untuk memberikan pemahaman yang mendalam tentang attrition karyawan dengan menampilkan metrik utama, tren, dan perbandingan berdasarkan berbagai faktor. Tujuannya adalah untuk membantu departemen HR mengidentifikasi area fokus untuk meningkatkan retensi karyawan. Adapun yang ditampilkan adalah faktor-faktor yang mempengaruhi attration berdasarkan analisis pada notebook.

🔗 URL : https://lookerstudio.google.com/reporting/1df393fd-e55c-43c5-a287-7e2feee0fa0d

## Conclusion

Proyek ini berhasil melakukan analisis mendalam terhadap data karyawan Jaya Jaya Maju untuk mengidentifikasi berbagai faktor yang berpotensi mempengaruhi tingginya tingkat attrition karyawan. Melalui eksplorasi data dan analisis statistik (seperti uji Chi-square dan t-test), korelasi dan perbedaan signifikan antara berbagai fitur karyawan  dengan status attrition berhasil diungkap.

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

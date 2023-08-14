# Submission1: Hosting Efisien Back-End Aplikasi Pencatatan Online dengan Google Kubernetes Engine

**Username dicoding:** mzfuadi97

## Masalah
Sebagai seorang Arsitek Google Cloud berpengalaman, Anda menghadapi tantangan di proyek dengan sebuah startup aplikasi pencatatan online yang menargetkan pasar Indonesia, terutama Jakarta. Aplikasi ini telah memiliki sisi Front-End yang berjalan sesuai harapan, tetapi Back-End masih belum dihosting. Meskipun source code Back-End tersedia di GitHub repository, perusahaan belum menentukan platform untuk hosting, satu-satunya permintaan adalah menggunakan container. Dalam peran Anda, Anda akan mencari solusi untuk mengatasi tantangan ini dan memutuskan untuk menggunakan Google Kubernetes Engine sebagai platform Back-End berdasarkan analisis yang dilakukan, terutama karena kemudahan pengelolaan container yang ditawarkan.


## Solusi
Setelah menganalisis berbagai opsi, solusi yang saya pilih adalah menggunakan layanan Google Kubernetes Engine (GKE) sebagai platform untuk hosting Back-End aplikasi pencatatan online. GKE menyediakan lingkungan yang efisien dan skalabel untuk menjalankan container, sehingga memudahkan pengelolaan, meningkatkan kinerja, dan siap menghadapi lonjakan pengguna saat peluncuran aplikasi. Dengan mengimplementasikan Back-End di GKE, perusahaan startup akan mendapatkan keuntungan dari fleksibilitas, skalabilitas, dan kemudahan manajemen yang ditawarkan oleh platform ini.


## Arsitektur Cloud
Berikut adalah arsitektur cloud pada GCP untuk mendeploy aplikasi:
![Architecture](https://github.com/mzfuadi97/CloudArch-Sub1/assets/70827786/807826aa-aca2-4aa1-9aa4-c0c317073ce5)

## Dokumentasi Deploy Aplikasi
### User Interface
![UI](https://github.com/mzfuadi97/CloudArch-Sub1/assets/70827786/9edfb769-7b7e-4e8e-b9ac-522246aafe9c)

### Load-Balancer
![LB](https://github.com/mzfuadi97/CloudArch-Sub1/assets/70827786/75fe99ae-fbd0-4e72-b0c9-a70633adfd4d)

### Permission
![Permission](https://github.com/mzfuadi97/CloudArch-Sub1/assets/70827786/d11e0c19-95f5-4f11-826c-96f35cd54ac2)

### IAM
![IAM](https://github.com/mzfuadi97/CloudArch-Sub1/assets/70827786/05d98de4-30c4-41d8-8b69-00e68d5ea11d)



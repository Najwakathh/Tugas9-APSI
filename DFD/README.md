## DFD Level 0

### Keterangan DFD Level 0

DFD Level 0 (Diagram Konteks) menggambarkan hubungan antara Sistem Informasi Adopsi Hewan Terlantar dengan entitas eksternal yang berinteraksi dengan sistem. Pada diagram ini terdapat empat aktor utama, yaitu Admin, Shelter, Adopter, dan Relawan.

- **Admin** mengelola data pengguna dan melihat laporan adopsi.
- **Shelter** mengelola data hewan serta melakukan verifikasi pengajuan adopsi.
- **Adopter** melakukan registrasi, melihat informasi hewan, dan mengajukan adopsi.
- **Relawan** memberikan data monitoring terkait kondisi hewan.

Sistem Informasi Adopsi Hewan Terlantar berfungsi sebagai pusat pengelolaan data yang menghubungkan seluruh aktor dalam proses adopsi hewan.

### Diagram DFD Level 0

![DFD Level 0](DFD/DFD-Level-0.jpeg)

## DFD Level 1

### Keterangan DFD Level 1

DFD Level 1 merupakan pengembangan dari DFD Level 0 yang menjelaskan proses-proses utama dalam Sistem Informasi Adopsi Hewan Terlantar.

Terdapat empat proses utama yaitu:

#### 1. Kelola User
Proses ini digunakan untuk mengelola data pengguna sistem, baik Admin, Shelter, Relawan, maupun Adopter. Data pengguna disimpan pada **D1 Data User**.

#### 2. Kelola Hewan
Proses ini digunakan oleh Shelter untuk menambahkan, mengubah, dan mengelola data hewan yang tersedia untuk diadopsi. Data hewan disimpan pada **D2 Data Hewan**.

#### 3. Pengajuan Adopsi
Proses ini digunakan oleh Adopter untuk mengajukan permohonan adopsi hewan. Data pengajuan akan disimpan pada **D3 Data Adopsi** dan selanjutnya diverifikasi oleh Shelter.

#### 4. Kelola Laporan
Proses ini digunakan oleh Admin untuk melihat dan mengelola laporan yang berasal dari data pengguna, data hewan, dan data adopsi.

### Data Store

| Kode | Nama Data Store | Fungsi |
|--------|--------|--------|
| D1 | Data User | Menyimpan data pengguna sistem |
| D2 | Data Hewan | Menyimpan data hewan yang tersedia untuk diadopsi |
| D3 | Data Adopsi | Menyimpan data pengajuan dan status adopsi |

### Diagram DFD Level 1

![DFD Level 1](DFD/DFD-Level-1.jpeg)

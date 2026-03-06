# Membuat Billing Alert di AWS untuk menghindari kelebihan alokasi dana

1. Menu dashboar AWS kita pilih Billing Prefence untuk mengaktifkan Alert
    - Masuk Menu billing and cost management
    - pilih menu billing preferences paling bawah
    - pilih menu alert preference klik edit
    - isi email ceklis receive
    - klik Update
    ![alt text](image.png)

2. menu CLoudwath
    - all service
    - cloudWatch
    ![alt text](image-1.png)

3. Create Alarm
![alt text](image-2.png)
    - Buat Alarm
    - Pastikan region ada di US N Virginia
    - klik Metric
    - klik menu billing
    - pilih total perkiraan Biaya
    - ceklis Mata uang USD
    - Pilih Matrik
    - beri Nama metrik
    - scroll bawah pilih USD $
    - next (konfigurasi)
    - creat new topic => NIM_BillingAlert => Create
    - Kirim Pemberitahuan ke ... (NIM_BillingAlert) 
    ![alt text](image-3.png)
next
    - alarm name
    ![alt text](image-4.png)
next
    ![alt text](image-5.png)
    - buat alarm
    - selesai
    ![alt text](image-6.png)
Buka inbox/spam email dari AWS kemudian Klik Confirm.
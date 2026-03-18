1. memilih tools migrasi file, misal kita akan gunakan filezila
    - untuh dan migrasi https://filezilla-project.org/download.php?type=client
    - buka filezila
    ![alt text](image.png)
    - aktifkan server lokal
    ![alt text](image-1.png)
    - Kembali ke filezilla
    - klik file
    - klik site meneger
    - klik new site
    - berikan nama nim_server
    ![alt text](image-2.png)
    - logon type
    ![alt text](image-3.png)
2. pada dashboard utama filezila
    ![alt text](image-4.png)
    - panel kiri file local
    ![alt text](image-5.png)
    - panel kanan pilih server aws ec2
    ![alt text](image-6.png)
3. Arahkan directory cloud (Panel kanan) ke Folder web server services area
    ![alt text](image-7.png)
4. cara menanangani permision untuk edit code
    - massuk ke putty aktifkan
    - ubah kepemilikan folder
    /var/www/html
    - sintaks sudo chown -R
    ubuntu:ubuntu var/www/html
5. ubah tampilannya 
    ![alt text](image-10.png)
6. lalu berhasil save index html
    ![alt text](image-9.png)
7. buka link nya
    ![alt text](image-11.png)

# REMOTE INSTANCE


1. download putty
   [![1772423000348](https://github.com/Raflysaputra20/materi-kuliah-smt-6/raw/main/PERTEMUAN%202/image/RemoteSSH/1772423000348.png)](https://github.com/Raflysaputra20/materi-kuliah-smt-6/blob/main/PERTEMUAN%202/image/RemoteSSH/1772423000348.png)

[![1772423193067](https://github.com/Raflysaputra20/materi-kuliah-smt-6/raw/main/PERTEMUAN%202/image/RemoteSSH/1772423193067.png)](https://github.com/Raflysaputra20/materi-kuliah-smt-6/blob/main/PERTEMUAN%202/image/RemoteSSH/1772423193067.png)

2. convert file public key daro .pem menjadi .ppk di putty
   > buka putty gen load file save as .ppk
   >

[![1772423585483](https://github.com/Raflysaputra20/materi-kuliah-smt-6/raw/main/PERTEMUAN%202/image/RemoteSSH/1772423585483.png)](https://github.com/Raflysaputra20/materi-kuliah-smt-6/blob/main/PERTEMUAN%202/image/RemoteSSH/1772423585483.png)

3. Set up putty untuk remote ssh

   > buka apps putty isi ip public isi port SSH load file.ppl (klik -> SSH -> AUTH -> CREDENTIAL -> upload .ppk kita) lalu kembali ke dalam session LALU SAVE klik open masukan username sesuai instance
   >

   [![1772424444863](https://github.com/Raflysaputra20/materi-kuliah-smt-6/raw/main/PERTEMUAN%202/image/RemoteSSH/1772424444863.png)](https://github.com/Raflysaputra20/materi-kuliah-smt-6/blob/main/PERTEMUAN%202/image/RemoteSSH/1772424444863.png)
   [![1772425445779](https://github.com/Raflysaputra20/materi-kuliah-smt-6/raw/main/PERTEMUAN%202/image/RemoteSSH/1772425445779.png)](https://github.com/Raflysaputra20/materi-kuliah-smt-6/blob/main/PERTEMUAN%202/image/RemoteSSH/1772425445779.png)
   [![1772425331999](https://github.com/Raflysaputra20/materi-kuliah-smt-6/raw/main/PERTEMUAN%202/image/RemoteSSH/1772425331999.png)](https://github.com/Raflysaputra20/materi-kuliah-smt-6/blob/main/PERTEMUAN%202/image/RemoteSSH/1772425331999.png)
4. sudo apt-get update sudo apt-get upgrade jika ada versi baru [![1772425476851](https://github.com/Raflysaputra20/materi-kuliah-smt-6/raw/main/PERTEMUAN%202/image/RemoteSSH/1772425476851.png)](https://github.com/Raflysaputra20/materi-kuliah-smt-6/blob/main/PERTEMUAN%202/image/RemoteSSH/1772425476851.png)
5. pembuktian remote ssh secara visual

   > copy public ip address instance paste ke browser [![1772425731362](https://github.com/Raflysaputra20/materi-kuliah-smt-6/raw/main/PERTEMUAN%202/image/RemoteSSH/1772425731362.png)](https://github.com/Raflysaputra20/materi-kuliah-smt-6/blob/main/PERTEMUAN%202/image/RemoteSSH/1772425731362.png) install web server seperti apache/nginx sudo apt install ketika sudah install reload browser nya [![1772425917850](https://github.com/Raflysaputra20/materi-kuliah-smt-6/raw/main/PERTEMUAN%202/image/RemoteSSH/1772425917850.png)](https://github.com/Raflysaputra20/materi-kuliah-smt-6/blob/main/PERTEMUAN%202/image/RemoteSSH/1772425917850.png)
   >
6. matikan instance agar tidak kena tagihan

   > sudo shutdown now
   >

[![1772426221412](https://github.com/Raflysaputra20/materi-kuliah-smt-6/raw/main/PERTEMUAN%202/image/RemoteSSH/1772426221412.png)](https://github.com/Raflysaputra20/materi-kuliah-smt-6/blob/main/PERTEMUAN%202/image/RemoteSSH/1772426221412.png)

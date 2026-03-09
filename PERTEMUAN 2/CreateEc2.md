# membuat ec2 / instance / vm

1. pilih menu all services lalu cari ec2

![1772421171488](image/CreateEc2/1772421171488.png)

2. di dalam menu EC2 kita pilih instance

![1772421228949](image/CreateEc2/1772421228949.png)

3. di dalam instance kita pilih launc instance

![1772421264562](image/CreateEc2/1772421264562.png)

4. Beri nama Instance kita dengan format (NIM MASING MASING)2388010028

![1772421336224](image/CreateEc2/1772421336224.png)

5. kita pilih os sever untuk iinstance (ubuntu)

![1772422052593](image/CreateEc2/1772422052593.png)

6. pilih resource t3.micro

![1772422156336](image/CreateEc2/1772422156336.png)

7. membuat key pair, pilih new key pair, isi nama key, pilih rsa, format file.pem, create key pair

![1772422299453](image/CreateEc2/1772422299453.png)

8. kemudian setting kepijakan keamanan / security
   -> Allow SSH = artinya membolehkan remote SSH dari luar
   -> Allow HTTPS = artinya instance bisa di akses dari protocol HTTPS
   -> ALLOW HTTP = Instance bisa di akses dari protocol HTTP

![1772422615031](image/CreateEc2/1772422615031.png)

9. Selesai itu pencet launc instance

![1772422772075](image/CreateEc2/1772422772075.png)

10. pastikan launch instance nya sukses

![1772422845634](image/CreateEc2/1772422845634.png)

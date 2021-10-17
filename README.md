## Latihan 1
## Tutorial Github



### Cara Membuat Akun Github
- Buka [Github](https://github.com)<p>
- Jika Belum mendaftar klik Regiter/Sign up <p>
- Jika sudah mendaftar silahkan klik Masuk/Sign in <p>

![image](https://user-images.githubusercontent.com/92609633/137633546-8773fce8-fafe-4267-b5a4-47a106bcfa57.png)

- Jika sudah Sign in muncul tampilan seperti tampilan dibawah ini<p>
- Kemudian klik Create repository<p>

![image](https://user-images.githubusercontent.com/92609633/137633663-cc30ad29-378c-4e58-9a5e-89d3f0c28ce4.png)


- kemudian isi Repository name<p>
- deskripsi (optional) boleh di isi boleh tidak<p>
- Ceklist Add a README file<p>
- kemudian klik Create repository seperti gambar dibawah<p>

![image](https://user-images.githubusercontent.com/92609633/137633758-dc3c5691-5ef8-482d-98a7-2655bf2dd222.png)
- Setelah muncul tampilan seperti gambar dibawah<p>
- Klik Code kemudian kalian bisa pilih HTTPS, SSH, Github, atau CLI. Lalu copy link yang tersedia<p>

![image](https://user-images.githubusercontent.com/92609633/137633830-3971c829-104f-46fb-84a8-d5c407449b35.png)

- Jika kalian belum instal git-scm silahkan, instal terlebih dahulu (skip saja jika sudah instal)
- [Git-scm](https://git-scm.com/) klik Download for Windows
- Jika sudah didownload silahkan instal seperti biasa, klik next saja

![image](https://user-images.githubusercontent.com/92609633/137633916-f4fe7e4d-1cb3-4f5b-b8d6-552d90ae59ba.png)
- Buat satu folder kosong untuk directory kerja
- Kemudian klik kanan pada mouse pilih "Git Bash Here"

![image](https://user-images.githubusercontent.com/92609633/137633982-ce65f6cf-2400-403d-a78f-7be8fbf4f3c8.png)

- Kemudian copy link HTTPS Github kalian
```bash
> git clone 'link Github'
```
- Tekan Enter pada keyboard

![Gambar 7](ssan/7.png)

- Kemudian muncul file README.md di file kalian
- Klik kanan pada mouse, lalu pilih open with pilih "Visual Studio Code"
- Jika kalian belum instal "Visual Studio Code" kalian bisa download [VCS](https://code.visualstudio.com/)
- Tutorial cara instal [Video instalasi VCS](https://www.youtube.com/watch?v=OSmaWPSgvTQ)

![Gambar 8](ssan/8.png)

Setelah terbuka Visual Code Studio, pastikan kalian koding di file README.md</p>
- Edit file README.md, lalu jangan lupa  di save (ctrl+s)
- Setelah itu buka Git Bash yang sebelumnya
```bash
> git add README.md
> git commit -m "Dekripsi"
> git push -u origin main
```

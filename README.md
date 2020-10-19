#latihan1

Membuat Repository Lokal

1. Pertama buka direktori aktif untuk membuat project git
2. klik kanan pada direktory aktif tersebut, dan pilih menu Git Bash,
	sehingga muncul git bash command
![langkah awal](https://user-images.githubusercontent.com/73072514/96452452-3cf91e00-1243-11eb-9b11-eaa9d19482c3.png)

3. lalu buat direktori untuk project baru dengan perintah 
	mkdir Latihan_VCS
4. lalu masuk ke direktori procect yang akan di buat dengan perintah
	cd Latihan_VCS
![langkah kedua](https://user-images.githubusercontent.com/73072514/96452731-a842f000-1243-11eb-92fe-1113419a50fc.png)

5. setelah itu jalankan perintah 
	git init
![langkah ketiga](https://user-images.githubusercontent.com/73072514/96452864-df190600-1243-11eb-9e35-48b8ce9ebb5e.png)

6. dengan terbentuknya satu direktori hidden dengan nama .git pada direktori tersebut, semua perubahan pada working directory
	akan disimpan.

Menambahkan file baru ke repository

1. buka text editor untuk membuat file, dan simpan filenya di direktori aktif(repository)
2. buat file bernama README.md(text file) dengan cara
   echo "# LatihanVCS">> README.md
3. Untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah 
	git add README.md
![langkah keempat](https://user-images.githubusercontent.com/73072514/96453031-1e475700-1244-11eb-9234-abe15a20061d.png)

Menyimpan Perubahan ke Database
1. Untuk menyimpan perubahan yang ada kedalam database repository
   local, gunakan perintah
    git commit -m “File Bahasa Pemograman”
![langkah kelima](https://user-images.githubusercontent.com/73072514/96453241-5fd80200-1244-11eb-8972-55fc6d63091c.png)

	Membuat Repository Server

1. Server yang digunakan adalah http://github.com
2. Buat akun github
3. Pada laman github, klik tombol start a project, atau dari menu (icon +) klik New Repository
4. Isi nama repositorynya lalu klik tombol create repository
![langkah 2](https://user-images.githubusercontent.com/73072514/96453366-8eee7380-1244-11eb-8a7b-d90159cd7308.png)

Menambahkan Remote Repository

1. Remote Repository merupakan repository server yang akan
   digunakan untuk menyimpan setiap perubahan pada local repository,
   sehingga dapat diakses oleh banyak user. 
2. Untuk menambahkan remote repository server, gunakan perintah
    git remote add origin [url]
![langkah keenam](https://user-images.githubusercontent.com/73072514/96453569-d8d75980-1244-11eb-9256-e1f1cdf6ea32.png)

Mengirim Ke Server

1. Untuk mengirim perubahan pada local repository ke server gunakan perintah git push dengan cara
    git push -u origin master
![langkah 7](https://user-images.githubusercontent.com/73072514/96453729-163be700-1245-11eb-843b-b8e6e21eee7a.png)

2. Perintah ini akan meminta memasukkan username dan password pada akun github.com
3. untuk melihat hasilnya buka laman github.com, arahkan pada repositorinya.

Clone Repository

1. clone repository, pada dasarnya adalah meng-copy repository server
   dan secara otomatis membuat satu direktory sesuai dengan nama
   repositorynya (working directory).Untuk melakukan cloning, gunakan perintah git clone [url]
![langkah 8](https://user-images.githubusercontent.com/73072514/96453808-3370b580-1245-11eb-9965-1eea4abaab82.png)

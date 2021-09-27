# Langkah Membuat Repo
1. Click tanda + pada bagian kanan atas github dan pilih New Repository 


![contoh](https://github.com/zimera-systems/petunjuk-git-github/blob/main/images/03/03-01-new-repo.png)

2. isi nama dan keterangan untuk reponya lalu pilih reponya private atau public
3. click create repository dan repo anda langsung terbuat

repo yang dalap disimpan dan dikelola dalam file lokal, untuk melakukanya user perlu melakukan CLONING
## Langkah Untuk Clone Repo

Proses Clone adalah proses menduplikasi repo yang berada di GitHub kedalam komputer lokal untuk melakukan cloning lakukan perintah berikut:
1. buka gitBash
2. Login kedalam akun anda(anda hanya perlu login sekali)

$ git config --global user.name "Nama Anda di GitHub"

$ git config --global user.email email@domain.tld

untuk mengecek :

$ git config --list

3. Masukkan command dibawah ini(untuk link anda hanya perlu mencopy link reponya):

$ git clone https://github.com/username/nama-repo

lalu akan terdapat direktory dari repo tersebut yang isinya sama dengan di Github

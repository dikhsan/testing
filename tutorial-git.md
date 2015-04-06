# Penggunaan Git sehari-hari #

## Istilah x##

* working folder : folder tempat file-file kita berada
* Staging area : wilayah (virtual) untuk perubahan yang akan dicommit
* Commit area / local repository : penyimpanan 

## Membuat Repository baru di local ##
* Perintah : `git init <nama-folder>`
* Contoh : git init blog-endy
* Hasil : membuat folder baru

## Melihat isi stagin area ##

* Perintah : `git diff --staged`

# Melihat History Perubahan

* Perintah : `git log`
* Opsi : 
	* `--online` : menampilkan satu commit per baris (lebih ringkas)
	* `--graph` : menampilkan rantai perubahan
	
* output :
	......
	* ba2c211 commit kedua
	* 77619c2 commit pertama hahhaha
	
	
	
Template Naskah Skripsi Menggunakan LaTeX
==========================================

Template Naskah Skripsi dengan typesetting LaTeX untuk Jurusan Ilmu Komputer Universitas Negeri Semarang. Template ini merupakan hasil modifikasi dari versi Departemen Teknik Elektro (Guntur) dan pak Pekik Nurwantoro (FMIPA UGM) dan mas Yohan (T Elektro UGM 2008).

Semoga bermanfaat. Anda sangat dibolehkan untuk turut berkontribusi dalam project ini dengan *Fork*, *Pull Request*, *Create New Issue*, atau turut menjadi kontributor repo ini.

Terimakasih.

Download
--------
Silakan download di [https://github.com/ajienator/template-skripsi-latex-ilkom](https://github.com/ajienator/template-skripsi-latex-ilkom).

Quick Start
-----------
1. Siapkan LaTeX environment pada komputer anda, begitu pula LaTeX editornya. File yang diperlukan biasanya berukuran besar, jadi siapkan koneksi internet yang lancar jaya.
	- [*Windows*](https://www.google.com/search?q=windows+setup+latex&oq=windows+setup+latex&aqs=chrome..69i57.6207j0j7&sourceid=chrome&es_sm=91&ie=UTF-8)
	- [*Linux*](https://www.google.com/search?q=windows+setup+latex&oq=windows+setup+latex&aqs=chrome..69i57.6207j0j7&sourceid=chrome&es_sm=91&ie=UTF-8#q=linux+setup+latex)
	- [*Mac OS X*](https://www.google.com/search?q=windows+setup+latex&oq=windows+setup+latex&aqs=chrome..69i57.6207j0j7&sourceid=chrome&es_sm=91&ie=UTF-8#q=mac+setup+latex)
	- [Editor LaTeX di web](https://www.overleaf.com/) bisa dengan overleaf.com. Dengan ini kita tidak usah repot siapkan LaTeX environment.

2. *Clone* repository ini dengan melakukan [unduh](https://github.com/ajienator/template-skripsi-latex-ilkom) repository ini (cara ini lebih mudah).
3. Mulai tulis naskah anda, keterangan dari masing-masing file dalam template ini ada di bawah.
4. Pertamakali pakai LaTeX? Butuh bantuan? Pergunakanlah Google dengan baik dan bijak. Saya bantu:
	- [Bahasa Indonesia](https://www.google.com/search?q=tutorial+menggunakan+latex&oq=tutorial+menggunakan+latex&aqs=chrome..69i57j0.3219j0j7&sourceid=chrome&es_sm=91&ie=UTF-8)
	- [English](https://www.google.com/search?q=latex+tutorial&oq=latex+tutorial&aqs=chrome..69i57j69i65l3j69i60l2.1884j0j7&sourceid=chrome&es_sm=91&ie=UTF-8)

Minimum Requirements
--------------------

* texlive-latex-extra
* texlive-lang-other (Bahasa Indonesia)
* texlive-fonts-recommended (Font khusus)
* texlive-bibtex-extra (Sitasi dan Bibliografi)

Contents
--------
Berikut penjelasan dari file-file utama dalam template ini. File lain yang tidak tercantum hanya pelengkap dalam repository ini.

		template-skripsi-latex-ilkom/
			├── image/
			│	   ├── unnes.png
			│	   ├── wsn.png
			│	   └── Screen Shot 2019-09-06 at 8.27.56 AM.png
			├── mottopersembahan.tex
			├── prakata.tex
			├── abstrak.tex
			├── bab1.tex
			├── bab2.tex
			├── bab3.tex
			├── bab4.tex
			├── bab5.tex
			├── collection.bib
			├── lampiran.tex
			├── main.pdf
			├── main.tex
			├── natnotes.pdf
			├── UNNESapa.bst
			└── skripsi.cls


### mottopersembahan.tex
File ini berisikan tentang motto dan persembahan dari penulis skripsi.

### prakata.tex
File ini berisikan tentang prakata dari penulis skripsi.

### abstrak.tex
File abstrak.tx berisikan tentang abstrak skripsi.

### lampiran.tex
File lampiran.tx digunakan untuk menuliskan lampiran skripsi.

### bab1.tex - bab5.tex
Konten utama dari skripsi, mulai dari BAB I (pendahuluan) sampe BAB V (kesimpulan). Silakan disesuaikan dengan jumlah bab skripsi anda, hapus file yang tidak perlu atau tambahkan file baru untuk bab baru.

### collection.bib
File yang berisi daftar referensi-referensi yang anda gunakan dalam skripsi. File ini penting guna menyusun daftar pustaka anda. Dengan file ini menyusun daftar pustaka menjadi sangat sangat sangat mudah.

File ini adalah hasil export dari aplikasi *reference management* seperti Mendeley, Zotero, EndNote, dll. Biasakan mengorganisir referensi skripsi anda menggunakan aplikasi *reference management*.

### main.tex
File ini main.tex adalah file utama (kepala) dari template. Berisi informasi-informasi dasar, seperti judul skripsi, nama penulis, nama pembimbing, dll.

### main.pdf
File ini adalah skripsi anda dalam bentuk matang. Sudah rapi dan dapat dicetak untuk dijilid. File ini di-*generate* secara otomatis menggunakan LaTeX.

### natnotes.pdf
File ini berisikan petunjuk untuk melakukan sitasi

### UNNESapa.bst
File UNNESapa.bst adalah library yg digunakan oleh template untuk membuat referensi.

### skripsi.cls
File yang berisi aturan-aturan format skripsi. Contoh, format cover, halaman pengesahan, daftar isi, daftar pustaka, dan konten skripsi.

Jika anda ingin memodifikasi template skripsi ini, ubahlah file *skripsi.cls*.

### image/
Masukkan gambar-gambar pada skripsi anda di folder ini. Gambar default: unnes.png (dipakai di cover) dan wsn.png (hanya dipakai di template awal, silakan dihapus jika tidak diperlukan). Screen Shot 2019-09-06 at 8.27.56 AM.png merupakan setting dari texmaker, supaya bibliografi muncul saat di lakukan kompilasi.
			

Lisensi
-------
Template sripsi ini dilisensikan dengan menggunakan [lisensi MIT](https://raw.githubusercontent.com/gtrdp/template-skripsi/master/LICENSE).

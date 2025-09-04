# AI_NLP-TwitterDatasetClassification

Salman Hanif - 13523056

### Deskripsi Masalah
Diberi suatu dataset yang berisi 4.403 tweet dari Indonesia yang sudah diberi label lima jenis emosi :

1. Love
2. Anger
3. Sadness
4. Joy
5. Fear

### Format Data
Setiap baris terdiri dari sebuah twit dan label emosinya masing-masing yang dipisahkan oleh titik koma (,). Baris pertama adalah judul. Untuk twit dengan tanda koma (,) di dalam teks, terdapat tanda kutip (" ") untuk menghindari pemisahan kolom.
Tweet dalam kumpulan data ini telah diproses sebelumnya menggunakan kriteria berikut:
1. Penyebutan nama pengguna (@) telah diganti dengan istilah [USERNAME]
2. URL/hyperlink (http://... atau https://...) telah diganti dengan istilah [URL]
3. Nomor sensitif, seperti nomor telepon, nomor faktur, dan nomor pelacakan kurir telah diganti dengan istilah [SENSITIVE-NO]

### Pendekatan untuk menyelesaikan masalah
Saya akan menggunakan pretrained-model indoBERTweet yang merupakan model yang dilatih menggunakan tweet berbahasa indonesia

Jalankan notebook untuk melihat proses, bisa dijalankan dengan google colab/di lokal. Sesuaikan nama variabel dan siapkan token WANDB untuk proses pelatihan model

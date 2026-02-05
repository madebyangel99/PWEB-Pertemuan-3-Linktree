# PWEB-pertemuan-3-Linktree-

#Bagian index.html

Pada bagian awal di deklrasi untuk html dengan bahasa inggris. Pada bagian head terdapat beberapa kode, seperti kode agar browser bisa membaca simbol dan huruf, ada juga kode yang membuat browser itu menyesuaikan ukuran device dari yang mengakses. 

Kemudian kode <title>Angel's Profile</title> untuk membuat tulisan yang muncul di tab browser menjadi Angel's Profile. Terdapat beberapa macam link yang mengikuti dibawahnya, seperti kode dari web font yang merupakan kode untuk menambahkan jenis font baru diluar font default atau font yang telah disiapkan. Kemudian ada link untuk menyambungkan file html dengan file style.css yang terpisah. Fungsi dari css sendiri adalah tempat mempercantik atau kulit dari suatu website dimana file html merupakan tulangnya. Dan link terakhir yang dipakai ada <script src="https://kit.fontawesome.com/3e0754edb5.js" crossorigin="anonymous"></script> agar dapat memunculkan logo-logo yang dibutuhkan.

Masuk bagian body, semua isi pertama dibungkus dalam div dengan class container. Untuk kelas profil berisi kode  untuk menautkan gambar yang sudah ada di dalam folder yang sama sebelumnya dengan menambahkan kata foto profil sebagai alt. Kemudian dengan judul utama profil ini dalam h1 yang berisi sapaan.

Kemudian masuk ke class socials yang disinilah akan dimasukkan info-info sosial media yang dimiliki, seperti contoh <a target="_blank" href="https://www.instagram.com/arahmatun.a?igsh=bzZpeG5uZXY3ZHBj">
            <div class="sosmed Playpen"><i class="fa-brands fa-square-instagram"></i>Instagram</div>
            </a>
dengan kode <a> untuk membuat link kemudian dengan target="_blank" agar link terbuka di tab baru jika di klik, lalu kode href berisi link tujuan jika user mengklik button sosial media nantinya. Bagian ini berada dalam class sosmed dan juga font yang sebelumnya sudah di set juga dipanggil, yang terakhir digunakan kode <i> untuk menggunakan ikon dari font awesome. Begitu seterusnya untuk sosial media facebook, x, dan juga github.

#Bagian style.css
Kode diawal untuk mengatur agar jarak margin dan padding menjadi 0. Lalu masuk bagian body untuk mengatur background dan posisi konten dari website agar tetap di tengah. Kemudian ada section untuk kelas profil fotonya, disini saya menggunakan foto 4:3 jadi ukuran frame mengikuti foto, dengan border radius untuk memberi efek lengkungan sekitar frame foto.

Kemudian juga terdapat kode untuk mengatur kelas profil h1 atau judulnya dengan memanfaatkan fungsi warna, font size, yang juga diberikan background color agar tulisan dapat terbaca jelas, yang dipadukan dengan kode padding, dan juga border-radius.

kelas untuk font baru yang kita tambah juga dapat kita set untuk ukuran font yang dimau diluar dari kode bawaan font. Kemudian masuk ke kelas container, terdapat flex-direction: column; yang membuat elemen tersusun rapi dari atas ke bawah dengan kode gap untuk memberi jarak antara profil dan tombol sosmed.

Kemudian ada kelas socials yang berisi untuk mengatur font di dalam buttonnya. Lalu kode untuk kelas socials a yang berguna untuk menghilangkan underline dibawah link yang telah kita masukkan sehingga link akan terlihat seperti tombol di dalam kotak. Kemudian ada kelas socials h1 untuk mengatur warna font dari judul dan juga sizenya.

Masuk ke bagian button, terdapat kelas sosmed yang berisi untuk mengatur background color, position relative untuk mengatur agar ikon disa diatur posisinya, border radius agar buttonnya bisa lebih smooth, dll. Kemudian ada kode untuk kelas sosmed khusus hover agar memberi efek ketika button akan ditekan dengan transition agar perubahan warnanya bertahap. Yang terakhir kode kelas sosmed i untuk mengatur logo, dengan posisi absolute, left: 8px yang membuat ikon akan menempel di sisi kiri tombol. Untuk mengatur ukuran ikon bisa digunakan kode untuk mengatur font size.

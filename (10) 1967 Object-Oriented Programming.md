# __1967 Object-Oriented Programming__
### __Ole-Johan Dahl__ (1931–2002), __Kristen Nygaard__ (1926–2002)
___

Program pertama melakukan tugas penting tetapi berulang, seperti mencetak tabel artileri, melakukan perhitungan untuk senjata nuklir, dan memecahkan kode. Program-program ini terdiri dari loop yang mengeksekusi fungsi matematika yang sama berulang-ulang, setiap kali dengan parameter yang sedikit berbeda. Komputer bisnis awal melakukan perhitungan berulang serupa pada buku besar bisnis dan catatan lainnya, berulang kali membaca data dari disk, memprosesnya, dan menyimpan hasilnya.

Di Pusat Komputasi Norwegia, profesor Ole-Johan Dahl dan Kristen Nygaard ingin menggunakan komputer mereka untuk mensimulasikan sistem fisik, khususnya simulasi kapal, dan di sini mereka menemukan bahasa pemrograman yang dikembangkan untuk memungkinkan tugas sederhana dan berulang menjadi kurang. Jadi mereka mengembangkan cara baru untuk memprogram dan bahasa komputer baru, yang mereka sebut SIMULA 67.

Ide kunci dari SIMULA adalah untuk data yang mewakili objek fisik untuk digabungkan bersama dengan kode komputer untuk bertindak pada data tersebut. Misalnya, simulasi lalu lintas mungkin memiliki tipe data yang disebut CAR yang mungkin memiliki variabel untuk lokasi dan kecepatan mobil. Sebuah fungsi khusus mungkin menangani perilaku mobil ketika bertemu lampu lalu lintas. SIMULA mengacu pada masing-masing tipe data ini sebagai "kelas." Kelas berbeda yang disebut TRUCK mungkin mewakili truk. Ide kunci lainnya adalah pewarisan, yang memungkinkan kelas dengan karakteristik bersama untuk diatur dalam hierarki. Jadi TRUCK dan CAR mungkin mewarisi dari kelas abstrak yang disebut KENDARAAN, yang dengan sendirinya mungkin mewarisi dari kelas abstrak lain yang disebut OBJEK.

Saat ini, gaya pemrograman SIMULA disebut pemrograman berorientasi objek, dan SIMULA 67 diakui sebagai bahasa berorientasi objek pertama. Ternyata ide SIMULA bagus untuk lebih dari sekadar menulis simulasi: hampir setiap bahasa komputer modern berorientasi objek, termasuk C++, Java, Python, dan Go, dan saat ini pemrograman berorientasi objek adalah cara yang dominan perangkat lunak ditulis.

*Pemrogram membuat program berorientasi objek dengan merancang kelas objek yang mewakili objek fisik, proses, atau pengaturan data. Mereka kemudian menghubungkan objek dengan kode.*
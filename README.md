Muhammad Navis Raditya Riayatsyah
2106717291 
Tutorial 8

**I. Pembuatan Particle Environment**

**Langkah Pertama: Menambahkan Particle Hujan Abu**
- Buka template Level 1 di Godot.
- Tambahkan "Particles2D" ke level.
  
**Penambahan Bahan untuk Particle**
- Godot akan minta kita tambahkan Material ke Particles2D.
- Pergi ke "Process Material" di tab inspector, tambahkan "ParticlesMaterial" baru.

**Mengatur Particle**
- Klik Particles2D dan atur "Amount" jadi 500, "Lifetime" jadi 4, dan "Speed Scale" jadi 0.5.
  
**Mengatur Warna dan Gerakan Particle**
- Ubah warna jadi abu-abu dan atur kecepatan serta arah gerakan.
  
**Penyesuaian Lainnya**
- Putar particle agar menghadap kiri dan pastikan terlihat di layar.

**Uji Coba dan Penyesuaian**
- Jalankan permainan dan lihat apakah hujan abu terlihat dengan baik.

**II. Pembuatan Particle Trail**

**Menambahkan Jejak Particle untuk Pemain**
- Buka scene "player.tscn".
- Tambahkan Particles2D dan atur material serta tekstur particle.

**Mengatur Perilaku dan Penampilan Particle**
- Atur jumlah dan waktu hidup particle, serta bagaimana mereka muncul.

**Mengatur Aktivasi Particle**
- Gunakan script untuk mengontrol kapan particle muncul, bergantung pada aksi pemain.

**III. Menyeimbangkan Permainan**

**Menyeimbangkan Tingkat Spawn**
- Tambahkan scene "Spawner.tscn" ke Level 1.
- Atur nilai "Spawn Rate" agar permainan tidak terlalu mudah atau terlalu sulit.

**Pengujian dan Penyesuaian**
- Jalankan permainan dan pastikan tingkat kesulitan terasa pas.



**Team Project Balancing**
1. Terdapat beberapa hal positif yang berhasil diidentifikasi berdasarkan perilaku dan timbal balik dari pemain ketika sedang melakukan _testing_ terhadap permainan yang sedang kelompok kami kembangkan, antara lain:
   - Pemain merasa penasaran dengan jalan cerita ketika mencoba permainan
   - Pemain merasa santai ketika mencoba permainan
   - Pemain merasa bahwa permainan ini memiliki unsur horor dan dapat membawa perasaan claustrophobic

2. Terdapat beberapa hal negatif yang berhasil diidentifikasi berdasarkan perilaku dan timbal balik dari pemain ketika sedang melakukan _testing_ terhadap permainan yang sedang kelompok kami kembangkan, antara lain:
   - UI yang tidak terbaca karena terlalu kecil dan memiliki kontras yang kurang baik
   - Pemain tidak merasakan urgensi untuk melakukan objective utama
   - Objective yang tidak begitu jelas

3. Ya, pemain merasa bahwa di setiap level tidak ada urgensi untuk melakukan objective utama dan pemain kebingungan harus melakukan apa

4 dan 5. Beberapa hal yang ingin di-polish dan balance:
   - Perbaikan kontras pada UI dan scaling agar lebih terbaca; Untuk object yang interaktif, akan diberikan kotak sebagai dialogue box unutk UI sehingga pemain dapat mengetahui bahwa pemain dapat berinteraksi dengan object tersebut. Selain itu jika waktunya cukup, posisi munculnya dialogue box ingin dibedakan sehingga kemunculan dialogue box tidak akan menghalangi pengalaman bermain.
   - Mengadakan tutorial agar pemain bisa belajar fitur-fitur utama yang ada pada permainan; Diberikan sebuah dialogue box ketika pemain spawn untuk pertama kalinya di Scene awal yang menjelaskan cara bermain.
   - Melakukan balancing terkait beberapa obstacle pendukung objective agar pemain dapat merasakan urgensi untuk melakukan main objective; Ada beberapa hal yang ingin dilakukan, antara lain:
     a. [Level 1] Memperbaiki UX agar pemain dapat memasukkan kode pada vending machine tanpa harus menggunakan mouse terlebih dahulu. Mematikan input pada box kode ketika pemain ingin bergerak serta menutup box tersebut ketika pemain sudah tidak ingin melakukan input kode yang telah ditemukan.
     b. [Level 2] Melakukan balancing terhadap object kucing yang menjadi obstacle pendukung objective utama agar bisa mengejar pemain terus-terusan
     c. [Level 3] Membuat object musuh sebagai obstacle menjadi lebih nampak sehingga pemain merasa dikejar dan merasakan urgensi untuk menyelesaikan objective utama pada level tersebut jika ingin menyelesaikan permainan.

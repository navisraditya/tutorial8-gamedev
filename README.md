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

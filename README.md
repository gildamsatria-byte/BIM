1. Multi-lantai dengan tinggi antar-lantai

Kartu Level / Lantai di atas menampilkan semua level (Lantai 2 di atas, Lantai 1 di bawah — seperti susunan gedung).
Setiap level punya nama dan tinggi (floor-to-floor) yang bisa diedit langsung.
Klik Aktifkan untuk memilih level yang sedang digambar/diedit di denah 2D.
Bagian pentingnya: elevasi tiap level dihitung otomatis dari akumulasi tinggi level di bawahnya. Jadi kalau Anda ubah tinggi Lantai 1 dari 3,5 m ke 4 m, Lantai 2 dan semua elemennya otomatis naik — tidak perlu digeser manual.
Tombol + Tambah lantai menambah level baru di atas. Tombol Hapus pada level menghapus level beserta seluruh elemennya (dengan konfirmasi).
Ada opsi tampilkan level di bawah sebagai referensi: dinding level di bawahnya muncul samar (garis putus-putus) di denah, membantu menyelaraskan dinding antar-lantai — seperti "underlay" di Revit.
Model 3D menampilkan semua lantai sekaligus, bertumpuk sesuai elevasi.

2. Informasi pada elemen

Pilih elemen apa pun (dinding, pintu, jendela, lantai, atap) di mode Pilih, lalu di bawah properti angka akan muncul kolom Nama, Material, Catatan, dan properti kustom (pasangan nama-nilai bebas, bisa tambah sebanyak yang diinginkan).
Kartu baru Daftar elemen & informasi merangkum semua elemen dari semua lantai beserta nama dan materialnya.
Semua informasi ini ikut terekspor ke IFC: Material menjadi IfcMaterial yang terhubung ke elemen, sementara Catatan dan properti kustom menjadi IfcPropertySet bernama MiniBIM_Properties.


WebGL Water: Simulasi Air Realistis Berbasis Web oleh Evan Wallace
==================================================================

*WebGL Water* adalah sebuah demo visual interaktif yang menunjukkan kemampuan simulasi air secara real-time menggunakan teknologi WebGL. Dibuat oleh Evan Wallace, demo ini memanfaatkan berbagai fitur grafis canggih untuk menciptakan efek air yang sangat realistis, lengkap dengan pantulan, pembiasan, dan bayangan yang halus.

Namun, untuk dapat menjalankan demo ini dengan optimal, diperlukan perangkat keras grafis yang memadai serta driver yang terbaru. Jika Anda mengalami kesulitan menjalankan demo ini di browser, Anda masih dapat menyaksikan demonstrasinya melalui video di YouTube.

Interaksi yang Didukung
------------------------

Demo ini tidak hanya menampilkan visual yang memukau, tetapi juga memungkinkan pengguna untuk berinteraksi secara langsung, seperti:

- Menggambar pada permukaan air untuk menciptakan riak
- Menyeret latar belakang untuk memutar kamera
- Menekan tombol ``SPACEBAR`` untuk menjeda dan melanjutkan simulasi
- Menggerakkan bola dengan menyeretnya
- Menekan tombol ``L`` untuk mengatur arah cahaya
- Menekan tombol ``G`` untuk mengaktifkan atau menonaktifkan gravitasi

Fitur Teknis Unggulan
----------------------

*WebGL Water* menghadirkan berbagai fitur grafis lanjutan, antara lain:

- Refleksi dan refraksi yang dihitung menggunakan metode *ray tracing*
- *Analytic ambient occlusion* untuk pencahayaan yang lebih realistis
- Simulasi permukaan air berbasis *heightfield*\ *
- Bayangan halus (*soft shadows*)
- Efek *caustics* yang meniru pola cahaya di dasar air\ **

\* Simulasi air ini membutuhkan ekstensi WebGL bernama ``OES_texture_float``.

\** Efek caustics memerlukan ekstensi ``OES_standard_derivatives``.

Kredit Tambahan
----------------

Tekstur ubin pada latar belakang demo ini diambil dari akun Flickr bernama *zooboing*.
# Packet Bloom

Sebuah gerakan algoritmik tentang jaringan yang sedang diperiksa. Setiap seed adalah satu topologi unik: titik-titik tersebar lewat best-candidate sampling sehingga terasa rata tanpa terlihat berbaris, lalu dihubungkan ke dua tetangga terdekat dengan jalur melengkung yang bengkoknya ditentukan seed. Tidak ada garis lurus dan tidak ada dua jaringan yang sama.

Di atas topologi itu paket berjalan. Setiap paket menyusuri satu jalur, tiba di sebuah node, lalu memilih jalur berikutnya secara acak, seperti traceroute yang tidak pernah selesai. Jejak yang memudar menunjukkan arah tanpa perlu panah. Keindahannya lahir dari proses, bukan dari satu bingkai akhir: setiap detik komposisinya berubah, namun tetap setia pada strukturnya.

Sebagian node adalah port terbuka. Mereka diam sampai sebuah paket tiba, lalu berdenyut dengan cincin yang melebar dan meredup. Ini rujukan halus bagi siapa pun yang pernah menjalankan pemindaian port: hanya yang terbuka yang menjawab. Yang tidak paham tetap melihat komposisi generatif yang tenang.

Setiap parameter, dari jumlah node, lengkung jalur, sampai rasio port terbuka, dipilih dengan teliti oleh implementasi yang dikerjakan seperti hasil ribuan jam penyempurnaan oleh seorang ahli komputasi estetis. Algoritma ini harus terasa dibuat dengan sabar dan keahlian tingkat tinggi, dan tiap seed layak dicetak sebagai karya tersendiri.

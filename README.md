Niken Anggraini X-8

    Proyek fisika berbasis Python dan Pygame yang dibuat untuk memvisualisasikan konsep gravitational slingshot atau ayunan gravitasi. Proyek ini menunjukkan bagaimana sebuah pesawat luar angkasa dapat mengubah lintasan dan kecepatannya secara signifikan saat melewati medan gravitasi sebuah planet.
Inti simulasi ini terletak pada implementasi rumus Newton. Program menghitung jarak antara pesawat dan planet menggunakan rumus Pythagoras untuk menentukan dasar perhitungan gaya. Setelah jarak diketahui, simulasi menerapkan Hukum Gravitasi Universal Newton untuk menghitung besar gaya tarik-menarik antar objek

                                                  F = G . Mpesawat . M planet / distance^2

   Untuk memastikan arah gaya selalu menuju pusat planet, simulasi memanfaatkan fungsi trigonometri seperti atan2 untuk mencari sudut arah gaya, serta fungsi cos dan sin untuk mengurai gaya tersebut menjadi komponen vektor sumbu x dan y. Dengan menggunakan hubungan a = F / m, program menentukan percepatan yang dialami oleh pesawat.
Setiap frame simulasi, program melakukan pembaruan posisi secara berulang. Kecepatan pesawat diperbarui dengan menambahkan nilai percepatan, dan posisi pesawat diubah berdasarkan kecepatan yang baru diperbarui tersebut. Hal inilah yang menghasilkan lintasan melengkung yang terlihat realistis saat pesawat melintasi planet. 

   User dapat terlibat langsung dalam simulasi ini melalui antarmuka interaktif. Dengan melakukan klik dan menarik (drag) mouse pada layar, pengguna dapat menentukan vektor arah dan kecepatan awal pesawat. Setelah dilepaskan, pesawat akan meluncur ke dalam sistem dan terpengaruh oleh gravitasi planet, menciptakan skenario slingshot setiap kali simulasi dijalankan. Seluruh proses ini berjalan secara real-time untuk memberikan pengalaman simulasi yang edukatif bagi pengembang maupun pengguna.

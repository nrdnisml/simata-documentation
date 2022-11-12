# **SIMATA** (Sistem Informasi Manajemen Turn Around)

## Alur Input Data Lembur Tenaga Non-Organik TA

1. Akses melalui laman [SIMATA (https://ta-pg.com)](https://ta-pg.com)
   ![Landing Page](/assets/1.png "Landing Page")
2. Klik tombol 'Pengajuan Lembur' / 'Log in'
3. Menginputkan username dan password untuk mengakses sistem sesuai dengan role user !(tenaga non-organik/foreman/supervisor/avp) ![Login Page](/assets/2.png "Login Page")
4. Menginputkan data lembur

   a. Tampilan role user tenaga non-organik ![Umum Page](/assets/3.png "Umum Page")
   b. Tampilan role user foreman/supervisor ![SPV Page](/assets/4.png "Umum Page")

5. Jika semua data sudah terisi, tekan tombol next pada bagian bawah untuk melakukan review data yang diinputkan ![Review Page](/assets/5.png "Umum Page")
6. Jika data sudah dirasa benar bisa menekan tombol submit, jika ada yang salah bisa kembali ke halaman input dengan menekan tombol back. Setelah menekan tombol submit, data akan diinput ke database dan bisa dilakukan proses selanjutnya. ![Submit Page](/assets/6.png "Submit Page")

### Hal - Hal yang Perlu Diperhatikan Dalam Melakukan Input Data Lembur

1. Kategori Lembur, Pilih Shift untuk tenaga shift, dan Normal Day untuk tenaga non-shift atau tenaga shift yang di-normal day-kan
2. Untuk lembur pada saat TA, pilih jenis lembur **Overtime Turn Around** dan Proyek TA sesuai dengan unit/plant yang sedang dikerjakan
3. Penulisan **badge** harus sesuai dengan **KIB**, Jika di KIB terdapat tanda baca semisal - atau . perlu dituliskan misal **22-15540**

## Alur Approval SPL

![Alur Page](/assets/7.png "Alur Page")

1. Tampilan halaman approval foreman/supervisor, Pada role foreman akan tampil data yang diajukan oleh tenaga non-organik sedangkan pada role supervisor data yang ditampilkan adalah pengajuan dari tenaga non-organik dan foreman (input pengajuan dari foreman atau data yang diapprove oleh foreman)
   ![Approval Page](/assets/8.png "Approval Page")
2. Untuk menyetujui pengajuan terdapat **tombol setujui** pada kolom aksi
3. Untuk menolak pengajuan terdapat **tombol tolak** kemudian muncul _pop-up dialog_ untuk input alasan penolakan
4. Terdapat **tombol review** untuk mengubah data pengajuan yang masuk jika terjadi kesalahan input data, ketika data dirasa sudah valid bisa menekan tombol **update & ajukan** agar data pengajuan dilanjutkan ke approval berikutnya ![Review app Page](/assets/9.png "Approval Review Page")
5. Data yang sudah melewati Supervisor akan masuk ke dalam role AVP untuk validasi akhir. Terdapat total data yang belum divalidasi per-project TA. Anda bisa menekan tombol Data untuk melihat list datanya.
   ![AVP Page](/assets/10.png "AVP Page")
   ![AVP Page](/assets/11.png "AVP Page")
   Terdapat beberapa aksi yang bisa dilakukan oleh role AVP terkait data SPL yang masuk yaitu:
   - Setujui SPL
   - Tolak SPL (dengan alasan)
   - Meminta review ulang/dikembalikan ke Supervisor (jika ditemukan kekeliruan data)
   - Melihat detail data
6. Untuk melihat status pengajuan lembur bisa dengan memanfaatkan menu Status SPL pada halaman utama dan pada halaman dashboard dengan menginputkan data badge ![status Page](/assets/12.png "status Page")

## FAQ (Frequently Ask Questions)

1. Bagaimana saya bisa mengetahui data akun untuk mengakses sistem ?
   - bisa menghubungi kantor TA pada ekstensi yang terdapat pada halaman utama
2. Bagaimana jika saya lupa password / username akun untuk mengakses sistem ?
   - bisa menghubungi kantor TA untuk meminta reset akun pada ekstensi yang terdapat pada halaman utama
3. Mengapa penulisan badge harus sesuai aturan ?
   - Penulisan badge digunakan untuk melakukan identifikasi data pekerja, setiap pekerja memiliki 1 badge yang unik, jika penulisan tidak sesuai atau tidak sama maka data yang diinputkan akan dianggap data yang berbeda atau milik orang lain
4. Bagaimana jika saya sudah terlanjur menuliskan badge yang tidak sesuai?
   - Penulisan badge **tidak perlu diubah** dipengajuan selanjutnya, karena data yang diinputkan pada saat awal mengisi SPL dalam sistem dianggap sebagai data registrasi sehingga jika Anda mencoba untuk mengubah/membenarkan penulisan badge di pengajuan berikutnya akan dianggap data yang berbeda
5. Bagaimana saya mengetahui badge saya sudah teregister atau belum?
   - Pada saat menginputkan data badge pada form pengajuan, jika badge Anda sudah teregistrasi maka kolom unit/bagian kerja dan kolom nama akan terisi secara otomatis. Jika setelah Anda menginputkan badge namun kolom nama dan unit kerja tidak terisi otomatis artinya badge yang Anda inputkan belum pernah teregistrasi sebelumnya.
6. Bagaimana jika terjadi kekeliruan data dalam penulisan data pekerja (nama dan unit kerja)?
   - Anda hanya perlu mengubah data tersebut pada pengajuan SPL selanjutnya, data nama dan unit kerja yang telah ter-input sebelumnya akan diupdate secara otomatis
7. Bagaimana jika terjadi kesalahan dalam melakukan input data lembur?
   - Anda bisa meminta reviewer (Foreman/Supervisor) untuk mengubah datanya / menolak pengajuan SPL sehingga Anda bisa melakukan pengajuan ulang ditanggal yang sama.
8. Apakah saya bisa melakukan pengajuan lembur untuk esok hari/minggu depan?
   - Tidak bisa
9. Apakah saya bisa melakukan pengajuan lembur dua kali untuk tanggal yang sama?
   - Tidak bisa, jika terjadi kekeliruan data hubungi reviewer untuk mengubah/menolak pengajuan.

# branch_html
PENGERTIAN DAN KEGUNAN NYA :
repository : database yang menyimpan history/ riwayat perubahan

snapshot : potret kondisi file dan folder pada saat tertentu

commit : snapshot yang disimpan di repository

branch : serangkaian commit yang berkaitan sehingga kalau digambar seperti garis lurus berisi banyak commit. Satu repository bisa berisi banyak branch.

master : nama branch default yang diberikan git pada waktu kita membuat repository. Branch master ini tidak istimewa. Dia bisa dihapus dan direname sesuka hati.

head : ujung branch, commit terbaru di dalam branch

HEAD : head yang sedang aktif. Walaupun satu repository bisa memiliki banyak branch, tapi cuma satu yang aktif.

working folder : folder berisi file dan folder tempat kita bekerja. Biasanya working folder berisi banyak file source code untuk aplikasi yang sedang kita buat. Git memantau 
working folder ini, dan bisa mengetahui file dan folder mana yang sudah berbeda dari posisi commit terakhir. Perbedaan atau perubahan ini bisa disimpan menjadi commit baru, atau dikembalikan ke kondisi sebelum diubah.

staging area : snapshot dari working folder yang akan kita simpan pada saat commit. Ini adalah fitur unik Git yang tidak dimiliki version control lain. Dengan adanya staging area, kita bisa memilih perubahan mana yang akan di-commit dan mana yang tidak.

object store : ini adalah database tempat semua commit disimpan.

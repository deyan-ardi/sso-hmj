Untuk menggunakan sistem di local server, berikut cara instalasinya

1. Silahkan buat DB baru di phpmyadmin dengan nama bebas
2. Silahkan import DB project_hmj_fixed.sql di phpmyadmin
3. Ubah setelah DB di file database.php yang ada di folder "application/config/database.php"
4. Jalankan xampp, lalu akses melalui localhost
5. Bagi yang sudah punya file ini dari project sebelumnya, silahkan yang digunakan adalah project yang baru. Karena ada beberapa penyesuaian bug, sehingga file sebelumnya tidak bisa dipakai


Note :
- Pastikan sudah terinstal git di laptop
- Pastikan anda mengclone dari gitlab, gunakan perintah "https://github.com/deyan-ardi/sso-hmj.git" untuk mengclone file ini
- Jangan pernah mengutak ngatik folder bagian system
- Setelah program yang dikerjakan jadi, silahkan buat brench baru agar mempermudah dalam melakukan merge


========================================================================================

Perhatian !! 
Terdapat 3 sistem yang berbeda didalamnya, hati-hati dalam mengubah informasi pada EORS, WEB HMJ, INTEGER, serta Model

Update by Deyan
ETIKA : 50% FINISH (Front End on Progress)


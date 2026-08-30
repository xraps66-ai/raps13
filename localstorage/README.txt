Local Storage seed untuk Project Rapzwy
=====================================
File di folder ini meniru data localStorage browser.

Akun admin:
  username: rapzwy
  password: Xycbaue8

Saat index.html dibuka lewat server (GitHub Pages / localhost),
data akun (users + profil admin) diimpor ke localStorage jika belum ada.
Session TIDAK di-seed — user selalu diarahkan ke halaman Login/Daftar dulu.
Setelah login sukses, session disimpan di localStorage dan dipakai di kunjungan berikutnya
(sampai logout).

Keys:
  rapz_admin_profile_v1.json  -> profil admin (disimpan di localStorage)
  rapz_tools_users_v1.json    -> daftar semua akun (admin + member)
  rapz_tools_session_v1.json  -> session login (kosong di seed; diisi setelah login)
  rapz_last_login_v1.json     -> login terakhir (diisi setelah login)
  rapz_custom_tools_v1.json   -> tools custom admin

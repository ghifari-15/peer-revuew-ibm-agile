title: "[BUG] - Tanggal jatuh tempo tidak tersimpan setelah edit tugas"
labels: bug
assignees: ''

**Deskripsi Bug:**
Ketika saya mencoba mengedit tugas yang sudah ada untuk mengubah tanggal jatuh temponya, perubahan tanggal tersebut tidak tersimpan. Setelah menyimpan, tanggal jatuh tempo kembali ke tanggal semula sebelum diedit.

**Langkah-langkah untuk Reproduksi:**
1. Pergi ke halaman daftar tugas.
2. Buat tugas baru dengan deskripsi "Tes Edit Tanggal" dan tanggal jatuh tempo '2025-06-10'.
3. Simpan tugas. Pastikan tugas muncul dengan tanggal yang benar.
4. Klik pada tugas "Tes Edit Tanggal" untuk membukanya dalam mode edit.
5. Ubah field tanggal jatuh tempo menjadi '2025-06-12'.
6. Klik tombol "Simpan Perubahan".
7. Amati tanggal jatuh tempo yang ditampilkan untuk tugas "Tes Edit Tanggal" di daftar tugas.

**Perilaku yang Diharapkan:**
Tanggal jatuh tempo untuk tugas "Tes Edit Tanggal" seharusnya berubah dan menampilkan '2025-06-12'.

**Perilaku Aktual:**
Tanggal jatuh tempo untuk tugas "Tes Edit Tanggal" tetap menampilkan '2025-06-10', tidak berubah sesuai editan.

**Screenshot (jika ada):**
(Saya akan melampirkan screenshot di sini jika ini adalah laporan bug sungguhan yang menu

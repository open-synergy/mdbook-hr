# Mengkonfirmasi Cash Advance

## A. INPUT

* Data *Cash Advance* yang akan dikonfirmasi harus memiliki status **Draft**.

![](../../img/cash-advance/status-draft.png)

* User yang akan mengkonfirmasi harus memiliki akses untuk **[Mengkonfirmasi Document](./penjelasan.md#field-can-confirm)** Cash Advance.

## B. INSTRUKSI KERJA

1. Buka menu **Human Resources -> Cash Advance -> Cash Advance**. Abaikan jika sudah berada pada menu yang dimaksud.
2. Buka data Cash Advance yang akan dikonfirmasi. Abaikan jika data sudah dibuka.
3. Klik tombol **Confirm** pada bagian atas-kiri form.

![](../../img/cash-advance/tombol-confirm.png)

## C. OUTPUT

* Data Cash Advance akan berubah menjadi **Waiting for Approval**.

![](../../img/cash-advance/status-waiting-for-approval.png)

* Data Cash Advance sudah tidak bisa dimodifikasi atau dihapus.
* Data **[Confirmation](./penjelasan.md#field-log-confirmation)** pada log Cash Advance akan berisi nama user dan tanggal saat konfirmasi.

## Chapter
- [Transaksi](../../transaksi.md)
- [Penjelasan Cash Advance](./penjelasa.md)
- [Membuat Cash Advance](./membuat.md)
- [Modifikasi Cash Advance](./modifikasi.md)
- [Menghapus Cash Advance](./menghapus.md)
- [Menambah Detail Cash Advance](./membuat-detail.md)
- [Modifikasi Detail Cash Advance](./modifikasi-detail.md)
- [Menghapus Detail Cash Advance](./menghapus-detail.md)
- [Menyetujui Cash Advance](./menyetujui.md)
- [Menolak Cash Advance](./menolak.md)
- [Merestart Persetujuan Cash Advance](./merestart-persetujuan.md)
- [Mengubah Nilai Cash Advance](./cash-advance/mengubah-nilai-cash-advance.md)
- [Membatalkan Cash Advance](./membatalkan.md)
- [Merestart Cash Advance](./merestart.md)
- [Terminate Cash Advance](./terminate.md)

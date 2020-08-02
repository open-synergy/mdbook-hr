# Menyetujui Cash Advance

## A. INPUT

* Data *Cash Advance* yang akan disetujui harus memiliki status **Waiting For Approval**.

![](../../img/cash-advance/status-waiting-for-approval.png)

* User yang akan menyetujui harus memiliki akses untuk **[Menyetujui Document](./penjelasan.md#tab-reviews)** Cash Advance.

## B. INSTRUKSI KERJA

1. Buka menu **Human Resources -> Cash Advance -> Cash Advance**. Abaikan jika sudah berada pada menu yang dimaksud.
2. Buka data Cash Advance yang akan disetujui. Abaikan jika data sudah dibuka.
3. Klik tombol **Validate** pada bagian atas-kiri form.

![](../../img/cash-advance/tombol-validate.png)

## C. OUTPUT

* Data Cash Advance akan berubah menjadi **Waiting for Realization** jika semua user yang harus memvalidasi sudah melakukan proses validasi.

![](../../img/cash-advance/status-waiting-for-realization.png)

* Data Accounting Entry (**[# Move](./penjelasan.md#field-move)**, **[Employee Advance Payable Move Line](./penjelasan.md#field-move-payable-line)** dan  **[Employee Advance Move Line](./penjelasan.md#field-move-advance-line)**) akan berubah terisi otomatis jika semua user yang harus memvalidasi sudah melakukan proses validasi.

![](../../img/cash-advance/status-done-accounting.png)

* Data **[Validation](./penjelasan.md#tab-reviews)** pada tab review akan berisi nama user dan tanggal saat menyetujui.
* Data **[Approval](./penjelasan.md#field-log-approval)** pada log Cash Advance akan berisi nama user dan tanggal saat melakukan approval.

## Chapter
- [Transaksi](../../transaksi.md)
- [Penjelasan Cash Advance](./penjelasa.md)
- [Membuat Cash Advance](./membuat.md)
- [Modifikasi Cash Advance](./modifikasi.md)
- [Menghapus Cash Advance](./menghapus.md)
- [Menambah Detail Cash Advance](./membuat-detail.md)
- [Modifikasi Detail Cash Advance](./modifikasi-detail.md)
- [Menghapus Detail Cash Advance](./menghapus-detail.md)
- [Mengkonfirmasi Cash Advance](./mengkonfirmasi.md)
- [Menolak Cash Advance](./menolak.md)
- [Merestart Persetujuan Cash Advance](./merestart-persetujuan.md)
- [Mengubah Nilai Cash Advance](./cash-advance/mengubah-nilai-cash-advance.md)
- [Membatalkan Cash Advance](./membatalkan.md)
- [Merestart Cash Advance](./merestart.md)
- [Terminate Cash Advance](./terminate.md)

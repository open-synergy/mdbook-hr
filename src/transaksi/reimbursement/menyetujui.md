# Menyetujui Reimbursement

## A. INPUT

* Data *Reimbursement* yang akan disetujui harus memiliki status **Waiting For Approval**.

![](../../img/reimbursement/status-waiting-for-approval.png)

* User yang akan menyetujui harus memiliki akses untuk **[Menyetujui Document](./penjelasan.md#tab-reviews)** reimbursement.

## B. INSTRUKSI KERJA

1. Buka menu **Human Resources -> Reimbursement -> Reimbursement**. Abaikan jika sudah berada pada menu yang dimaksud.
2. Buka data reimbursement yang akan disetujui. Abaikan jika data sudah dibuka.
3. Klik tombol **Validate** pada bagian atas-kiri form.

![](../../img/reimbursement/tombol-validate.png)

## C. OUTPUT

* Data reimbursement akan berubah menjadi **Waiting for Payment** jika semua user yang harus memvalidasi sudah melakukan proses validasi.

![](../../img/reimbursement/status-waiting-for-payment.png)

* Data Accounting Entry (**[# Move](./penjelasan.md#field-move)** dan **[Reimbursement Payable Move Line](./penjelasan.md#field-move-line)** akan berubah terisi otomatis jika semua user yang harus memvalidasi sudah melakukan proses validasi.

![](../../img/reimbursement/status-waiting-for-payment-accounting.png)

* Data **[Validation](./penjelasan.md#tab-reviews)** pada tab review akan berisi nama user dan tanggal saat menyetujui.
* Data **[Approval](./penjelasan.md#field-log-approval)** pada log reimbursement akan berisi nama user dan tanggal saat melakukan approval.

## Chapter
- [Transaksi](../../transaksi.md)
- [Penjelasan Reimbursement](./penjelasan.md)
- [Membuat Reimbursement](./membuat.md)
- [Modifikasi Reimbursement](./modifikasi.md)
- [Menghapus Reimbursement](./menghapus.md)
- [Menambah Detail Reimbursement](./membuat-detail.md)
- [Modifikasi Detail Reimbursement](./modifikasi-detail.md)
- [Menghapus Detail Reimbursement](./menghapus-detail.md)
- [Mengkonfirmasi Reimbursement](./mengkonfirmasi.md)
- [Menolak Reimbursement](./menolak.md)
- [Merestart Persetujuan Reimbursement](./merestart-persetujuan.md)
- [Mengubah Nilai Reimbursement](./mengubah-nilai-reimbursement.md)
- [Membatalkan Reimbursement](./membatalkan.md)
- [Merestart Reimbursement](./merestart.md)
- [Terminate Reimbursement](./terminate.md)

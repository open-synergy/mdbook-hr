# Terminate Reimbursement

## A. INPUT

* Data *Reimbursement* yang akan diterminate harus memiliki status **Waiting For Payment**.

![](../../img/reimbursement/status-waiting-for-payment.png)

* User yang akan mengkonfirmasi harus memiliki akses untuk **[Terminate Document](./penjelasan.md#field-can-terminate)** reimbursement.

## B. INSTRUKSI KERJA

1. Buka menu **Human Resources -> Reimbursement -> Reimbursement**. Abaikan jika sudah berada pada menu yang dimaksud.
2. Buka data reimbursement yang akan diterminate. Abaikan jika data sudah dibuka.
3. Klik tombol **Terminate** pada bagian atas-kiri form.

![](../../img/reimbursement/tombol-terminate.png)

4. Klik tombol **OK** pada bagian bawah form.

![](../../img/reimbursement/tombol-terminate-ok.png)

5. Pilih **[Reason](./penjelasan.md#field-terminate-reason)**. Harus disi.

6. Klik tombol **Confirm** pada bagian bawah kiri form.

![](../../img/reimbursement/tombol-terminate-ok-confirm.png)

7. Klik tombol **OK** pada bagian bawah kiri form.

![](../../img/reimbursement/tombol-terminate-ok-confirm-ok.png)

## C. OUTPUT

* Data reimbursement akan berubah menjadi **Terminate**.

![](../../img/reimbursement/status-terminate.png)

* Data **[Terminate](./penjelasan.md#field-log-terminate)** pada log reimbursement akan berisi nama user dan tanggal saat pembatalan.

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
- [Menyetujui Reimbursement](./menyetujui.md)
- [Menolak Reimbursement](./menolak.md)
- [Merestart Persetujuan Reimbursement](./merestart-persetujuan.md)
- [Mengubah Nilai Reimbursement](./mengubah-nilai-reimbursement.md)
- [Membatalkan Reimbursement](./membatalkan.md)
- [Merestart Reimbursement](./merestart.md)

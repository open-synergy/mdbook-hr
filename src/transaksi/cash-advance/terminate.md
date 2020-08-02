# Terminate cash-advance

## A. INPUT

* Data *cash advance* yang akan diterminate harus memiliki status **Waiting For Realization**.

![](../../img/cash-advance/status-waiting-for-realization.png)

* User yang akan melakukan terminasi harus memiliki akses untuk **[Terminate Document](./penjelasan.md#field-can-terminate)** cash advance.

## B. INSTRUKSI KERJA

1. Buka menu **Human Resources -> Cash Advance -> Cash Advance**. Abaikan jika sudah berada pada menu yang dimaksud.
2. Buka data cash advance yang akan diterminate. Abaikan jika data sudah dibuka.
3. Klik tombol **Terminate** pada bagian atas-kiri form.

![](../../img/cash-advance/tombol-terminate.png)

4. Klik tombol **OK** pada bagian bawah form.

![](../../img/cash-advance/tombol-terminate-ok.png)

5. Pilih **[Reason](./penjelasan.md#field-terminate-reason)**. Harus disi.

6. Klik tombol **Confirm** pada bagian bawah kiri form.

![](../../img/cash-advance/tombol-terminate-ok-confirm.png)

7. Klik tombol **OK** pada bagian bawah kiri form.

![](../../img/cash-advance/tombol-terminate-ok-confirm-ok.png)

## C. OUTPUT

* Data cash advance akan berubah menjadi **Terminate**.

![](../../img/cash-advance/status-terminate.png)

* Data **[Terminate](./penjelasan.md#field-log-terminate)** pada log cash advance akan berisi nama user dan tanggal saat pembatalan.

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
- [Menyetujui Cash Advance](./menyetujui.md)
- [Menolak Cash Advance](./menolak.md)
- [Merestart Persetujuan Cash Advance](./merestart-persetujuan.md)
- [Mengubah Nilai Cash Advance](./cash-advance/mengubah-nilai-cash-advance.md)
- [Membatalkan Cash Advance](./membatalkan.md)
- [Merestart Cash Advance](./merestart.md)

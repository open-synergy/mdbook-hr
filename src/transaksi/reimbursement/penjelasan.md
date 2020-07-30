# Penjelasan Reimbursement

Informasi pada **Reimbursement**  dibagi menjadi beberapa area, diantaranya:
* [Header](#bagian-header)
* [Tab Reimbursement Detail](#tab-detail)
* [Tab Accounting Info](#tab-accounting)
* [Tab Reviews](#tab-reviews)
* [Tab Note](#tab-note)
* [Tab Policies](#tab-policy)
* [Tab Logs](#tab-log)

Form lainnya yang muncul pada proses reimbursement
* [Form Pembatalan](#form-batal)
* [Form Terminate](#form-terminate)

### <a name="bagian-header">HEADER</a>

![](../../img/reimbursement/header.png)

#### <a name="field-document"># Document</a>

Nomor dokumen.

#### <a name="field-employee">Employee</a>

Karyawan.

#### <a name="field-department">Department</a>

Departemen. Akan terisi otomatis sesuai isian pada data master karyawan/*Employee*

#### <a name="field-manager">Manager</a>

Nama Manajer. Akan terisi otomatis sesuai isian pada data master karyawan/*Employee*

#### <a name="field-job-position">Job Position</a>

Nama Posisi pekerjaan. Akan terisi otomatis sesuai isian pada data master karyawan/*Employee*

#### <a name="field-date-expense">Date Expense</a>

Tanggal terjadinya pengeluaran.

#### <a name="field-date-due">Date Due</a>

Tanggal estimasi dibayarnya reimbursement.

#### <a name="field-type">Type</a>

Jenis reimbursement. Pilihan diambil dari master data **type reimbursement**.

#### <a name="field-currency">Currency</a>

Mata Uang. Pilihan diambil dari master data **currency**.

### <a name="tab-detail">Tab Reimbursement Detail</a>

![](../../img/reimbursement/tab-reimbursement-detail.png)

#### <a name="field-product">Product</a>

Nama produk yang akan direimburse. Pilihan sesuai dengan tabel **Allowed Product Categories** atau **Allowed Products** dari **Type** yang dipilih.

#### <a name="field-note">Note</a>

Catatan mengenai item reimbursement.

#### <a name="field-reference">Reference</a>

Nomor dokumen rujukan (contoh: nomor bon, nomor kwitansi, nomor invoice, dll) dari item yang akan direimburse.

#### <a name="field-account">Account</a>

Kode akun beban yang akan digunakan pada pembuatan penjurnalan akuntansi. Secara default isian akan sesuai dengan isian **Expense Account** dari data **Product** yang dipilih atau sesuai dengan isian **Expense Account** dari category **Product** yang dipilih. Pilihan diambil dari master data **Account**.

#### <a name="field-analytic-account">Analytic Account</a>

Akun analitik (cost center) dari item yang akan direimburse. Pilihan diambil dari master data **analytic account**.

#### <a name="field-unit-price">Unit Price</a>

Harga satuan produk yang akan direimburse.

#### <a name="field-approve-price">Aprroved Price Unit</a>

Harga yang disetujui dari produk yang direimburse. Tidak bisa diubah langsung. Isian dapat diubah dengan menjalankan instruksi kerja [Mengubah Nilai Reimbursement](./mengubah-nilai-reimbursement.md)

#### <a name="field-qty">Qty</a>

Jumlah produk yang akan direimburse.

#### <a name="field-approve-qty">Aprroved Quantity</a>

Jumlah produk yang disetujui untuk direimburse. Tidak bisa diubah langsung. Isian dapat diubah dengan menjalankan instruksi kerja [Mengubah Nilai Reimbursement](./mengubah-nilai-reimbursement.md)

#### <a name="field-uom">UoM</a>

Satuan/Unit of Measurement dari produk yang direimburse. Secara default isian akan sesuai dengan isian *UoM* dari data **Product** yang dipilih. Pilihan diambil dari master data **Unit of Measure**.

#### <a name="field-sub-total">Sub Total</a>

Perkalian antara **Aprroved Quantity** dan **Aprroved Price Unit**. Akan terhitung secara otomatis.

#### <a name="field-total">Total</a>

Jumlah total reimbursement yang harus dibayarkan. Akan terhitung secara otomatis.

#### <a name="field-total-payment">Total Payment</a>

Total dari reimbursement yang sudah dibayarkan kepada karyawan yang mengajukan. Akan terhitung secara otomatis.

#### <a name="field-total-residu">Total Residual</a>

Total Residual merupakan selisih **Total** dan **Total Payment**. Akan terhitung secara otomatis.

### <a name="tab-accounting">Tab Accounting Info</a>

![](../../img/reimbursement/tab-accounting-info.png)

#### <a name="field-journal">Journal</a>

Buku Jurnal yang akan digunakan dalam pembuatan penjurnalan akuntansi. Secara default isian akan sesuai dengan isian **Journal** dari **Type** yang dipilih. Pilihan diambil dari master data **Journal**.

#### <a name="field-payable-account">Reimbursement Payable Account</a>

Akun utang (payable) yang akan digunakan dalam pembuatan penjurnalan akuntansi. Secara default isian akan sesuai dengan isian **Payable Account** dari **Type** yang dipilih. Pilihan diambil dari master data **account**.

#### <a name="field-move"># Move</a>

Penjurnalan akuntansi yang dihasilkan. Akan terisi otomatis ketika reimbursement disetujui.

#### <a name="field-move-line">Reimbursement Payable Move Line</a>

Detail penjurnalan akuntansi untuk payable. Akan terisi otomatis ketika reimbursement disetujui.

### <a name="tab-reviews">Tab Reviews</a>

![](../../img/reimbursement/tab-reviews.png)

#### <a name="field-definition">Definition</a>

Konfigurasi multiple approval yang digunakan. Secara default akan terisi otomatis sesuai dengan keadaan reimbursement ketika reimbursement dikonfirmasi.

#### <a name="field-review-validation">Review Partner Validation</a>

Daftar User yang berhak melakukan validasi sesuai **Definition** yang ditetapkan. Akan terisi otomatis.

### <a name="tab-note">Tab Note</a>

![](../../img/reimbursement/tab-note.png)

#### <a name="field-tab-note-note">Note</a>

Catatan lebih detail mengenai reimbursement.

### <a name="tab-policy">Tab Policies</a>

![](../../img/reimbursement/tab-policy.png)

#### <a name="field-can-confirm">Can Confirm</a>

Identifikasi apakah user berhak melakukan proses confirmasi.

#### <a name="field-can-restart-approval">Can Restart Approval</a>

Identifikasi apakah user berhak melakukan proses restart persetujuan.

#### <a name="field-can-change-detail">Can Change Detail</a>

Identifikasi apakah user berhak melakukan perubahan isi detail.

#### <a name="field-can-cancel">Can Cancel</a>

Identifikasi apakah user berhak melakukan pembatalan reimbursement.

#### <a name="field-can-terminate">Can Terminate</a>

Identifikasi apakah user berhak melakukan proses terminasi reimbursement.

#### <a name="field-can-restart">Can Restart</a>

Identifikasi apakah user berhak melakukan proses restart reimbursement.

#### <a name="field-can-see">Can See Accounting Info</a>

Identifikasi apakah user berhak melihat informati accounting.

### <a name="tab-log">Tab Logs</a>

Tab Log berisikan informasi log mengenai nama dan tanggal proses
![](../../img/reimbursement/tab-log.png)

#### <a name="field-log-confirmation">Confirmation</a>

Informasi mengenai nama dan kapan proses konfirmasi dilakukan.

#### <a name="field-log-approval">Approval</a>

Informasi mengenai nama dan kapan proses persetujuan dilakukan.

#### <a name="field-log-finish">Finish</a>

Informasi mengenai nama dan kapan proses persetujuan dilakukan.

#### <a name="field-log-cancel">Cancellation</a>

Informasi mengenai nama dan kapan proses pembatalan dilakukan.

#### <a name="field-log-terminate">Termination</a>

Informasi mengenai nama dan kapan proses terminasi dilakukan.

### <a name="form-batal">Form Pembatalan</a>

Form ini muncul saat transaksi pembatalan/cancel dilakukan

![](../../img/reimbursement/tombol-cancel-confirm.png)

#### <a name="field-cancel-reason">Reason</a>

Definisikan alasan pembatalan

### <a name="form-terminate">Form Terminate</a>

Form ini muncul saat proses terminate dilakukan

![](../../img/reimbursement/tombol-terminate-ok-confirm.png)

#### <a name="field-terminate-reason">Reason</a>

Definisikan alasan terminate

## Chapter
- [Transaksi](../../transaksi.md)
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
- [Terminate Reimbursement](./terminate.md)

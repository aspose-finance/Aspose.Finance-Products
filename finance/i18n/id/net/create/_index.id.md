---
title: Buat laporan keuangan melalui .NET
url: /id/net/create/
description:  C# kode untuk membuat laporan keuangan di XBRL, dan OFX permintaan atau tanggapan file melalui .NET perpustakaan.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Buat file pelaporan keuangan melalui C#" h2="Pembuatan format laporan keuangan termasuk XBRL dan OFX permintaan atau file tanggapan dalam format 1.03 atau 2.2 dalam aplikasi berbasis .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) Adalah fitur yang kaya, extensible dan mudah digunakan pembuatan laporan keuangan dan pengolahan API. Pengembang dapat dengan mudah membuat contoh XBRL dari awal serta dapat menambahkan referensi skema, konteks, unit, item, Tautan catatan kaki, referensi peran dan 
Referensi peran busur. API menyediakan kelas yang relevan untuk setiap fitur seperti untuk konteks, pengembang dapat menggunakan [Konteks periode](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextperiod), [Conextentity](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextentity) Dan [Konteks](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context). 
Selain itu, API juga mendukung pertukaran keuangan terbuka (OFX) permintaan format/pembuatan tanggapan dalam format 1.03 atau 2.2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Buat File XBRL dengan menambahkan Item" %}}

Untuk membuat berkas XBRL dan menambahkan item ke dalam dokumen, proses adalah, buat [Kelas xbrldokumen-dokumen](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Contoh. Siapkan pengaturan yang relevan untuk barang dengan menggunakan kelas API yang sesuai seperti [Kelas SchemaRef](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemaref), Kelas konteks yang relevan seperti yang disebutkan di atas dan [Kelas konsep](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/concept). Akhirnya mendefinisikan dan intim [Kelas barang](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/item) Properti serta panggilan [Metode Simpan](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) Untuk [Buat XBRL](https://products.aspose.com/finance/net/create/xbrl/) Masukkan ke dalam cakram.

{{% blocks/products/pf/feature-page-code h3="C# kode untuk membuat berkas XBRL dengan menambahkan Item" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-item.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Membuat file permintaan dan respons OFX" %}}


Untuk menghasilkan file OFX, API menyediakan [OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) Dan [Dokumen ofxresponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) Kelas dan pengembang dapat dengan mudah [Buat permintaan OFX](https://products.aspose.com/finance/net/create/ofx-request/) Dan file respons dalam format 1.03 dan 2.2. Untuk menginisialisasi properti dokumen permintaan, API juga menyediakan kelas lain seperti [SignonRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [Lembaga keuangan](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution) Dan [StatementTransactionRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest) Kelas. Demikian pula, untuk intimalisasi properti xresponse, API menyediakan kelas yang mendukung seperti [SignonResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [StatementTransactionResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse) Dan [Transaksi pernyataan](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction). Berikut adalah potongan kode untuk kedua kasus dengan penggunaan kelas yang sesuai yang relevan.

{{% blocks/products/pf/feature-page-code h3="C# kode untuk menghasilkan OFX permintaan dokumen" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# kode untuk menghasilkan OFX Dokumen Tanggapan" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
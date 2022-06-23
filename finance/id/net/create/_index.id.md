---
title: Buat Laporan Keuangan melalui .NET
url: /id/net/create/
description:  C# kode untuk membuat Laporan Keuangan di XBRL, dan OFX file permintaan atau tanggapan melalui perpustakaan .NET.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Buat File Pelaporan Keuangan melalui C#" h2="Pembuatan format laporan keuangan termasuk XBRL dan OFX file permintaan atau tanggapan dalam format 1.03 atau 2.2 dalam aplikasi berbasis .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) adalah fitur yang kaya, dapat diperluas, dan mudah digunakan pembuatan dan pemrosesan laporan keuangan API. Pengembang dapat dengan mudah membuat XBRL instance dari awal serta dapat menambahkan referensi skema, konteks, unit, item, tautan catatan kaki, referensi peran, dan 
referensi peran busur. API menyediakan kelas yang relevan untuk setiap fitur seperti untuk konteks, pengembang dapat menggunakan [KonteksPeriode](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextperiod), [Entitas Konteks](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextentity) dan [Konteks](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context). 
Selain itu, API juga mendukung pembuatan format permintaan/tanggapan pertukaran keuangan terbuka (OFX) dalam format 1.03 atau 2.2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Buat XBRL File dengan Menambahkan Item" %}}

Untuk membuat XBRL file dan menambahkan item ke dalam dokumen, prosesnya adalah, buat [Kelas dokumen Xbrl](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) contoh. Siapkan setelan yang relevan untuk item dengan menggunakan API kelas yang sesuai seperti [kelas SchemaRef](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemaref)kelas konteks yang relevan seperti yang disebutkan di atas dan [Kelas konsep](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/concept). Akhirnya tentukan dan inisialisasi [kelas barang](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/item) properti serta menyebutnya [Simpan metode](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) ke [buat XBRL](https://products.aspose.com/finance/net/create/xbrl/) file ke dalam disk.

{{% blocks/products/pf/feature-page-code h3="C# Kode untuk Membuat XBRL Berkas dengan Menambahkan Item" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-item.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Buat OFX File Permintaan dan Respons" %}}


Untuk membuat OFX file, API menyediakan [OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) dan [Dokumen OfxResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) kelas dan pengembang dapat dengan mudah [buat OFX Permintaan](https://products.aspose.com/finance/net/create/ofx-request/) dan file Respon dalam format 1.03 dan 2.2. Untuk menginisialisasi properti OfxRequestDocument, API juga menyediakan kelas lain seperti [Permintaan Masuk](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [Lembaga keuangan](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution) dan [PernyataanPermintaanTransaksi](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest) kelas. Demikian pula, untuk menginisialisasi properti OfxResponseDocument, API menyediakan kelas yang mendukung seperti [SignonRespons](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [PernyataanTransaksiRespons](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse) dan [Transaksi Pernyataan](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction). Di bawah ini adalah cuplikan kode untuk kedua kasus dengan penggunaan kelas yang sesuai dan relevan.

{{% blocks/products/pf/feature-page-code h3="C# Kode untuk Menghasilkan OFX Meminta Dokumen" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Kode untuk Menghasilkan OFX Dokumen Respons" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
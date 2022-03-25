---
title: Mengonversi laporan keuangan melalui .NET
url: /id/net/conversion/
description:  C# kode untuk mengonversi laporan keuangan dalam XBRL, iXBRL dan OFX berkas templat melalui .NET perpustakaan.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Mengonversi file laporan keuangan melalui C#" h2="Laporan Keuangan memformat konversi termasuk berkas XBRL, iXBRL dan OFX dari format 1.03 hingga 2.2 dalam aplikasi berbasis .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) Adalah fitur yang kaya, extensible dan mudah digunakan API. Pengembang dapat dengan mudah memvalidasi contoh XBRL, basis Tautan dan skema taksonomi menggunakan [Validasi () metode](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) Itu harus sesuai dengan persyaratan sintaks yang dikenakan dalam spesifikasi. Selain itu, mereka dapat membaca XBRL, iXBRL format serta membuat XBRL contoh dari awal. Selain itu, mereka dapat mengubah format XBRL ** menjadi iXBRL dan file Microsoft Excel XLSX. API juga mendukung pertukaran keuangan terbuka (OFX) permintaan format/pembuatan respons dan mengubah OFX permintaan/tanggapan file dari format 1.03 hingga 2.2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Mengonversi file respons dan permintaan OFX" %}}

API mendukung pembuatan OFX permintaan dan file respon dengan menyediakan dua kelas. [OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) Untuk membuat dan memuat OFX meminta file dalam format 1.03 dan 2.2 dan [Dokumen ofxresponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) Untuk file respons OFX dalam format 1.03 dan 2.2. Selanjutnya, [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) Penjabaran yang memiliki anggota V1x yaitu versi 1.x, format file sgml dan versi V2x 2.x, format file xml. Setelah memanggil metode penyimpanan ofxrequestkelas dokumen atau ofxresponsekelas dokumen, pengembang dapat dengan mudah mengkonversi dari 1.03 file sgml ke 2.2 format xml.


{{% blocks/products/pf/feature-page-code h3="C# kode untuk mengonversi OFX file respons" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-response-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# kode untuk mengonversi OFX meminta file" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-request-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL konversi laporan keuangan" %}}

API mendukung konversi file XBRL ke iXBRL dan Microsoft®Format Excel XLSX. Proses konversi sederhana, pertama-tama memuat file melalui [Kelas xbrldokumen-dokumen](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument). Gunakan [Kelas saveoption](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions) Untuk [Format hemat](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions/properties/saveformat), Untuk digunakan sebagai parameter dalam metode Simpan kelas xbrldokumen. Untuk menyimpan di berkas iXBLR, [SaveFormat.IXBRL](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveformat) Akan digunakan dan untuk mengekspor ke format XLSX, simpan format. XLSX akan digunakan.

{{% blocks/products/pf/feature-page-code h3="C# kode untuk mengekspor XBRL ke iXBRL" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-ixbrl.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# kode untuk XBRL ke konversi XLSX" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-xlsx.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}
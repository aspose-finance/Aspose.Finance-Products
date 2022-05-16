---
title: Konversi Laporan Keuangan melalui .NET
url: /id/net/conversion/
description:  C# kode untuk mengonversi Laporan Keuangan dalam format file XBRL, iXBRL(xbrl sebaris) dan OFX melalui pustaka .NET.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konversi File Laporan Keuangan melalui C#" h2="Konversi format laporan keuangan termasuk file XBRL, iXBRL dan OFX dari format 1,03 menjadi 2.2 dalam aplikasi berbasis .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) adalah fitur yang kaya, dapat diperluas, dan mudah digunakan API. Pengembang dapat dengan mudah memvalidasi XBRL contoh, basis tautan, dan skema taksonomi menggunakan [validasi() metode](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) yang harus sesuai dengan persyaratan sintaks yang dikenakan dalam spesifikasi. Selain itu, mereka dapat membaca format XBRL, iXBRL serta membuat instance XBRL dari awal. Selain itu, mereka dapat **mengonversi XBRL format** ke iXBRL dan file Microsoft Excel XLSX. API juga mendukung permintaan / tanggapan format pertukaran keuangan terbuka (OFX) dan mengonversi OFX permintaan / tanggapan file dari format 1,03 menjadi 2,2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Konversikan OFX File Respons dan Permintaan" %}}

API mendukung pembuatan OFX file permintaan dan tanggapan dengan menyediakan dua kelas. [OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) untuk membuat dan memuat OFX file permintaan dalam format 1.03 dan 2.2 dan [OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) untuk OFX file tanggapan dalam format 1.03 dan 2.2. Selanjutnya, [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) Pencacahan yang memiliki anggota V1x yaitu versi 1.x, format file sgml dan versi V2x 2.x, format file xml. Setelah memanggil metode Simpan kelas OfxRequestDocument atau kelas OfxResponseDocument, pengembang dapat dengan mudah mengonversi dari file 1,03 sgml ke format 2,2 xml.


{{% blocks/products/pf/feature-page-code h3="C# Kode untuk Mengonversi OFX Berkas Respons" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-response-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Kode untuk Mengonversi OFX Berkas Permintaan" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-request-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL Konversi Laporan Keuangan" %}}

API mendukung konversi file XBRL ke iXBRL dan format Microsoft® Excel XLSX. Proses konversi sederhana, pertama-tama muat file melalui [Kelas Dokumen Xbrl](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument). Menggunakan [Kelas SaveOptions](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions) untuk [SimpanFormat](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions/properties/saveformat), untuk digunakan sebagai parameter dalam metode Simpan Kelas XbrlDocument. Untuk menyimpan dalam file iXBLR, [SimpanFormat.IXBRL](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveformat) akan digunakan dan untuk mengekspor ke format XLSX, SaveFormat.XLSX akan digunakan.

{{% blocks/products/pf/feature-page-code h3="C# Kode untuk Mengekspor XBRL ke iXBRL" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-ixbrl.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Kode untuk Konversi XBRL ke XLSX" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-xlsx.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}
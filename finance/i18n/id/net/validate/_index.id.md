---
title: Validasi laporan keuangan melalui .NET
url: /id/net/validate/
description:  C# kode untuk memvalidasi laporan keuangan di XBRL dan iXBRL file melalui perpustakaan .NET.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Validasi file pelaporan keuangan melalui C#" h2="Memvalidasi Format laporan keuangan termasuk XBRL dan iXBRL dalam aplikasi berbasis .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) Adalah fitur yang kaya, extensible dan mudah digunakan laporan keuangan pengolahan API. Pengembang dapat dengan mudah Memuat, memvalidasi, melihat atau membuat format XBRL dan iXBRL untuk solusi keuangan dan bisnis. API menyediakan [Xbrldokumen-dokumen](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Kelas dan  [Dokumen inlinexbrl](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) Kelas untuk memuat file XBRL dan iXBRL.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Dokumen {validasi 0}" %}}

Validasi berkas XBRL diperlukan untuk sejumlah kasus seperti untuk memeriksa data dalam struktur dan format yang tepat. Untuk memvalidasi dokumen XBLR, pertama-tama gunakan kelas dokumen xbrluntuk memuat file XBRL. Untuk menggunakan [Validasi ()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) Metode dari [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) Kelas, pertama intim [XbrlInstanceCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) Dengan xbrlmendokumentasikan objek xbrlintions. Berulang melalui setiap [XbrlInstance. Kesalahan validasi](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/properties/validationerrors) Untuk mendapatkan kode kesalahan yang tepat dan bertindak sesuai dengan mencetak pesan kesalahan yang disesuaikan pada konsol atau menulis dalam file.

{{% blocks/products/pf/feature-page-code h3="C# kode untuk memvalidasi berkas XBRL" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-xbrl-file.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Dokumen {validasi 0}" %}}

Untuk validasi iplrb, muat via [Dokumen inlinexbrl](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) Kelas dan menggunakan metode validasi (). Dalam [ValidationErrorCode](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.validator/validationerrorcode) Penjabaran, kode kesalahan validasi didefinisikan untuk setiap aturan validasi. Beberapa kode yang ContextPeriodNoStartTime, ContextPeriodNoEndTime, CONT, CONT stantnotime, Cou, Cou dll pengembang dapat men-debug dan menampilkan kode pada pengguna akhir atau dapat menunjukkan arah untuk menyelesaikan masalah.

{{% blocks/products/pf/feature-page-code h3="C# kode untuk memvalidasi dokumen iXBRL" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-ixbrl-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}
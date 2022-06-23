---
title: Validasi Laporan Keuangan melalui .NET
url: /id/net/validate/
description:  C# kode untuk memvalidasi laporan keuangan dalam file XBRL dan iXBRL melalui perpustakaan .NET.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Validasi File Pelaporan Keuangan melalui C#" h2="Memvalidasi format laporan keuangan termasuk XBRL dan iXBRL dalam aplikasi berbasis .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) adalah fitur yang kaya, dapat diperluas, dan mudah digunakan untuk memproses laporan keuangan API. Pengembang dapat dengan mudah memuat, memvalidasi, melihat, atau membuat format XBRL dan iXBRL untuk solusi keuangan dan bisnis. API menyediakan [XbrlDokumen](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) kelas dan  [Dokumen InlineXbrl](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) kelas untuk memuat file XBRL dan iXBRL.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Validasi XBRL Dokumen" %}}

Validasi file XBRL diperlukan untuk beberapa kasus seperti untuk memeriksa data dalam struktur dan format yang benar. Untuk memvalidasi dokumen XBLR, Pertama gunakan kelas XbrlDocument untuk memuat file XBRL. Untuk menggunakan [mengesahkan()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) metode dari [Contoh Xbrl](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) kelas, pertama-tama inisialisasi [Koleksi Instance Xbrl](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) dengan objek XbrlDocument XbrlInstances. Ulangi setiap [XbrlInstance.ValidationErrors](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/properties/validationerrors) untuk mendapatkan kode kesalahan yang tepat dan bertindak sesuai dengan itu dengan mencetak pesan kesalahan yang disesuaikan di konsol atau menulis di dalam file.

{{% blocks/products/pf/feature-page-code h3="C# Kode untuk Memvalidasi XBRL Berkas" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-xbrl-file.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Validasi iXBRL Dokumen" %}}

Untuk validasi iXLRB, muat melalui [Dokumen InlineXbrl](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) kelas dan gunakan metode Validate()-nya. Di [ValidationErrorCode](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.validator/validationerrorcode) enumerasi, kode kesalahan validasi ditentukan untuk setiap aturan validasi. Beberapa kode adalah ContextPeriodNoStartTime, ContextPeriodNoEndTime, ContextPeriodStartAfterEnd, ContextInstantNoTime, ContextScenarioXbrlNamespace, ContextScenarioXbrlSubstitutionGroup dll. Pengembang dapat men-debug dan menampilkan kode sebagai pengguna akhir atau dapat menunjukkan arah untuk menyelesaikan masalah.

{{% blocks/products/pf/feature-page-code h3="C# Kode untuk Memvalidasi iXBRL Dokumen" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-ixbrl-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}
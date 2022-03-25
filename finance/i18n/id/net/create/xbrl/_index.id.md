---
title: Buat File XBRL melalui C#
description: Contoh kode untuk pembuatan berkas XBRL. Gunakan kode contoh API untuk pembuatan file batch XBRL dalam aplikasi berbasis .NET. 
url: /id/net/create/xbrl/
family: finance
platformtag: net
feature: create
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Buat file XBRL melalui C#" h2="XBRL pembuatan file tanpa perlu Microsoft Office diinstal atau perangkat lunak lainnya." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Cara membuat file XBRL" %}}

Ikuti langkah-langkah dalam cuplikan kode atau Sempurnakan sebagai kebutuhan aplikasi Anda untuk menghasilkan bahasa pelaporan bisnis yang dapat diperluas XBRL file. Pastikan memiliki persyaratan pembuatan dalam aplikasi Anda.

1. Buat [Kelas xbrldokumen-dokumen](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Contoh.1. Untuk membuat dokumen instans XBRL baru [XbrlInstanceCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) Dan [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance).1. Menambahkan referensi skema menggunakan [SchemaRefCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemarefcollection)1. Tergantung pada sifat aplikasi menambahkan konteks, unit, item, Tautan catatan kaki, dan lainnya.1. Hubungi yang [Metode Simpan](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) Dengan menyediakan jalur berkas sasaran.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan pembuatan" %}}
Untuk melanjutkan pembuatan dokumen XBRL, .NET Finance API adalah persyaratan utama yang harus disertakan dalam aplikasi. 
- Menginstalnya melalui baris perintah sebagai "nuget instal Aspose.Finance" "atau melalui konsol manajer paket Studio Visual dengan" menginstal-paket Aspose.Finance ".
- Atau, dapatkan pemasang MSI offline atau DLLs dalam file ZIP dari [Unduhan](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# kode untuk pembuatan file XBRL" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-schema-reference.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Pilihan kreasi lainnya" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX permintaan" description="Format 1.03 atau 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX Tanggapan" description="Format 1.03 atau 2.2" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
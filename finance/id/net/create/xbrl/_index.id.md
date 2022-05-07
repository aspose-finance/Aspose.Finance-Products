---
title: Buat XBRL Berkas melalui C#
description: Contoh kode untuk XBRL pembuatan file. Gunakan kode contoh API untuk pembuatan file XBRL batch dalam aplikasi berbasis .NET. 
url: /id/net/create/xbrl/
family: finance
platformtag: net
feature: create
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Buat XBRL Berkas melalui C#" h2="XBRL pembuatan file tanpa perlu menginstal Microsoft Office atau perangkat lunak lainnya." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Cara Membuat XBRL Berkas" %}}

Ikuti langkah-langkah dalam cuplikan kode atau tingkatkan sesuai kebutuhan aplikasi Anda untuk menghasilkan file XBRL bahasa pelaporan bisnis yang dapat diperluas. Pastikan memiliki persyaratan pembuatan dalam aplikasi Anda.

1. Membuat [Kelas dokumen Xbrl](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Contoh.1. Untuk membuat XBRL dokumen instance . baru [Koleksi Instance Xbrl](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) dan [Contoh Xbrl](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance).1. Tambahkan referensi skema menggunakan [SkemaRefCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemarefcollection)1. Bergantung pada sifat aplikasi, tambahkan konteks, unit, item, tautan catatan kaki, dan lainnya.1. Panggil [Simpan metode](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) dengan menyediakan jalur file target.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Pembuatan" %}}
Untuk melanjutkan pembuatan XBRL dokumen, .NET Finance API adalah persyaratan utama untuk disertakan dalam aplikasi. 
- Instal melalui baris perintah sebagai ```nuget install Aspose.Finance``` atau melalui Package Manager Console dari Visual Studio dengan ```Install-Package Aspose.Finance```.
- Atau, dapatkan penginstal MSI offline atau DLL dalam file ZIP dari [unduhan](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# kode untuk XBRL pembuatan file" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-schema-reference.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Opsi Kreasi Lainnya" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX Permintaan" description="1.03 atau 2.2 Format" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX Tanggapan" description="1.03 atau 2.2 Format" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
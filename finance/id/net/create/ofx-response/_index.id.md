---
title: Buat OFX Berkas Tanggapan melalui C#
description: Kode contoh untuk OFX pembuatan file respons. Gunakan kode contoh API untuk pembuatan file respons OFX batch dalam aplikasi berbasis .NET. 
url: /id/net/create/ofx-response/
family: finance
platformtag: net
feature: create
informat: OFX Response
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Buat OFX Berkas Tanggapan melalui C#" h2="OFX pembuatan file respons tanpa perlu menginstal Microsoft Office atau perangkat lunak lainnya." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Cara Membuat OFX File Respons" %}}

Ikuti langkah-langkah dalam cuplikan kode atau tingkatkan sesuai kebutuhan aplikasi Anda setelah memiliki persyaratan pembuatan dalam aplikasi Anda.

1. Membuat [Kelas OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) obyek.1. Tetapkan properti yang relevan menggunakan kelas berbeda yang disediakan oleh API like [SignonRespons](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [PernyataanTransaksiRespons](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse), [Transaksi Pernyataan](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction)1. Gunakan ofxVersion V2x atau V1x untuk file xml dan sgml masing-masing dari [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) sebagai parameter dalam metode Simpan.1. Panggil [Simpan metode](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument/methods/save) dengan menyediakan file target dan ofxVersion.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Pembuatan" %}}
Untuk melanjutkan OFX Pembuatan file respons, .NET Finance API adalah persyaratan utama untuk disertakan dalam aplikasi pembuatan laporan. 
- Instal melalui baris perintah sebagai ```nuget install Aspose.Finance``` atau melalui Package Manager Console dari Visual Studio dengan ```Install-Package Aspose.Finance```.
- Atau, dapatkan penginstal MSI offline atau DLL dalam file ZIP dari [unduhan](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# kode untuk OFX pembuatan file tanggapan" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Opsi Kreasi Lainnya" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX Berkas Permintaan" description="1.03 atau 2.2 Format" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL Berkas" description="Bahasa Pelaporan Bisnis yang Dapat Diperluas" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
---
title: Buat File permintaan OFX melalui C#
description: Kode sampel untuk OFX meminta pembuatan file. Gunakan kode contoh API untuk pembuatan file permintaan batch OFX dalam aplikasi berbasis .NET. 
url: /id/net/create/ofx-request/
family: finance
platformtag: net
feature: create
informat: OFX Request
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Buat file permintaan OFX melalui C#" h2="OFX meminta pembuatan file tanpa perlu Microsoft Office diinstal atau perangkat lunak lainnya." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Cara membuat file permintaan OFX" %}}

Setelah memiliki OFX meminta persyaratan pembuatan file dalam aplikasi Anda, ikuti langkah-langkah dalam cuplikan kode atau Sempurnakan sesuai kebutuhan Anda.

1. Buat [Kelas dokumen permintaan](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) Objek.1. Tetapkan properti yang relevan menggunakan kelas yang berbeda yang disediakan oleh API seperti [SignonRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [Lembaga keuangan](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution), [StatementTransactionRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest)1. Gunakan ofxVersion V2x atau V1x untuk berkas xml dan sgml masing-masing dari [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) Sebagai parameter dalam metode simpan.1. Hubungi yang [Metode Simpan](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument/methods/save) Dengan menyediakan berkas target dan ofxVersion.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan pembuatan" %}}
Untuk melanjutkan pembuatan file OFX permintaan, .NET Finance API adalah persyaratan utama untuk dimasukkan dalam aplikasi pembuatan laporan. 
- Menginstalnya melalui baris perintah sebagai "nuget instal Aspose.Finance" "atau melalui konsol manajer paket Studio Visual dengan" menginstal-paket Aspose.Finance ".
- Atau, dapatkan pemasang MSI offline atau DLLs dalam file ZIP dari [Unduhan](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# kode untuk OFX meminta pembuatan file" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-request-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Pilihan kreasi lainnya" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX File Tanggapan" description="Format 1.03 atau 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL File" description="Bahasa pelaporan bisnis yang dapat diperluas" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
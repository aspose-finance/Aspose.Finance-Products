---
title: Buat OFX Berkas Permintaan melalui Python
description: Kode contoh untuk OFX pembuatan file permintaan. Gunakan API kode contoh untuk pembuatan file permintaan OFX batch dalam aplikasi berbasis Python. 
url: /id/python-net/create/ofx-request/
family: finance
platformtag: python
feature: create
informat: OFX Request
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Buat OFX Berkas Permintaan melalui Python" h2="OFX meminta pembuatan file tanpa perlu menginstal Microsoft Office atau perangkat lunak lainnya." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Cara Membuat OFX File Permintaan" %}}

Setelah OFX Minta persyaratan pembuatan file dalam aplikasi Anda, Ikuti langkah-langkah dalam cuplikan kode atau tingkatkan sesuai kebutuhan Anda.

1. Buat objek kelas OfxRequestDocument.2. Tetapkan properti yang relevan menggunakan kelas berbeda yang disediakan oleh API seperti SignonRequest, FinancialInstitution], StatementTransactionRequest
3. Gunakan ofxVersion V2x atau V1x untuk file xml dan sgml masing-masing dari OfxVersionEnum sebagai parameter dalam metode Simpan.
4. Panggil metode save dengan menyediakan file target dan ofxVersion.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Pembuatan" %}}
Untuk melanjutkan OFX Minta pembuatan file, pastikan Anda memiliki prasyarat berikut. 
- OS berbasis Microsoft Windows atau Linux.- Python 3.5 atau lebih baru.- Aspose.Finance untuk Python yang dirujuk dalam proyek Anda.{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python kode untuk OFX permintaan pembuatan file" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-request-files.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Opsi Kreasi Lainnya" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-response/" name="OFX Berkas Tanggapan" description="1.03 atau 2.2 Format" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/xbrl/" name="XBRL Berkas" description="Bahasa Pelaporan Bisnis yang Dapat Diperluas" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
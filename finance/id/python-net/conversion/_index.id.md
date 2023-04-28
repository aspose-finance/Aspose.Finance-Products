---
title: Konversi Laporan Keuangan melalui Python
url: /id/python-net/conversion/
description:  Python kode untuk mengonversi Laporan Keuangan dalam format file XBRL, iXBRL(xbrl sebaris) dan OFX melalui pustaka Python.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konversi File Laporan Keuangan melalui Python" h2="Konversi format laporan keuangan termasuk file XBRL, iXBRL dan OFX dari format 1,03 menjadi 2.2 dalam aplikasi berbasis Python." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance untuk Python melalui .NET](https://products.aspose.com/finance/python-net/) adalah fitur yang kaya, dapat diperluas, dan mudah digunakan API. Pengembang dapat dengan mudah memvalidasi XBRL instans, basis tautan, dan skema taksonomi menggunakan metode validasi() yang harus mematuhi persyaratan sintaks yang ditetapkan dalam spesifikasi. Selain itu, mereka dapat membaca format XBRL, iXBRL serta membuat instance XBRL dari awal. Selain itu, mereka dapat **mengonversi format XBRL** ke iXBRL dan file Microsoft Excel XLSX. API juga mendukung permintaan / tanggapan format pertukaran keuangan terbuka (OFX) dan mengonversi OFX permintaan / tanggapan file dari format 1,03 menjadi 2,2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Konversikan OFX File Respons dan Permintaan" %}}

API mendukung pembuatan OFX file permintaan dan tanggapan dengan menyediakan dua kelas. OfxRequestDocument untuk membuat dan memuat OFX file permintaan dalam format 1.03 dan 2.2 dan OfxResponseDocument untuk OFX file tanggapan dalam format 1.03 dan 2.2. Selanjutnya, OfxVersionEnum Enumeration memiliki anggota V1x yaitu versi 1.x, format file sgml dan versi V2x 2.x, format file xml. Setelah memanggil metode simpan kelas OfxRequestDocument atau kelas OfxResponseDocument, pengembang dapat dengan mudah mengonversi dari file 1,03 sgml ke format 2,2 xml.


{{% blocks/products/pf/feature-page-code h3="C# Kode untuk Mengonversi OFX Berkas Respons" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-ofx-response-from-1.03-to-2.2.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Kode untuk Mengonversi OFX Berkas Permintaan" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-ofx-request-from-1.03-to-2.2.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL Konversi Laporan Keuangan" %}}

API mendukung konversi file XBRL ke iXBRL dan format Microsoft® Excel XLSX. Proses konversi sederhana, pertama-tama muat file melalui Kelas XbrlDocument. Gunakan kelas SaveOptions untuk SaveFormat, untuk digunakan sebagai parameter dalam metode simpan Kelas XbrlDocument. Untuk menyimpan dalam file iXBLR, SaveFormat.IXBRL akan digunakan dan untuk mengekspor ke format XLSX, SaveFormat.XLSX akan digunakan.

{{% blocks/products/pf/feature-page-code h3="Python Kode untuk Mengekspor XBRL ke iXBRL" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-xbrl-to-ixbrl.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python Kode untuk Konversi XBRL ke XLSX" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-xbrl-to-xlsx.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}
{{< /blocks/products/pf/feature-page-wrap >}}
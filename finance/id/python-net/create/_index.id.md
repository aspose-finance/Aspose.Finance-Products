---
title: Buat Laporan Keuangan melalui Python
url: /id/python-net/create/
description:  Python kode untuk membuat Laporan Keuangan di XBRL, dan OFX file permintaan atau tanggapan melalui perpustakaan Python.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Buat File Pelaporan Keuangan melalui Python" h2="Pembuatan format laporan keuangan termasuk XBRL dan OFX file permintaan atau tanggapan dalam format 1.03 atau 2.2 dalam aplikasi berbasis Python." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance untuk Python melalui .NET](https://products.aspose.com/finance/python-net/) adalah fitur yang kaya, dapat diperluas, dan mudah digunakan pembuatan dan pemrosesan laporan keuangan API. Pengembang dapat dengan mudah membuat XBRL instance dari awal serta dapat menambahkan referensi skema, konteks, unit, item, tautan catatan kaki, referensi peran, dan 
referensi peran busur. API menyediakan kelas yang relevan untuk setiap fitur seperti untuk konteks, pengembang dapat menggunakan ContextPeriod, ContextEntity, dan Context. 
Selain itu, API juga mendukung pembuatan format permintaan/tanggapan pertukaran keuangan terbuka (OFX) dalam format 1.03 atau 2.2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Buat XBRL File dengan Menambahkan Item" %}}

Untuk membuat file XBRL dan menambahkan item ke dalam dokumen, prosesnya adalah, membuat instance kelas XbrlDocument. Siapkan pengaturan yang relevan untuk item dengan menggunakan kelas API yang sesuai seperti kelas SchemaRef, kelas konteks yang relevan seperti yang disebutkan di atas dan kelas Konsep. Terakhir, tentukan dan inisialisasi properti kelas Item serta panggil metode simpan untuk membuat file XBRL ke dalam disk.

{{% blocks/products/pf/feature-page-code h3="Python Kode untuk Membuat XBRL Berkas dengan Menambahkan Item" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-xbrl-file-and-add-item.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Buat OFX File Permintaan dan Respons" %}}


Untuk menghasilkan OFX berkas, API menyediakan kelas OfxRequestDocument dan OfxResponseDocument dan pengembang dapat dengan mudah [buat OFX Permintaan](https://products.aspose.com/finance/python-net/create/ofx-request/) dan file Respon dalam format 1.03 dan 2.2. Untuk menginisialisasi properti OfxRequestDocument, API juga menyediakan kelas lain seperti kelas SignonRequest, FinancialInstitution, dan StatementTransactionRequest. Demikian pula, untuk menginisialisasi properti OfxResponseDocument, API menyediakan kelas yang mendukung seperti SignonResponse, StatementTransactionResponse, dan StatementTransaction. Di bawah ini adalah cuplikan kode untuk kedua kasus dengan penggunaan kelas yang sesuai dan relevan.

{{% blocks/products/pf/feature-page-code h3="Python Kode untuk Menghasilkan OFX Meminta Dokumen" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python Kode untuk Menghasilkan OFX Dokumen Respons" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< /blocks/products/pf/feature-page-wrap >}}
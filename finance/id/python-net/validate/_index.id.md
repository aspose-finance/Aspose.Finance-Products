---
title: Validasi Laporan Keuangan melalui Python
url: /id/python-net/validate/
description:  Python kode untuk memvalidasi laporan keuangan dalam file XBRL dan iXBRL melalui perpustakaan Python.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Validasi File Pelaporan Keuangan melalui Python" h2="Memvalidasi format laporan keuangan termasuk XBRL dan iXBRL dalam aplikasi berbasis Python." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance untuk Python melalui .NET](https://products.aspose.com/finance/python-net/) adalah fitur yang kaya, dapat diperluas, dan mudah digunakan untuk memproses laporan keuangan API. Pengembang dapat dengan mudah memuat, memvalidasi, melihat, atau membuat format XBRL dan iXBRL untuk solusi keuangan dan bisnis. API menyediakan kelas XbrlDocument dan kelas InlineXbrlDocument untuk memuat file XBRL dan iXBRL.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Validasi XBRL Dokumen" %}}

Validasi file XBRL diperlukan untuk beberapa kasus seperti untuk memeriksa data dalam struktur dan format yang benar. Untuk memvalidasi dokumen XBLR, Pertama gunakan kelas XbrlDocument untuk memuat file XBRL. Untuk menggunakan metode validasi kelas XbrlInstance, pertama-tama inisialisasi XbrlInstanceCollection dengan objek XbrlDocument XbrlInstances. Ulangi setiap XbrlInstance.ValidationErrors untuk mendapatkan kode kesalahan yang tepat dan bertindak sesuai dengan itu dengan mencetak pesan kesalahan yang disesuaikan di konsol atau menulis di dalam file.

{{% blocks/products/pf/feature-page-code h3="Python Kode untuk Memvalidasi XBRL Berkas" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "validate-xbrl-instance-file.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Validasi iXBRL Dokumen" %}}

Untuk validasi iXLRB, muat melalui kelas InlineXbrlDocument dan gunakan metode validasi(). Dalam enumerasi ValidationErrorCode, kode kesalahan validasi ditentukan untuk setiap aturan validasi. Beberapa kode adalah ContextPeriodNoStartTime, ContextPeriodNoEndTime, ContextPeriodStartAfterEnd, ContextInstantNoTime, ContextScenarioXbrlNamespace, ContextScenarioXbrlSubstitutionGroup dll. Pengembang dapat men-debug dan menampilkan kode sebagai pengguna akhir atau dapat menunjukkan arah untuk menyelesaikan masalah.

{{% blocks/products/pf/feature-page-code h3="Python Kode untuk Memvalidasi iXBRL Dokumen" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "validate-ixbrl-file.py" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}
{{< /blocks/products/pf/feature-page-wrap >}}
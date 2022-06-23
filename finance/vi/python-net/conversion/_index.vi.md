---
title: Chuyển đổi Báo cáo Tài chính qua Python
url: /vi/python-net/conversion/
description:  Python mã để chuyển đổi Báo cáo Tài chính trong XBRL, iXBRL (xbrl nội tuyến) và OFX tệp fomats qua thư viện Python.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Chuyển đổi Tệp Báo cáo Tài chính qua Python" h2="Chuyển đổi định dạng báo cáo tài chính bao gồm tệp XBRL, iXBRL và OFX từ định dạng 1.03 sang 2.2 trong các ứng dụng dựa trên Python." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance cho Python qua .NET](https://products.aspose.com/finance/python-net/) là một tính năng phong phú, có thể mở rộng và dễ sử dụng API. Các nhà phát triển có thể dễ dàng xác thực XBRL các phiên bản, cơ sở liên kết và lược đồ phân loại bằng cách sử dụng phương thức validate () phải tuân thủ các yêu cầu cú pháp áp dụng trong đặc tả. Hơn nữa, họ có thể đọc các định dạng XBRL, iXBRL cũng như tạo phiên bản XBRL từ đầu. Hơn nữa, họ có thể ** chuyển đổi XBRL định dạng ** thành iXBRL và các tệp Microsoft Excel XLSX. API cũng hỗ trợ tạo yêu cầu / phản hồi định dạng trao đổi tài chính mở (OFX) và chuyển đổi OFX tệp yêu cầu / phản hồi từ định dạng 1.03 sang 2.2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Chuyển đổi OFX Tệp phản hồi và yêu cầu" %}}

API hỗ trợ tạo OFX tệp yêu cầu và phản hồi bằng cách cung cấp hai lớp. OfxRequestDocument để tạo và tải OFX tệp yêu cầu ở định dạng 1.03 và 2.2 và OfxResponseDocument cho OFX tệp phản hồi ở định dạng 1.03 và 2.2. Hơn nữa, OfxVersionEnum Enumeration có các thành viên V1x là phiên bản 1.x, định dạng tệp sgml và phiên bản V2x 2.x, định dạng tệp xml. Sau khi gọi phương thức lưu của lớp OfxRequestDocument hoặc lớp OfxResponseDocument, các nhà phát triển có thể dễ dàng chuyển đổi từ tệp 1.03 sgml sang định dạng 2.2 xml.


{{% blocks/products/pf/feature-page-code h3="C# Mã để Chuyển đổi OFX Tệp Phản hồi" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-ofx-response-from-1.03-to-2.2.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Mã để Chuyển đổi OFX Yêu cầu Tệp" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-ofx-request-from-1.03-to-2.2.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL Chuyển đổi Báo cáo Tài chính" %}}

API hỗ trợ chuyển đổi tệp XBRL sang iXBRL và định dạng Microsoft® Excel XLSX. Quá trình chuyển đổi rất đơn giản, trước tiên hãy tải tệp qua Lớp XbrlDocument. Sử dụng lớp SaveOptions cho SaveFormat, được sử dụng làm tham số trong phương thức lưu của Lớp XbrlDocument. Để lưu trong tệp iXBLR, SaveFormat.IXBRL sẽ được sử dụng và để xuất sang định dạng XLSX, SaveFormat.XLSX sẽ được sử dụng.

{{% blocks/products/pf/feature-page-code h3="Python Mã để Xuất XBRL sang iXBRL" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-xbrl-to-ixbrl.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python Mã cho Chuyển đổi XBRL sang XLSX" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-xbrl-to-xlsx.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}
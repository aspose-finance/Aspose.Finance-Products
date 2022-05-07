---
title: Chuyển đổi Báo cáo Tài chính qua .NET
url: /vi/net/conversion/
description:  C# mã để chuyển đổi Báo cáo Tài chính trong tệp XBRL, iXBRL và OFX fomats qua thư viện .NET.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Chuyển đổi Tệp Báo cáo Tài chính qua C#" h2="Chuyển đổi định dạng báo cáo tài chính bao gồm tệp XBRL, iXBRL và OFX từ định dạng 1.03 sang 2.2 trong các ứng dụng dựa trên .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) là một tính năng phong phú, có thể mở rộng và dễ sử dụng API. Các nhà phát triển có thể dễ dàng xác thực XBRL bản sao, cơ sở liên kết và lược đồ phân loại bằng cách sử dụng [phương thức validate ()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) phải tuân thủ các yêu cầu cú pháp áp đặt trong đặc tả. Hơn nữa, họ có thể đọc các định dạng XBRL, iXBRL cũng như tạo phiên bản XBRL từ đầu. Hơn nữa, họ có thể ** chuyển đổi XBRL định dạng ** thành iXBRL và các tệp Microsoft Excel XLSX. API cũng hỗ trợ tạo yêu cầu / phản hồi định dạng trao đổi tài chính mở (OFX) và chuyển đổi OFX tệp yêu cầu / phản hồi từ định dạng 1.03 sang 2.2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Chuyển đổi OFX Tệp phản hồi và yêu cầu" %}}

API hỗ trợ tạo OFX tệp yêu cầu và phản hồi bằng cách cung cấp hai lớp. [OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) để tạo và tải OFX tệp yêu cầu ở định dạng 1.03 và 2.2 và [OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) cho OFX tệp phản hồi ở định dạng 1.03 và 2.2. Hơn nữa, [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) Bảng kê có thành viên V1x là phiên bản 1.x, định dạng tệp sgml và phiên bản V2x 2.x, định dạng tệp xml. Sau khi gọi phương thức Save của lớp OfxRequestDocument hoặc lớp OfxResponseDocument, các nhà phát triển có thể dễ dàng chuyển đổi từ tệp 1.03 sgml sang định dạng 2.2 xml.


{{% blocks/products/pf/feature-page-code h3="C# Mã để Chuyển đổi OFX Tệp Phản hồi" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-response-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Mã để Chuyển đổi OFX Yêu cầu Tệp" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-request-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL Chuyển đổi Báo cáo Tài chính" %}}

API hỗ trợ chuyển đổi tệp XBRL sang iXBRL và định dạng Microsoft® Excel XLSX. Quá trình chuyển đổi rất đơn giản, trước tiên hãy tải tệp qua [Lớp XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument). Sử dụng [Lớp SaveOptions](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions) vì [SaveFormat](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions/properties/saveformat), được sử dụng làm tham số trong phương thức Lưu của Lớp XbrlDocument. Để lưu trong tệp iXBLR, [SaveFormat.IXBRL](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveformat) sẽ được sử dụng và để xuất sang định dạng XLSX, SaveFormat.XLSX sẽ được sử dụng.

{{% blocks/products/pf/feature-page-code h3="C# Mã để Xuất XBRL sang iXBRL" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-ixbrl.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Mã cho Chuyển đổi XBRL sang XLSX" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-xlsx.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}
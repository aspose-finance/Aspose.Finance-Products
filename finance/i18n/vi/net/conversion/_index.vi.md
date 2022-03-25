---
title: Chuyển đổi Tài Chính Báo Cáo thông qua .NET
url: /vi/net/conversion/
description:  C# mã để chuyển đổi Tài Chính Báo Cáo trong XBRL, iXBRL và OFX tập tin fomats qua .NET thư viện.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Chuyển đổi Tài Chính Báo Cáo Tập Tin thông qua C#" h2="Tài Chính báo cáo định dạng chuyển đổi bao gồm XBRL, iXBRL và OFX tập tin từ 1.03-2.2 định dạng trong vòng .NET các ứng dụng dựa trên." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) Là một tính năng phong phú, mở rộng và dễ dàng để sử dụng API. Các nhà phát triển có thể dễ dàng xác nhận XBRL trường hợp, linkbases và phân loại schemas sử dụng [XÁC NHẬN () phương pháp](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) Mà phải tuân thủ với các cú pháp yêu cầu áp đặt trong Đặc điểm kỹ thuật. Hơn nữa, họ có thể đọc XBRL, iXBRL các định dạng cũng như tạo ra XBRL Ví dụ từ đầu. Hơn nữa, họ có thể ** chuyển đổi XBRL định dạng ** để iXBRL và Microsoft Excel XLSX các tập tin. API cũng hỗ trợ mở Tài Chính trao đổi (OFX) yêu cầu định dạng/đáp ứng sáng tạo và chuyển đổi OFX tập tin yêu cầu/đáp ứng từ 1.03-2.2 định dạng.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Chuyển đổi OFX Đáp Ứng và Yêu Cầu Các Tập Tin" %}}

API hỗ trợ tạo ra OFX yêu cầu và đáp ứng các tập tin bằng cách cung cấp hai các lớp học. [OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) Cho việc tạo ra và tải OFX yêu cầu các tập tin trong 1.03 và 2.2 định dạng và [OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) Cho OFX đáp ứng các tập tin trong 1.03 và 2.2 định dạng. Hơn nữa, [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) Enumeration có thành viên V1x đó là 1.x phiên bản, sgml tập tin định dạng và V2x 2.x phiên bản, XML tập tin định dạng. Sau khi gọi điện thoại các Tiết Kiệm phương pháp của OfxRequestDocument lớp học hoặc OfxResponseDocument lớp, các nhà phát triển có thể dễ dàng chuyển đổi từ 1.03 sgml tập tin để 2.2 XML định dạng.


{{% blocks/products/pf/feature-page-code h3="C# mã để Chuyển Đổi OFX Đáp Ứng Các Tập Tin" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-response-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# mã để Chuyển Đổi OFX Yêu Cầu Các Tập Tin" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-request-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL Tài Chính Báo Cáo Chuyển Đổi" %}}

API hỗ trợ chuyển đổi XBRL các tập tin để iXBRL và Microsoft®Excel XLSX định dạng. Quá trình chuyển đổi là đơn giản, trước hết là tải các tập tin thông qua [XbrlDocument Lớp](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument). Sử dụng các [SaveOptions lớp](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions) Cho [SaveFormat](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions/properties/saveformat), Để được sử dụng như tham số trong Tiết Kiệm phương pháp của XbrlDocument Lớp. Cho tiết kiệm trong iXBLR tập tin, [SaveFormat.IXBRL](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveformat) Sẽ được sử dụng và cho xuất khẩu vào XLSX định dạng, SaveFormat.XLSX sẽ được sử dụng.

{{% blocks/products/pf/feature-page-code h3="C# mã để Xuất Khẩu XBRL để iXBRL" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-ixbrl.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# mã cho XBRL để XLSX Chuyển Đổi" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-xlsx.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}
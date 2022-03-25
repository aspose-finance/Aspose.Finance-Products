---
title: Tạo ra Tài Chính Báo Cáo thông qua .NET
url: /vi/net/create/
description:  C# mã để tạo ra Tài Chính Báo Cáo trong XBRL, và OFX yêu cầu hoặc đáp ứng các tập tin thông qua .NET thư viện.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Tạo ra Báo Cáo Tài Chính Tập Tin thông qua C#" h2="Tài Chính báo cáo định dạng sáng tạo bao gồm XBRL và OFX yêu cầu hoặc đáp ứng tập tin trong 1.03 hoặc 2.2 định dạng trong vòng .NET các ứng dụng dựa trên." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) Là một tính năng phong phú, mở rộng và dễ dàng để sử dụng tài chính báo cáo sáng tạo và chế biến API. Các nhà phát triển có thể dễ dàng tạo ra XBRL Ví dụ từ đầu cũng như có thể thêm schema để tham khảo, bối cảnh, đơn vị, mục, chú thích liên kết, vai trò tham khảo và 
ARC vai trò để tham khảo. API cung cấp có liên quan lớp cho mỗi tính năng chẳng hạn như đối với bối cảnh, Các nhà phát triển có thể sử dụng [ContextPeriod](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextperiod), [ContextEntity](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextentity) Và [Bối cảnh](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context). 
Hơn nữa, API cũng hỗ trợ mở Tài Chính trao đổi (OFX) yêu cầu định dạng/đáp ứng sáng tạo trong 1.03 hoặc 2.2 định dạng.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Tạo ra XBRL Tập Tin bằng cách Thêm Mục" %}}

Cho việc tạo ra XBRL tập tin và thêm mục vào các tài liệu, quá trình là, tạo ra [XbrlDocument lớp](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Ví dụ. Chuẩn bị có liên quan cài đặt cho mặt hàng bằng cách sử dụng thích hợp API lớp học chẳng hạn như [SchemaRef lớp](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemaref), Có liên quan bối cảnh lớp học như đã đề cập ở trên và [Khái niệm lớp](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/concept). Cuối cùng xác định và intialize [Mục lớp](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/item) Đặc tính cũng như cuộc gọi các [Tiết kiệm phương pháp](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) Để [Tạo ra XBRL](https://products.aspose.com/finance/net/create/xbrl/) Tập tin vào đĩa.

{{% blocks/products/pf/feature-page-code h3="C# mã để Tạo Ra XBRL Tập Tin bằng cách Thêm Mục" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-item.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Tạo ra OFX Yêu Cầu và Đáp Ứng Các Tập Tin" %}}


Cho tạo ra OFX các tập tin, các API cung cấp [OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) Và [OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) Các lớp học và các nhà phát triển có thể dễ dàng [Tạo ra OFX Yêu Cầu](https://products.aspose.com/finance/net/create/ofx-request/) Và Đáp Ứng các tập tin trong cả 1.03 và 2.2 các định dạng. Cho initializing OfxRequestDocument đặc tính, API cũng cung cấp khác lớp học chẳng hạn như [SignonRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [FinancialInstitution](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution) Và [StatementTransactionRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest) Các lớp học. Tương tự như vậy, cho intializing OfxResponseDocument đặc tính, API cung cấp hỗ trợ lớp học chẳng hạn như [SignonResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [StatementTransactionResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse) Và [StatementTransaction](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction). Dưới đây là các mã đoạn cho cả hai Trường hợp với việc sử dụng của có liên quan Thích hợp các lớp học.

{{% blocks/products/pf/feature-page-code h3="C# mã để Tạo Ra OFX Yêu Cầu Tài Liệu" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# mã để Tạo Ra OFX Đáp Ứng Tài Liệu" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
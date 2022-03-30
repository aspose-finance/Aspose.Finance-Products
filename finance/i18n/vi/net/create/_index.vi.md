---
title: Tạo Báo cáo Tài chính qua .NET
url: /vi/net/create/
description:  C# mã để tạo Báo cáo Tài chính trong XBRL và OFX tệp yêu cầu hoặc phản hồi qua thư viện .NET.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Tạo Tệp Báo cáo Tài chính qua C#" h2="Tạo các định dạng báo cáo tài chính bao gồm XBRL và OFX tệp yêu cầu hoặc phản hồi ở định dạng 1.03 hoặc 2.2 trong các ứng dụng dựa trên .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) là một tính năng phong phú, có thể mở rộng và dễ sử dụng để tạo và xử lý báo cáo tài chính API. Các nhà phát triển có thể dễ dàng tạo phiên bản XBRL từ đầu cũng như có thể thêm tham chiếu giản đồ, ngữ cảnh, đơn vị, mục, liên kết chú thích cuối trang, tham chiếu vai trò và 
tham chiếu vai trò vòng cung. API cung cấp lớp phù hợp cho từng tính năng, chẳng hạn như đối với ngữ cảnh, nhà phát triển có thể sử dụng [ContextPeriod](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextperiod), [ContextEntity](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextentity) và [Bối cảnh](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context). 
Hơn nữa, API cũng hỗ trợ tạo yêu cầu / phản hồi định dạng trao đổi tài chính mở (OFX) ở định dạng 1.03 hoặc 2.2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Tạo tệp XBRL bằng cách thêm mục" %}}

Để tạo tệp XBRL và thêm mục vào tài liệu, quy trình là, tạo [Lớp XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) ví dụ. Chuẩn bị các cài đặt có liên quan cho mục bằng cách sử dụng các lớp API thích hợp, chẳng hạn như [Lớp SchemaRef](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemaref)các lớp ngữ cảnh có liên quan như đã đề cập ở trên và [Lớp khái niệm](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/concept). Cuối cùng xác định và intialize [Hạng mục](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/item) thuộc tính cũng như gọi [Lưu phương pháp](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) đến [tạo XBRL](https://products.aspose.com/finance/net/create/xbrl/) tập tin vào đĩa.

{{% blocks/products/pf/feature-page-code h3="C# Mã để Tạo XBRL Tệp bằng cách Thêm Mục" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-item.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Tạo OFX Tệp yêu cầu và phản hồi" %}}


Để tạo tệp OFX, API cung cấp [OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) và [OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) các lớp học và nhà phát triển có thể dễ dàng [tạo OFX Yêu cầu](https://products.aspose.com/finance/net/create/ofx-request/) và các tệp Phản hồi ở cả định dạng 1.03 và 2.2. Để khởi tạo các thuộc tính OfxRequestDocument, API cũng cung cấp các lớp khác như [SignonRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [Tổ chức tài chính](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution) và [StatementTransactionRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest) các lớp học. Tương tự, để phức tạp hóa các thuộc tính OfxResponseDocument, API cung cấp các lớp hỗ trợ như [SignonResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [StatementTransactionResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse) và [StatementTransaction](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction). Dưới đây là các đoạn mã cho cả hai trường hợp với việc sử dụng các lớp thích hợp có liên quan.

{{% blocks/products/pf/feature-page-code h3="C# Mã để Tạo OFX Tài liệu Yêu cầu" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Mã để Tạo OFX Tài liệu Phản hồi" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
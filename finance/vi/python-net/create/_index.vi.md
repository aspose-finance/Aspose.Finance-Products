---
title: Tạo Báo cáo Tài chính qua Python
url: /vi/python-net/create/
description:  Python mã để tạo Báo cáo Tài chính trong XBRL và OFX tệp yêu cầu hoặc phản hồi qua thư viện Python.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Tạo Tệp Báo cáo Tài chính qua Python" h2="Tạo các định dạng báo cáo tài chính bao gồm XBRL và OFX tệp yêu cầu hoặc phản hồi ở định dạng 1.03 hoặc 2.2 trong các ứng dụng dựa trên Python." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance cho Python qua .NET](https://products.aspose.com/finance/python-net/) là một tính năng phong phú, có thể mở rộng và dễ sử dụng để tạo và xử lý báo cáo tài chính API. Các nhà phát triển có thể dễ dàng tạo phiên bản XBRL từ đầu cũng như có thể thêm tham chiếu giản đồ, ngữ cảnh, đơn vị, mục, liên kết chú thích cuối trang, tham chiếu vai trò và 
tham chiếu vai trò vòng cung. API cung cấp lớp phù hợp cho từng tính năng, chẳng hạn như đối với ngữ cảnh, nhà phát triển có thể sử dụng ContextPeriod, ContextEntity và Context. 
Hơn nữa, API cũng hỗ trợ tạo yêu cầu / phản hồi định dạng trao đổi tài chính mở (OFX) ở định dạng 1.03 hoặc 2.2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Tạo tệp XBRL bằng cách thêm mục" %}}

Để tạo tệp XBRL và thêm mục vào tài liệu, quy trình là tạo phiên bản lớp XbrlDocument. Chuẩn bị các cài đặt có liên quan cho mục bằng cách sử dụng các lớp API thích hợp như lớp SchemaRef, các lớp ngữ cảnh có liên quan như đã đề cập ở trên và lớp Khái niệm. Cuối cùng xác định và intialize các thuộc tính lớp Item cũng như gọi phương thức lưu để tạo tệp XBRL vào đĩa.

{{% blocks/products/pf/feature-page-code h3="Python Mã để Tạo XBRL Tệp bằng cách Thêm Mục" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-xbrl-file-and-add-item.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Tạo OFX Tệp yêu cầu và phản hồi" %}}


Để tạo tệp OFX, API cung cấp các lớp OfxRequestDocument và OfxResponseDocument và các nhà phát triển có thể dễ dàng [tạo OFX Yêu cầu](https://products.aspose.com/finance/python-net/create/ofx-request/) và các tệp Phản hồi ở cả định dạng 1.03 và 2.2. Để khởi tạo các thuộc tính OfxRequestDocument, API cũng cung cấp các lớp khác như các lớp SignonRequest, FinancialInstitution và StatementTransactionRequest. Tương tự, để phức tạp hóa các thuộc tính OfxResponseDocument, API cung cấp các lớp hỗ trợ như SignonResponse, StatementTransactionResponse và StatementTransaction. Dưới đây là các đoạn mã cho cả hai trường hợp với việc sử dụng các lớp thích hợp có liên quan.

{{% blocks/products/pf/feature-page-code h3="Python Mã để Tạo OFX Tài liệu Yêu cầu" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python Mã để Tạo OFX Tài liệu Phản hồi" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
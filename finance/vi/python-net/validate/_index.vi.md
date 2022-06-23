---
title: Xác thực Báo cáo Tài chính qua Python
url: /vi/python-net/validate/
description:  Python mã để xác thực các báo cáo tài chính trong tệp XBRL và iXBRL qua thư viện Python.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Xác thực các Tệp Báo cáo Tài chính qua Python" h2="Xác thực các định dạng báo cáo tài chính bao gồm XBRL và iXBRL trong các ứng dụng dựa trên Python." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance cho Python qua .NET](https://products.aspose.com/finance/python-net/) là một tính năng phong phú, có thể mở rộng và dễ sử dụng để xử lý báo cáo tài chính API. Các nhà phát triển có thể dễ dàng tải, xác thực, xem hoặc tạo các định dạng XBRL và iXBRL cho các giải pháp tài chính và kinh doanh. API cung cấp lớp XbrlDocument và lớp InlineXbrlDocument để tải các tệp XBRL và iXBRL.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Xác thực XBRL tài liệu" %}}

Xác thực tệp XBRL là cần thiết cho một số trường hợp chẳng hạn như để kiểm tra dữ liệu có đúng cấu trúc và định dạng hay không. Để xác thực tài liệu XBLR, trước tiên hãy sử dụng lớp XbrlDocument để tải tệp XBRL. Để sử dụng phương thức xác thực của lớp XbrlInstance, trước tiên hãy phức tạp hóa XbrlInstanceCollection với đối tượng XbrlInstances của XbrlDocument. Lặp lại từng XbrlInstance.ValidationErrors để lấy mã lỗi phù hợp và hành động tương ứng bằng cách in thông báo lỗi tùy chỉnh trên bảng điều khiển hoặc viết trong tệp.

{{% blocks/products/pf/feature-page-code h3="Python Mã để Xác thực XBRL Tệp" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "validate-xbrl-instance-file.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Xác thực iXBRL tài liệu" %}}

Để xác thực iXLRB, hãy tải nó qua lớp InlineXbrlDocument và sử dụng phương thức validate () của nó. Trong liệt kê ValidationErrorCode, mã lỗi xác thực được xác định cho mỗi quy tắc xác thực. Một số mã là ContextPeriodNoStartTime, ContextPeriodNoEndTime, ContextPeriodStartAfterEnd, ContextInstantNoTime, ContextScenarioXbrlNamespace, ContextScenarioXbrlSubstitutionGroup, v.v. Nhà phát triển có thể gỡ lỗi và hiển thị mã khi người dùng cuối hoặc có thể hiển thị hướng giải quyết vấn đề.

{{% blocks/products/pf/feature-page-code h3="Python Mã để Xác thực iXBRL Tài liệu" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "validate-ixbrl-file.py" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}
---
title: Xác thực Báo cáo Tài chính qua .NET
url: /vi/net/validate/
description:  C# mã để xác thực các báo cáo tài chính trong tệp XBRL và iXBRL qua thư viện .NET.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Xác thực các Tệp Báo cáo Tài chính qua C#" h2="Xác thực các định dạng báo cáo tài chính bao gồm XBRL và iXBRL trong các ứng dụng dựa trên .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) là một tính năng phong phú, có thể mở rộng và dễ sử dụng để xử lý báo cáo tài chính API. Các nhà phát triển có thể dễ dàng tải, xác thực, xem hoặc tạo các định dạng XBRL và iXBRL cho các giải pháp tài chính và kinh doanh. API cung cấp [XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) lớp học và  [InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) lớp để tải tệp XBRL và iXBRL.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Xác thực XBRL tài liệu" %}}

Xác thực tệp XBRL là cần thiết cho một số trường hợp chẳng hạn như để kiểm tra dữ liệu có đúng cấu trúc và định dạng hay không. Để xác thực tài liệu XBLR, trước tiên hãy sử dụng lớp XbrlDocument để tải tệp XBRL. Để sử dụng [xác thực ()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) phương pháp của [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) lớp học, trước hết hãy phức tạp hóa [XbrlInstanceCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) với đối tượng XbrlDocument XbrlInstances. Lặp lại từng [XbrlInstance.ValidationErrors](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/properties/validationerrors) để nhận mã lỗi phù hợp và hành động tương ứng bằng cách in thông báo lỗi tùy chỉnh trên bảng điều khiển hoặc viết trong tệp.

{{% blocks/products/pf/feature-page-code h3="C# Mã để Xác thực XBRL Tệp" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-xbrl-file.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Xác thực iXBRL tài liệu" %}}

Để xác thực iXLRB, hãy tải nó qua [InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) và sử dụng phương thức Validate () của nó. Trong [ValidationErrorCode](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.validator/validationerrorcode) liệt kê, mã lỗi xác thực được xác định cho mỗi quy tắc xác thực. Một số mã là ContextPeriodNoStartTime, ContextPeriodNoEndTime, ContextPeriodStartAfterEnd, ContextInstantNoTime, ContextScenarioXbrlNamespace, ContextScenarioXbrlSubstitutionGroup, v.v. Nhà phát triển có thể gỡ lỗi và hiển thị mã khi người dùng cuối hoặc có thể hiển thị hướng giải quyết vấn đề.

{{% blocks/products/pf/feature-page-code h3="C# Mã để Xác thực iXBRL Tài liệu" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-ixbrl-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}
{{< /blocks/products/pf/feature-page-wrap >}}
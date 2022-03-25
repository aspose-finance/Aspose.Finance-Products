---
title: Xác nhận Tài Chính Báo Cáo thông qua .NET
url: /vi/net/validate/
description:  C# mã để xác nhận Tài Chính báo cáo trong XBRL và iXBRL các tập tin thông qua .NET thư viện.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Xác nhận Báo Cáo Tài Chính Tập Tin thông qua C#" h2="Validating Tài Chính báo cáo các định dạng bao gồm XBRL và iXBRL trong vòng .NET các ứng dụng dựa trên." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) Là một tính năng phong phú, mở rộng và dễ dàng để sử dụng tài chính báo cáo chế biến API. Các nhà phát triển có thể dễ dàng tải, xác nhận, xem hoặc tạo ra XBRL và iXBRL các định dạng cho tài chính và kinh doanh các giải pháp. API cung cấp [XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Lớp và  [InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) Lớp cho tải XBRL và iXBRL các tập tin.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Xác nhận XBRL Tài Liệu" %}}

Xác nhận của XBRL tập tin là cần thiết cho một số trường hợp chẳng hạn như để kiểm tra dữ liệu là trong phải cấu trúc và định dạng. Để xác nhận XBLR tài liệu, Trước Hết Là sử dụng XbrlDocument lớp học để tải các XBRL tập tin. Để sử dụng các [XÁC NHẬN ()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) Phương pháp của [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) Lớp, trước hết là intialize các [XbrlInstanceCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) Với XbrlDocument đối tượng XbrlInstances. Iterate thông qua mỗi [XbrlInstance.ValidationErrors](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/properties/validationerrors) Để có được đúng mã lỗi và hành động cho phù hợp bằng in ấn các tùy chỉnh thông báo lỗi trên giao diện điều khiển hoặc bằng văn bản trong vòng một tập tin.

{{% blocks/products/pf/feature-page-code h3="C# mã để Xác Nhận XBRL Tập Tin" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-xbrl-file.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Xác nhận iXBRL Tài Liệu" %}}

Cho iXLRB xác nhận, tải nó thông qua [InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) Lớp và sử dụng của nó Xác Nhận () phương pháp. Trong [ValidationErrorCode](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.validator/validationerrorcode) Enumeration, xác nhận mã lỗi được xác định cho mỗi xác nhận quy tắc. Vài trong số mã số là ContextPeriodNoStartTime, ContextPeriodNoEndTime, ContextPeriodStartAfterEnd, ContextInstantNoTime, ContextScenarioXbrlNamespace, ContextScenarioXbrlSubstitutionGroup vv. Các nhà phát triển có thể gỡ lỗi và hiển thị mã như của người dùng cuối hoặc có thể hiển thị các hướng cho việc giải quyết các vấn đề.

{{% blocks/products/pf/feature-page-code h3="C# mã để Xác Nhận iXBRL Tài Liệu" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-ixbrl-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}
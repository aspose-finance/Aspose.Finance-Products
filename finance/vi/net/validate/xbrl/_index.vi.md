---
title: Xác thực XBRL Tệp qua C#
description: Mã mẫu để xác thực tệp XBRL. Sử dụng API mã mẫu để xác thực hàng loạt XBRL tệp trong các ứng dụng dựa trên .NET. 
url: /vi/net/validate/xbrl/
family: finance
platformtag: net
feature: validate
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Xác thực XBRL Tệp qua C#" h2="Xác thực các báo cáo tài chính ở định dạng XBRL mà không cần cài đặt Microsoft Office hoặc bất kỳ phần mềm nào khác." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Cách xác thực XBRL tệp" %}}

Thực hiện theo các bước trong đoạn mã hoặc nâng cao đoạn mã khi ứng dụng của bạn cần để xác thực tài liệu XBRL ngôn ngữ báo cáo kinh doanh có thể mở rộng. Đảm bảo có các yêu cầu xác thực trong ứng dụng của bạn.

1. Tải tệp XBRL bằng [Lớp XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Ví dụ.1. Để kiểm tra tính hợp lệ của tệp đã tải, để tệp phải khớp với [Đặc điểm kỹ thuật XBRL](http://www.xbrl.org/specification/inlinexbrl-part1/rec-2013-11-18/inlinexbrl-part1-rec-2013-11-18.html)1. Để kiểm tra tính hợp lệ, hãy sử dụng [Xác thực ()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) phương pháp của [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) lớp.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu xác thực" %}}
Để tiếp tục xác thực XBRL tài liệu, .NET Finance API là yêu cầu chính cần có trong ứng dụng. 
- Cài đặt nó thông qua dòng lệnh là `` nuget install Aspose.Finance '' hoặc thông qua Bảng điều khiển Trình quản lý Gói của Visual Studio với `` Cài đặt Gói Aspose.Finance ''.
- Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [tải xuống](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# mã để xác thực XBRL tệp" offSpacer="" %}}

{{< gist "aspose-com-gists" "1272da1f804f8cef122600269db09fbb" "validate-xbrl-instance-file.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Các tùy chọn xác thực khác" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/validate/ixbrl/" name="XBRL" description="Ngôn ngữ Báo cáo Kinh doanh Có thể Mở rộng Nội tuyến" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
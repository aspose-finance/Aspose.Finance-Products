---
title: Tạo tệp iXBRL (inline xbrl) qua C#
description: Mã mẫu để tạo tệp iXBRL (inline xbrl). Sử dụng API mã ví dụ để tạo hàng loạt tệp iXBRL (xbrl nội tuyến) trong các ứng dụng dựa trên .NET. 
url: /vi/net/create/ixbrl/
family: finance
platformtag: net
feature: create
informat: iXBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Tạo Tệp iXBRL (xbrl nội tuyến) qua C#" h2="iXBRL (inline xbrl) tạo tệp mà không cần cài đặt Microsoft Office hoặc bất kỳ phần mềm nào khác." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Cách tạo tệp iXBRL (xbrl nội tuyến)" %}}

Thực hiện theo các bước trong đoạn mã hoặc nâng cao đoạn mã khi ứng dụng của bạn cần để tạo các tệp ngôn ngữ báo cáo kinh doanh iXBRL (inline xbrl) có thể mở rộng. Đảm bảo có các yêu cầu tạo trong ứng dụng của bạn.

1. Tạo ra [Lớp InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) Ví dụ.2. Xây dựng cây dom phần tử
3. Gọi cho [Lưu phương pháp](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline.inlinexbrldocument/save/methods/1) bằng cách cung cấp đường dẫn tệp đích.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu tạo" %}}
Để tiếp tục tạo tài liệu iXBRL (inline xbrl), .NET Finance API là yêu cầu chính cần có trong ứng dụng. 
- Cài đặt nó thông qua dòng lệnh là `` nuget install Aspose.Finance '' hoặc thông qua Bảng điều khiển Trình quản lý Gói của Visual Studio với `` Cài đặt Gói Aspose.Finance ''.
- Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [tải xuống](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# mã để tạo tệp XBRL" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e4ec79e68a0658a63611ae321b110a48" "create-ixbrl.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Các tùy chọn tạo khác" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX Yêu cầu" description="Định dạng 1.03 hoặc 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX Phản hồi" description="Định dạng 1.03 hoặc 2.2" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
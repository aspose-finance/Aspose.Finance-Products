---
title: Tạo XBRL Tệp qua C#
description: Mã mẫu để tạo tệp XBRL. Sử dụng API mã mẫu để tạo hàng loạt XBRL tệp trong các ứng dụng dựa trên .NET. 
url: /vi/net/create/xbrl/
family: finance
platformtag: net
feature: create
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Tạo XBRL Tệp qua C#" h2="XBRL tạo tệp mà không cần cài đặt Microsoft Office hoặc bất kỳ phần mềm nào khác." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Cách tạo XBRL Tệp" %}}

Thực hiện theo các bước trong đoạn mã hoặc nâng cao đoạn mã khi ứng dụng của bạn cần để tạo tệp XBRL ngôn ngữ báo cáo kinh doanh có thể mở rộng. Đảm bảo có các yêu cầu tạo trong ứng dụng của bạn.

1. Tạo ra [Lớp XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Ví dụ.1. Để tạo một tài liệu phiên bản XBRL mới [XbrlInstanceCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) và [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance).1. Thêm tham chiếu giản đồ bằng cách sử dụng [SchemaRefCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemarefcollection)1. Tùy thuộc vào tính chất ứng dụng, hãy thêm ngữ cảnh, đơn vị, mục, liên kết chú thích cuối trang và hơn thế nữa.1. Gọi [Lưu phương pháp](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) bằng cách cung cấp đường dẫn tệp đích.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu tạo" %}}
Để tiếp tục XBRL tạo tài liệu, .NET Finance API là yêu cầu chính cần có trong ứng dụng. 
- Cài đặt nó qua dòng lệnh là `` nuget install Aspose.Finance `` '' hoặc qua Bảng điều khiển Trình quản lý Gói của Visual Studio với `` Cài đặt-Gói Aspose.Finance ''.
- Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [tải xuống](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# mã để tạo tệp XBRL" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-schema-reference.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Các tùy chọn tạo khác" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX Yêu cầu" description="Định dạng 1.03 hoặc 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX Phản hồi" description="Định dạng 1.03 hoặc 2.2" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
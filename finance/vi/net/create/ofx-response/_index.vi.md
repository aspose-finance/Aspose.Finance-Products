---
title: Tạo OFX Tệp Phản hồi qua C#
description: Mã mẫu để tạo tệp phản hồi OFX. Sử dụng API mã mẫu để tạo hàng loạt OFX tệp phản hồi trong các ứng dụng dựa trên .NET. 
url: /vi/net/create/ofx-response/
family: finance
platformtag: net
feature: create
informat: OFX Response
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Tạo OFX Tệp phản hồi qua C#" h2="OFX tạo tệp phản hồi mà không cần cài đặt Microsoft Office hoặc bất kỳ phần mềm nào khác." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Cách tạo OFX Tệp phản hồi" %}}

Thực hiện theo các bước trong đoạn mã hoặc nâng cao đoạn mã theo nhu cầu của ứng dụng sau khi có các yêu cầu tạo trong ứng dụng của bạn.

1. Tạo ra [Lớp OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) sự vật.1. Chỉ định các thuộc tính có liên quan bằng cách sử dụng các lớp khác nhau được cung cấp bởi API như [SignonResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [StatementTransactionResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse), [StatementTransaction](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction)1. Sử dụng ofxVersion V2x hoặc V1x cho các tệp xml và sgml tương ứng từ [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) dưới dạng tham số trong phương thức Lưu.1. Gọi [Lưu phương pháp](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument/methods/save) bằng cách cung cấp tệp đích và ofxVersion.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu tạo" %}}
Để tiếp tục OFX tạo tệp phản hồi, .NET Finance API là yêu cầu chính cần có trong ứng dụng tạo báo cáo. 
- Cài đặt nó thông qua dòng lệnh là `` nuget install Aspose.Finance '' hoặc thông qua Bảng điều khiển Trình quản lý Gói của Visual Studio với `` Cài đặt Gói Aspose.Finance ''.
- Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [tải xuống](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# mã để OFX tạo tệp phản hồi" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Các tùy chọn tạo khác" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX Tệp Yêu cầu" description="Định dạng 1.03 hoặc 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL Tệp" description="Ngôn ngữ Báo cáo Kinh doanh Có thể Mở rộng" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
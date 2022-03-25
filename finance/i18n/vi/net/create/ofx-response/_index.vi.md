---
title: Tạo ra OFX Đáp Ứng Tập Tin thông qua C#
description: Mẫu mã cho OFX đáp ứng tập tin sáng tạo. Sử dụng API Ví dụ mã cho hàng loạt OFX đáp ứng các tập tin thế hệ trong vòng .NET các ứng dụng dựa trên. 
url: /vi/net/create/ofx-response/
family: finance
platformtag: net
feature: create
informat: OFX Response
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Tạo ra OFX Đáp Ứng Các Tập Tin thông qua C#" h2="OFX đáp ứng các tập tin sáng tạo mà không cần phải Microsoft Văn Phòng được cài đặt hoặc bất kỳ phần mềm khác." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Làm thế nào để Tạo Ra OFX Đáp Ứng Các Tập Tin" %}}

Thực hiện theo các bước trong mã snippet hoặc tăng cường nó như là của ứng dụng của bạn nhu cầu sau khi có việc tạo ra các yêu cầu trong vòng ứng dụng của bạn.

1. Tạo ra [OfxResponseDocument lớp](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) Đối tượng.1. Chỉ định có liên quan tính chất sử dụng khác nhau Lớp Học Được cung cấp bởi API như [SignonResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [StatementTransactionResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse), [StatementTransaction](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction)1. Sử dụng các ofxVersion V2x hoặc V1x cho XML và sgml các tập tin tương ứng từ [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) Như tham số trong Tiết Kiệm phương pháp.1. Cuộc gọi các [Tiết kiệm phương pháp](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument/methods/save) Bằng cách cung cấp các tập tin mục tiêu và ofxVersion.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Sáng Tạo Yêu Cầu" %}}
Để tiến hành cho OFX Đáp Ứng tập tin sáng tạo, .NET Finance API là chính yêu cầu để được bao gồm trong báo cáo thế hệ ứng dụng. 
- Cài đặt nó thông qua dòng lệnh như '''nuget cài đặt Aspose.Finance'' 'hoặc thông qua Gói Quản Lý Giao Diện Điều Khiển của Visual Studio với '''Install-Gói Aspose.Finance' ''.
- Ngoài ra, có được các ẩn MSI cài đặt hoặc DLL trong một ZIP tập tin từ [Tải](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# mã cho OFX đáp ứng các tập tin sáng tạo" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Khác Sáng Tạo Tùy Chọn" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX yêu cầu Tập Tin" description="1.03 hoặc 2.2 Định Dạng" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL tập tin" description="Mở rộng Kinh Doanh Báo Cáo Ngôn Ngữ" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
---
title: Tạo ra OFX Yêu Cầu Tập Tin thông qua C#
description: Mẫu mã cho OFX yêu cầu tập tin sáng tạo. Sử dụng API Ví dụ mã cho hàng loạt OFX yêu cầu các tập tin thế hệ trong vòng .NET các ứng dụng dựa trên. 
url: /vi/net/create/ofx-request/
family: finance
platformtag: net
feature: create
informat: OFX Request
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Tạo ra OFX Yêu Cầu Các Tập Tin thông qua C#" h2="OFX yêu cầu các tập tin sáng tạo mà không cần phải Microsoft Văn Phòng được cài đặt hoặc bất kỳ phần mềm khác." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Làm thế nào để Tạo Ra OFX Yêu Cầu Các Tập Tin" %}}

Sau khi có các OFX Yêu Cầu các tập tin sáng tạo yêu cầu trong vòng ứng dụng của bạn, thực hiện theo các bước trong mã snippet hoặc tăng cường nó như yêu cầu của bạn.

1. Tạo ra [OfxRequestDocument lớp](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) Đối tượng.1. Chỉ định có liên quan tính chất sử dụng khác nhau Lớp Học Được cung cấp bởi API như [SignonRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [FinancialInstitution](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution), [StatementTransactionRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest)1. Sử dụng các ofxVersion V2x hoặc V1x cho XML và sgml các tập tin tương ứng từ [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) Như tham số trong Tiết Kiệm phương pháp.1. Cuộc gọi các [Tiết kiệm phương pháp](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument/methods/save) Bằng cách cung cấp các tập tin mục tiêu và ofxVersion.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Sáng Tạo Yêu Cầu" %}}
Để tiến hành cho OFX Yêu Cầu tập tin sáng tạo, .NET Finance API là chính yêu cầu để được bao gồm trong báo cáo thế hệ ứng dụng. 
- Cài đặt nó thông qua dòng lệnh như '''nuget cài đặt Aspose.Finance'' 'hoặc thông qua Gói Quản Lý Giao Diện Điều Khiển của Visual Studio với '''Install-Gói Aspose.Finance' ''.
- Ngoài ra, có được các ẩn MSI cài đặt hoặc DLL trong một ZIP tập tin từ [Tải](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# mã cho OFX yêu cầu các tập tin sáng tạo" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-request-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Khác Sáng Tạo Tùy Chọn" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX đáp ứng Tập Tin" description="1.03 hoặc 2.2 Định Dạng" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL tập tin" description="Mở rộng Kinh Doanh Báo Cáo Ngôn Ngữ" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
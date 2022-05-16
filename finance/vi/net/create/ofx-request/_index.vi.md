---
title: Tạo OFX Tệp Yêu cầu qua C#
description: Mã mẫu cho OFX yêu cầu tạo tệp. Sử dụng API mã mẫu để tạo hàng loạt OFX tệp yêu cầu trong các ứng dụng dựa trên .NET. 
url: /vi/net/create/ofx-request/
family: finance
platformtag: net
feature: create
informat: OFX Request
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Tạo OFX Tệp Yêu cầu qua C#" h2="OFX yêu cầu tạo tệp mà không cần cài đặt Microsoft Office hoặc bất kỳ phần mềm nào khác." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Cách tạo OFX Tệp yêu cầu" %}}

Sau khi có OFX Yêu cầu yêu cầu tạo tệp trong ứng dụng của bạn, Hãy làm theo các bước trong đoạn mã hoặc nâng cao nó theo yêu cầu của bạn.

1. Tạo ra [Lớp OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) vật.1. Chỉ định các thuộc tính có liên quan bằng cách sử dụng các lớp khác nhau được cung cấp bởi API như [SignonRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [Tổ chức tài chính](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution), [StatementTransactionRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest)1. Sử dụng ofxVersion V2x hoặc V1x cho các tệp xml và sgml tương ứng từ [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) dưới dạng tham số trong phương thức Lưu.1. Gọi [Lưu phương pháp](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument/methods/save) bằng cách cung cấp tệp đích và ofxVersion.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu tạo" %}}
Để tiếp tục OFX Yêu cầu tạo tệp, .NET Finance API là yêu cầu chính cần có trong ứng dụng tạo báo cáo. 
- Cài đặt nó qua dòng lệnh là `` nuget install Aspose.Finance `` '' hoặc qua Bảng điều khiển Trình quản lý Gói của Visual Studio với `` Cài đặt-Gói Aspose.Finance ''.
- Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [tải xuống](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# mã để OFX yêu cầu tạo tệp" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-request-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Các tùy chọn tạo khác" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX Tệp Phản hồi" description="Định dạng 1.03 hoặc 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL Tệp" description="Ngôn ngữ Báo cáo Kinh doanh Có thể Mở rộng" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
---
title: Tạo OFX Tệp Phản hồi qua Python
description: Mã mẫu để tạo tệp phản hồi OFX. Sử dụng API mã mẫu để tạo hàng loạt OFX tệp phản hồi trong các ứng dụng dựa trên Python. 
url: /vi/python-net/create/ofx-response/
family: finance
platformtag: python
feature: create
informat: OFX Response
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Tạo OFX Tệp phản hồi qua Python" h2="OFX tạo tệp phản hồi mà không cần cài đặt Microsoft Office hoặc bất kỳ phần mềm nào khác." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Cách tạo OFX Tệp phản hồi" %}}

Thực hiện theo các bước trong đoạn mã hoặc nâng cao đoạn mã theo nhu cầu của ứng dụng sau khi có các yêu cầu tạo trong ứng dụng của bạn.

1. Tạo đối tượng lớp OfxResponseDocument.1. Chỉ định các thuộc tính có liên quan bằng cách sử dụng các lớp khác nhau do API cung cấp như SignonResponse, StatementTransactionResponse, StatementTransaction1. Sử dụng ofxVersion V2x hoặc V1x cho các tệp xml và sgml tương ứng từ OfxVersionEnum làm tham số trong phương thức lưu.1. Gọi phương thức lưu bằng cách cung cấp tệp đích và ofxVersion.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu tạo" %}}
Để tiếp tục OFX tạo tệp phản hồi, hãy đảm bảo rằng bạn có các điều kiện tiên quyết sau. 
- Hệ điều hành dựa trên Microsoft Windows hoặc Linux.- Python 3.5 trở lên.- Aspose.Finance cho Python được tham chiếu trong dự án của bạn.{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python mã để OFX tạo tệp phản hồi" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Các tùy chọn tạo khác" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-request/" name="OFX Tệp Yêu cầu" description="Định dạng 1.03 hoặc 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/xbrl/" name="XBRL Tệp" description="Ngôn ngữ Báo cáo Kinh doanh Có thể Mở rộng" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
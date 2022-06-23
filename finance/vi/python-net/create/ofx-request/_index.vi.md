---
title: Tạo OFX Tệp Yêu cầu qua Python
description: Mã mẫu cho OFX yêu cầu tạo tệp. Sử dụng API mã mẫu để tạo hàng loạt OFX tệp yêu cầu trong các ứng dụng dựa trên Python. 
url: /vi/python-net/create/ofx-request/
family: finance
platformtag: python
feature: create
informat: OFX Request
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Tạo OFX Tệp Yêu cầu qua Python" h2="OFX yêu cầu tạo tệp mà không cần cài đặt Microsoft Office hoặc bất kỳ phần mềm nào khác." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Cách tạo OFX Tệp yêu cầu" %}}

Sau khi có OFX Yêu cầu yêu cầu tạo tệp trong ứng dụng của bạn, Hãy làm theo các bước trong đoạn mã hoặc nâng cao nó theo yêu cầu của bạn.

1. Tạo đối tượng lớp OfxRequestDocument.2. Gán các thuộc tính có liên quan bằng cách sử dụng các lớp khác nhau do API cung cấp như SignonRequest, FinancialInstitution], StatementTransactionRequest
3. Sử dụng ofxVersion V2x hoặc V1x cho các tệp xml và sgml tương ứng từ OfxVersionEnum làm tham số trong phương thức Lưu.
4. Gọi phương thức lưu bằng cách cung cấp tệp đích và ofxVersion.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu cầu tạo" %}}
Để tiếp tục OFX Yêu cầu tạo tệp, hãy đảm bảo rằng bạn có các điều kiện tiên quyết sau. 
- Hệ điều hành dựa trên Microsoft Windows hoặc Linux.- Python 3.5 trở lên.- Aspose.Finance cho Python được tham chiếu trong dự án của bạn.{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python mã để OFX yêu cầu tạo tệp" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-request-files.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Các tùy chọn tạo khác" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-response/" name="OFX Tệp Phản hồi" description="Định dạng 1.03 hoặc 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/xbrl/" name="XBRL Tệp" description="Ngôn ngữ Báo cáo Kinh doanh Có thể Mở rộng" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
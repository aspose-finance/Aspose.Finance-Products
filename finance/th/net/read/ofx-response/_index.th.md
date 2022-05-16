---
title: อ่านไฟล์ตอบกลับ OFX ผ่าน C#
description: โค้ดตัวอย่างสำหรับการอ่านไฟล์ตอบกลับ OFX ใช้โค้ดตัวอย่าง API เพื่ออ่านไฟล์ตอบกลับแบบกลุ่ม OFX ภายในแอปพลิเคชันที่ใช้ .NET 
url: /th/net/read/ofx-response/
family: finance
platformtag: net
feature: read
informat: OFX response
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="อ่านไฟล์ตอบกลับ OFX ผ่าน C#" h2="การอ่านรายงานทางการเงินในรูปแบบการตอบสนองของ OFX โดยไม่ต้องติดตั้ง Microsoft Office หรือซอฟต์แวร์อื่นๆ" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="วิธีอ่านOFXไฟล์ตอบกลับ" %}}

ทำตามขั้นตอนในข้อมูลโค้ดหรือปรับปรุงตามที่แอปพลิเคชันของคุณต้องการสำหรับการอ่านไฟล์ตอบกลับภาษาการรายงานทางธุรกิจที่ขยายได้ OFX ไฟล์ ตรวจสอบให้แน่ใจว่ามีข้อกำหนดในการอ่านในใบสมัครของคุณ

1. สร้าง [OfxResponseDocument คลาส](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) ตัวอย่าง.1. ส่งชื่อของไฟล์ตอบกลับ OFX ที่ถูกต้องเป็นพารามิเตอร์1. เพื่อให้ได้รายละเอียดภายในของไฟล์ ให้ใช้คลาสที่เกี่ยวข้องเช่น [SignonResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดในการอ่าน" %}}
ในการดำเนินการอ่านเอกสารตอบกลับ OFX .NET Finance API เป็นข้อกำหนดหลักที่จะรวมไว้ในใบสมัคร 
- ติดตั้งผ่านบรรทัดคำสั่งเป็น ```nuget install Aspose.Finance``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Finance```
- หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# รหัสสำหรับอ่าน OFX ไฟล์ตอบกลับ" offSpacer="" %}}

{{< gist "aspose-finance-gists" "01125f8901f4fde8dfd5c9764b59ef2f" "read-ofx-response.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="ตัวเลือกการอ่านอื่นๆ" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/read/ixbrl/" name="iXBRL" description="ภาษาการรายงานธุรกิจที่ขยายได้แบบอินไลน์" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
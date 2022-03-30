---
title: ตรวจสอบ iXBRL ไฟล์ผ่าน C#
description: โค้ดตัวอย่างสำหรับการตรวจสอบความถูกต้องของไฟล์ iXBRL ใช้โค้ดตัวอย่าง API เพื่อตรวจสอบความถูกต้องของไฟล์แบตช์ iXBRL ภายในแอปพลิเคชันที่ใช้ .NET 
url: /th/net/validate/ixbrl/
family: finance
platformtag: net
feature: validate
informat: iXBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="ตรวจสอบ iXBRL ไฟล์ผ่าน C#" h2="การตรวจสอบความถูกต้องของรายงานทางการเงินในรูปแบบ iXBRL โดยไม่ต้องติดตั้ง Microsoft Office หรือซอฟต์แวร์อื่นๆ" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="วิธีตรวจสอบความถูกต้องของ iXBRL Files" %}}

ทำตามขั้นตอนในข้อมูลโค้ดหรือปรับปรุงตามที่แอปพลิเคชันของคุณต้องการสำหรับการตรวจสอบความถูกต้องของเอกสารภาษาการรายงานทางธุรกิจที่ขยายได้ iXBRL ตรวจสอบให้แน่ใจว่ามีข้อกำหนดในการตรวจสอบความถูกต้องภายในใบสมัครของคุณ

1. โหลดไฟล์ iXBRL โดยใช้ [InlineXbrlคลาสเอกสาร](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) ตัวอย่าง.1. เพื่อตรวจสอบความถูกต้องของไฟล์ที่โหลดมานั้นต้องตรงกับ [iXBRL ข้อมูลจำเพาะ](http://www.xbrl.org/specification/inlinexbrl-part1/rec-2013-11-18/inlinexbrl-part1-rec-2013-11-18.html)1. ใช้ [ตรวจสอบความถูกต้อง()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument/methods/validate) วิธีการตรวจสอบความถูกต้องของไฟล์
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการตรวจสอบ" %}}
ในการดำเนินการตรวจสอบเอกสาร iXBRL ฉบับ .NET Finance API เป็นข้อกำหนดหลักที่จะรวมไว้ในใบสมัคร 
- ติดตั้งผ่านบรรทัดคำสั่งเป็น ``` ติดตั้ง nuget Aspose.Finance``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Finance```
- หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# รหัสสำหรับตรวจสอบ iXBRL ไฟล์" offSpacer="" %}}

{{< gist "aspose-com-gists" "1272da1f804f8cef122600269db09fbb" "validate-ixbrl-file.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="ตัวเลือกการตรวจสอบความถูกต้องอื่นๆ" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/validate/xbrl/" name="XBRL" description="ภาษาการรายงานทางธุรกิจที่ขยายได้" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
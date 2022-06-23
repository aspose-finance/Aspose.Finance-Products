---
title: อ่าน iXBRL ไฟล์ผ่าน C#
description: โค้ดตัวอย่างสำหรับการอ่านไฟล์ iXBRL ใช้โค้ดตัวอย่าง API เพื่ออ่านไฟล์แบตช์ iXBRL ภายในแอปพลิเคชันที่ใช้ .NET 
url: /th/net/read/ixbrl/
family: finance
platformtag: net
feature: read
informat: iXBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="อ่าน iXBRL ไฟล์ผ่าน C#" h2="การอ่านรายงานทางการเงินในรูปแบบ iXBRL โดยไม่ต้องติดตั้ง Microsoft Office หรือซอฟต์แวร์อื่นๆ" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="วิธีอ่าน iXBRL Files" %}}

ทำตามขั้นตอนในข้อมูลโค้ดหรือปรับปรุงตามที่แอปพลิเคชันของคุณต้องการสำหรับการอ่านเอกสารภาษาการรายงานทางธุรกิจที่ขยายได้ iXBRL ตรวจสอบให้แน่ใจว่ามีข้อกำหนดในการอ่านในใบสมัครของคุณ

1. สร้าง [InlineXbrlคลาสเอกสาร](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) ตัวอย่าง.1. ส่งชื่อไฟล์ iXBRL ที่ถูกต้องเป็นพารามิเตอร์1. เพื่อให้ได้รายละเอียดภายในของไฟล์ ให้ใช้คลาสที่เกี่ยวข้องเช่น [InlineFact](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinefact), [บริบท](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context), [หน่วย](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/unit) 
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดในการอ่าน" %}}
หากต้องการอ่านเอกสาร iXBRL ต่อ .NET Finance API เป็นข้อกำหนดหลักที่จะรวมไว้ในใบสมัคร 
- ติดตั้งผ่านบรรทัดคำสั่งเป็น ``` ติดตั้ง nuget Aspose.Finance``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Finance```
- หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# รหัสสำหรับอ่าน iXBRL ไฟล์" offSpacer="" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "read-ixbrl-file.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="ตัวเลือกการอ่านอื่นๆ" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/read/xbrl/" name="XBRL" description="ภาษาการรายงานทางธุรกิจที่ขยายได้" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
---
title: สร้างไฟล์ iXBRL(inline xbrl) ผ่าน C#
description: โค้ดตัวอย่างสำหรับการสร้างไฟล์ iXBRL(inline xbrl) ใช้รหัสตัวอย่าง API สำหรับการสร้างไฟล์แบทช์ iXBRL(inline xbrl) ภายในแอปพลิเคชันที่ใช้ .NET 
url: /th/net/create/ixbrl/
family: finance
platformtag: net
feature: create
informat: iXBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="สร้างไฟล์ iXBRL(inline xbrl) ผ่าน C#" h2="iXBRL(inline xbrl) การสร้างไฟล์โดยไม่จำเป็นต้องติดตั้ง Microsoft Office หรือซอฟต์แวร์อื่นๆ" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="วิธีสร้างไฟล์ iXBRL(inline xbrl)" %}}

ทำตามขั้นตอนในข้อมูลโค้ดหรือปรับปรุงตามที่แอปพลิเคชันของคุณต้องการสำหรับการสร้างไฟล์ iXBRL(inline xbrl) ของภาษาการรายงานทางธุรกิจที่ขยายได้ ตรวจสอบให้แน่ใจว่ามีข้อกำหนดในการสร้างภายในแอปพลิเคชันของคุณ

1. สร้าง [InlineXbrlคลาสเอกสาร](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) ตัวอย่าง.2. สร้างองค์ประกอบ dom tree
3. โทรหา [บันทึกวิธีการ](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline.inlinexbrldocument/save/methods/1) โดยระบุเส้นทางไฟล์เป้าหมาย

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดในการสร้าง" %}}
หากต้องการดำเนินการสร้างเอกสาร iXBRL(inline xbrl) ต่อไป .NET Finance API เป็นข้อกำหนดหลักที่จะรวมไว้ในแอปพลิเคชัน 
- ติดตั้งผ่านบรรทัดคำสั่งเป็น ```nuget install Aspose.Finance``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Finance```
- หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="รหัส C# สำหรับ XBRL การสร้างไฟล์" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e4ec79e68a0658a63611ae321b110a48" "create-ixbrl.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="ตัวเลือกการสร้างอื่นๆ" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX คำขอ" description="1.03 หรือ 2.2 รูปแบบ" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX ตอบกลับ" description="1.03 หรือ 2.2 รูปแบบ" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
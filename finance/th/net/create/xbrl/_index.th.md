---
title: สร้าง XBRL ไฟล์ผ่าน C#
description: โค้ดตัวอย่างสำหรับการสร้างไฟล์ XBRL ใช้โค้ดตัวอย่าง API สำหรับการสร้างไฟล์แบทช์ XBRL ภายในแอปพลิเคชันที่ใช้ .NET 
url: /th/net/create/xbrl/
family: finance
platformtag: net
feature: create
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="สร้าง XBRL ไฟล์ผ่าน C#" h2="การสร้างไฟล์ XBRL โดยไม่ต้องติดตั้ง Microsoft Office หรือซอฟต์แวร์อื่นๆ" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="วิธีสร้าง XBRL ไฟล์" %}}

ทำตามขั้นตอนในข้อมูลโค้ดหรือปรับปรุงตามที่แอปพลิเคชันของคุณต้องการสำหรับการสร้างไฟล์ภาษาการรายงานทางธุรกิจที่ขยายได้ XBRL ตรวจสอบให้แน่ใจว่ามีข้อกำหนดในการสร้างภายในแอปพลิเคชันของคุณ

1. สร้าง [XbrlDocument class](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) ตัวอย่าง.1. ในการสร้าง XBRL เอกสารอินสแตนซ์ ใหม่ [XbrlInstanceCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) และ [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance).1. เพิ่มการอ้างอิงสคีมาโดยใช้ [สคีมาRefCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemarefcollection)1. ขึ้นอยู่กับลักษณะแอปพลิเคชัน เพิ่มบริบท หน่วย รายการ ลิงก์เชิงอรรถและอื่น ๆ1. โทรหา [บันทึกวิธีการ](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) โดยระบุเส้นทางไฟล์เป้าหมาย
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดในการสร้าง" %}}
หากต้องการดำเนินการสร้างเอกสาร XBRL ต่อไป .NET Finance API เป็นข้อกำหนดหลักที่จะรวมไว้ในแอปพลิเคชัน 
- ติดตั้งผ่านบรรทัดคำสั่งเป็น ``` ติดตั้ง nuget Aspose.Finance``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Finance```
- หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="รหัส C# สำหรับ XBRL การสร้างไฟล์" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-schema-reference.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="ตัวเลือกการสร้างอื่นๆ" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX คำขอ" description="1.03 หรือ 2.2 รูปแบบ" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX ตอบกลับ" description="1.03 หรือ 2.2 รูปแบบ" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
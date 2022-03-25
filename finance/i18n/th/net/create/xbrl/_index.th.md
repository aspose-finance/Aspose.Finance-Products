---
title: สร้าง XBRL ไฟล์ผ่าน C#
description: ตัวอย่างโค้ดสำหรับการสร้างไฟล์ XBRL ใช้รหัสตัวอย่าง API สำหรับการสร้างไฟล์แบทช์ XBRL ภายในแอพพลิเคชันที่ใช้ .NET 
url: /th/net/create/xbrl/
family: finance
platformtag: net
feature: create
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="สร้าง XBRL ไฟล์ผ่าน C#" h2="XBRL การสร้างไฟล์โดยไม่จำเป็นต้องติดตั้ง Microsoft Office หรือซอฟต์แวร์อื่นๆ" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="วิธีการสร้าง XBRL ไฟล์" %}}

ทำตามขั้นตอนในโค้ดตัวอย่างหรือเพิ่มมันเป็นความต้องการของแอพลิเคชันของคุณสำหรับการสร้าง Extensible ธุรกิจรายงานภาษา XBRL ไฟล์ตรวจสอบให้แน่ใจว่ามีความต้องการในการสร้างภายในแอปพลิเคชันของคุณ

1. สร้าง [ระดับเอกสาร xbrldocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) อินสแตนซ์1. เมื่อต้องการสร้างเอกสารอินสแตนซ์ XBRL ใหม่ [Xbrlinstancecollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) และ [Xbrlinstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance).1. เพิ่มการอ้างอิง Schema โดยใช้ [Schemarefcollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemarefcollection)1. ขึ้นอยู่กับธรรมชาติของแอ็พพลิเคชันเพิ่มบริบทหน่วยรายการลิงก์เชิงอรรถและอื่นๆ1. โทรหา [บันทึกวิธีการ](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) โดยให้เส้นทางไฟล์เป้าหมาย
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ความต้องการการสร้าง" %}}
XBRL Documents Generation, .NET Finance API คือข้อกำหนดหลักที่จะรวมอยู่ในใบสมัคร 
- ติดตั้งผ่านบรรทัดคำสั่งเป็น '''nuget ติดตั้ง Aspose.Finance'''หรือผ่านทางคอนโซลผู้จัดการแพคเกจของ Visual Studio กับ'' 'install-Package Aspose.Finance'''
- หรือรับการติดตั้ง MSI แบบออฟไลน์หรือ dlls ในไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# รหัสสำหรับ XBRL การสร้างไฟล์" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-schema-reference.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="ตัวเลือกการสร้างอื่นๆ" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX คำขอ" description="รูปแบบ1.03หรือ2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX การตอบสนอง" description="รูปแบบ1.03หรือ2.2" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
---
title: อ่าน XBRL ไฟล์ผ่าน C#
description: ตัวอย่างรหัสสำหรับ XBRL การอ่านไฟล์ใช้ API ตัวอย่างรหัสเพื่ออ่านแบทช์ XBRL ไฟล์ภายใน .NET การใช้งานตาม 
url: /th/net/read/xbrl/
family: finance
platformtag: net
feature: read
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="อ่าน XBRL ไฟล์ผ่าน C#" h2="อ่านรายงานทางการเงินในรูปแบบ XBRL โดยไม่จำเป็นต้องติดตั้ง Microsoft Office หรือซอฟต์แวร์อื่นๆ" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="วิธีการอ่าน XBRL ไฟล์" %}}

ทำตามขั้นตอนในโค้ดตัวอย่างหรือเพิ่มมันเป็นความต้องการของแอพลิเคชันของคุณสำหรับการอ่าน Extensible ธุรกิจรายงานภาษา XBRL ไฟล์ตรวจสอบให้แน่ใจว่ามีข้อกำหนดในการอ่านภายในแอปพลิเคชันของคุณ

1. สร้าง [ระดับเอกสาร xbrldocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) อินสแตนซ์1. ส่งชื่อไฟล์ XBRL ที่ถูกต้องเป็นพารามิเตอร์1. เพื่อให้ได้รายละเอียดภายในของไฟล์ให้ใช้คลาสที่เกี่ยวข้องเช่น [Schemarefcollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemarefcollection),, [บริบท](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context),, [หน่วย](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/unit) 
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ความต้องการในการอ่าน" %}}
XBRL เอกสาร .NET Finance API เป็นข้อกำหนดหลักที่จะรวมอยู่ในใบสมัคร 
- ติดตั้งผ่านบรรทัดคำสั่งเป็น '''nuget ติดตั้ง Aspose.Finance'''หรือผ่านทางคอนโซลผู้จัดการแพคเกจของ Visual Studio กับ'' 'install-Package Aspose.Finance'''
- หรือรับการติดตั้ง MSI แบบออฟไลน์หรือ dlls ในไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# รหัสเพื่ออ่าน XBRL ไฟล์" offSpacer="" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "read-xbrl-file.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="ตัวเลือกการอ่านอื่นๆ" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/read/ixbrl/" name="iXBRL" description="ภาษารายงานธุรกิจแบบอินไลน์ Extensible" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
---
title: ตรวจสอบไฟล์ XBRL ผ่าน C#
description: ตัวอย่างรหัสสำหรับ XBRL การตรวจสอบไฟล์ใช้รหัสตัวอย่าง API เพื่อตรวจสอบไฟล์ batch XBRL ภายในแอพพลิเคชันที่ใช้ .NET 
url: /th/net/validate/xbrl/
family: finance
platformtag: net
feature: validate
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="ตรวจสอบไฟล์ XBRL ผ่าน C#" h2="ตรวจสอบรายงานทางการเงินในรูปแบบ XBRL โดยไม่จำเป็นต้องติดตั้ง Microsoft Office หรือซอฟต์แวร์อื่นๆ" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="วิธีการตรวจสอบไฟล์ XBRL" %}}

ทำตามขั้นตอนในโค้ดตัวอย่างหรือเพิ่มมันเป็นความต้องการของแอพลิเคชันของคุณสำหรับการตรวจสอบ Extensible ธุรกิจรายงานภาษา XBRL เอกสารให้แน่ใจว่ามีการตรวจสอบความต้องการภายในโปรแกรมของคุณ

1. โหลดไฟล์ XBRL โดยใช้ [ระดับเอกสาร xbrldocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) อินสแตนซ์1. หากต้องการตรวจสอบความถูกต้องของไฟล์ที่โหลดเพื่อให้ตรงกับ [XBRL ข้อมูลจำเพาะ](http://www.xbrl.org/specification/inlinexbrl-part1/rec-2013-11-18/inlinexbrl-part1-rec-2013-11-18.html)1. หากต้องการตรวจสอบความถูกต้องให้ใช้ [ตรวจสอบ ()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) วิธีการ [Xbrlinstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) คลาส.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ความต้องการการตรวจสอบ" %}}
เพื่อดำเนินการตรวจสอบเอกสาร XBRL .NET Finance API คือข้อกำหนดหลักที่จะรวมอยู่ในใบสมัคร 
- ติดตั้งผ่านบรรทัดคำสั่งเป็น '''nuget ติดตั้ง Aspose.Finance'''หรือผ่านทางคอนโซลผู้จัดการแพคเกจของ Visual Studio กับ'' 'install-Package Aspose.Finance'''
- หรือรับการติดตั้ง MSI แบบออฟไลน์หรือ dlls ในไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# รหัสเพื่อตรวจสอบไฟล์ XBRL" offSpacer="" %}}

{{< gist "aspose-com-gists" "1272da1f804f8cef122600269db09fbb" "validate-xbrl-instance-file.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="ตัวเลือกการตรวจสอบอื่นๆ" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/validate/ixbrl/" name="XBRL" description="ภาษารายงานธุรกิจแบบอินไลน์ Extensible" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
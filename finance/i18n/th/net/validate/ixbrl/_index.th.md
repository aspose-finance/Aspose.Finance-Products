---
title: ตรวจสอบไฟล์ iXBRL ผ่าน C#
description: ตัวอย่างรหัสสำหรับ iXBRL การตรวจสอบไฟล์ใช้รหัสตัวอย่าง API เพื่อตรวจสอบไฟล์ batch iXBRL ภายในแอพพลิเคชันที่ใช้ .NET 
url: /th/net/validate/ixbrl/
family: finance
platformtag: net
feature: validate
informat: iXBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="ตรวจสอบไฟล์ iXBRL ผ่าน C#" h2="ตรวจสอบรายงานทางการเงินในรูปแบบ iXBRL โดยไม่จำเป็นต้องติดตั้ง Microsoft Office หรือซอฟต์แวร์อื่นๆ" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="วิธีการตรวจสอบไฟล์ iXBRL" %}}

ทำตามขั้นตอนในโค้ดตัวอย่างหรือเพิ่มมันเป็นความต้องการของแอพลิเคชันของคุณสำหรับการตรวจสอบ Extensible ธุรกิจรายงานภาษา iXBRL เอกสารให้แน่ใจว่ามีการตรวจสอบความต้องการภายในโปรแกรมของคุณ

1. โหลดไฟล์ iXBRL โดยใช้ [คลาส inlinexbrldocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) อินสแตนซ์1. หากต้องการตรวจสอบความถูกต้องของไฟล์ที่โหลดเพื่อให้ตรงกับ [iXBRL ข้อมูลจำเพาะ](http://www.xbrl.org/specification/inlinexbrl-part1/rec-2013-11-18/inlinexbrl-part1-rec-2013-11-18.html)1. ใช้ดี [ตรวจสอบ ()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument/methods/validate) วิธีการตรวจสอบความถูกต้องของไฟล์
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ความต้องการการตรวจสอบ" %}}
เพื่อดำเนินการตรวจสอบเอกสาร iXBRL .NET Finance API คือข้อกำหนดหลักที่จะรวมอยู่ในใบสมัคร 
- ติดตั้งผ่านบรรทัดคำสั่งเป็น '''nuget ติดตั้ง Aspose.Finance'''หรือผ่านทางคอนโซลผู้จัดการแพคเกจของ Visual Studio กับ'' 'install-Package Aspose.Finance'''
- หรือรับการติดตั้ง MSI แบบออฟไลน์หรือ dlls ในไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# รหัสเพื่อตรวจสอบไฟล์ iXBRL" offSpacer="" %}}

{{< gist "aspose-com-gists" "1272da1f804f8cef122600269db09fbb" "validate-ixbrl-file.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="ตัวเลือกการตรวจสอบอื่นๆ" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/validate/xbrl/" name="XBRL" description="ภาษารายงานธุรกิจที่ขยายได้" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
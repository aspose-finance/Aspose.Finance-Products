---
title: สร้าง OFX ไฟล์ตอบสนองผ่าน C#
description: ตัวอย่างโค้ดสำหรับการสร้างไฟล์ตอบสนอง OFX ใช้ API ตัวอย่างรหัสสำหรับแบทช์ OFX การสร้างไฟล์ตอบสนองภายใน .NET การใช้งานตาม 
url: /th/net/create/ofx-response/
family: finance
platformtag: net
feature: create
informat: OFX Response
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="สร้าง OFX ไฟล์ตอบสนองผ่าน C#" h2="OFX การสร้างไฟล์ตอบสนองโดยไม่จำเป็นต้องติดตั้ง Microsoft Office หรือซอฟต์แวร์อื่นๆ" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="วิธีการสร้าง OFX ไฟล์ตอบสนอง" %}}

ทำตามขั้นตอนในโค้ดตัวอย่างหรือเพิ่มมันเป็นความต้องการของแอพลิเคชันของคุณหลังจากที่มีความต้องการในการสร้างภายในโปรแกรมของคุณ

1. สร้าง [ระดับ ofxresponsedocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) วัตถุ1. กำหนดคุณสมบัติที่เกี่ยวข้องโดยใช้ชั้นเรียนที่แตกต่างกันโดย API เช่น [Signonresponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),,  [Stementtransactionresponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse),, [การทำธุรกรรม](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction)1. ใช้ V2x ofxversion หรือ V1x สำหรับไฟล์ XML และ SGML ตามลำดับจาก [Ofxversionenum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) เป็นพารามิเตอร์ในบันทึกวิธีการ1. โทรหา [บันทึกวิธีการ](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument/methods/save) โดยให้ไฟล์เป้าหมายและ ofxversion.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ความต้องการการสร้าง" %}}
ในการดำเนินการสร้างไฟล์ตอบสนอง OFX .NET Finance API เป็นข้อกำหนดหลักที่จะรวมอยู่ในแอ็พพลิเคชันการสร้างรายงาน 
- ติดตั้งผ่านบรรทัดคำสั่งเป็น '''nuget ติดตั้ง Aspose.Finance'''หรือผ่านทางคอนโซลผู้จัดการแพคเกจของ Visual Studio กับ'' 'install-Package Aspose.Finance'''
- หรือรับการติดตั้ง MSI แบบออฟไลน์หรือ dlls ในไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# รหัสสำหรับ OFX การสร้างไฟล์ตอบสนอง" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="ตัวเลือกการสร้างอื่นๆ" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX ไฟล์คำขอ" description="รูปแบบ1.03หรือ2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL ไฟล์" description="ภาษารายงานธุรกิจที่ขยายได้" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
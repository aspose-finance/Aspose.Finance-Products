---
title: สร้าง OFX ขอไฟล์ผ่าน C#
description: ตัวอย่างโค้ดสำหรับ OFX ขอสร้างไฟล์ใช้ API ตัวอย่างรหัสสำหรับแบทช์ OFX ร้องขอการสร้างไฟล์ภายใน .NET การใช้งานตาม 
url: /th/net/create/ofx-request/
family: finance
platformtag: net
feature: create
informat: OFX Request
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="สร้าง OFX ขอไฟล์ผ่าน C#" h2="OFX ขอสร้างไฟล์โดยไม่จำเป็นต้องติดตั้ง Microsoft Office หรือซอฟต์แวร์อื่นๆ" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="วิธีการสร้าง OFX request Files" %}}

หลังจากมี OFX ร้องขอความต้องการในการสร้างไฟล์ภายในโปรแกรมของคุณให้ทำตามขั้นตอนในโค้ดตัวอย่างหรือเพิ่มตามความต้องการของคุณ

1. สร้าง [ชั้น ofxrequestdocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) วัตถุ1. กำหนดคุณสมบัติที่เกี่ยวข้องโดยใช้ชั้นเรียนที่แตกต่างกันโดย API เช่น [Signonrequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest),, [สถาบันการเงิน](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution),, [Statementtransactionrequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest)1. ใช้ V2x ofxversion หรือ V1x สำหรับไฟล์ XML และ SGML ตามลำดับจาก [Ofxversionenum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) เป็นพารามิเตอร์ในบันทึกวิธีการ1. โทรหา [บันทึกวิธีการ](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument/methods/save) โดยให้ไฟล์เป้าหมายและ ofxversion.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ความต้องการการสร้าง" %}}
OFX request File creation, .NET Finance API เป็นข้อกำหนดหลักที่จะรวมอยู่ในแอพพลิเคชันการสร้างรายงาน 
- ติดตั้งผ่านบรรทัดคำสั่งเป็น '''nuget ติดตั้ง Aspose.Finance'''หรือผ่านทางคอนโซลผู้จัดการแพคเกจของ Visual Studio กับ'' 'install-Package Aspose.Finance'''
- หรือรับการติดตั้ง MSI แบบออฟไลน์หรือ dlls ในไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# รหัสสำหรับ OFX การสร้างไฟล์คำขอ" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-request-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="ตัวเลือกการสร้างอื่นๆ" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX ไฟล์การตอบสนอง" description="รูปแบบ1.03หรือ2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL ไฟล์" description="ภาษารายงานธุรกิจที่ขยายได้" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
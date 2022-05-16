---
title: สร้าง OFX ไฟล์คำขอผ่าน C#
description: โค้ดตัวอย่างสำหรับการสร้างไฟล์คำขอ OFX ใช้รหัสตัวอย่าง API สำหรับการสร้างไฟล์คำขอแบทช์ OFX ภายในแอปพลิเคชันที่ใช้ .NET 
url: /th/net/create/ofx-request/
family: finance
platformtag: net
feature: create
informat: OFX Request
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="สร้าง OFX ไฟล์คำขอผ่าน C#" h2="OFX ขอสร้างไฟล์โดยไม่จำเป็นต้องติดตั้ง Microsoft Office หรือซอฟต์แวร์อื่นๆ" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="วิธีสร้าง OFX ไฟล์คำขอ" %}}

หลังจากมีOFXข้อกำหนดในการสร้างไฟล์คำขอภายในแอปพลิเคชันของคุณแล้ว ให้ทำตามขั้นตอนในข้อมูลโค้ดหรือปรับปรุงตามความต้องการของคุณ

1. สร้าง [OfxRequestDocument คลาส](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) วัตถุ.1. กำหนดคุณสมบัติที่เกี่ยวข้องโดยใช้คลาสต่างๆ ที่จัดเตรียมโดย API like [SignonRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [สถาบันการเงิน](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution), [คำสั่งธุรกรรมคำขอ](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest)1. ใช้ ofxVersion V2x หรือ V1x สำหรับไฟล์ xml และ sgml ตามลำดับจาก [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) เป็นพารามิเตอร์ในวิธีบันทึก1. โทรหา [บันทึกวิธีการ](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument/methods/save) โดยให้ไฟล์เป้าหมายและ ofxVersion
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดในการสร้าง" %}}
หากต้องการดำเนินการ OFX สร้างไฟล์คำขอ .NET Finance API เป็นข้อกำหนดหลักที่จะรวมไว้ในแอปพลิเคชันการสร้างรายงาน 
- ติดตั้งผ่านบรรทัดคำสั่งเป็น ```nuget install Aspose.Finance``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Finance```
- หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="รหัส C# สำหรับ OFX คำขอสร้างไฟล์" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-request-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="ตัวเลือกการสร้างอื่นๆ" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX ไฟล์ตอบกลับ" description="1.03 หรือ 2.2 รูปแบบ" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL ไฟล์" description="ภาษาการรายงานทางธุรกิจที่ขยายได้" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
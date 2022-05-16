---
title: สร้าง OFX ไฟล์ตอบกลับผ่าน C#
description: โค้ดตัวอย่างสำหรับการสร้างไฟล์ตอบกลับ OFX ใช้โค้ดตัวอย่าง API สำหรับการสร้างไฟล์ตอบกลับแบบกลุ่ม OFX ภายในแอปพลิเคชันที่ใช้ .NET 
url: /th/net/create/ofx-response/
family: finance
platformtag: net
feature: create
informat: OFX Response
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="สร้าง OFX ไฟล์ตอบกลับผ่าน C#" h2="OFX การสร้างไฟล์ตอบกลับโดยไม่จำเป็นต้องติดตั้ง Microsoft Office หรือซอฟต์แวร์อื่นๆ" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="วิธีสร้าง OFX ไฟล์ตอบกลับ" %}}

ทำตามขั้นตอนในข้อมูลโค้ดหรือปรับปรุงตามความต้องการของแอปพลิเคชันของคุณ หลังจากมีข้อกำหนดในการสร้างภายในแอปพลิเคชันของคุณแล้ว

1. สร้าง [OfxResponseDocument คลาส](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) วัตถุ.1. กำหนดคุณสมบัติที่เกี่ยวข้องโดยใช้คลาสต่างๆ ที่จัดเตรียมโดย API like [SignonResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [คำชี้แจงธุรกรรมการตอบสนอง](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse), [คำสั่งธุรกรรม](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction)1. ใช้ ofxVersion V2x หรือ V1x สำหรับไฟล์ xml และ sgml ตามลำดับจาก [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) เป็นพารามิเตอร์ในวิธีบันทึก1. โทรหา [บันทึกวิธีการ](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument/methods/save) โดยให้ไฟล์เป้าหมายและ ofxVersion
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดในการสร้าง" %}}
หากต้องการดำเนินการต่อสำหรับ OFX การสร้างไฟล์ตอบกลับ .NET Finance API เป็นข้อกำหนดหลักที่จะรวมไว้ในแอปพลิเคชันการสร้างรายงาน 
- ติดตั้งผ่านบรรทัดคำสั่งเป็น ```nuget install Aspose.Finance``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Finance```
- หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="โค้ด C# สำหรับ OFX การสร้างไฟล์ตอบกลับ" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="ตัวเลือกการสร้างอื่นๆ" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX ร้องขอไฟล์" description="1.03 หรือ 2.2 รูปแบบ" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL ไฟล์" description="ภาษาการรายงานทางธุรกิจที่ขยายได้" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
---
title: แปลง XBRL เป็น iXBRL ผ่าน C#
description: โค้ดตัวอย่างสำหรับการแปลง XBRL เป็น SEC xlsx รายงาน C# ใช้โค้ดตัวอย่าง API สำหรับไฟล์แบทช์ XBRL เพื่อแปลงรายงาน SEC xlsx ภายในแอปพลิเคชันที่ใช้ .NET 
url: /th/net/conversion/xbrl-to-sec-xlsx-report/
family: finance
platformtag: net
feature: convert
informat: XBRL
outformat: XLSX
otherformats: HTML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="แปลง XBRL เป็นรายงาน SEC xlsx ผ่าน C#" h2="การแปลงรายงาน XBRL เป็น SEC xlsx โดยไม่ต้องใช้ซอฟต์แวร์อื่นภายในแอปพลิเคชันที่ใช้ .NET" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) เป็น API ในการประมวลผล XBRL, iXBRL รูปแบบ และนักพัฒนาสามารถสร้างแอปพลิเคชันซอฟต์แวร์การจัดการกระบวนการทางธุรกิจ การวิเคราะห์ทางการเงิน และการรายงานเพื่อแปลง สร้าง อ่าน ดู และตรวจสอบ XBRL และ iXBRL ที่เกี่ยวข้องกับการเงิน ไฟล์. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="วิธีแปลงรายงาน XBRL เป็น SEC xlsx" %}}
1. โหลดอินพุต XBRL ไฟล์โดยใช้ [XbrlDocument class](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument).2. เซ็ต [SaveOptions](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions) สำหรับไฟล์เอาต์พุตโดยเลือก [SaveFormat.SEC_XLSX_REPORT](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveformat).
3. โทรหา [บันทึกวิธีการ](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/2) โดยระบุไฟล์เป้าหมายและ SaveOptions ที่เกี่ยวข้องเป็นพารามิเตอร์

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
หากต้องการดำเนินการแปลงรายงาน XBRL เป็น SEC xlsx นั้น .NET Finance API เป็นข้อกำหนดหลัก ติดตั้งผ่านบรรทัดคำสั่งเป็น ```nuget install Aspose.Finance``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Finance```

หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/finance/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# ซอร์สโค้ดเพื่อแปลง XBRL เป็นไฟล์รายงาน xlsx ของ SEC" offSpacer="" %}}

{{< gist "aspose-finance-gists" "283cfe3a6a0f0493c28290717b5b9379" "convert-xbrl-to-xlsx-sec-report.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="ตัวเลือกการแปลงอื่น ๆ" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/conversion/xbrl-to-xlsx/" name="XBRL เป็น XLSX" description="สเปรดชีต Microsoft Excel Open XML" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/conversion/ofx-response/" name="OFX ตอบกลับ" description="จาก 1.03 ถึง 2.2 รูปแบบ" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/conversion/ofx-request/" name="OFX คำขอ" description="จาก 1.03 ถึง 2.2 รูปแบบ" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
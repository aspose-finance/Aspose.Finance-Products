﻿---
title: แปลง XBRL เป็น iXBRL ผ่าน C#
description: โค้ดตัวอย่างสำหรับการแปลง XBRL ถึง iXBRL C# ใช้รหัสตัวอย่าง API สำหรับไฟล์แบทช์ XBRL เป็น iXBRL การแปลงภายในแอปพลิเคชันที่ใช้ .NET 
url: /th/net/conversion/xbrl-to-ixbrl/
family: finance
platformtag: net
feature: convert
informat: XBRL
outformat: iXBRL
otherformats: XLSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="แปลง XBRL เป็น iXBRL ผ่าน C#" h2="การแปลง XBRL เป็น iXBRL โดยไม่ต้องใช้ซอฟต์แวร์อื่นภายในแอปพลิเคชันที่ใช้ .NET" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) เป็น API ในการประมวลผล XBRL, iXBRL รูปแบบ และนักพัฒนาสามารถสร้างแอปพลิเคชันซอฟต์แวร์การจัดการกระบวนการทางธุรกิจ การวิเคราะห์ทางการเงิน และการรายงานเพื่อแปลง สร้าง อ่าน ดู และตรวจสอบ XBRL และ iXBRL ที่เกี่ยวข้องกับการเงิน ไฟล์. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="วิธีการแปลง XBRL เป็น iXBRL" %}}
1. โหลดอินพุต XBRL ไฟล์โดยใช้ [XbrlDocument class](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument).2. เซ็ต [SaveOptions](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions) สำหรับไฟล์เอาต์พุตโดยเลือก [SaveFormat.IXBRL](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveformat).
3. โทรหา [บันทึกวิธีการ](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/2) โดยระบุไฟล์เป้าหมายและ SaveOptions ที่เกี่ยวข้องเป็นพารามิเตอร์

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการแปลง" %}}
ในการดำเนินการสำหรับการแปลง XBRL เป็น iXBRL นั้น .NET Finance API เป็นข้อกำหนดหลัก ติดตั้งผ่านบรรทัดคำสั่งเป็น ``` ติดตั้ง nuget Aspose.Finance``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Finance```

หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/finance/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# ซอร์สโค้ดเพื่อแปลง XBRL เป็น iXBRL file" offSpacer="" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-ixbrl.cs" >}}

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
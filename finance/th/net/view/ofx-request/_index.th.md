---
title: ดู OFX ไฟล์คำขอผ่าน C#
description: โค้ดตัวอย่างสำหรับการดูไฟล์คำขอ OFX ใช้โค้ดตัวอย่าง API เพื่อดูไฟล์คำขอแบทช์ OFX ภายในแอปพลิเคชันที่ใช้ .NET 
url: /th/net/view/ofx-request/
family: finance
platformtag: net
feature: view
informat: OFX request
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="ดู OFX ร้องขอไฟล์ผ่าน C#" h2="การดูรายงานทางการเงินในรูปแบบคำขอ OFX โดยไม่ต้องติดตั้ง Microsoft Office หรือซอฟต์แวร์อื่นใด" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="วิธีดู OFX คำขอไฟล์" %}}

ทำตามขั้นตอนในข้อมูลโค้ดหรือปรับปรุงตามที่แอปพลิเคชันของคุณต้องการสำหรับการดูไฟล์คำขอภาษาการรายงานทางธุรกิจที่ขยายได้ OFX ไฟล์ ตรวจสอบให้แน่ใจว่ามีข้อกำหนดในการอ่านในใบสมัครของคุณ

1. สร้าง [OfxRequestDocument คลาส](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) ตัวอย่าง.1. ส่งชื่อไฟล์คำขอ OFX ที่ถูกต้องเป็นพารามิเตอร์1. เพื่อให้ได้รายละเอียดภายในของไฟล์ ให้ใช้คลาสที่เกี่ยวข้องเช่น [SignonRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest)1. แสดงข้อมูลเหล่านี้
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดในการอ่าน" %}}
หากต้องการดำเนินการดู OFX เอกสารคำขอ .NET Finance API เป็นข้อกำหนดหลักที่จะรวมไว้ในใบสมัคร 
- ติดตั้งผ่านบรรทัดคำสั่งเป็น ```nuget install Aspose.Finance``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.Finance```
- หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# รหัสเพื่อดู OFX ไฟล์คำขอ" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e402ec71f2ad51f0fee413fa1a91945f" "read-ofx-request.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="ตัวเลือกการดูอื่นๆ" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/view/ixbrl/" name="iXBRL" description="ภาษาการรายงานธุรกิจที่ขยายได้แบบอินไลน์" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
---
title: แปลง Financial reports Via .NET
url: /th/net/conversion/
description:  C# รหัสเพื่อแปลงรายงานทางการเงินใน XBRL, iXBRL และ OFX ไฟล์ fomats ผ่านทางห้องสมุด .NET
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="แปลงไฟล์ Financial Report ผ่าน C#" h2="การแปลงรูปแบบรายงานทางการเงินรวมถึง XBRL, iXBRL และ OFX ไฟล์จาก1.03เป็น2.2รูปแบบภายใน .NET" >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) เป็นคุณลักษณะที่อุดมไปด้วยขยายและใช้งานง่าย API นักพัฒนาสามารถตรวจสอบได้อย่างง่ายดาย XBRL อินสแตนซ์ linkbases และอนุกรมวิธาน schemas โดยใช้ [วิธีการตรวจสอบ ()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) ที่ต้องสอดคล้องกับข้อกำหนดไวยากรณ์ที่กำหนดไว้ในข้อกำหนดนอกจากนี้ยังสามารถอ่านรูปแบบ XBRL, iXBRL รวมทั้งสร้างตัวอย่าง XBRL ตั้งแต่เริ่มต้นนอกจากนี้พวกเขาสามารถ ** แปลง XBRL รูปแบบ ** เป็น iXBRL และไฟล์ Microsoft Excel xlsx. API นอกจากนี้ยังสนับสนุน Open Financial Exchange (OFX) การสร้างรูปแบบคำขอ/การตอบสนองและแปลง OFX คำขอ/การตอบสนองจากรูปแบบ1.03เป็น2.2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="แปลง OFX การตอบสนองและไฟล์คำขอ" %}}

API สนับสนุนการสร้าง OFX คำขอและการตอบสนองไฟล์โดยการให้สองชั้นเรียน [Ofxrequestdocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) สำหรับการสร้างและโหลด OFX ไฟล์คำขอในรูปแบบ1.03และ2.2และ [Ofxresponsedocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) สำหรับ OFX ไฟล์ตอบสนองในรูปแบบ1.03และ2.2. Futhermore, [Ofxversionenum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) การนับจำนวนสมาชิก V1x ที่เป็นเวอร์ชัน1.x รูปแบบไฟล์ SGML และเวอร์ชัน V2x 2.x รูปแบบไฟล์ XML หลังจากเรียกวิธีการบันทึกของ ofxrequestdocument Class หรือ ofxresponsedocument Class นักพัฒนาสามารถแปลงจากไฟล์1.03 SGML เป็นรูปแบบ2.2 XML.


{{% blocks/products/pf/feature-page-code h3="C# รหัสเพื่อแปลง OFX ไฟล์ตอบสนอง" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-response-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# รหัสเพื่อแปลง OFX ไฟล์คำขอ" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-request-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL การแปลงรายงานทางการเงิน" %}}

API รองรับการแปลงไฟล์ XBRL เป็น iXBRL และ Microsoft®รูปแบบ Excel xlsx. ขั้นตอนการแปลงเป็นเรื่องง่ายก่อนโหลดไฟล์ผ่าน [ระดับเอกสาร xbrldocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument).ใช้ [ระดับ saveoptions](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions) สำหรับ [Saveformat](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions/properties/saveformat)เพื่อใช้เป็นพารามิเตอร์ในบันทึกวิธีการของคลาส xbrldocument. สำหรับการบันทึกในไฟล์ ixblr, [Saveformat.ixbrl](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveformat) จะถูกนำมาใช้และสำหรับการส่งออกเป็นรูปแบบ xlsx, saveformat.xlsx จะถูกนำมาใช้

{{% blocks/products/pf/feature-page-code h3="C# Code TO Export XBRL TO iXBRL" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-ixbrl.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# รหัสสำหรับ XBRL เพื่อแปลง xlsx" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-xlsx.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}
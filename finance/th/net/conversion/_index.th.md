---
title: แปลงรายงานทางการเงินผ่าน .NET
url: /th/net/conversion/
description:  C# รหัสเพื่อแปลงรายงานทางการเงินในรูปแบบไฟล์ XBRL, iXBRL(inline xbrl) และ OFX ผ่านไลบรารี .NET
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="แปลงไฟล์รายงานทางการเงินผ่าน C#" h2="การแปลงรูปแบบรายงานทางการเงิน รวมถึงไฟล์ XBRL, iXBRL และ OFX จากรูปแบบ 1.03 เป็น 2.2 ภายในแอปพลิเคชันที่ใช้ .NET" >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) เป็นคุณลักษณะที่สมบูรณ์ ขยายได้ และใช้งานง่าย API นักพัฒนาสามารถตรวจสอบ XBRL อินสแตนซ์ ลิงก์เบส และสคีมาการจัดหมวดหมู่ได้อย่างง่ายดายโดยใช้ [ตรวจสอบ () วิธีการ](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) ที่ต้องเป็นไปตามข้อกำหนดของไวยากรณ์ที่กำหนดไว้ในข้อกำหนด นอกจากนี้ ยังสามารถอ่านรูปแบบ XBRL, iXBRL และสร้างอินสแตนซ์ XBRL ได้ตั้งแต่เริ่มต้น นอกจากนี้ ยังสามารถ **แปลง XBRL รูปแบบ ** เป็น iXBRL และไฟล์ Microsoft Excel XLSX API ยังสนับสนุนรูปแบบคำขอเปิดการแลกเปลี่ยนทางการเงิน (OFX) / การสร้างการตอบกลับ และแปลงรูปแบบคำขอ / การตอบกลับ OFX จาก 1.03 เป็น 2.2

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="แปลง OFX ตอบกลับและร้องขอไฟล์" %}}

API รองรับการสร้างไฟล์คำขอและตอบกลับ OFX โดยจัดเตรียมสองคลาส [OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) สำหรับสร้างและโหลดไฟล์คำขอ OFX ไฟล์ในรูปแบบ 1.03 และ 2.2 และ [OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) สำหรับไฟล์ตอบกลับ OFX ในรูปแบบ 1.03 และ 2.2 นอกจากนี้ [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) การแจงนับที่มีสมาชิก V1x ที่เป็นเวอร์ชัน 1.x, รูปแบบไฟล์ sgml และเวอร์ชัน V2x 2.x, รูปแบบไฟล์ xml หลังจากเรียกวิธีการบันทึกของคลาส OfxRequestDocument หรือคลาส OfxResponseDocument นักพัฒนาสามารถแปลงจากไฟล์ 1.03 sgml เป็นรูปแบบ 2.2 xml ได้อย่างง่ายดาย


{{% blocks/products/pf/feature-page-code h3="C# รหัสเพื่อแปลง OFX ไฟล์ตอบกลับ" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-response-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# รหัสสำหรับแปลง OFX ไฟล์คำขอ" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-request-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL การแปลงรายงานทางการเงิน" %}}

API รองรับการแปลงไฟล์ XBRL เป็น iXBRL และรูปแบบ Microsoft® Excel XLSX ขั้นตอนการแปลงนั้นง่าย ขั้นแรกให้โหลดไฟล์ผ่าน [XbrlDocument Class](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument). ใช้ [คลาส SaveOptions](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions) สำหรับ [บันทึกรูปแบบ](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions/properties/saveformat)เพื่อใช้เป็นพารามิเตอร์ในวิธีบันทึกของ XbrlDocument Class สำหรับการบันทึกในไฟล์ iXBLR [SaveFormat.IXBRL](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveformat) จะถูกใช้และสำหรับการส่งออกเป็นรูปแบบ XLSX จะใช้ SaveFormat.XLSX

{{% blocks/products/pf/feature-page-code h3="C# รหัสที่จะส่งออก XBRL เป็น iXBRL" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-ixbrl.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# โค้ดสำหรับการแปลง XBRL เป็น XLSX" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-xlsx.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}
{{< /blocks/products/pf/feature-page-wrap >}}
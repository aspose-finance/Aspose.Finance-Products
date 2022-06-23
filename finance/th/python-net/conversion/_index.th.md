---
title: แปลงรายงานทางการเงินผ่าน Python
url: /th/python-net/conversion/
description:  Python รหัสเพื่อแปลงรายงานทางการเงินในรูปแบบไฟล์ XBRL, iXBRL(inline xbrl) และ OFX ผ่านไลบรารี Python
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="แปลงไฟล์รายงานทางการเงินผ่าน Python" h2="การแปลงรูปแบบรายงานทางการเงิน รวมถึงไฟล์ XBRL, iXBRL และ OFX จากรูปแบบ 1.03 เป็น 2.2 ภายในแอปพลิเคชันที่ใช้ Python" >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance สำหรับ Python ผ่าน .NET](https://products.aspose.com/finance/python-net/) เป็นคุณลักษณะที่สมบูรณ์ ขยายได้ และใช้งานง่าย API นักพัฒนาสามารถตรวจสอบอินสแตนซ์ XBRL, linkbases และ taxonomy schema ได้อย่างง่ายดายโดยใช้เมธอด validate() ที่ต้องปฏิบัติตามข้อกำหนดทางไวยากรณ์ที่กำหนดไว้ในข้อกำหนด นอกจากนี้ ยังสามารถอ่านรูปแบบ XBRL, iXBRL และสร้างอินสแตนซ์ XBRL ได้ตั้งแต่เริ่มต้น นอกจากนี้ ยังสามารถ **แปลง XBRL รูปแบบ ** เป็น iXBRL และไฟล์ Microsoft Excel XLSX API ยังสนับสนุนรูปแบบคำขอ / การสร้างคำตอบแบบเปิดการแลกเปลี่ยนทางการเงิน (OFX) และแปลงรูปแบบคำขอ / ตอบกลับ OFX จาก 1.03 เป็น 2.2

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="แปลง OFX ตอบกลับและร้องขอไฟล์" %}}

API รองรับการสร้างไฟล์คำขอและตอบกลับ OFX โดยจัดเตรียมสองคลาส OfxRequestDocument สำหรับสร้างและโหลดไฟล์คำขอ OFX ในรูปแบบ 1.03 และ 2.2 และ OfxResponseDocument สำหรับไฟล์ตอบกลับ OFX ในรูปแบบ 1.03 และ 2.2 นอกจากนี้ OfxVersionEnum Enumeration มีสมาชิก V1x ที่เป็นเวอร์ชัน 1.x, รูปแบบไฟล์ sgml และเวอร์ชัน V2x 2.x, รูปแบบไฟล์ xml หลังจากเรียกใช้วิธีการบันทึกของคลาส OfxRequestDocument หรือคลาส OfxResponseDocument นักพัฒนาสามารถแปลงจากไฟล์ 1.03 sgml เป็นรูปแบบ 2.2 xml ได้อย่างง่ายดาย


{{% blocks/products/pf/feature-page-code h3="C# รหัสเพื่อแปลง OFX ไฟล์ตอบกลับ" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-ofx-response-from-1.03-to-2.2.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# รหัสสำหรับแปลง OFX ไฟล์คำขอ" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-ofx-request-from-1.03-to-2.2.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL การแปลงรายงานทางการเงิน" %}}

API รองรับการแปลงไฟล์ XBRL เป็น iXBRL และรูปแบบ Microsoft® Excel XLSX ขั้นตอนการแปลงนั้นง่าย ขั้นแรกให้โหลดไฟล์ผ่าน XbrlDocument Class ใช้คลาส SaveOptions สำหรับ SaveFormat เพื่อใช้เป็นพารามิเตอร์ในวิธีการบันทึกของ XbrlDocument Class สำหรับการบันทึกในไฟล์ iXBLR จะใช้ SaveFormat.IXBRL และสำหรับการส่งออกเป็นรูปแบบ XLSX จะใช้ SaveFormat.XLSX

{{% blocks/products/pf/feature-page-code h3="Python รหัสที่จะส่งออก XBRL เป็น iXBRL" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-xbrl-to-ixbrl.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python โค้ดสำหรับการแปลง XBRL เป็น XLSX" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-xbrl-to-xlsx.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}
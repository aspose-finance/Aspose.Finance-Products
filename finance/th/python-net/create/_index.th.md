---
title: สร้างรายงานทางการเงินผ่าน Python
url: /th/python-net/create/
description:  รหัส Python เพื่อสร้างรายงานทางการเงินใน XBRL และ OFX ไฟล์คำขอหรือคำตอบผ่านไลบรารี Python
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="สร้างไฟล์การรายงานทางการเงินผ่าน Python" h2="การสร้างรูปแบบรายงานทางการเงิน รวมถึงไฟล์คำขอหรือคำตอบ XBRL และ OFX ในรูปแบบ 1.03 หรือ 2.2 ภายในแอปพลิเคชันที่ใช้ Python" >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance สำหรับ Python ผ่าน .NET](https://products.aspose.com/finance/python-net/) เป็นคุณลักษณะที่สมบูรณ์ ขยายได้ และง่ายต่อการใช้การสร้างและประมวลผลรายงานทางการเงิน API นักพัฒนาสามารถสร้างอินสแตนซ์ XBRL ได้อย่างง่ายดายตั้งแต่เริ่มต้น รวมทั้งสามารถเพิ่มการอ้างอิงสคีมา บริบท หน่วย รายการ ลิงก์เชิงอรรถ การอ้างอิงบทบาทและ 
การอ้างอิงบทบาทอาร์ค API มีคลาสที่เกี่ยวข้องสำหรับแต่ละคุณลักษณะ เช่น สำหรับบริบท นักพัฒนาสามารถใช้ ContextPeriod, ContextEntity และ Context 
ยิ่งกว่านั้น API ยังสนับสนุนรูปแบบการเปิด/การตอบกลับของรูปแบบการแลกเปลี่ยนทางการเงินแบบเปิด (OFX) ในรูปแบบ 1.03 หรือ 2.2

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="สร้างไฟล์ XBRL โดยการเพิ่มรายการ" %}}

สำหรับการสร้างไฟล์ XBRL และเพิ่มรายการลงในเอกสาร กระบวนการคือ สร้างอินสแตนซ์คลาส XbrlDocument เตรียมการตั้งค่าที่เกี่ยวข้องสำหรับรายการโดยใช้คลาส API ที่เหมาะสม เช่น คลาส SchemaRef คลาสบริบทที่เกี่ยวข้องตามที่กล่าวไว้ข้างต้น และคลาส Concept ขั้นสุดท้ายให้กำหนดและกำหนดค่าคุณสมบัติของคลาส Item รวมทั้งเรียกวิธีการบันทึกเพื่อสร้างไฟล์ XBRL ลงในดิสก์

{{% blocks/products/pf/feature-page-code h3="Python รหัสสำหรับสร้าง XBRL ไฟล์โดยการเพิ่มรายการ" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-xbrl-file-and-add-item.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="สร้าง OFX ไฟล์คำขอและตอบกลับ" %}}


สำหรับการสร้างไฟล์ OFX ไฟล์ API มีคลาส OfxRequestDocument และ OfxResponseDocument และนักพัฒนาสามารถ [สร้าง OFX คำขอ](https://products.aspose.com/finance/python-net/create/ofx-request/) และไฟล์ตอบกลับทั้งในรูปแบบ 1.03 และ 2.2 สำหรับการกำหนดค่าเริ่มต้นคุณสมบัติ OfxRequestDocument API ยังจัดเตรียมคลาสอื่นๆ เช่น SignonRequest, FinancialInstitution และ StatementTransactionRequest ในทำนองเดียวกัน สำหรับการเริ่มต้นคุณสมบัติ OfxResponseDocument API มีคลาสที่สนับสนุน เช่น SignonResponse, StatementTransactionResponse และ StatementTransaction ด้านล่างนี้คือข้อมูลโค้ดสำหรับทั้งสองกรณีโดยใช้คลาสที่เกี่ยวข้องที่เหมาะสม

{{% blocks/products/pf/feature-page-code h3="Python รหัสสำหรับสร้าง OFX เอกสารคำขอ" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python รหัสสำหรับสร้าง OFX เอกสารตอบกลับ" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
---
title: สร้างรายงานทางการเงินผ่าน .NET
url: /th/net/create/
description:  รหัส C# เพื่อสร้างรายงานทางการเงินใน XBRL และ OFX ไฟล์คำขอหรือคำตอบผ่านไลบรารี .NET
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="สร้างไฟล์การรายงานทางการเงินผ่าน C#" h2="การสร้างรูปแบบรายงานทางการเงิน รวมถึงไฟล์คำขอหรือคำตอบ XBRL และ OFX ในรูปแบบ 1.03 หรือ 2.2 ภายในแอปพลิเคชันที่ใช้ .NET" >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) เป็นคุณลักษณะที่สมบูรณ์ ขยายได้ และง่ายต่อการใช้การสร้างและประมวลผลรายงานทางการเงิน API นักพัฒนาสามารถสร้างอินสแตนซ์ XBRL ได้อย่างง่ายดายตั้งแต่เริ่มต้น รวมทั้งสามารถเพิ่มการอ้างอิงสคีมา บริบท หน่วย รายการ ลิงก์เชิงอรรถ การอ้างอิงบทบาทและ 
การอ้างอิงบทบาทอาร์ค API มีคลาสที่เกี่ยวข้องสำหรับแต่ละคุณลักษณะ เช่น บริบท นักพัฒนาสามารถใช้ [ระยะเวลาบริบท](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextperiod), [ContextEntity](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextentity) และ [บริบท](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context). 
ยิ่งกว่านั้น API ยังสนับสนุนรูปแบบการเปิด/การตอบกลับของรูปแบบการแลกเปลี่ยนทางการเงินแบบเปิด (OFX) ในรูปแบบ 1.03 หรือ 2.2

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="สร้างไฟล์ XBRL โดยการเพิ่มรายการ" %}}

สำหรับการสร้างไฟล์ XBRL และเพิ่มรายการลงในเอกสาร กระบวนการคือ create [XbrlDocument class](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) ตัวอย่าง. เตรียมการตั้งค่าที่เกี่ยวข้องสำหรับรายการโดยใช้ API คลาสที่เหมาะสม เช่น [สคีมาRef class](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemaref)คลาสบริบทที่เกี่ยวข้องตามที่กล่าวข้างต้นและ [คลาสแนวคิด](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/concept). สุดท้ายกำหนดและ intialize [ประเภทรายการ](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/item) คุณสมบัติตลอดจนเรียก [บันทึกวิธีการ](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) ถึง [สร้าง XBRL](https://products.aspose.com/finance/net/create/xbrl/) ไฟล์ลงในดิสก์

{{% blocks/products/pf/feature-page-code h3="C# รหัสสำหรับสร้าง XBRL ไฟล์โดยการเพิ่มรายการ" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-item.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="สร้าง OFX คำขอและไฟล์ตอบกลับ" %}}


สำหรับการสร้างไฟล์ OFX ไฟล์ API จะจัดเตรียม [OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) และ [OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) ชั้นเรียนและนักพัฒนาได้อย่างง่ายดาย [สร้าง OFX คำขอ](https://products.aspose.com/finance/net/create/ofx-request/) และไฟล์ตอบกลับทั้งในรูปแบบ 1.03 และ 2.2 สำหรับการเริ่มต้นคุณสมบัติ OfxRequestDocument API ยังมีคลาสอื่นๆ เช่น [SignonRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [สถาบันการเงิน](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution) และ [คำสั่งธุรกรรมคำขอ](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest) ชั้นเรียน ในทำนองเดียวกัน สำหรับการทำให้คุณสมบัติ OfxResponseDocument เป็นค่าเริ่มต้น API มีคลาสที่สนับสนุน เช่น [SignonResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [คำชี้แจงธุรกรรมการตอบสนอง](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse) และ [คำสั่งธุรกรรม](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction). ด้านล่างนี้คือข้อมูลโค้ดสำหรับทั้งสองกรณีโดยใช้คลาสที่เหมาะสมที่เกี่ยวข้อง

{{% blocks/products/pf/feature-page-code h3="C# รหัสสำหรับสร้าง OFX เอกสารคำขอ" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# รหัสเพื่อสร้าง OFX เอกสารตอบกลับ" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
---
title: สร้างรายงานทางการเงินผ่าน .NET
url: /th/net/create/
description:  C# รหัสเพื่อสร้างรายงานทางการเงินใน XBRL และ OFX คำขอหรือการตอบสนองไฟล์ผ่านห้องสมุด .NET
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="สร้างไฟล์รายงานทางการเงินผ่าน C#" h2="การสร้างรูปแบบรายงานทางการเงินรวมถึง XBRL และ OFX คำขอหรือไฟล์ตอบสนองในรูปแบบ1.03หรือ2.2ภายใน .NET" >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) เป็นคุณลักษณะที่อุดมไปด้วยขยายและง่ายต่อการใช้การสร้างรายงานทางการเงินและการประมวลผล API นักพัฒนาสามารถสร้างตัวอย่าง XBRL ตั้งแต่เริ่มต้นรวมทั้งสามารถเพิ่มการอ้างอิง Schema, บริบท, หน่วย, รายการ, การเชื่อมโยงเชิงอรรถ, การอ้างอิงบทบาทและ 
อ้างอิงบทบาท Arc. API ให้ชั้นเรียนที่เกี่ยวข้องสำหรับแต่ละคุณลักษณะเช่นบริบทนักพัฒนาสามารถใช้ [Contextperiod](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextperiod),, [Contextentity](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextentity) และ [บริบท](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context). 
นอกจากนี้ API ยังสนับสนุน Open Financial Exchange (OFX) การสร้างรูปแบบคำขอ/การตอบสนองในรูปแบบ1.03หรือ2.2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="สร้างไฟล์ XBRL โดยการเพิ่มไอเทม" %}}

สำหรับการสร้างไฟล์ XBRL และเพิ่มสินค้าลงในเอกสารกระบวนการคือสร้าง [ระดับเอกสาร xbrldocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) อินสแตนซ์จัดเตรียมการตั้งค่าที่เกี่ยวข้องสำหรับสินค้าโดยใช้คลาส API ที่เหมาะสมเช่น [ชั้น schemaref](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemaref), ชั้นเรียนบริบทที่เกี่ยวข้องดังกล่าวข้างต้นและ [คลาสแนวคิด](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/concept).ในที่สุดกำหนดและข่มขู่ [ชั้นสินค้า](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/item) คุณสมบัติเช่นเดียวกับโทร [บันทึกวิธีการ](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) TO [สร้าง XBRL](https://products.aspose.com/finance/net/create/xbrl/) ไฟล์ลงในดิสก์

{{% blocks/products/pf/feature-page-code h3="C# รหัสเพื่อสร้าง XBRL ไฟล์โดยการเพิ่มสินค้า" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-item.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="สร้าง OFX คำขอและการตอบสนองไฟล์" %}}


สำหรับการสร้างไฟล์ OFX ให้ API [Ofxrequestdocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) และ [Ofxresponsedocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) ชั้นเรียนและนักพัฒนาสามารถทำได้อย่างง่ายดาย [สร้าง OFX คำขอ](https://products.aspose.com/finance/net/create/ofx-request/) และไฟล์ตอบสนองทั้งในรูปแบบ1.03และ2.2. สำหรับการเริ่มต้นคุณสมบัติ ofxrequestdocument API ยังมีชั้นเรียนอื่นๆเช่น [Signonrequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest),, [สถาบันการเงิน](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution) และ [Statementtransactionrequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest) ชั้นเรียนในทำนองเดียวกันสำหรับการข่มขู่คุณสมบัติ ofxresponsedocument API ให้ชั้นเรียนสนับสนุนเช่น [Signonresponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),,  [Stementtransactionresponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse) และ [การทำธุรกรรม](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction).ด้านล่างนี้เป็นตัวอย่างโค้ดสำหรับทั้งสองกรณีที่มีการใช้ชั้นเรียนที่เหมาะสมที่เกี่ยวข้อง

{{% blocks/products/pf/feature-page-code h3="C# รหัสเพื่อสร้าง OFX ขอเอกสาร" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# รหัสเพื่อสร้าง OFX เอกสารการตอบสนอง" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
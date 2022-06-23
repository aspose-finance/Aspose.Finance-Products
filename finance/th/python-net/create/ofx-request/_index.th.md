---
title: สร้าง OFX ไฟล์คำขอผ่าน Python
description: โค้ดตัวอย่างสำหรับการสร้างไฟล์คำขอ OFX ใช้รหัสตัวอย่าง API สำหรับการสร้างไฟล์คำขอแบทช์ OFX ภายในแอปพลิเคชันที่ใช้ Python 
url: /th/python-net/create/ofx-request/
family: finance
platformtag: python
feature: create
informat: OFX Request
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="สร้าง OFX ไฟล์คำขอผ่าน Python" h2="OFX ขอสร้างไฟล์โดยไม่จำเป็นต้องติดตั้ง Microsoft Office หรือซอฟต์แวร์อื่นๆ" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="วิธีสร้าง OFX ไฟล์คำขอ" %}}

หลังจากมีOFXข้อกำหนดในการสร้างไฟล์คำขอภายในแอปพลิเคชันของคุณแล้ว ให้ทำตามขั้นตอนในข้อมูลโค้ดหรือปรับปรุงตามความต้องการของคุณ

1. สร้างวัตถุคลาส OfxRequestDocument2. กำหนดคุณสมบัติที่เกี่ยวข้องโดยใช้คลาสต่างๆ ที่จัดเตรียมโดย API เช่น SignonRequest, FinancialInstitution], StatementTransactionRequest
3. ใช้ ofxVersion V2x หรือ V1x สำหรับไฟล์ xml และ sgml ตามลำดับจาก OfxVersionEnum เป็นพารามิเตอร์ในวิธีบันทึก
4. เรียกวิธีการบันทึกโดยระบุไฟล์เป้าหมายและ ofxVersion

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดในการสร้าง" %}}
หากต้องการดำเนินการ OFX ขอสร้างไฟล์ ตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นดังต่อไปนี้ 
- ระบบปฏิบัติการที่ใช้ Microsoft Windows หรือ Linux- Python 3.5 หรือใหม่กว่า- Aspose.Finance สำหรับ Python ที่อ้างอิงในโครงการของคุณ{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="รหัส Python สำหรับ OFX คำขอสร้างไฟล์" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-request-files.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="ตัวเลือกการสร้างอื่นๆ" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-response/" name="OFX ไฟล์ตอบกลับ" description="1.03 หรือ 2.2 รูปแบบ" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/xbrl/" name="XBRL ไฟล์" description="ภาษาการรายงานทางธุรกิจที่ขยายได้" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
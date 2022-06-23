---
title: สร้างไฟล์ iXBRL(inline xbrl) ผ่าน Python
description: โค้ดตัวอย่างสำหรับการสร้างไฟล์ iXBRL(inline xbrl) ใช้รหัสตัวอย่าง API สำหรับการสร้างไฟล์แบทช์ iXBRL(inline xbrl) ภายในแอปพลิเคชันที่ใช้ Python 
url: /th/python-net/create/ixbrl/
family: finance
platformtag: python
feature: create
informat: iXBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="สร้างไฟล์ iXBRL(inline xbrl) ผ่าน Python" h2="iXBRL(inline xbrl) การสร้างไฟล์โดยไม่จำเป็นต้องติดตั้ง Microsoft Office หรือซอฟต์แวร์อื่นๆ" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="วิธีสร้างไฟล์ iXBRL(inline xbrl)" %}}

ทำตามขั้นตอนในข้อมูลโค้ดหรือปรับปรุงตามที่แอปพลิเคชันของคุณต้องการสำหรับการสร้างไฟล์ iXBRL(inline xbrl) ของภาษาการรายงานทางธุรกิจที่ขยายได้ ตรวจสอบให้แน่ใจว่ามีข้อกำหนดในการสร้างภายในแอปพลิเคชันของคุณ

1. สร้างอินสแตนซ์คลาส InlineXbrlDocument2. สร้างองค์ประกอบ dom tree
3. เรียกวิธีการบันทึกโดยระบุเส้นทางของไฟล์เป้าหมาย

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดในการสร้าง" %}}
หากต้องการดำเนินการสร้างเอกสาร iXBRL(inline xbrl) ตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นดังต่อไปนี้ 
- ระบบปฏิบัติการที่ใช้ Microsoft Windows หรือ Linux- Python 3.5 หรือใหม่กว่า- Aspose.Finance สำหรับ Python ที่อ้างอิงในโครงการของคุณ{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="รหัส Python สำหรับ XBRL การสร้างไฟล์" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ixbrl.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="ตัวเลือกการสร้างอื่นๆ" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-request/" name="OFX คำขอ" description="1.03 หรือ 2.2 รูปแบบ" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-response/" name="OFX ตอบกลับ" description="1.03 หรือ 2.2 รูปแบบ" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
---
title: สร้าง XBRL ไฟล์ผ่าน Python
description: โค้ดตัวอย่างสำหรับการสร้างไฟล์ XBRL ใช้โค้ดตัวอย่าง API สำหรับการสร้างไฟล์แบทช์ XBRL ภายในแอปพลิเคชันที่ใช้ Python 
url: /th/python-net/create/xbrl/
family: finance
platformtag: python
feature: create
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="สร้าง XBRL ไฟล์ผ่าน Python" h2="การสร้างไฟล์ XBRL โดยไม่ต้องติดตั้ง Microsoft Office หรือซอฟต์แวร์อื่นๆ" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="วิธีสร้าง XBRL ไฟล์" %}}

ทำตามขั้นตอนในข้อมูลโค้ดหรือปรับปรุงตามที่แอปพลิเคชันของคุณต้องการสำหรับการสร้างไฟล์ภาษาการรายงานทางธุรกิจที่ขยายได้ XBRL ตรวจสอบให้แน่ใจว่ามีข้อกำหนดในการสร้างภายในแอปพลิเคชันของคุณ

1. สร้างอินสแตนซ์คลาส XbrlDocument1. ในการสร้าง XBRL เอกสารอินสแตนซ์ XbrlInstanceCollection และ XbrlInstance ใหม่1. เพิ่มการอ้างอิงสคีมาโดยใช้ SchemaRefCollection1. ขึ้นอยู่กับลักษณะแอปพลิเคชัน เพิ่มบริบท หน่วย รายการ ลิงก์เชิงอรรถและอื่น ๆ1. เรียกวิธีการบันทึกโดยระบุเส้นทางของไฟล์เป้าหมาย
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดในการสร้าง" %}}
หากต้องการดำเนินการสร้างเอกสาร XBRL ตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นดังต่อไปนี้ 
- ระบบปฏิบัติการที่ใช้ Microsoft Windows หรือ Linux- Python 3.5 หรือใหม่กว่า- Aspose.Finance สำหรับ Python ที่อ้างอิงในโครงการของคุณ{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="รหัส Python สำหรับ XBRL การสร้างไฟล์" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-xbrl-file-and-add-schema-reference.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="ตัวเลือกการสร้างอื่นๆ" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-request/" name="OFX คำขอ" description="1.03 หรือ 2.2 รูปแบบ" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-response/" name="OFX ตอบกลับ" description="1.03 หรือ 2.2 รูปแบบ" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
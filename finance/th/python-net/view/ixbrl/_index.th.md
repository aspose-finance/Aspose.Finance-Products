---
title: ดู iXBRL ไฟล์ผ่าน Python
description: โค้ดตัวอย่างสำหรับการดูไฟล์ iXBRL ใช้โค้ดตัวอย่าง API เพื่อดูไฟล์แบตช์ iXBRL ภายในแอปพลิเคชันที่ใช้ Python 
url: /th/python-net/view/ixbrl/
family: finance
platformtag: python
feature: view
informat: iXBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="ดู iXBRL ไฟล์ผ่าน Python" h2="การดูรายงานทางการเงินในรูปแบบ iXBRL โดยไม่ต้องติดตั้ง Microsoft Office หรือซอฟต์แวร์อื่นๆ" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="วิธีดู iXBRL ไฟล์" %}}

ทำตามขั้นตอนในข้อมูลโค้ดหรือปรับปรุงตามที่แอปพลิเคชันของคุณต้องการสำหรับการดูเอกสารภาษาการรายงานทางธุรกิจที่ขยายได้ iXBRL ตรวจสอบให้แน่ใจว่ามีข้อกำหนดในการอ่านในใบสมัครของคุณ

1. สร้างอินสแตนซ์คลาส InlineXbrlDocument2. ส่งชื่อไฟล์ iXBRL ที่ถูกต้องเป็นพารามิเตอร์
3. เพื่อให้ได้รายละเอียดภายในของไฟล์ ให้ใช้คลาสที่เกี่ยวข้อง เช่น InlineFact, Context, Unit
4. แสดงข้อมูลเหล่านี้

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดในการอ่าน" %}}
หากต้องการดูเอกสาร iXBRL ต่อ ตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นดังต่อไปนี้ 
- ระบบปฏิบัติการที่ใช้ Microsoft Windows หรือ Linux- Python 3.5 หรือใหม่กว่า- Aspose.Finance สำหรับ Python ที่อ้างอิงในโครงการของคุณ{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python รหัสสำหรับอ่าน iXBRL ไฟล์" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "read-ixbrl-file.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="ตัวเลือกการดูอื่นๆ" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/view/xbrl/" name="XBRL" description="ภาษาการรายงานทางธุรกิจที่ขยายได้" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
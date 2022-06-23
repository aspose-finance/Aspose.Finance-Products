---
title: อ่านไฟล์คำขอ OFX ผ่าน Python
description: โค้ดตัวอย่างสำหรับการอ่านไฟล์คำขอ OFX ใช้โค้ดตัวอย่าง API เพื่ออ่านไฟล์คำขอแบทช์ OFX ภายในแอปพลิเคชันที่ใช้ Python 
url: /th/python-net/read/ofx-request/
family: finance
platformtag: python
feature: read
informat: OFX request
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="อ่านไฟล์คำขอ OFX ผ่าน Python" h2="การอ่านรายงานทางการเงินในรูปแบบคำขอ OFX โดยไม่ต้องติดตั้ง Microsoft Office หรือซอฟต์แวร์อื่นๆ" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="วิธีอ่าน OFX ร้องขอไฟล์" %}}

ทำตามขั้นตอนในข้อมูลโค้ดหรือปรับปรุงตามที่แอปพลิเคชันของคุณต้องการสำหรับการอ่านไฟล์คำขอภาษาการรายงานทางธุรกิจที่ขยายได้ OFX ตรวจสอบให้แน่ใจว่ามีข้อกำหนดในการอ่านในใบสมัครของคุณ

1. สร้างอินสแตนซ์คลาส OfxRequestDocument1. ส่งชื่อไฟล์คำขอ OFX ที่ถูกต้องเป็นพารามิเตอร์1. หากต้องการทราบรายละเอียดภายในของไฟล์ ให้ใช้คลาสที่เกี่ยวข้อง เช่น SignonRequest
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดในการอ่าน" %}}
หากต้องการอ่านเอกสารคำขอต่อ OFX ตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นดังต่อไปนี้ 
- ระบบปฏิบัติการที่ใช้ Microsoft Windows หรือ Linux- Python 3.5 หรือใหม่กว่า- Aspose.Finance สำหรับ Python ที่อ้างอิงในโครงการของคุณ{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python รหัสสำหรับอ่าน OFX ไฟล์คำขอ" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "read-ofx-request.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="ตัวเลือกการอ่านอื่นๆ" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/read/ixbrl/" name="iXBRL" description="Inline Extensible Business Reporting Language" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
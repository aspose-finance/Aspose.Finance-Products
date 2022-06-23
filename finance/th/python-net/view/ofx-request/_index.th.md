---
title: ดู OFX ไฟล์คำขอผ่าน Python
description: โค้ดตัวอย่างสำหรับการดูไฟล์คำขอ OFX ใช้โค้ดตัวอย่าง API เพื่อดูไฟล์คำขอแบทช์ OFX ภายในแอปพลิเคชันที่ใช้ Python 
url: /th/python-net/view/ofx-request/
family: finance
platformtag: python
feature: view
informat: OFX request
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="ดู OFX ร้องขอไฟล์ผ่าน Python" h2="การดูรายงานทางการเงินในรูปแบบคำขอ OFX โดยไม่ต้องติดตั้ง Microsoft Office หรือซอฟต์แวร์อื่นใด" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="วิธีดู OFX คำขอไฟล์" %}}

ทำตามขั้นตอนในข้อมูลโค้ดหรือปรับปรุงตามที่แอปพลิเคชันของคุณต้องการสำหรับการดูไฟล์คำขอภาษาการรายงานทางธุรกิจที่ขยายได้ OFX ไฟล์ ตรวจสอบให้แน่ใจว่ามีข้อกำหนดในการอ่านในใบสมัครของคุณ

1. สร้างอินสแตนซ์คลาส OfxRequestDocument1. ส่งชื่อไฟล์คำขอ OFX ที่ถูกต้องเป็นพารามิเตอร์1. หากต้องการทราบรายละเอียดภายในของไฟล์ ให้ใช้คลาสที่เกี่ยวข้อง เช่น SignonRequest1. แสดงข้อมูลเหล่านี้
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดในการอ่าน" %}}
หากต้องการดูเอกสารคำขอต่อ OFX ตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นดังต่อไปนี้ 
- ระบบปฏิบัติการที่ใช้ Microsoft Windows หรือ Linux- Python 3.5 หรือใหม่กว่า- Aspose.Finance สำหรับ Python ที่อ้างอิงในโครงการของคุณ{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python รหัสเพื่อดู OFX ไฟล์คำขอ" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "read-ofx-request.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="ตัวเลือกการดูอื่นๆ" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/view/ixbrl/" name="iXBRL" description="Inline Extensible Business Reporting Language" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
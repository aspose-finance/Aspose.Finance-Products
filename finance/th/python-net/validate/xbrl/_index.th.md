---
title: ตรวจสอบ XBRL ไฟล์ผ่าน Python
description: โค้ดตัวอย่างสำหรับการตรวจสอบความถูกต้องของไฟล์ XBRL ใช้โค้ดตัวอย่าง API เพื่อตรวจสอบความถูกต้องของไฟล์แบตช์ XBRL ภายในแอปพลิเคชันที่ใช้ Python 
url: /th/python-net/validate/xbrl/
family: finance
platformtag: python
feature: validate
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="ตรวจสอบ XBRL ไฟล์ผ่าน Python" h2="การตรวจสอบความถูกต้องของรายงานทางการเงินในรูปแบบ XBRL โดยไม่ต้องติดตั้ง Microsoft Office หรือซอฟต์แวร์อื่นๆ" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="วิธีตรวจสอบความถูกต้องของ XBRL Files" %}}

ทำตามขั้นตอนในข้อมูลโค้ดหรือปรับปรุงตามที่แอปพลิเคชันของคุณต้องการสำหรับการตรวจสอบความถูกต้องของเอกสารภาษาการรายงานทางธุรกิจที่ขยายได้ XBRL ตรวจสอบให้แน่ใจว่ามีข้อกำหนดในการตรวจสอบความถูกต้องภายในใบสมัครของคุณ

1. โหลดไฟล์ XBRL โดยใช้อินสแตนซ์คลาส XbrlDocument2. การตรวจสอบความถูกต้องของไฟล์ที่โหลดมานั้นต้องตรงกันกับ [XBRL ข้อมูลจำเพาะ](http://www.xbrl.org/specification/inlinexbrl-part1/rec-2013-11-18/inlinexbrl-part1-rec-2013-11-18.html)
3. ในการตรวจสอบความถูกต้อง ใช้วิธีตรวจสอบความถูกต้องของคลาส XbrlInstance

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ข้อกำหนดการตรวจสอบ" %}}
ในการดำเนินการตรวจสอบเอกสาร XBRL ฉบับ ตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นดังต่อไปนี้ 
- ระบบปฏิบัติการที่ใช้ Microsoft Windows หรือ Linux- Python 3.5 หรือใหม่กว่า- Aspose.Finance สำหรับ Python ที่อ้างอิงในโครงการของคุณ{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python รหัสสำหรับตรวจสอบ XBRL ไฟล์" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "validate-xbrl-instance-file.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="ตัวเลือกการตรวจสอบความถูกต้องอื่นๆ" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/validate/ixbrl/" name="XBRL" description="Inline Extensible Business Reporting Language" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
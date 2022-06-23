---
title: ตรวจสอบรายงานทางการเงินผ่าน Python
url: /th/python-net/validate/
description:  Python รหัสสำหรับตรวจสอบรายงานทางการเงินในไฟล์ XBRL และ iXBRL ผ่านไลบรารี Python
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="ตรวจสอบไฟล์การรายงานทางการเงินผ่าน Python" h2="การตรวจสอบความถูกต้องของรูปแบบรายงานทางการเงิน รวมถึง XBRL และ iXBRL ภายในแอปพลิเคชันที่ใช้ Python" >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance สำหรับ Python ผ่าน .NET](https://products.aspose.com/finance/python-net/) เป็นคุณลักษณะที่สมบูรณ์ ขยายได้ และง่ายต่อการใช้การประมวลผลรายงานทางการเงิน API นักพัฒนาสามารถโหลด ตรวจสอบ ดูหรือสร้างรูปแบบ XBRL และ iXBRL ได้อย่างง่ายดายสำหรับโซลูชันทางการเงินและธุรกิจ API มีคลาส XbrlDocument และคลาส InlineXbrlDocument สำหรับการโหลดไฟล์ XBRL และ iXBRL
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="ตรวจสอบความถูกต้อง XBRL Document" %}}

การตรวจสอบความถูกต้องของไฟล์ XBRL เป็นสิ่งจำเป็นสำหรับกรณีต่างๆ เช่น การตรวจสอบข้อมูลว่ามีโครงสร้างและรูปแบบที่ถูกต้อง ในการตรวจสอบเอกสาร XBLR ขั้นแรกให้ใช้คลาส XbrlDocument เพื่อโหลดไฟล์ XBRL เมื่อต้องการใช้วิธีการตรวจสอบความถูกต้องของคลาส XbrlInstance ขั้นแรก ให้เริ่มต้น XbrlInstanceCollection ด้วยวัตถุ XbrlDocument XbrlInstances ทำซ้ำผ่านแต่ละ XbrlInstance.ValidationErrors เพื่อรับรหัสข้อผิดพลาดที่ถูกต้องและดำเนินการตามนั้นโดยการพิมพ์ข้อความแสดงข้อผิดพลาดที่กำหนดเองบนคอนโซลหรือเขียนภายในไฟล์

{{% blocks/products/pf/feature-page-code h3="Python รหัสสำหรับตรวจสอบ XBRL ไฟล์" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "validate-xbrl-instance-file.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="ตรวจสอบความถูกต้อง iXBRL Document" %}}

สำหรับการตรวจสอบ iXLRB ให้โหลดผ่านคลาส InlineXbrlDocument และใช้เมธอด validate() ในการแจงนับ ValidationErrorCode รหัสข้อผิดพลาดในการตรวจสอบจะถูกกำหนดสำหรับแต่ละกฎการตรวจสอบ โค้ดบางส่วน ได้แก่ ContextPeriodNoStartTime, ContextPeriodNoEndTime, ContextPeriodStartAfterEnd, ContextInstantNoTime, ContextScenarioXbrlNamespace, ContextScenarioXbrlSubstitutionGroup เป็นต้น นักพัฒนาสามารถดีบักและแสดงรหัสในฐานะผู้ใช้ปลายทาง หรือสามารถแสดงทิศทางในการแก้ไขปัญหาได้

{{% blocks/products/pf/feature-page-code h3="Python รหัสสำหรับตรวจสอบ iXBRL เอกสาร" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "validate-ixbrl-file.py" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}
---
title: ตรวจสอบรายงานทางการเงินผ่าน .NET
url: /th/net/validate/
description:  C# รหัสสำหรับตรวจสอบรายงานทางการเงินในไฟล์ XBRL และ iXBRL ผ่านไลบรารี .NET
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="ตรวจสอบไฟล์การรายงานทางการเงินผ่าน C#" h2="การตรวจสอบความถูกต้องของรูปแบบรายงานทางการเงิน รวมถึง XBRL และ iXBRL ภายในแอปพลิเคชันที่ใช้ .NET" >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) เป็นคุณลักษณะที่สมบูรณ์ ขยายได้ และง่ายต่อการใช้การประมวลผลรายงานทางการเงิน API นักพัฒนาสามารถโหลด ตรวจสอบ ดูหรือสร้างรูปแบบ XBRL และ iXBRL ได้อย่างง่ายดายสำหรับโซลูชันทางการเงินและธุรกิจ APIให้ [XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) ชั้นเรียนและ  [InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) คลาสสำหรับการโหลดไฟล์ XBRL และ iXBRL
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="ตรวจสอบความถูกต้อง XBRL Document" %}}

การตรวจสอบความถูกต้องของไฟล์ XBRL เป็นสิ่งจำเป็นสำหรับกรณีต่างๆ เช่น การตรวจสอบข้อมูลว่ามีโครงสร้างและรูปแบบที่ถูกต้อง ในการตรวจสอบเอกสาร XBLR ขั้นแรกให้ใช้คลาส XbrlDocument เพื่อโหลดไฟล์ XBRL การใช้ [ตรวจสอบความถูกต้อง()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) วิธีการของ [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) คลาส ขั้นแรก ให้เริ่มต้น [XbrlInstanceCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) ด้วยวัตถุ XbrlDocument XbrlInstances ทำซ้ำผ่านแต่ละ [XbrlInstance.ValidationErrors](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/properties/validationerrors) เพื่อรับรหัสข้อผิดพลาดที่ถูกต้องและดำเนินการตามนั้นโดยการพิมพ์ข้อความแสดงข้อผิดพลาดที่กำหนดเองบนคอนโซลหรือเขียนภายในไฟล์

{{% blocks/products/pf/feature-page-code h3="C# รหัสสำหรับตรวจสอบ XBRL ไฟล์" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-xbrl-file.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="ตรวจสอบความถูกต้อง iXBRL Document" %}}

สำหรับการตรวจสอบ iXLRB ให้โหลดผ่าน [InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) คลาสและใช้วิธี Validate() ใน [ValidationErrorCode](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.validator/validationerrorcode) การแจงนับ รหัสข้อผิดพลาดในการตรวจสอบถูกกำหนดไว้สำหรับกฎการตรวจสอบแต่ละข้อ โค้ดบางส่วน ได้แก่ ContextPeriodNoStartTime, ContextPeriodNoEndTime, ContextPeriodStartAfterEnd, ContextInstantNoTime, ContextScenarioXbrlNamespace, ContextScenarioXbrlSubstitutionGroup เป็นต้น นักพัฒนาสามารถดีบักและแสดงรหัสในฐานะผู้ใช้ปลายทาง หรือสามารถแสดงทิศทางในการแก้ไขปัญหาได้

{{% blocks/products/pf/feature-page-code h3="C# รหัสสำหรับตรวจสอบ iXBRL เอกสาร" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-ixbrl-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}
{{< /blocks/products/pf/feature-page-wrap >}}
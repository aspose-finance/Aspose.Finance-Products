---
title: ตรวจสอบรายงานทางการเงินผ่าน .NET
url: /th/net/validate/
description:  C# รหัสเพื่อตรวจสอบรายงานทางการเงินใน XBRL และ iXBRL ไฟล์ผ่านห้องสมุด .NET
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="ตรวจสอบไฟล์รายงานทางการเงินผ่าน C#" h2="ตรวจสอบรูปแบบรายงานทางการเงินรวมถึง XBRL และ iXBRL ภายใน .NET การใช้งานตาม" >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) เป็นคุณลักษณะที่อุดมไปด้วยขยายและง่ายต่อการใช้การประมวลผลรายงานทางการเงิน API นักพัฒนาสามารถโหลดตรวจสอบมุมมองหรือสร้างรูปแบบ XBRL และ iXBRL สำหรับโซลูชันทางการเงินและธุรกิจ API ให้ [เอกสาร xbrldocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) คลาสและ  [Inlinexbrldocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) คลาสสำหรับการโหลด XBRL และ iXBRL ไฟล์
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="ตรวจสอบเอกสาร XBRL" %}}

การตรวจสอบไฟล์ XBRL เป็นสิ่งจำเป็นสำหรับหลายกรณีเช่นการตรวจสอบข้อมูลอยู่ในโครงสร้างและรูปแบบที่เหมาะสมหากต้องการตรวจสอบเอกสาร xblr ประการแรกให้ใช้คลาส xbrldocument เพื่อโหลดไฟล์ XBRL To use คำกริยา [ตรวจสอบ ()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) วิธีการ [Xbrlinstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) ชั้นแรก intialize [Xbrlinstancecollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) ด้วยวัตถุ xbrldocument xbrlinstances ซ้ำผ่านแต่ละ [Xbrlinstance.การตรวจสอบข้อผิดพลาด](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/properties/validationerrors) เพื่อรับรหัสข้อผิดพลาดที่ถูกต้องและดำเนินการตามโดยการพิมพ์ข้อความแสดงข้อผิดพลาดที่กำหนดเองบนคอนโซลหรือเขียนภายในไฟล์

{{% blocks/products/pf/feature-page-code h3="C# รหัสเพื่อตรวจสอบไฟล์ XBRL" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-xbrl-file.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="ตรวจสอบเอกสาร iXBRL" %}}

สำหรับการตรวจสอบ ixlrb โหลดผ่านทาง [Inlinexbrldocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) คลาสและใช้วิธีการตรวจสอบ () ใน [Validationerrorcode](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.validator/validationerrorcode) การนับรหัสข้อผิดพลาดในการตรวจสอบจะถูกกำหนดไว้สำหรับกฎการตรวจสอบแต่ละข้อไม่กี่รหัสคือ contextperiodnostarttime, contextperiodnoendtime, contextperiodstartafterend, contextinstantnotime, contextscenarioxbrlnamespace, contextscenarioxbrlsubstitutiongroup ฯลฯนักพัฒนาสามารถแก้ปัญหาและแสดงรหัสเป็นของผู้ใช้ปลายทางหรือสามารถแสดงทิศทางสำหรับการแก้ไขปัญหา

{{% blocks/products/pf/feature-page-code h3="C# รหัสเพื่อตรวจสอบเอกสาร iXBRL" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-ixbrl-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}
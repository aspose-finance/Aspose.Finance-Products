---
title: C# के माध्यम से XBRL फ़ाइल बनाएं
description: XBRL फ़ाइल निर्माण के लिए नमूना कोड। बैच के लिए API उदाहरण कोड का उपयोग करें XBRL .NET आधारित अनुप्रयोगों के भीतर फाइल निर्माण। 
url: /hi/net/create/xbrl/
family: finance
platformtag: net
feature: create
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# के माध्यम से XBRL फ़ाइलें बनाएं" h2="XBRL Microsoft Office स्थापित या किसी अन्य सॉफ़्टवेयर की आवश्यकता के बिना फ़ाइलें बनाना।" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="कैसे बनाएं XBRL फ़ाइलें" %}}

कोड स्निपेट में दिए गए चरणों का पालन करें या एक्स्टेंसिबल व्यावसायिक रिपोर्टिंग भाषा XBRL फ़ाइलें जेनरेट करने के लिए आपके एप्लिकेशन की आवश्यकता के अनुसार इसे बेहतर बनाएं। सुनिश्चित करें कि आपके आवेदन में निर्माण संबंधी आवश्यकताएं हैं।

1. सृजन करना [XbrlDocument वर्ग](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) उदाहरण।1. एक नया XBRL इंस्टेंस दस्तावेज़ बनाने के लिए [XbrlInstanceCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) तथा [एक्सबीआरएल इंस्टेंस](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance).1. स्कीमा संदर्भ का उपयोग करके जोड़ें [स्कीमारेफसंग्रह](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemarefcollection)1. एप्लिकेशन प्रकृति के आधार पर संदर्भ, इकाई, आइटम, फुटनोट लिंक और बहुत कुछ जोड़ें।1. बुलाएं [विधि सहेजें](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) लक्ष्य फ़ाइल पथ प्रदान करके।
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="निर्माण आवश्यकता" %}}
XBRL दस्तावेज़ बनाने के लिए आगे बढ़ने के लिए, .NET Finance API आवेदन में शामिल करने की मुख्य आवश्यकता है। 
- इसे कमांड लाइन के माध्यम से ``nuget install Aspose.Finance``` के रूप में या विजुअल स्टूडियो के पैकेज मैनेजर कंसोल के माध्यम से ```इंस्टॉल-पैकेज Aspose.Finance``` के साथ इंस्टॉल करें।
- वैकल्पिक रूप से, एक ज़िप फ़ाइल में ऑफ़लाइन MSI इंस्टॉलर या DLL प्राप्त करें [डाउनलोड](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XBRL फ़ाइल निर्माण के लिए C# कोड" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-schema-reference.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="अन्य निर्माण विकल्प" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX अनुरोध" description="1.03 या 2.2 प्रारूप" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX प्रतिक्रिया" description="1.03 या 2.2 प्रारूप" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
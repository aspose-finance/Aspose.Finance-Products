---
title: वित्तीय रिपोर्ट को .NET के माध्यम से सत्यापित करें
url: /hi/net/validate/
description:  वित्तीय रिपोर्ट को XBRL और iXBRL फ़ाइलों में .NET लाइब्रेरी के माध्यम से सत्यापित करने के लिए C# कोड।
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="वित्तीय रिपोर्टिंग फ़ाइलों को C# के माध्यम से सत्यापित करें" h2=".NET आधारित अनुप्रयोगों में XBRL और iXBRL सहित वित्तीय रिपोर्ट प्रारूपों का सत्यापन।" >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) एक सुविधा संपन्न, एक्स्टेंसिबल और उपयोग में आसान वित्तीय रिपोर्ट संसाधन API है। डेवलपर वित्तीय और व्यावसायिक समाधानों के लिए XBRL और iXBRL प्रारूपों को आसानी से लोड, मान्य, देख या बना सकते हैं। API प्रदान करता है [एक्सबीआरएल दस्तावेज़](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) कक्षा और  [इनलाइनXbrlदस्तावेज़](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) XBRL और iXBRL फ़ाइलें लोड करने के लिए कक्षा।
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="XBRL दस्तावेज़ सत्यापित करें" %}}

कई मामलों के लिए XBRL फ़ाइल के सत्यापन की आवश्यकता होती है, जैसे कि डेटा की सही संरचना और प्रारूप में जाँच करना। XBLR दस्तावेज़ों को मान्य करने के लिए, सबसे पहले XBRL फ़ाइल लोड करने के लिए XbrlDocument वर्ग का उपयोग करें। का उपयोग करने के लिए [मान्य करें ()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) उसकि विधि [एक्सबीआरएल इंस्टेंस](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) क्लास, सबसे पहले इनिशियलाइज़ करें [XbrlInstanceCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) XbrlDocument ऑब्जेक्ट के साथ XbrlInstances. प्रत्येक के माध्यम से पुनरावृति [XbrlInstance.ValidationErrors](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/properties/validationerrors) सही त्रुटि कोड प्राप्त करने के लिए और कंसोल पर अनुकूलित त्रुटि संदेशों को प्रिंट करके या फ़ाइल के भीतर लिखकर तदनुसार कार्य करें।

{{% blocks/products/pf/feature-page-code h3="C# सत्यापित करने के लिए कोड XBRL फ़ाइल" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-xbrl-file.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="iXBRL दस्तावेज़ सत्यापित करें" %}}

iXLRB सत्यापन के लिए, इसे इसके माध्यम से लोड करें [इनलाइनXbrlदस्तावेज़](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) क्लास और इसकी Validate() विधि का उपयोग करें। में [सत्यापन त्रुटि कोड](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.validator/validationerrorcode) गणना, सत्यापन त्रुटि कोड प्रत्येक सत्यापन नियम के लिए परिभाषित किए गए हैं। कुछ कोड हैं ContextPeriodNoStartTime, ContextPeriodNoEndTime, ContextPeriodStartAfterEnd, ContextInstantNoTime, ContextScenarioXbrlNamespace, ContextScenarioXbrlSubstitutionGroup आदि। डेवलपर्स डिबग कर सकते हैं और अंतिम उपयोगकर्ताओं के रूप में कोड प्रदर्शित कर सकते हैं या समस्या को हल करने के लिए दिशा दिखा सकते हैं।

{{% blocks/products/pf/feature-page-code h3="C# सत्यापित करने के लिए कोड iXBRL दस्तावेज़" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-ixbrl-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}
{{< /blocks/products/pf/feature-page-wrap >}}
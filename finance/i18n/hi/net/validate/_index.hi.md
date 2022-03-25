---
title: Validate वित्तीय रिपोर्ट के माध्यम से .NET
url: /hi/net/validate/
description:  C# कोड validate करने के लिए वित्तीय रिपोर्ट में XBRL और iXBRL फ़ाइलें के माध्यम से .NET पुस्तकालय है।
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Validate वित्तीय रिपोर्टिंग फ़ाइलें के माध्यम से C#" h2="वैधीकरण वित्तीय रिपोर्ट सहित प्रारूपों XBRL और iXBRL भीतर .NET आधारित अनुप्रयोगों." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) एक सुविधा अमीर है, एक्स्टेंसिबल और प्रयोग करने में आसान वित्तीय रिपोर्ट प्रसंस्करण API. डेवलपर्स आसानी से कर सकते हैं लोड, validate, देखें या बनाने XBRL और iXBRL प्रारूपों के लिए वित्तीय और व्यापार समाधान है। API प्रदान करता [XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) वर्ग और  [InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) कक्षा के लिए लोड हो रहा है XBRL और iXBRL फ़ाइलें.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Validate XBRL दस्तावेज़" %}}

के सत्यापन XBRL फ़ाइल मामलों की एक संख्या के लिए की जरूरत है इस तरह के रूप में चेक डेटा में है सही संरचना और प्रारूप. Validate करने के लिए XBLR दस्तावेजों, सबसे पहले उपयोग XbrlDocument कक्षा लोड करने के लिए XBRL फ़ाइल. का उपयोग करने के लिए [Validate ()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) की विधि [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) वर्ग, सबसे पहले intialize के [XbrlInstanceCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) XbrlDocument के साथ वस्तु XbrlInstances. Iterate के माध्यम से प्रत्येक [XbrlInstance.ValidationErrors](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/properties/validationerrors) प्राप्त करने के लिए सही मुद्रण द्वारा त्रुटि कोड और अधिनियम तदनुसार अनुकूलित त्रुटि संदेश पर कंसोल या लेखन के भीतर एक फ़ाइल.

{{% blocks/products/pf/feature-page-code h3="C# Validate करने के लिए कोड XBRL फ़ाइल" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-xbrl-file.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Validate iXBRL दस्तावेज़" %}}

IXLRB के लिए सत्यापन, लोड के माध्यम से यह [InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) वर्ग और उपयोग अपने Validate() विधि है। में [ValidationErrorCode](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.validator/validationerrorcode) गणना, सत्यापन त्रुटि कोड के लिए परिभाषित कर रहे हैं प्रत्येक सत्यापन नियम. कोड के कुछ कर रहे हैं ContextPeriodNoStartTime, ContextPeriodNoEndTime, ContextPeriodStartAfterEnd, ContextInstantNoTime, ContextScenarioXbrlNamespace, ContextScenarioXbrlSubstitutionGroup आदि डेवलपर्स डिबग और प्रदर्शन कर सकते हैं कोड के रूप में अंत उपयोगकर्ताओं को विभाजित या के लिए दिशा दिखा सकते हैं इस मुद्दे

{{% blocks/products/pf/feature-page-code h3="C# Validate करने के लिए कोड iXBRL दस्तावेज़" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-ixbrl-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}
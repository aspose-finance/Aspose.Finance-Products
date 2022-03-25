---
title: Validate XBRL फ़ाइल के माध्यम से C#
description: नमूना कोड के लिए XBRL फ़ाइल सत्यापन. उपयोग API उदाहरण कोड validate करने के लिए बैच XBRL फ़ाइलें भीतर .NET आधारित अनुप्रयोगों. 
url: /hi/net/validate/xbrl/
family: finance
platformtag: net
feature: validate
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Validate XBRL फ़ाइलें के माध्यम से C#" h2="वैधीकरण वित्तीय रिपोर्ट में XBRL प्रारूप की जरूरत के बिना माइक्रोसॉफ्ट कार्यालय स्थापित या किसी भी अन्य सॉफ्टवेयर है।" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Validate करने के लिए कैसे XBRL फ़ाइलें" %}}

कोड snippet या बढ़ाने में यह चरणों का पालन के रूप में अपने आवेदन जरूरतों वैधीकरण के लिए एक्स्टेंसिबल व्यापार रिपोर्टिंग भाषा XBRL दस्तावेजों अपने भीतर आवेदन आवश्यकताओं वैधीकरण होने के बारे में सुनिश्चित किया जा सकता है।

1. लोड XBRL फ़ाइल का उपयोग [XbrlDocument वर्ग](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) उदाहरण है।1. लोड फ़ाइल की वैधता की जांच करने के लिए, इतना है कि यह के साथ मेल खाना चाहिए [XBRL विशिष्टता](http://www.xbrl.org/specification/inlinexbrl-part1/rec-2013-11-18/inlinexbrl-part1-rec-2013-11-18.html)1. Validatity की जांच करने के लिए, उपयोग [Validate()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) की विधि [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) वर्ग है।
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="सत्यापन आवश्यकता" %}}
वैधीकरण के लिए आगे बढ़ने के लिए XBRL दस्तावेजों, .NET Finance API मुख्य आवश्यकता है करने के लिए आवेदन के भीतर शामिल किया है। 
- के माध्यम से इसे स्थापित कमांड लाइन के रूप में '''nuget स्थापित Aspose.Finance विजुअल स्टूडियो के लिए '''या के माध्यम से पैकेज प्रबंधक की कंसोल '''Install-पैकेज के साथ Aspose.Finance के लिए'''.
- वैकल्पिक रूप से, ऑफ़लाइन प्राप्त एमएसआई संस्थापक या DLLs में से एक ज़िप फ़ाइल [डाउनलोड](https://downloads.aspose.com/finance/net)है।{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# validate करने के लिए कोड XBRL फ़ाइलें" offSpacer="" %}}

{{< gist "aspose-com-gists" "1272da1f804f8cef122600269db09fbb" "validate-xbrl-instance-file.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="अन्य वैधीकरण विकल्प" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/validate/ixbrl/" name="XBRL" description="इनलाइन एक्स्टेंसिबल व्यापार रिपोर्टिंग भाषा" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
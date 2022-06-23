---
title: iXBRL फ़ाइल को C# के माध्यम से सत्यापित करें
description: iXBRL फ़ाइल सत्यापन के लिए नमूना कोड। .NET आधारित एप्लिकेशन में बैच iXBRL फाइलों को मान्य करने के लिए API उदाहरण कोड का उपयोग करें। 
url: /hi/net/validate/ixbrl/
family: finance
platformtag: net
feature: validate
informat: iXBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# के माध्यम से iXBRL फ़ाइलें सत्यापित करें" h2="वित्तीय रिपोर्ट को iXBRL स्वरूप में Microsoft Office स्थापित या किसी अन्य सॉफ़्टवेयर की आवश्यकता के बिना मान्य करना।" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="कैसे सत्यापित करें iXBRL फ़ाइलें" %}}

कोड स्निपेट में दिए गए चरणों का पालन करें या एक्स्टेंसिबल व्यावसायिक रिपोर्टिंग भाषा iXBRL दस्तावेज़ों को मान्य करने के लिए आपके आवेदन की आवश्यकता के अनुसार इसे बेहतर बनाएं। सुनिश्चित करें कि आपके आवेदन में मान्य आवश्यकताएं हैं।

1. iXBRL फ़ाइल का उपयोग करके लोड करें [InlineXbrlDocument वर्ग](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) उदाहरण।1. लोड की गई फ़ाइल की वैधता की जांच करने के लिए, ताकि यह मेल खाना चाहिए [iXBRL विनिर्देश](http://www.xbrl.org/specification/inlinexbrl-part1/rec-2013-11-18/inlinexbrl-part1-rec-2013-11-18.html)1. प्रयोग करना [मान्य करें ()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument/methods/validate) फ़ाइल वैधता के लिए विधि।
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="सत्यापन आवश्यकता" %}}
iXBRL दस्तावेज़ों के सत्यापन के लिए आगे बढ़ने के लिए, .NET Finance API आवेदन में शामिल करने की मुख्य आवश्यकता है। 
- इसे कमांड लाइन के माध्यम से ``nuget install Aspose.Finance``` के रूप में या विजुअल स्टूडियो के पैकेज मैनेजर कंसोल के माध्यम से ```इंस्टॉल-पैकेज Aspose.Finance``` के साथ इंस्टॉल करें।
- वैकल्पिक रूप से, एक ज़िप फ़ाइल में ऑफ़लाइन MSI इंस्टॉलर या DLL प्राप्त करें [डाउनलोड](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="iXBRL फाइलों को सत्यापित करने के लिए C# कोड" offSpacer="" %}}

{{< gist "aspose-com-gists" "1272da1f804f8cef122600269db09fbb" "validate-ixbrl-file.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="अन्य मान्य विकल्प" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/validate/xbrl/" name="XBRL" description="एक्स्टेंसिबल बिजनेस रिपोर्टिंग लैंग्वेज" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
---
title: बनाने OFX प्रतिक्रिया फ़ाइल के माध्यम से C#
description: नमूना कोड के लिए OFX प्रतिक्रिया फ़ाइल निर्माण. उपयोग API उदाहरण कोड बैच के लिए OFX प्रतिक्रिया फ़ाइलें पीढ़ी के भीतर .NET आधारित अनुप्रयोगों है। 
url: /hi/net/create/ofx-response/
family: finance
platformtag: net
feature: create
informat: OFX Response
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="बनाने OFX प्रतिक्रिया के माध्यम से फ़ाइलें C#" h2="OFX प्रतिक्रिया फ़ाइलें निर्माण की जरूरत के बिना माइक्रोसॉफ्ट कार्यालय स्थापित या किसी भी अन्य सॉफ्टवेयर है।" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="कैसे बनाने के लिए OFX प्रतिक्रिया फ़ाइलें" %}}

कोड snippet या बढ़ाने में यह चरणों का पालन के रूप में अपने आवेदन जरूरतों होने के बाद के निर्माण आवश्यकताओं के भीतर अपने आवेदन

1. बनाने [OfxResponseDocument वर्ग](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) वस्तु है।1. आवंटित प्रासंगिक गुण का उपयोग अलग अलग वर्गों द्वारा प्रदान API की तरह [SignonResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [StatementTransactionResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse), [StatementTransaction](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction)1. OfxVersion V2x या V1x का उपयोग के लिए एक्सएमएल और sgml से क्रमशः फ़ाइलें [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) के रूप में पैरामीटर बचाने में विधि है।1. कॉल के [बचाने विधि](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument/methods/save) लक्ष्य फ़ाइल और ofxVersion प्रदान करके.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="निर्माण आवश्यकता" %}}
के लिए आगे बढ़ने के लिए OFX प्रतिक्रिया फ़ाइल निर्माण, .NET Finance API मुख्य आवश्यकता है करने के लिए रिपोर्ट के भीतर शामिल किया पीढ़ी आवेदन है। 
- के माध्यम से इसे स्थापित कमांड लाइन के रूप में '''nuget स्थापित Aspose.Finance विजुअल स्टूडियो के लिए '''या के माध्यम से पैकेज प्रबंधक की कंसोल '''Install-पैकेज के साथ Aspose.Finance के लिए'''.
- वैकल्पिक रूप से, ऑफ़लाइन प्राप्त एमएसआई संस्थापक या DLLs में से एक ज़िप फ़ाइल [डाउनलोड](https://downloads.aspose.com/finance/net)है।{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# कोड के लिए OFX प्रतिक्रिया फ़ाइलें निर्माण" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="अन्य निर्माण विकल्प" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX अनुरोध फ़ाइल" description="1.03 या 2.2 प्रारूप" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL फ़ाइल" description="एक्स्टेंसिबल व्यापार रिपोर्टिंग भाषा" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
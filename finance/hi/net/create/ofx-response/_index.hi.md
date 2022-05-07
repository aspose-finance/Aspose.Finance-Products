---
title: C# के माध्यम से OFX प्रतिक्रिया फ़ाइल बनाएं
description: OFX प्रतिक्रिया फ़ाइल निर्माण के लिए नमूना कोड। बैच के लिए API उदाहरण कोड का उपयोग करें OFX प्रतिक्रिया फ़ाइलें .NET आधारित अनुप्रयोगों के भीतर उत्पन्न होती हैं। 
url: /hi/net/create/ofx-response/
family: finance
platformtag: net
feature: create
informat: OFX Response
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# के माध्यम से OFX प्रतिक्रिया फ़ाइलें बनाएं" h2="OFX Microsoft Office स्थापित या किसी अन्य सॉफ़्टवेयर की आवश्यकता के बिना फ़ाइलों का निर्माण प्रतिक्रिया।" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="OFX प्रतिसाद फ़ाइलें कैसे बनाएं" %}}

कोड स्निपेट में दिए गए चरणों का पालन करें या अपने एप्लिकेशन के भीतर निर्माण आवश्यकताओं को पूरा करने के बाद इसे अपनी एप्लिकेशन की आवश्यकताओं के अनुसार बढ़ाएं।

1. सृजन करना [OfxResponseDocument वर्ग](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) वस्तु।1. API like . द्वारा प्रदान किए गए विभिन्न वर्गों का उपयोग करके प्रासंगिक गुण असाइन करें [साइनऑन रिस्पांस](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [वक्तव्य लेन-देन प्रतिक्रिया](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse), [स्टेटमेंट ट्रांजैक्शन](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction)1. से xVersion V2x या V1x का उपयोग क्रमशः xml और sgml फ़ाइलों के लिए करें [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) सहेजें विधि में पैरामीटर के रूप में।1. बुलाएं [विधि सहेजें](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument/methods/save) लक्ष्य फ़ाइल और ofxVersion प्रदान करके।
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="निर्माण आवश्यकता" %}}
OFX प्रतिसाद फ़ाइल निर्माण के लिए आगे बढ़ने के लिए, .NET Finance API रिपोर्ट जनरेशन एप्लिकेशन में शामिल करने की मुख्य आवश्यकता है। 
- इसे कमांड लाइन के माध्यम से ``nuget install Aspose.Finance``` के रूप में या विजुअल स्टूडियो के पैकेज मैनेजर कंसोल के माध्यम से ```इंस्टॉल-पैकेज Aspose.Finance``` के साथ इंस्टॉल करें।
- वैकल्पिक रूप से, एक ज़िप फ़ाइल में ऑफ़लाइन MSI इंस्टॉलर या DLL प्राप्त करें [डाउनलोड](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="OFX प्रतिसाद फ़ाइलों के निर्माण के लिए C# कोड" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="अन्य निर्माण विकल्प" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX अनुरोध फ़ाइल" description="1.03 या 2.2 प्रारूप" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL फ़ाइल" description="एक्स्टेंसिबल बिजनेस रिपोर्टिंग लैंग्वेज" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
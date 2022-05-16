---
title: C# के माध्यम से OFX अनुरोध फ़ाइल बनाएं
description: OFX अनुरोध फ़ाइल निर्माण के लिए नमूना कोड। बैच के लिए API उदाहरण कोड का उपयोग करें OFX .NET आधारित अनुप्रयोगों के भीतर फाइल निर्माण का अनुरोध करें। 
url: /hi/net/create/ofx-request/
family: finance
platformtag: net
feature: create
informat: OFX Request
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# के माध्यम से OFX अनुरोध फ़ाइलें बनाएं" h2="OFX Microsoft Office स्थापित या किसी अन्य सॉफ़्टवेयर की आवश्यकता के बिना फ़ाइल निर्माण का अनुरोध करें।" >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="कैसे बनाएं OFX अनुरोध फ़ाइलें" %}}

आपके आवेदन में OFX अनुरोध फ़ाइलें बनाने की आवश्यकताएं होने के बाद, कोड स्निपेट में दिए गए चरणों का पालन करें या अपनी आवश्यकता के अनुसार इसे बेहतर बनाएं।

1. सृजन करना [OfxRequestDocument वर्ग](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) वस्तु।1. API like . द्वारा प्रदान किए गए विभिन्न वर्गों का उपयोग करके प्रासंगिक गुण असाइन करें [साइनऑनअनुरोध](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [वित्तीय संस्थान](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution), [स्टेटमेंट ट्रांजैक्शन रिक्वेस्ट](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest)1. से xVersion V2x या V1x का उपयोग क्रमशः xml और sgml फ़ाइलों के लिए करें [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) सहेजें विधि में पैरामीटर के रूप में।1. बुलाएं [विधि सहेजें](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument/methods/save) लक्ष्य फ़ाइल और ofxVersion प्रदान करके।
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="निर्माण आवश्यकता" %}}
OFX फ़ाइल निर्माण का अनुरोध करने के लिए आगे बढ़ने के लिए, .NET Finance API रिपोर्ट जनरेशन एप्लिकेशन में शामिल करने की मुख्य आवश्यकता है। 
- इसे कमांड लाइन के माध्यम से ```nuget install Aspose.Finance``` के रूप में या विजुअल स्टूडियो के पैकेज मैनेजर कंसोल के माध्यम से `` `इंस्टॉल-पैकेज Aspose.Finance``` के साथ स्थापित करें।
- वैकल्पिक रूप से, एक ज़िप फ़ाइल में ऑफ़लाइन MSI इंस्टॉलर या DLL प्राप्त करें [डाउनलोड](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="OFX फ़ाइल निर्माण का अनुरोध करने के लिए C# कोड" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-request-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="अन्य निर्माण विकल्प" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX प्रतिक्रिया फ़ाइल" description="1.03 या 2.2 प्रारूप" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL फ़ाइल" description="एक्स्टेंसिबल बिजनेस रिपोर्टिंग लैंग्वेज" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
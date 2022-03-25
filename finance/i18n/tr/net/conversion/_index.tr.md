---
title: Finansal Raporları .NET aracılığıyla dönüştürün
url: /tr/net/conversion/
description:  C#, XBRL kitaplığı aracılığıyla Finansal Raporları XBRL, iXBRL ve OFX dosya fomatlarında dönüştürmek için.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Finansal Rapor Dosyalarını C# aracılığıyla dönüştürün" h2="XBRL, iXBRL ve OFX dosyası dahil olmak üzere XBRL, iXBRL ve OFX dosyasını içeren finansal rapor formatları dönüştürme." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) Zengin, genişletilebilir ve kullanımı kolay API bir özelliktir. Geliştiriciler XBRL örneklerini, bağlantı tabanlarını ve taksonomi şemasını kullanarak kolayca doğrulayabilir [Doğrulama () yöntemi](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) Şartnamede empoze edilen sözdizimi gerekliliklerine uymalıdır. Ayrıca, XBRL, iXBRL formatlarını okuyabilir ve sıfırdan XBRL örnek oluşturabilirler. Ayrıca, XBRL biçimini ** iXBRL ve Microsoft Excel XLSX dosyalarına dönüştürebilirler. API ayrıca açık finansal değişim (OFX) biçimi istek/yanıt oluşturmayı destekler ve OFX dosya isteği/yanıtı 1. 03'ten 2.2 biçimine dönüştürür.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="OFX Yanıt ve Talep Dosyaları Dönüştürün" %}}

API, iki sınıf sağlayarak OFX istek ve yanıt dosyaları oluşturmayı destekler. [OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) 1.03 ve 2.2 formatında OFX istek dosyaları oluşturmak ve yüklemek için ve [OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) 1.03 ve 2.2 formatında OFX yanıt dosyaları için. Dahası, [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) 1.x sürümü, sgml dosya formatı ve V2x 2.x sürümü, xml dosya formatı olan üyelere sahip V1x. OfxRequestDocument sınıfının veya OfxResponseDocument sınıfının Kaydet yöntemini çağırdıktan sonra, geliştiriciler 1.03 sgml dosyasından 2.2 xml biçimine kolayca dönüştürebilirler.


{{% blocks/products/pf/feature-page-code h3="C# Dönüştürmek için Kod OFX Yanıt Dosyaları" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-response-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Dosyaları Dönüştürmek için Kod OFX Talep Dosyaları" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-request-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL Finansal Raporlar Dönüşüm" %}}

API, XBRL dosyalarını iXBRL ve Microsoft'a dönüştürmeyi destekler®Excel XLSX formatı. Dönüşüm işlemi basittir, öncelikle dosya üzerinden yükleyin [XbrlDocument Sınıfı](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument). Kullanın [SaveOptions sınıfı](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions) Için [SaveFormat](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions/properties/saveformat), XbrlDocument Sınıfının Kaydet yönteminde parametre olarak kullanılacak. IXBLR dosyasına kaydetmek için, [SaveFormat.IXBRL](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveformat) Kullanılacak ve XLSX formatına ihracat için, SaveFormat.XLSX kullanılacaktır.

{{% blocks/products/pf/feature-page-code h3="C# XBRL ile iXBRL Dışa Aktar" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-ixbrl.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# XBRL için XLSX Dönüştürme Kodu" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-xlsx.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}
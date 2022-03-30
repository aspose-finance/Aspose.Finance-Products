---
title: Mali Raporları .NET aracılığıyla dönüştürün
url: /tr/net/conversion/
description:  .NET kitaplığı aracılığıyla XBRL, iXBRL ve OFX dosya biçimlerindeki Mali Raporları dönüştürmek için C# kodu.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Mali Rapor Dosyalarını C# aracılığıyla dönüştürün" h2="Mali rapor biçimleri, .NET tabanlı uygulamalarda XBRL, iXBRL ve OFX dosyası dahil olmak üzere 1.03\'ten 2.2 biçimine dönüştürülür." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) zengin özelliklere sahip, genişletilebilir ve kullanımı kolay bir API'dir. Geliştiriciler, aşağıdakileri kullanarak XBRL örneği, bağlantı tabanlarını ve sınıflandırma şemalarını kolayca doğrulayabilir: [validate() yöntemi](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) şartnamede belirtilen sözdizimi gereksinimlerine uygun olmalıdır. Ayrıca, XBRL, iXBRL biçimlerini okuyabilir ve sıfırdan XBRL örneği oluşturabilirler. Ayrıca, **XBRL biçimini** iXBRL ve Microsoft Excel XLSX dosyalarına dönüştürebilirler. API ayrıca açık finansal değişim (OFX) biçiminde istek/yanıt oluşturmayı destekler ve OFX dosya isteğini/yanıtını 1.03'ten 2.2 biçimine dönüştürür.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="OFX Yanıt ve İstek Dosyalarını Dönüştür" %}}

API, iki sınıf sağlayarak OFX istek ve yanıt dosyalarının oluşturulmasını destekler. [OfxRequestBelgesi](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) 1.03 ve 2.2 biçiminde OFX istek dosyası oluşturmak ve yüklemek için ve [OfxResponseBelgesi](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) 1.03 ve 2.2 biçimindeki OFX yanıt dosyaları için. ayrıca, [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) 1.x sürümü, sgml dosya biçimi ve V2x 2.x sürümü, xml dosya biçimi olan V1x üyelerine sahip numaralandırma. Geliştiriciler, OfxRequestDocument sınıfının veya OfxResponseDocument sınıfının Save yöntemini çağırdıktan sonra, 1.03 sgml dosyasını kolayca 2.2 xml formatına dönüştürebilir.


{{% blocks/products/pf/feature-page-code h3="OFX Yanıt Dosyalarını Dönüştürmek için C# Kodu" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-response-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="OFX İstek Dosyalarını Dönüştürmek için C# Kodu" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-request-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL Mali Rapor Dönüşümü" %}}

API, XBRL dosyalarının iXBRL ve Microsoft® Excel XLSX biçimine dönüştürülmesini destekler. Dönüştürme işlemi basittir, önce dosyayı şuradan yükleyin: [XbrlBelge Sınıfı](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument). Kullan [SaveOptions sınıfı](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions) için [Kaydet Formatı](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions/properties/saveformat), XbrlDocument Class'ın Save yönteminde parametre olarak kullanılacaktır. iXBLR dosyasına kaydetmek için, [SaveFormat.IXBRL](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveformat) kullanılacak ve XLSX formatına dışa aktarmak için SaveFormat.XLSX kullanılacaktır.

{{% blocks/products/pf/feature-page-code h3="XBRL - iXBRL Dışa Aktarılacak C# Kodu" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-ixbrl.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="XBRL - XLSX Dönüşümü için C# Kodu" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-xlsx.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}
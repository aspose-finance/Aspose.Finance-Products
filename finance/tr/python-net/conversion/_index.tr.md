---
title: Mali Raporları Python aracılığıyla dönüştürün
url: /tr/python-net/conversion/
description:  Python kitaplığı aracılığıyla XBRL, iXBRL(inline xbrl) ve OFX dosya biçimlerindeki Mali Raporları dönüştürmek için Python kodu.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Mali Rapor Dosyalarını Python aracılığıyla dönüştürün" h2="Mali rapor biçimleri, Python tabanlı uygulamalarda XBRL, iXBRL ve OFX dosyası dahil olmak üzere 1.03\'ten 2.2 biçimine dönüştürülür." >}}

{{% blocks/products/pf/feature-page-summary %}}

[.NET üzerinden Python için Aspose.Finance](https://products.aspose.com/finance/python-net/) zengin özelliklere sahip, genişletilebilir ve kullanımı kolay bir API'dir. Geliştiriciler, belirtimde belirtilen sözdizimi gereksinimlerine uyması gereken validate() yöntemini kullanarak XBRL örneği, bağlantı tabanlarını ve sınıflandırma şemalarını kolayca doğrulayabilir. Ayrıca, XBRL, iXBRL biçimlerini okuyabilir ve sıfırdan XBRL örneği oluşturabilirler. Ayrıca, **XBRL biçimini** iXBRL ve Microsoft Excel XLSX dosyalarına dönüştürebilirler. API ayrıca açık finansal değişim (OFX) biçiminde istek/yanıt oluşturmayı destekler ve OFX dosya isteğini/yanıtını 1.03'ten 2.2 biçimine dönüştürür.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="OFX Yanıt ve İstek Dosyalarını Dönüştür" %}}

API, iki sınıf sağlayarak OFX istek ve yanıt dosyalarının oluşturulmasını destekler. 1.03 ve 2.2 biçiminde OFX istek dosyası oluşturmak ve yüklemek için OfxRequestDocument ve 1.03 ve 2.2 biçiminde OFX yanıt dosyaları için OfxResponseDocument. Ayrıca, 1.x sürümü, sgml dosya biçimi ve V2x 2.x sürümü, xml dosya biçimi olan V1x üyelerine sahip OfxVersionEnum Enumeration. Geliştiriciler, OfxRequestDocument sınıfının veya OfxResponseDocument sınıfının kaydetme yöntemini çağırdıktan sonra, 1.03 sgml dosyasından 2.2 xml formatına kolayca dönüştürebilir.


{{% blocks/products/pf/feature-page-code h3="OFX Yanıt Dosyalarını Dönüştürmek için C# Kodu" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-ofx-response-from-1.03-to-2.2.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="OFX İstek Dosyalarını Dönüştürmek için C# Kodu" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-ofx-request-from-1.03-to-2.2.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL Mali Rapor Dönüşümü" %}}

API, XBRL dosyalarının iXBRL ve Microsoft® Excel XLSX biçimine dönüştürülmesini destekler. Dönüştürme işlemi basittir, öncelikle dosyayı XbrlDocument Class üzerinden yükleyin. XbrlDocument Sınıfının kaydetme yönteminde parametre olarak kullanılacak SaveFormat için SaveOptions sınıfını kullanın. iXBLR dosyasına kaydetmek için SaveFormat.IXBRL, XLSX formatına aktarmak için SaveFormat.XLSX kullanılacaktır.

{{% blocks/products/pf/feature-page-code h3="XBRL - iXBRL Dışa Aktarılacak Python Kodu" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-xbrl-to-ixbrl.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="XBRL - XLSX Dönüşümü için Python Kodu" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-xbrl-to-xlsx.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}
{{< /blocks/products/pf/feature-page-wrap >}}
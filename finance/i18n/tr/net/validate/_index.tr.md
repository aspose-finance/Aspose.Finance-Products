---
title: .NET aracılığıyla Finansal Raporları Doğrulayın
url: /tr/net/validate/
description:  XBRL ve iXBRL dosyalarındaki finansal raporları .NET kitaplığı aracılığıyla doğrulamak için C# kodu.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# aracılığıyla Finansal Raporlama Dosyalarını Doğrulayın" h2=".NET tabanlı uygulamalarda XBRL ve iXBRL dahil olmak üzere finansal rapor formatlarını doğrulamak." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) Zengin, genişletilebilir ve kullanımı kolay bir finansal rapor işleme API. Geliştiriciler, finansal ve iş çözümleri için XBRL ve iXBRL formatlarını kolayca yükleyebilir, doğrulayabilir, görüntüleyebilir veya oluşturabilir. API sağlar [XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Sınıf ve  [InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) XBRL ve iXBRL dosya yükleme sınıfı.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="XBRL Belgeyi Doğrulayın" %}}

Verilerin doğru yapı ve formatta olduğunu kontrol etmek gibi bir dizi durum için XBRL dosyasının doğrulanması gerekir. XBLR belgelerini doğrulamak için öncelikle XBRL dosyasını yüklemek için XbrlDocument sınıfını kullanın. Kullanmak için [Doğrulama ()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) Yöntemi [XbrlÖrnek](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) Sınıf, öncelikle [XbrlInstanceCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) XbrlDocument nesnesi ile XbrlInstances. Her birini tekrar et [Xbrlörnek. Doğrulama Hataları](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/properties/validationerrors) Doğru hata kodunu almak ve konsola özelleştirilmiş hata mesajlarını yazdırarak veya bir dosya içinde yazarak buna göre hareket etmek.

{{% blocks/products/pf/feature-page-code h3="C# XBRL Dosyayı Doğrulamak için Kod" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-xbrl-file.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="iXBRL Belgeyi Doğrulayın" %}}

İXLRB doğrulama için, aracılığıyla yükleyin [InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) Sınıf ve onun Doğrulama () yöntemini kullanın. İçinde [Doğrulama ErrorCode](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.validator/validationerrorcode) Numaralandırma, doğrulama hata kodları her doğrulama kuralı için tanımlanır. Çok az kod ContextPeriodNoStartTime, ContextPerioXbrlSubstitutionGroup vb.

{{% blocks/products/pf/feature-page-code h3="C# iXBRL Belgeyi Doğrulamak için Kod" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-ixbrl-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}
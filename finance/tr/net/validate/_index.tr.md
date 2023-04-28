---
title: Mali Raporları .NET aracılığıyla doğrulayın
url: /tr/net/validate/
description:  .NET kitaplığı aracılığıyla XBRL ve iXBRL dosyalarındaki mali raporları doğrulamak için C# kodu.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Mali Raporlama Dosyalarını C# aracılığıyla doğrulayın" h2=".NET tabanlı uygulamalarda XBRL ve iXBRL dahil olmak üzere mali rapor biçimlerinin doğrulanması." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) zengin özelliklere sahip, genişletilebilir ve kullanımı kolay bir mali rapor işlemedir API. Geliştiriciler, finans ve iş çözümleri için XBRL ve iXBRL biçimlerini kolayca yükleyebilir, doğrulayabilir, görüntüleyebilir veya oluşturabilir. API sağlar [XbrlBelgesi](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) sınıf ve  [Satır içiXbrlBelge](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) XBRL ve iXBRL dosyalarını yüklemek için sınıf.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="XBRL Belgesini Doğrula" %}}

Verilerin doğru yapı ve biçimde olup olmadığının kontrol edilmesi gibi bir dizi durum için XBRL dosyasının doğrulanması gerekir. XBLR belgelerini doğrulamak için, öncelikle XBRL dosyasını yüklemek için XbrlDocument sınıfını kullanın. kullanmak için [doğrulamak()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) yöntemi [XbrlÖrneği](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) class, öncelikle [XbrlÖrnek Koleksiyonu](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) XbrlDocument nesnesi XbrlInstances ile. Her birini yinele [XbrlInstance.ValidationErrors](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/properties/validationerrors) doğru hata kodunu almak ve özelleştirilmiş hata mesajlarını konsolda yazdırarak veya bir dosyaya yazarak buna göre hareket etmek.

{{% blocks/products/pf/feature-page-code h3="XBRL Dosyasını Doğrulamak için C# Kodu" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-xbrl-file.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="iXBRL Belgesini Doğrula" %}}

iXLRB doğrulaması için şununla yükleyin: [Satır içiXbrlBelge](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) sınıfını seçin ve Validate() yöntemini kullanın. İçinde [ValidationErrorCode](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.validator/validationerrorcode) numaralandırma, doğrulama hata kodları her doğrulama kuralı için tanımlanır. Kodların birkaçı ContextPeriodNoStartTime, ContextPeriodNoEndTime, ContextPeriodStartAfterEnd, ContextInstantNoTime, ContextScenarioXbrlNamespace, ContextScenarioXbrlSubstitutionGroup vb. Geliştiriciler kodları son kullanıcılar itibariyle ayıklayabilir ve görüntüleyebilir veya sorunun çözümü için yön gösterebilir.

{{% blocks/products/pf/feature-page-code h3="iXBRL Belgesini Doğrulamak için C# Kodu" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-ixbrl-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}
{{< /blocks/products/pf/feature-page-wrap >}}
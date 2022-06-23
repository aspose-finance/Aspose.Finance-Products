---
title: Mali Raporları Python aracılığıyla doğrulayın
url: /tr/python-net/validate/
description:  Python kitaplığı aracılığıyla XBRL ve iXBRL dosyalarındaki mali raporları doğrulamak için Python kodu.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Mali Raporlama Dosyalarını Python aracılığıyla doğrulayın" h2="Python tabanlı uygulamalarda XBRL ve iXBRL dahil olmak üzere mali rapor biçimlerinin doğrulanması." >}}

{{% blocks/products/pf/feature-page-summary %}}

[.NET üzerinden Python için Aspose.Finance](https://products.aspose.com/finance/python-net/) zengin özelliklere sahip, genişletilebilir ve kullanımı kolay bir mali rapor işlemedir API. Geliştiriciler, finans ve iş çözümleri için XBRL ve iXBRL biçimlerini kolayca yükleyebilir, doğrulayabilir, görüntüleyebilir veya oluşturabilir. API, XBRL ve iXBRL dosyalarını yüklemek için XbrlDocument sınıfı ve InlineXbrlDocument sınıfı sağlar.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="XBRL Belgesini Doğrula" %}}

Verilerin doğru yapı ve biçimde olup olmadığının kontrol edilmesi gibi bir dizi durum için XBRL dosyasının doğrulanması gerekir. XBLR belgelerini doğrulamak için, öncelikle XBRL dosyasını yüklemek için XbrlDocument sınıfını kullanın. XbrlInstance sınıfının validate yöntemini kullanmak için öncelikle XbrlInstanceCollection'ı XbrlDocument nesnesi XbrlInstances ile başlatınız. Doğru hata kodunu almak için her XbrlInstance.ValidationErrors'ı yineleyin ve özelleştirilmiş hata mesajlarını konsolda yazdırarak veya bir dosyaya yazarak buna göre hareket edin.

{{% blocks/products/pf/feature-page-code h3="XBRL Dosyasını Doğrulamak için Python Kodu" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "validate-xbrl-instance-file.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="iXBRL Belgesini Doğrula" %}}

iXLRB doğrulaması için InlineXbrlDocument sınıfı aracılığıyla yükleyin ve validate() yöntemini kullanın. ValidationErrorCode numaralandırmada, her doğrulama kuralı için doğrulama hata kodları tanımlanır. Kodların birkaçı ContextPeriodNoStartTime, ContextPeriodNoEndTime, ContextPeriodStartAfterEnd, ContextInstantNoTime, ContextScenarioXbrlNamespace, ContextScenarioXbrlSubstitutionGroup vb. Geliştiriciler kodları son kullanıcılar itibariyle ayıklayabilir ve görüntüleyebilir veya sorunun çözümü için yön gösterebilir.

{{% blocks/products/pf/feature-page-code h3="iXBRL Belgesini Doğrulamak için Python Kodu" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "validate-ixbrl-file.py" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}
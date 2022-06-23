---
title: XBRL Dosyasını Python aracılığıyla doğrulayın
description: XBRL dosya doğrulaması için örnek kod. Python tabanlı uygulamalarda toplu XBRL dosyalarını doğrulamak için API örnek kodunu kullanın. 
url: /tr/python-net/validate/xbrl/
family: finance
platformtag: python
feature: validate
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="XBRL Dosyayı Python aracılığıyla doğrulayın" h2="Microsoft Office yüklü veya başka bir yazılıma ihtiyaç duymadan XBRL formatındaki mali raporları doğrulama." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="XBRL Dosya Nasıl Doğrulanır" %}}

Kod parçacığındaki adımları izleyin veya genişletilebilir işletme raporlama dili XBRL belgelerini doğrulamak için uygulama gereksinimlerinize göre geliştirin. Uygulamanızda doğrulama gereksinimleri olduğundan emin olun.

1. XBRL dosyasını XbrlDocument sınıfı Örneği kullanarak yükleyin.2. Yüklenen dosyanın geçerliliğini kontrol etmek, böylece dosyayla eşleşmesi gerekir. [XBRL özelliği](http://www.xbrl.org/specification/inlinexbrl-part1/rec-2013-11-18/inlinexbrl-part1-rec-2013-11-18.html)
3. Geçerliliği kontrol etmek için XbrlInstance sınıfının validate yöntemini kullanın.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Doğrulama Gereksinimi" %}}
XBRL belgeyi doğrulamaya devam etmek için aşağıdaki ön koşullara sahip olduğunuzdan emin olun. 
- Microsoft Windows veya Linux tabanlı işletim sistemi.- Python 3.5 veya üzeri.- Projenizde referans verilen Python için Aspose.Finance.{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XBRL dosyaları doğrulamak için Python kodu" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "validate-xbrl-instance-file.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Diğer Doğrulama Seçenekleri" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/validate/ixbrl/" name="XBRL" description="Satır İçi Genişletilebilir İşletme Raporlama Dili" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
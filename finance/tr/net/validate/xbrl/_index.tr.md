---
title: XBRL Dosyasını C# aracılığıyla doğrulayın
description: XBRL dosya doğrulaması için örnek kod. .NET tabanlı uygulamalarda toplu XBRL dosyalarını doğrulamak için API örnek kodunu kullanın. 
url: /tr/net/validate/xbrl/
family: finance
platformtag: net
feature: validate
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="XBRL Dosyayı C# aracılığıyla doğrulayın" h2="Microsoft Office yüklü veya başka bir yazılıma ihtiyaç duymadan XBRL formatındaki mali raporları doğrulama." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="XBRL Dosya Nasıl Doğrulanır" %}}

Kod parçacığındaki adımları izleyin veya genişletilebilir işletme raporlama dili XBRL belgelerini doğrulamak için uygulama gereksinimlerinize göre geliştirin. Uygulamanızda doğrulama gereksinimleri olduğundan emin olun.

1. XBRL dosyasını kullanarak yükleyin [XbrlDocument sınıfı](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Misal.1. Yüklenen dosyanın geçerliliğini kontrol etmek için, böylece eşleşmesi gerekir. [XBRL özelliği](http://www.xbrl.org/specification/inlinexbrl-part1/rec-2013-11-18/inlinexbrl-part1-rec-2013-11-18.html)1. Geçerliliği kontrol etmek için şunu kullanın: [Doğrula()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) yöntemi [XbrlÖrneği](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) sınıf.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Doğrulama Gereksinimi" %}}
XBRL belgeyi doğrulamaya devam etmek için .NET Finance API, başvuruya dahil edilmesi gereken ana gereksinimdir. 
- Komut satırı aracılığıyla ```nuget install Aspose.Finance``` veya Visual Studio'nun Paket Yönetici Konsolu aracılığıyla ```Install-Package Aspose.Finance``` ile kurun.
- Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri bir ZIP dosyasında şu adresten alın: [İndirilenler](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XBRL dosyaları doğrulamak için C# kodu" offSpacer="" %}}

{{< gist "aspose-com-gists" "1272da1f804f8cef122600269db09fbb" "validate-xbrl-instance-file.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Diğer Doğrulama Seçenekleri" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/validate/ixbrl/" name="XBRL" description="Satır İçi Genişletilebilir İşletme Raporlama Dili" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
---
title: iXBRL Dosyasını C# aracılığıyla doğrulayın
description: iXBRL dosya doğrulaması için örnek kod. .NET tabanlı uygulamalarda toplu iXBRL dosyalarını doğrulamak için API örnek kodunu kullanın. 
url: /tr/net/validate/ixbrl/
family: finance
platformtag: net
feature: validate
informat: iXBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="iXBRL Dosyayı C# aracılığıyla doğrulayın" h2="Microsoft Office yüklü veya başka bir yazılıma ihtiyaç duymadan iXBRL formatındaki mali raporları doğrulama." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="iXBRL Dosya Nasıl Doğrulanır" %}}

Kod parçacığındaki adımları izleyin veya genişletilebilir işletme raporlama dili iXBRL belgelerini doğrulamak için uygulama gereksinimlerinize göre geliştirin. Uygulamanızda doğrulama gereksinimleri olduğundan emin olun.

1. iXBRL dosyasını kullanarak yükleyin [InlineXbrlDocument sınıfı](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) Misal.1. Yüklenen dosyanın geçerliliğini kontrol etmek için, böylece eşleşmesi gerekir. [iXBRL özelliği](http://www.xbrl.org/specification/inlinexbrl-part1/rec-2013-11-18/inlinexbrl-part1-rec-2013-11-18.html)1. Kullanmak [Doğrula()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument/methods/validate) Dosya geçerliliği için yöntem.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Doğrulama Gereksinimi" %}}
iXBRL belgeyi doğrulamaya devam etmek için .NET Finance API, başvuruya dahil edilmesi gereken ana gereksinimdir. 
- Komut satırı aracılığıyla ```nuget install Aspose.Finance``` veya Visual Studio'nun Paket Yönetici Konsolu aracılığıyla ```Install-Package Aspose.Finance``` ile kurun.
- Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri bir ZIP dosyasında şu adresten alın: [İndirilenler](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="iXBRL dosyaları doğrulamak için C# kodu" offSpacer="" %}}

{{< gist "aspose-com-gists" "1272da1f804f8cef122600269db09fbb" "validate-ixbrl-file.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Diğer Doğrulama Seçenekleri" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/validate/xbrl/" name="XBRL" description="Genişletilebilir İşletme Raporlama Dili" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
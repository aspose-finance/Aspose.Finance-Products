---
title: C# aracılığıyla XBRL Dosyasını Doğrulayın
description: XBRL dosya doğrulama için örnek kod. .NET tabanlı uygulamalarda toplu XBRL dosyalarını doğrulamak için API örnek kodu kullanın. 
url: /tr/net/validate/xbrl/
family: finance
platformtag: net
feature: validate
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# aracılığıyla XBRL Dosyaları Doğrulayın" h2="Finansal raporları, Microsoft Office\'in yüklü veya başka bir yazılıma ihtiyaç duymadan XBRL biçiminde doğrulanması." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="XBRL Dosyaları Nasıl Doğrulanır" %}}

Genişletilebilir iş raporlama dili XBRL belgelerini doğrulamak için uygulama ihtiyaçlarınız itibariyle kod parçacıkındaki adımları izleyin veya geliştirin. Başvurunuzda doğrulama gereksinimlerine sahip olduğunuzdan emin olun.

1. Kullanarak XBRL dosyasını yükleyin [XbrlDocument sınıfı](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Örnek.1. Yüklenen dosyanın geçerliliğini kontrol etmek için, böylece eşleşmesi gerekir [XBRL şartname](http://www.xbrl.org/specification/inlinexbrl-part1/rec-2013-11-18/inlinexbrl-part1-rec-2013-11-18.html)1. Doğrulama kontrol etmek için kullanın [Doğrulama ()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) Yöntemi [XbrlÖrnek](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) Sınıf.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Doğrulama Gereksinimi" %}}
XBRL belgelerini onaylamaya devam etmek için, .NET Finance API, uygulamaya dahil edilmesi gereken ana gerekliliktir. 
- Komut satırı aracılığıyla ''nuget install Aspose.Finance'' olarak veya ''Install-Package Aspose.Finance'' ile Visual Studio Paket Yöneticisi Konsolu aracılığıyla yükleyin.
- Alternatif olarak, bir ZIP dosyasında çevrimdışı MSI yükleyicisini veya DLL'leri alın [Indirmeler](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XBRL dosyalarını doğrulamak için C# kodu" offSpacer="" %}}

{{< gist "aspose-com-gists" "1272da1f804f8cef122600269db09fbb" "validate-xbrl-instance-file.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Diğer Doğrulama Seçenekleri" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/validate/ixbrl/" name="XBRL" description="Satır içi Genişletilebilir İş Raporlama Dili" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
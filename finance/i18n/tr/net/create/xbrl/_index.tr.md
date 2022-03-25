---
title: C# aracılığıyla XBRL Dosya Oluştur
description: XBRL dosya oluşturma için örnek kod. .NET tabanlı uygulamalarda toplu XBRL dosya üretimi için API örnek kodu kullanın. 
url: /tr/net/create/xbrl/
family: finance
platformtag: net
feature: create
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# aracılığıyla XBRL Dosyalar oluşturun" h2="XBRL Microsoft Office yüklü veya başka bir yazılıma ihtiyaç duymadan dosyalar oluşturma." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="XBRL Dosyaları Nasıl Oluşturulur" %}}

Kod pasajındaki adımları izleyin veya genişletilebilir iş raporlama dili XBRL dosyaları oluşturmak için uygulamanızın ihtiyaçları doğrultusunda geliştirin. Başvurunuzda oluşturma gereksinimlerine sahip olduğunuzdan emin olun.

1. Oluştur [XbrlDocument sınıfı](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Örnek.1. Yeni bir XBRL örnek belge oluşturmak için [XbrlInstanceCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) Ve [XbrlÖrnek](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance).1. Kullanarak şema referansı ekle [Şema Koleksiyonu](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemarefcollection)1. Uygulama niteliğine bağlı olarak bağlam, birim, öğe, dipnot bağlantısı ve daha fazlasını ekleyin.1. Ara [Kaydet yöntemi](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) Hedef dosya yolunu sağlayarak.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yaratma Gereksinimi" %}}
XBRL belge üretimine devam etmek için, .NET Finance API, uygulamaya dahil edilmesi gereken ana gerekliliktir. 
- Komut satırı aracılığıyla ''nuget install Aspose.Finance'' olarak veya ''Install-Package Aspose.Finance'' ile Visual Studio Paket Yöneticisi Konsolu aracılığıyla yükleyin.
- Alternatif olarak, bir ZIP dosyasında çevrimdışı MSI yükleyicisini veya DLL'leri alın [Indirmeler](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XBRL dosya oluşturma için C# kodu" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-schema-reference.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Diğer Oluşturma Seçenekleri" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX Talep" description="1.03 veya 2.2 Formatı" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX Yanıt" description="1.03 veya 2.2 Formatı" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
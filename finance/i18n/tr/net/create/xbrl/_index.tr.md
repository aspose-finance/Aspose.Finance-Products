---
title: C# aracılığıyla XBRL Dosyası oluşturun
description: XBRL dosyası oluşturma için örnek kod. .NET tabanlı uygulamalarda toplu XBRL dosyaları oluşturmak için API örnek kodunu kullanın. 
url: /tr/net/create/xbrl/
family: finance
platformtag: net
feature: create
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# aracılığıyla XBRL Dosya oluşturun" h2="Microsoft Office yüklü veya başka bir yazılıma ihtiyaç duymadan XBRL dosya oluşturma." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="XBRL Dosya Nasıl Oluşturulur" %}}

Kod parçacığındaki adımları izleyin veya genişletilebilir iş raporlama dili XBRL dosyaları oluşturmak için uygulama gereksinimlerinize göre geliştirin. Uygulamanızda oluşturma gereksinimleri olduğundan emin olun.

1. Yaratmak [XbrlDocument sınıfı](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Misal.1. Yeni bir XBRL örnek belgesi oluşturmak için [XbrlÖrnek Koleksiyonu](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) ve [XbrlÖrneği](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance).1. kullanarak şema referansı ekleyin [ŞemaRefKoleksiyon](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemarefcollection)1. Uygulamanın doğasına bağlı olarak bağlam, birim, öğe, dipnot bağlantısı ve daha fazlasını ekleyin.1. Ara [Yöntemi kaydet](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) hedef dosya yolunu sağlayarak.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Oluşturma Gereksinimi" %}}
XBRL belge üretimine devam etmek için .NET Finance API, başvuruya dahil edilecek ana gereksinimdir. 
- Komut satırı aracılığıyla ```nuget install Aspose.Finance``` veya Visual Studio'nun Paket Yönetici Konsolu aracılığıyla ```Install-Package Aspose.Finance``` ile kurun.
- Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri bir ZIP dosyasında şu adresten alın: [İndirilenler](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XBRL dosya oluşturma için C# kodu" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-schema-reference.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Diğer Oluşturma Seçenekleri" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX İstek" description="1.03 veya 2.2 Biçimi" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX Yanıt" description="1.03 veya 2.2 Biçimi" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
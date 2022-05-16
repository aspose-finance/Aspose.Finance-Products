---
title: OFX yanıt Dosyasını C# aracılığıyla okuyun
description: OFX yanıt dosyası okuması için örnek kod. .NET tabanlı uygulamalarda toplu OFX yanıt dosyalarını okumak için API örnek kodunu kullanın. 
url: /tr/net/read/ofx-response/
family: finance
platformtag: net
feature: read
informat: OFX response
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# aracılığıyla OFX yanıt Dosyalarını okuyun" h2="Microsoft Office yüklü veya başka bir yazılıma ihtiyaç duymadan finansal raporları OFX yanıt formatında okuma." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="OFX yanıt Dosyaları Nasıl Okunur" %}}

Kod parçacığındaki adımları izleyin veya genişletilebilir iş raporlama dili OFX yanıt dosyalarını okumak için uygulama gereksinimlerinize göre geliştirin. Uygulamanızda okuma gereksinimleri olduğundan emin olun.

1. Yaratmak [OfxResponseDocument sınıfı](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) Misal.1. Geçerli bir OFX yanıt dosyasının adını parametre olarak iletin.1. Dosyanın iç detayını elde etmek için aşağıdaki gibi ilgili sınıfları kullanın. [SignonResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Okuma Gereksinimi" %}}
OFX yanıt belgesini okumaya devam etmek için .NET Finance API, başvuruya dahil edilmesi gereken ana gereksinimdir. 
- Komut satırı aracılığıyla ```nuget install Aspose.Finance``` olarak veya Visual Studio'nun Paket Yönetici Konsolu aracılığıyla ```Install-Package Aspose.Finance``` ile kurun.
- Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri bir ZIP dosyasında şu adresten alın: [İndirilenler](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="OFX yanıt dosyalarını okumak için C# kodu" offSpacer="" %}}

{{< gist "aspose-finance-gists" "01125f8901f4fde8dfd5c9764b59ef2f" "read-ofx-response.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Diğer Okuma Seçenekleri" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/read/ixbrl/" name="iXBRL" description="Satır İçi Genişletilebilir İşletme Raporlama Dili" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
﻿---
title: C# üzerinden XBRL Dosyayı Görüntüle
description: XBRL dosya görüntüleme için örnek kod. .NET tabanlı uygulamalarda toplu XBRL dosyalarını görüntülemek için API örnek kodunu kullanın. 
url: /tr/net/view/xbrl/
family: finance
platformtag: net
feature: view
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# üzerinden XBRL Dosyayı Görüntüle" h2="Microsoft Office yüklü veya başka bir yazılıma ihtiyaç duymadan finansal raporları XBRL formatında görüntüleme." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="XBRL Dosya Nasıl Görüntülenir" %}}

Kod parçacığındaki adımları izleyin veya genişletilebilir iş raporlama dili XBRL dosyalarını okumak için uygulama gereksinimlerinize göre geliştirin. Uygulamanızda okuma gereksinimleri olduğundan emin olun.

1. Oluşturmak [XbrlDocument sınıfı](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Misal.2. Geçerli bir XBRL dosyasının adını parametre olarak iletin.
3. Dosyanın iç detayını elde etmek için aşağıdaki gibi ilgili sınıfları kullanın. [ŞemaRefKoleksiyon](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemarefcollection), [Bağlam](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context), [Birim](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/unit) 
4. Bu bilgileri göster

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Okuma Gereksinimi" %}}
XBRL dokümanı görüntülemeye devam etmek için .NET Finance API, başvuruya dahil edilecek ana gereksinimdir. 
- Komut satırı aracılığıyla ```nuget install Aspose.Finance``` veya Visual Studio'nun Paket Yönetici Konsolu aracılığıyla ```Install-Package Aspose.Finance``` ile kurun.
- Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri bir ZIP dosyasında şu adresten alın: [İndirilenler](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XBRL dosyaları okumak için C# kodu" offSpacer="" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "read-xbrl-file.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Diğer Görüntüleme Seçenekleri" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/view/ixbrl/" name="iXBRL" description="Satır İçi Genişletilebilir İşletme Raporlama Dili" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
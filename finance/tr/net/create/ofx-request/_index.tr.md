---
title: C# aracılığıyla OFX İstek Dosyası oluşturun
description: OFX istek dosyası oluşturma için örnek kod. .NET tabanlı uygulamalarda toplu OFX istek dosyaları oluşturmak için API örnek kodunu kullanın. 
url: /tr/net/create/ofx-request/
family: finance
platformtag: net
feature: create
informat: OFX Request
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# aracılığıyla OFX İstek Dosyası Oluşturun" h2="OFX Microsoft Office yüklü veya başka bir yazılıma ihtiyaç duymadan dosya oluşturma isteğinde bulunun." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="OFX İstek Dosyası Nasıl Oluşturulur" %}}

Uygulamanızda OFX İstek dosyaları oluşturma gereksinimlerine sahip olduktan sonra, kod parçacığındaki adımları izleyin veya gereksiniminize göre geliştirin.

1. Oluşturmak [OfxRequestDocument sınıfı](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) nesne.1. API like tarafından sağlanan farklı sınıfları kullanarak ilgili özellikleri atayın [SignonRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [Finansal kurum](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution), [AçıklamaİşlemTalebi](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest)1. xml ve sgml dosyaları için sırasıyla ofxVersion V2x veya V1x'i kullanın. [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) Kaydet yönteminde parametre olarak.1. Ara [Yöntemi kaydet](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument/methods/save) hedef dosyayı ve ofxVersion'ı sağlayarak.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Oluşturma Gereksinimi" %}}
OFX İstek dosyası oluşturmaya devam etmek için .NET Finance API, rapor oluşturma uygulamasına dahil edilmesi gereken ana gereksinimdir. 
- Komut satırı aracılığıyla ```nuget install Aspose.Finance``` veya Visual Studio'nun Paket Yönetici Konsolu aracılığıyla ```Install-Package Aspose.Finance``` ile kurun.
- Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri bir ZIP dosyasında şu adresten alın: [İndirilenler](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="OFX istek dosyası oluşturma için C# kodu" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-request-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Diğer Oluşturma Seçenekleri" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX Yanıt Dosyası" description="1.03 veya 2.2 Biçimi" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL Dosya" description="Genişletilebilir İşletme Raporlama Dili" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
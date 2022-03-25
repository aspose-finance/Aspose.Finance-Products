---
title: C# aracılığıyla OFX Talep Dosyası Oluştur
description: OFX istek dosyası oluşturma için örnek kod. .NET tabanlı uygulamalarda toplu OFX dosya oluşturma isteği için API örnek kodu kullanın. 
url: /tr/net/create/ofx-request/
family: finance
platformtag: net
feature: create
informat: OFX Request
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# aracılığıyla OFX Talep Dosyaları Oluştur" h2="OFX Microsoft Office yüklü veya başka bir yazılıma ihtiyaç duymadan dosya oluşturma isteği." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="OFX Talep Dosyaları Nasıl Oluşturulur" %}}

OFX Başvurunuzda dosya oluşturma gereksinimlerini talep ettikten sonra, kod snippet'teki adımları izleyin veya gereksiniminiz olarak geliştirin.

1. Oluştur [OfxRequestDocument sınıfı](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) Nesne.1. API gibi tarafından sağlanan farklı sınıfları kullanarak ilgili özellikleri atayın [İşaret isteği](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [Finans Kurumu](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution), [StatementTransactionRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest)1. Sırasıyla xml ve sgml dosyaları için ofxVersion V2x veya V1x kullanın [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) Kaydet yönteminde parametre olarak.1. Ara [Kaydet yöntemi](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument/methods/save) Hedef dosya ve ofxVersion sağlayarak.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yaratma Gereksinimi" %}}
OFX Dosyanın oluşturulmasına devam etmek için, .NET Finance API, rapor oluşturma uygulamasına dahil edilmesi gereken ana gerekliliktir. 
- Komut satırı aracılığıyla ''nuget install Aspose.Finance'' olarak veya ''Install-Package Aspose.Finance'' ile Visual Studio Paket Yöneticisi Konsolu aracılığıyla yükleyin.
- Alternatif olarak, bir ZIP dosyasında çevrimdışı MSI yükleyicisini veya DLL'leri alın [Indirmeler](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="OFX istek dosyası oluşturma için C# kodu" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-request-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Diğer Oluşturma Seçenekleri" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX Yanıt Dosyası" description="1.03 veya 2.2 Formatı" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL Dosya" description="Genişletilebilir İş Raporlama Dili" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
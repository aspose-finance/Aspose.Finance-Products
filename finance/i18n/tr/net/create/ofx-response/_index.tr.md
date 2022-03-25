---
title: C# aracılığıyla OFX Yanıt Dosyası Oluştur
description: OFX yanıt dosyası oluşturma için örnek kod. .NET tabanlı uygulamalarda toplu OFX yanıt dosyaları oluşturmak için API örnek kodu kullanın. 
url: /tr/net/create/ofx-response/
family: finance
platformtag: net
feature: create
informat: OFX Response
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# aracılığıyla OFX Yanıt Dosyaları Oluştur" h2="OFX Microsoft Office yüklü veya başka bir yazılıma ihtiyaç duymadan yanıt dosyaları oluşturma." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="OFX Yanıt Dosyaları Nasıl Oluşturulur" %}}

Kod snippet'teki adımları izleyin veya uygulamanızda oluşturma gereksinimlerini karşıladıktan sonra uygulama ihtiyaçlarınız doğrultusunda geliştirin.

1. Oluştur [OfxResponseDocument sınıfı](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) Nesne.1. API gibi tarafından sağlanan farklı sınıfları kullanarak ilgili özellikleri atayın [SignonResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [Bildiri TransactionResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse), [Statementİşlem](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction)1. Sırasıyla xml ve sgml dosyaları için ofxVersion V2x veya V1x kullanın [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) Kaydet yönteminde parametre olarak.1. Ara [Kaydet yöntemi](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument/methods/save) Hedef dosya ve ofxVersion sağlayarak.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yaratma Gereksinimi" %}}
OFX Yanıt dosyası oluşturmaya devam etmek için, .NET Finance API, rapor oluşturma uygulamasına dahil edilmesi gereken ana gerekliliktir. 
- Komut satırı aracılığıyla ''nuget install Aspose.Finance'' olarak veya ''Install-Package Aspose.Finance'' ile Visual Studio Paket Yöneticisi Konsolu aracılığıyla yükleyin.
- Alternatif olarak, bir ZIP dosyasında çevrimdışı MSI yükleyicisini veya DLL'leri alın [Indirmeler](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="OFX yanıt dosyaları oluşturma için C# kodu" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Diğer Oluşturma Seçenekleri" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX Talep Dosyası" description="1.03 veya 2.2 Formatı" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL Dosya" description="Genişletilebilir İş Raporlama Dili" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
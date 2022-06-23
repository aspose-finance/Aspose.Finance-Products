---
title: Python aracılığıyla OFX Yanıt Dosyası oluşturun
description: OFX yanıt dosyası oluşturma için örnek kod. Python tabanlı uygulamalarda toplu OFX yanıt dosyalarının oluşturulması için API örnek kodunu kullanın. 
url: /tr/python-net/create/ofx-response/
family: finance
platformtag: python
feature: create
informat: OFX Response
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Python aracılığıyla OFX Yanıt Dosyası oluşturun" h2="OFX Microsoft Office yüklü veya başka bir yazılıma ihtiyaç duymadan yanıt dosyaları oluşturma." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="OFX Yanıt Dosyası Nasıl Oluşturulur" %}}

Kod parçacığındaki adımları izleyin veya oluşturma gereksinimlerini uygulamanız içinde yaptıktan sonra uygulama ihtiyaçlarınıza göre geliştirin.

1. OfxResponseDocument sınıf nesnesi oluşturun.1. SignonResponse, StatementTransactionResponse, StatementTransaction gibi API tarafından sağlanan farklı sınıfları kullanarak ilgili özellikleri atayın1. Kaydetme yönteminde parametre olarak OfxVersionEnum'dan sırasıyla xml ve sgml dosyaları için ofxVersion V2x veya V1x'i kullanın.1. Hedef dosyayı ve ofxVersion'ı sağlayarak kaydetme yöntemini çağırın.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Oluşturma Gereksinimi" %}}
OFX Yanıt dosyası oluşturmaya devam etmek için aşağıdaki ön koşullara sahip olduğunuzdan emin olun. 
- Microsoft Windows veya Linux tabanlı işletim sistemi.- Python 3.5 veya üzeri.- Projenizde referans verilen Python için Aspose.Finance.{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="OFX yanıt dosyalarının oluşturulması için Python kodu" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Diğer Oluşturma Seçenekleri" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-request/" name="OFX İstek Dosyası" description="1.03 veya 2.2 Biçimi" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/xbrl/" name="XBRL Dosya" description="Genişletilebilir İşletme Raporlama Dili" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
---
title: .NET aracılığıyla Mali Raporlar Oluşturun
url: /tr/net/create/
description:  XBRL içinde Mali Raporlar oluşturmak için C# kodu ve .NET kitaplığı aracılığıyla OFX istek veya yanıt dosyaları.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# aracılığıyla Finansal Raporlama Dosyaları Oluşturun" h2=".NET tabanlı uygulamalarda 1.03 veya 2.2 formatında XBRL ve OFX istek veya yanıt dosyasını içeren mali rapor formatları oluşturma." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) zengin özelliklere sahip, genişletilebilir ve kullanımı kolay bir mali rapor oluşturma ve işleme özelliğidir API. Geliştiriciler kolayca sıfırdan XBRL örneği oluşturabilir ve şema referansı, bağlam, birim, öğe, dipnot bağlantısı, rol referansı ve 
ark rolü referansı. API, geliştiricilerin kullanabileceği bağlam gibi her özellik için ilgili sınıf sağlar [BağlamPeriod](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextperiod), [BağlamVarlığı](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextentity) ve [Bağlam](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context). 
Ayrıca API, 1.03 veya 2.2 biçiminde açık finansal değişim (OFX) biçiminde istek / yanıt oluşturmayı da destekler.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Öğe Ekleyerek XBRL Dosyası Oluşturun" %}}

XBRL dosyası oluşturmak ve belgeye öğe eklemek için işlem şudur: [XbrlDocument sınıfı](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) misal. gibi uygun API sınıflarını kullanarak öğe için ilgili ayarları hazırlayın. [SchemaRef sınıfı](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemaref)yukarıda belirtildiği gibi ilgili bağlam sınıfları ve [konsept sınıfı](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/concept). Sonunda tanımla ve başlat [Öğe sınıfı](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/item) özelliklerini aramanın yanı sıra [Yöntemi kaydet](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) ile [XBRL oluştur](https://products.aspose.com/finance/net/create/xbrl/) diske dosya.

{{% blocks/products/pf/feature-page-code h3="Öğe Ekleyerek XBRL Dosyası Oluşturmak için C# Kodu" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-item.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="OFX İstek ve Yanıt Dosyası Oluşturun" %}}


OFX dosya oluşturmak için API şunları sağlar: [OfxRequestBelgesi](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) ve [OfxResponseBelgesi](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) sınıflar ve geliştiriciler kolayca [OFX İsteği oluştur](https://products.aspose.com/finance/net/create/ofx-request/) ve hem 1.03 hem de 2.2 biçimlerinde Yanıt dosyaları. OfxRequestDocument özelliklerini başlatmak için API, aşağıdakiler gibi başka sınıflar da sağlar: [SignonRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [Finansal kurum](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution) ve [AçıklamaİşlemTalebi](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest) sınıflar. Benzer şekilde, OfxResponseDocument özelliklerini başlatmak için API, aşağıdakiler gibi destekleyici sınıflar sağlar: [SignonResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [AçıklamaİşlemYanıt](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse) ve [Açıklamaİşlem](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction). Aşağıda, ilgili uygun sınıfların kullanımı ile her iki durum için kod parçacıkları bulunmaktadır.

{{% blocks/products/pf/feature-page-code h3="OFX Talep Belgesi Oluşturmak için C# Kodu" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="OFX Yanıt Belgesi Oluşturmak için C# Kodu" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< /blocks/products/pf/feature-page-wrap >}}
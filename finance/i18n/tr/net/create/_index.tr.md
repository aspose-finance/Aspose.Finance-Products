---
title: .NET aracılığıyla Finansal Raporlar Oluştur
url: /tr/net/create/
description:  XBRL 'de Finansal Raporlar oluşturmak için C# kodu ve OFX kitaplığı aracılığıyla OFX istek veya yanıt dosyaları.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# aracılığıyla Finansal Raporlama Dosyaları Oluşturun" h2=".NET tabanlı uygulamalarda 1.03 veya 2.2 formatında XBRL ve OFX istek veya yanıt dosyası dahil olmak üzere finansal rapor formatları oluşturma." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) Zengin, genişletilebilir ve kullanımı kolay bir finansal rapor oluşturma ve işleme API. Geliştiriciler sıfırdan XBRL örneğini kolayca oluşturmanın yanı sıra şema referansı, bağlam, birim, öğe, dipnot bağlantısı, rol referansı ve 
Ark rol referansı. API, geliştiricilerin kullanabileceği bağlam gibi her özellik için ilgili sınıf sağlar [Bağlam Dönemi](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextperiod), [Bağlam Varlığı](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextentity) Ve [Bağlam](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context). 
Ayrıca, API ayrıca 1.03 veya 2.2 formatında açık finansal değişim (OFX) formatı istek/yanıt oluşturmayı da destekler.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Öğe Ekleyerek XBRL Dosya Oluştur" %}}

XBRL dosyası oluşturmak ve belgeye öğe eklemek için, işlem, [XbrlDocument sınıfı](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Örnek. Uygun API sınıfları kullanarak öğe için ilgili ayarları hazırlayın [Şema sınıfı](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemaref), Yukarıda belirtildiği gibi ilgili bağlam sınıfları ve [Konsept sınıfı](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/concept). Sonunda tanımlayın ve aşılayın [Öğe sınıfı](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/item) Özellikleri yanı sıra çağrı [Kaydet yöntemi](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) Için [XBRL oluştur](https://products.aspose.com/finance/net/create/xbrl/) Dosya diske.

{{% blocks/products/pf/feature-page-code h3="C# Öğe Ekleyerek XBRL Dosya Oluşturmak için Kod" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-item.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="OFX İstek ve Yanıt Dosyaları Oluştur" %}}


OFX dosyaları oluşturmak için API sağlar [OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) Ve [OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) Sınıflar ve geliştiriciler kolayca [OFX oluştur](https://products.aspose.com/finance/net/create/ofx-request/) Ve 1.03 ve 2.2 formatlarında Yanıt dosyaları. OfxRequestDocument özelliklerini başlatmak için, API gibi diğer sınıfları da sağlar [İşaret isteği](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [Finans Kurumu](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution) Ve [StatementTransactionRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest) Dersler. Benzer şekilde, OfxResponseDocument özelliklerini aşılamak için, API gibi destekleyici sınıflar sağlar [SignonResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [Bildiri TransactionResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse) Ve [Statementİşlem](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction). Aşağıda, ilgili uygun sınıfların kullanımıyla her iki durum için kod parçacıkları bulunmaktadır.

{{% blocks/products/pf/feature-page-code h3="C# Oluşturmak için Kod OFX Belge Talep Edin" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# OFX Yanıt Belgeleri Oluşturmak için Kod" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
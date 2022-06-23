---
title: Python aracılığıyla Mali Raporlar Oluşturun
url: /tr/python-net/create/
description:  XBRL içinde Mali Raporlar oluşturmak için Python kodu ve Python kitaplığı aracılığıyla OFX istek veya yanıt dosyaları.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Python aracılığıyla Finansal Raporlama Dosyaları Oluşturun" h2="Python tabanlı uygulamalarda 1.03 veya 2.2 formatında XBRL ve OFX istek veya yanıt dosyasını içeren mali rapor formatları oluşturma." >}}

{{% blocks/products/pf/feature-page-summary %}}

[.NET üzerinden Python için Aspose.Finance](https://products.aspose.com/finance/python-net/) zengin özelliklere sahip, genişletilebilir ve kullanımı kolay bir mali rapor oluşturma ve işleme özelliğidir API. Geliştiriciler kolayca sıfırdan XBRL örneği oluşturabilir ve şema referansı, bağlam, birim, öğe, dipnot bağlantısı, rol referansı ve 
ark rolü referansı. API, bağlam gibi her özellik için ilgili sınıf sağlar; geliştiriciler ContextPeriod, ContextEntity ve Context'i kullanabilir. 
Ayrıca API, 1.03 veya 2.2 biçiminde açık finansal değişim (OFX) biçiminde istek / yanıt oluşturmayı da destekler.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Öğe Ekleyerek XBRL Dosyası Oluşturun" %}}

XBRL dosyası oluşturmak ve belgeye öğe eklemek için işlem, XbrlDocument sınıfı örneği oluşturmaktır. SchemaRef sınıfı, yukarıda belirtilen ilgili bağlam sınıfları ve Concept sınıfı gibi uygun API sınıflarını kullanarak öğe için ilgili ayarları hazırlayın. Son olarak, Item sınıfı özelliklerini tanımlayın ve başlatın, ayrıca diske XBRL dosyası oluşturmak için kaydetme yöntemini çağırın.

{{% blocks/products/pf/feature-page-code h3="Öğe Ekleyerek XBRL Dosyası Oluşturmak için Python Kodu" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-xbrl-file-and-add-item.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="OFX İstek ve Yanıt Dosyası Oluşturun" %}}


OFX dosyaları oluşturmak için API, OfxRequestDocument ve OfxResponseDocument sınıfları sağlar ve geliştiriciler [OFX İsteği oluştur](https://products.aspose.com/finance/python-net/create/ofx-request/) ve hem 1.03 hem de 2.2 biçimlerinde Yanıt dosyaları. OfxRequestDocument özelliklerini başlatmak için API ayrıca SignonRequest, FinancialInstitution ve StatementTransactionRequest sınıfları gibi başka sınıflar da sağlar. Benzer şekilde, OfxResponseDocument özelliklerini başlatmak için API, SignonResponse, StatementTransactionResponse ve StatementTransaction gibi destekleyici sınıflar sağlar. Aşağıda, ilgili uygun sınıfların kullanımı ile her iki durum için kod parçacıkları bulunmaktadır.

{{% blocks/products/pf/feature-page-code h3="OFX Talep Belgesi Oluşturmak için Python Kodu" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="OFX Yanıt Belgesi Oluşturmak için Python Kodu" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
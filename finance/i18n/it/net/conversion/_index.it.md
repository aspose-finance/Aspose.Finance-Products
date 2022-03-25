---
title: Convertire rapporti finanziari tramite .NET
url: /it/net/conversion/
description:  C# codice per convertire i rapporti finanziari in XBRL, iXBRL e OFX file fomat tramite .NET libreria.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convertire file di report finanziari tramite C#" h2="Conversione dei formati di report finanziari, inclusi file XBRL, iXBRL e OFX dal formato 1.03 al formato 2.2 all\'interno di applicazioni basate su .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) È una funzionalità ricca, estensibile e facile da usare API. Gli sviluppatori possono convalidare facilmente XBRL istanze, linkbase e schemi di tassonomia utilizzando [Validare () metodo](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) Che devono essere conformi ai requisiti di sintassi imposti nelle specifiche. Inoltre, possono leggere XBRL, iXBRL formati e creare XBRL istanza da zero. Inoltre, possono ** convertire XBRL formato ** in iXBRL e file XLSX di Microsoft Excel. API supporta anche la creazione di richieste/risposte in formato open financial exchange (OFX) e converte OFX file di richiesta/risposta dal formato 1.03 al formato 2.2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Convertire OFX Risposta e Richiedi file" %}}

API supporta la creazione di OFX file di richiesta e risposta fornendo due classi. [OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) Per la creazione e il caricamento di OFX file di richiesta in formato 1.03 e 2.2 e [OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) Per OFX file di risposta in formato 1.03 e 2.2. Inoltre, [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) Enumerazione con membri V1x che è la versione 1.x, il formato di file sgml e la versione V2x 2.x, il formato di file xml. Dopo aver chiamato il metodo Save della classe OfxRequestDocument o della classe OfxResponseDocument, gli sviluppatori possono convertire facilmente da un file sg03 a un formato da 2,2 xml.


{{% blocks/products/pf/feature-page-code h3="C# codice per convertire OFX file di risposta" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-response-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# codice per convertire OFX file di richiesta" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-request-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL conversione dei rapporti finanziari" %}}

API supporta la conversione di XBRL file in iXBRL e Microsoft®Formato Excel XLSX. Il processo di conversione è semplice, in primo luogo caricare il file tramite [Classe XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument). Usa il [Classe SaveOptions](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions) Per [Formato di salvataggio](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions/properties/saveformat), Da utilizzare come parametro nel metodo di salvataggio della classe XbrlDocument. Per il salvataggio nel file iXBLR, [SaveFormat.IXBRL](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveformat) Verrà utilizzato e per l'esportazione in formato XLSX, verrà utilizzato SaveFormat.XLSX.

{{% blocks/products/pf/feature-page-code h3="C# codice per esportare XBRL in iXBRL" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-ixbrl.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# codice per XBRL alla conversione XLSX" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-xlsx.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}
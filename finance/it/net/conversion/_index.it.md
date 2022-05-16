---
title: Converti rapporti finanziari tramite .NET
url: /it/net/conversion/
description:  C# codice per convertire i rapporti finanziari nei formati di file XBRL, iXBRL(inline xbrl) e OFX tramite la libreria .NET.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Converti file di report finanziari tramite C#" h2="Conversione dei formati di report finanziari inclusi i file XBRL, iXBRL e OFX dal formato 1.03 al 2.2 all\'interno di applicazioni basate su .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) è una funzionalità ricca, estensibile e facile da usare API. Gli sviluppatori possono facilmente convalidare XBRL istanze, linkbase e schemi di tassonomia utilizzando [validate()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) che deve essere conforme ai requisiti di sintassi imposti nella specifica. Inoltre, possono leggere i formati XBRL, iXBRL e creare un'istanza XBRL da zero. Inoltre, possono **convertire il formato XBRL** in iXBRL e file XLSX di Microsoft Excel. API supporta anche la creazione di richieste/risposte in formato Open Financial Exchange (OFX) e converte OFX richieste/risposte di file dal formato 1.03 al 2.2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Converti OFX file di risposta e richiesta" %}}

API supporta la creazione di OFX file di richiesta e risposta fornendo due classi. [Documento di richiesta Ofx](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) per creare e caricare OFX file di richiesta in formato 1.03 e 2.2 e [OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) per OFX file di risposta in formato 1.03 e 2.2. Inoltre, [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) Enumerazione con membri V1x che è versione 1.x, formato file sgml e versione V2x 2.x, formato file xml. Dopo aver chiamato il metodo Save della classe OfxRequestDocument o della classe OfxResponseDocument, gli sviluppatori possono convertire facilmente dal file sgml 1.03 al formato 2.2 xml.


{{% blocks/products/pf/feature-page-code h3="C# Codice per convertire OFX file di risposta" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-response-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Codice per convertire OFX file di richiesta" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-request-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL Conversione dei rapporti finanziari" %}}

API supporta la conversione di XBRL file in formato iXBRL e Microsoft® Excel XLSX. Il processo di conversione è semplice, innanzitutto carica il file tramite [Classe XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument). Usa il [Classe SaveOptions](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions) per [Salva formato](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions/properties/saveformat), da utilizzare come parametro nel metodo Save della classe XbrlDocument. Per salvare nel file iXBLR, [SalvaFormat.IXBRL](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveformat) verrà utilizzato e per l'esportazione in formato XLSX verrà utilizzato SaveFormat.XLSX.

{{% blocks/products/pf/feature-page-code h3="C# Codice da esportare da XBRL a iXBRL" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-ixbrl.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C#Codice per la conversione da XBRL a XLSX" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-xlsx.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}
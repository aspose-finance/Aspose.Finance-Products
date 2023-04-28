---
title: Converti rapporti finanziari tramite Python
url: /it/python-net/conversion/
description:  Python codice per convertire i rapporti finanziari nei formati di file XBRL, iXBRL(inline xbrl) e OFX tramite la libreria Python.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Converti file di report finanziari tramite Python" h2="Conversione dei formati di report finanziari inclusi i file XBRL, iXBRL e OFX dal formato 1.03 al 2.2 all\'interno di applicazioni basate su Python." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance per Python tramite .NET](https://products.aspose.com/finance/python-net/) è una funzionalità ricca, estensibile e facile da usare API. Gli sviluppatori possono facilmente convalidare XBRL istanze, linkbase e schemi di tassonomia utilizzando il metodo validate() che deve essere conforme ai requisiti di sintassi imposti nelle specifiche. Inoltre, possono leggere i formati XBRL, iXBRL e creare un'istanza XBRL da zero. Inoltre, possono **convertire il formato XBRL** in iXBRL e file XLSX di Microsoft Excel. API supporta anche la creazione di richieste/risposte in formato Open Financial Exchange (OFX) e converte OFX richieste/risposte di file dal formato 1.03 al 2.2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Converti OFX file di risposta e richiesta" %}}

API supporta la creazione di OFX file di richiesta e risposta fornendo due classi. OfxRequestDocument per la creazione e il caricamento di OFX file di richiesta in formato 1.03 e 2.2 e OfxResponseDocument per OFX file di risposta in formato 1.03 e 2.2. Inoltre, l'enumerazione OfxVersionEnum con membri V1x ovvero versione 1.x, formato file sgml e versione V2x 2.x, formato file xml. Dopo aver chiamato il metodo di salvataggio della classe OfxRequestDocument o della classe OfxResponseDocument, gli sviluppatori possono convertire facilmente dal file sgml 1.03 al formato 2.2 xml.


{{% blocks/products/pf/feature-page-code h3="C# Codice per convertire OFX file di risposta" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-ofx-response-from-1.03-to-2.2.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Codice per convertire OFX file di richiesta" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-ofx-request-from-1.03-to-2.2.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL Conversione dei rapporti finanziari" %}}

API supporta la conversione di XBRL file in formato iXBRL e Microsoft® Excel XLSX. Il processo di conversione è semplice, innanzitutto carica il file tramite la classe XbrlDocument. Utilizzare la classe SaveOptions per SaveFormat, da utilizzare come parametro nel metodo di salvataggio della classe XbrlDocument. Per il salvataggio nel file iXBLR verrà utilizzato SaveFormat.IXBRL e per l'esportazione in formato XLSX verrà utilizzato SaveFormat.XLSX.

{{% blocks/products/pf/feature-page-code h3="Python Codice da esportare da XBRL a iXBRL" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-xbrl-to-ixbrl.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="PythonCodice per la conversione da XBRL a XLSX" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-xbrl-to-xlsx.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}
{{< /blocks/products/pf/feature-page-wrap >}}
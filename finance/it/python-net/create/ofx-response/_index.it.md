---
title: Crea OFX file di risposta tramite Python
description: Codice di esempio per la creazione del file di risposta OFX. Utilizza API codice di esempio per la generazione di file di risposta in batch OFX all'interno di applicazioni basate su Python. 
url: /it/python-net/create/ofx-response/
family: finance
platformtag: python
feature: create
informat: OFX Response
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Crea OFX file di risposta tramite Python" h2="OFX creazione di file di risposta senza la necessità di installare Microsoft Office o qualsiasi altro software." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Come creare OFX file di risposta" %}}

Segui i passaggi nello snippet di codice o miglioralo in base alle esigenze dell'applicazione dopo aver soddisfatto i requisiti di creazione all'interno dell'applicazione.

1. Crea un oggetto classe OfxResponseDocument.1. Assegna le proprietà pertinenti utilizzando diverse classi fornite da API come SignonResponse, StatementTransactionResponse, StatementTransaction1. Utilizzare ofxVersion V2x o V1x rispettivamente per i file xml e sgml da OfxVersionEnum come parametro nel metodo di salvataggio.1. Chiama il metodo save fornendo il file di destinazione e ofxVersion.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisito di creazione" %}}
Per procedere con la OFXcreazione del file di risposta, assicurati di disporre dei seguenti prerequisiti. 
- Sistema operativo basato su Microsoft Windows o Linux.- Python 3.5 o successivo.- Aspose.Finance per Python a cui si fa riferimento nel tuo progetto.{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python codice per OFX creazione di file di risposta" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Altre opzioni di creazione" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-request/" name="OFX File di richiesta" description="Formato 1.03 o 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/xbrl/" name="XBRL File" description="Linguaggio di reporting aziendale estensibile" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
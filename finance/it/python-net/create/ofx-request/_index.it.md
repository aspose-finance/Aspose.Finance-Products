---
title: Crea OFX file di richiesta tramite Python
description: Codice di esempio per OFX la creazione del file di richiesta. Utilizza API codice di esempio per la generazione di file di richiesta batch OFX all'interno di applicazioni basate su Python. 
url: /it/python-net/create/ofx-request/
family: finance
platformtag: python
feature: create
informat: OFX Request
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Crea OFX file di richiesta tramite Python" h2="OFX richiedere la creazione di file senza che sia necessario installare Microsoft Office o qualsiasi altro software." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Come creare OFX file di richiesta" %}}

Dopo aver soddisfatto i OFXrequisiti per la creazione di file di richiesta all'interno della tua applicazione, segui i passaggi nello snippet di codice o miglioralo in base alle tue esigenze.

1. Crea un oggetto classe OfxRequestDocument.2. Assegna le proprietà rilevanti utilizzando diverse classi fornite da API come SignonRequest, FinancialInstitution], StatementTransactionRequest
3. Utilizzare ofxVersion V2x o V1x rispettivamente per i file xml e sgml da OfxVersionEnum come parametro nel metodo Save.
4. Chiamare il metodo save fornendo il file di destinazione e ofxVersion.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisito di creazione" %}}
Per procedere con la OFXcreazione del file di richiesta, assicurati di disporre dei seguenti prerequisiti. 
- Sistema operativo basato su Microsoft Windows o Linux.- Python 3.5 o successivo.- Aspose.Finance per Python a cui si fa riferimento nel tuo progetto.{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python codice per OFX creazione di file di richiesta" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-request-files.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Altre opzioni di creazione" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-response/" name="OFX File di risposta" description="Formato 1.03 o 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/xbrl/" name="XBRL File" description="Linguaggio di reporting aziendale estensibile" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
---
title: Convalida file XBRL tramite C#
description: Codice di esempio per la convalida del file XBRL. Usa API codice di esempio per convalidare i file batch XBRL all'interno di applicazioni basate su .NET. 
url: /it/net/validate/xbrl/
family: finance
platformtag: net
feature: validate
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convalida XBRL file tramite C#" h2="Convalida dei rapporti finanziari in formato XBRL senza la necessità di installare Microsoft Office o qualsiasi altro software." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Come convalidare XBRL file" %}}

Segui i passaggi nello snippet di codice o miglioralo in base alle esigenze della tua applicazione per la convalida di documenti del linguaggio di reporting aziendale estensibile XBRL. Assicurati di avere requisiti di convalida all'interno della tua applicazione.

1. Carica XBRL file utilizzando [Classe XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Esempio.1. Per verificare la validità del file caricato, in modo che debba corrispondere a [XBRL specifica](http://www.xbrl.org/specification/inlinexbrl-part1/rec-2013-11-18/inlinexbrl-part1-rec-2013-11-18.html)1. Per verificare la validità, utilizzare [Convalidare()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) metodo di [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) classe.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisito di convalida" %}}
Per procedere alla convalida di XBRL documenti, .NET Finance API è il requisito principale da includere nella domanda. 
- Installalo tramite riga di comando come ```nuget install Aspose.Finance``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Finance```.
- In alternativa, ottenere il programma di installazione MSI offline o le DLL in un file ZIP da [download](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# codice per convalidare XBRL file" offSpacer="" %}}

{{< gist "aspose-com-gists" "1272da1f804f8cef122600269db09fbb" "validate-xbrl-instance-file.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Altre opzioni di convalida" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/validate/ixbrl/" name="XBRL" description="Linguaggio di reporting aziendale estensibile in linea" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
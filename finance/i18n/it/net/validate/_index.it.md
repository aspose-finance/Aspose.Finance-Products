---
title: Convalidare i rapporti finanziari tramite .NET
url: /it/net/validate/
description:  C# codice per convalidare i rapporti finanziari nei file XBRL e iXBRL tramite .NET libreria.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convalidare i file di reporting finanziario tramite C#" h2="Convalida dei formati di report finanziari inclusi XBRL e iXBRL entro .NET applicazioni basate." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) È una funzionalità ricca, estensibile e facile da usare elaborazione del rapporto finanziario API. Gli sviluppatori possono facilmente caricare, convalidare, visualizzare o creare formati XBRL e iXBRL per soluzioni finanziarie e aziendali. API fornisce [XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Classe e  [Documento InlineXbrl](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) Classe per il caricamento di file XBRL e iXBRL.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Convalidare XBRL documento" %}}

La convalida del file XBRL è necessaria per una serie di casi, ad esempio per verificare che i dati siano nella giusta struttura e formato. Per convalidare i documenti XBLR, utilizzare in primo luogo la classe XbrlDocument per caricare il file XBRL. Per utilizzare il [Convalidare ()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) Metodo di [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) Classe, in primo luogo inzializzare il [Collezione XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) Con oggetto XbrlDocument XbrlInstances. Iterare attraverso ciascuno [XbrlInstance. ValidazioneErrori](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/properties/validationerrors) Per ottenere il codice di errore corretto e agire di conseguenza stampando i messaggi di errore personalizzati sulla console o scrivendo all'interno di un file.

{{% blocks/products/pf/feature-page-code h3="C# Codice da convalidare XBRL File" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-xbrl-file.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Convalidare iXBRL documento" %}}

Per la convalida iXLRB, caricarlo tramite [Documento InlineXbrl](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) Classe e utilizzare il suo metodo Validate(). In [ValidationErrorCode](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.validator/validationerrorcode) Enumerazione, i codici di errore di convalida sono definiti per ogni regola di convalida. Pochi codici sono ContextPeriodNoStartTime, ContextPeriodNoEndTime, ContextPeriodStartAfterEnd, ContextInstantNoTime, ContextScenarioXbrlNamespace, ContextScenarioXbrlSubstitutionGroup ecc. Gli sviluppatori possono eseguire il debug e visualizzare i codici degli utenti finali o possono mostrare la direzione per la risoluzione del problema.

{{% blocks/products/pf/feature-page-code h3="C# Codice per la convalida del documento iXBRL" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-ixbrl-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}
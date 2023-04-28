---
title: Convalida i rapporti finanziari tramite .NET
url: /it/net/validate/
description:  C# codice per convalidare i rapporti finanziari nei file XBRL e iXBRL tramite la libreria .NET.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convalida i file di rendicontazione finanziaria tramite C#" h2="Convalida dei formati di report finanziari inclusi XBRL e iXBRL all\'interno di applicazioni basate su .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) è un'elaborazione di report finanziari API ricca di funzionalità, estensibile e facile da usare. Gli sviluppatori possono facilmente caricare, convalidare, visualizzare o creare formati XBRL e iXBRL per soluzioni finanziarie e aziendali. API fornisce [XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) classe e  [InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) classe per caricare i file XBRL e iXBRL.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Convalida XBRL documento" %}}

La convalida del file XBRL è necessaria per una serie di casi, ad esempio per verificare che i dati siano nella struttura e nel formato corretti. Per convalidare i documenti XBLR, utilizza innanzitutto la classe XbrlDocument per caricare il file XBRL. Per usare il [convalidare()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) metodo di [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) classe, in primo luogo inizializzare il [XbrlInstanceCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) con XbrlDocument oggetto XbrlInstances. Iterare attraverso ciascuno [XbrlInstance.ValidationErrors](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/properties/validationerrors) per ottenere il codice di errore corretto e agire di conseguenza stampando i messaggi di errore personalizzati su console o scrivendo all'interno di un file.

{{% blocks/products/pf/feature-page-code h3="C# Codice per convalidare il file XBRL" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-xbrl-file.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Convalida iXBRL documento" %}}

Per la convalida iXLRB, caricalo tramite [InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) class e usa il suo metodo Validate(). In [ValidationErrorCode](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.validator/validationerrorcode) enumerazione, i codici di errore di convalida sono definiti per ciascuna regola di convalida. Alcuni codici sono ContextPeriodNoStartTime, ContextPeriodNoEndTime, ContextPeriodStartAfterEnd, ContextInstantNoTime, ContextScenarioXbrlNamespace, ContextScenarioXbrlSubstitutionGroup ecc. Gli sviluppatori possono eseguire il debug e visualizzare i codici degli utenti finali o possono mostrare la direzione per risolvere il problema.

{{% blocks/products/pf/feature-page-code h3="C# Codice per convalidare iXBRL documento" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-ixbrl-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}
{{< /blocks/products/pf/feature-page-wrap >}}
---
title: Convalida i rapporti finanziari tramite Python
url: /it/python-net/validate/
description:  Python codice per convalidare i rapporti finanziari nei file XBRL e iXBRL tramite la libreria Python.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convalida i file di rendicontazione finanziaria tramite Python" h2="Convalida dei formati di report finanziari inclusi XBRL e iXBRL all\'interno di applicazioni basate su Python." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance per Python tramite .NET](https://products.aspose.com/finance/python-net/) è un'elaborazione di report finanziari API ricca di funzionalità, estensibile e facile da usare. Gli sviluppatori possono facilmente caricare, convalidare, visualizzare o creare formati XBRL e iXBRL per soluzioni finanziarie e aziendali. API fornisce la classe XbrlDocument e la classe InlineXbrlDocument per caricare i file XBRL e iXBRL.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Convalida XBRL documento" %}}

La convalida del file XBRL è necessaria per una serie di casi, ad esempio per verificare che i dati siano nella struttura e nel formato corretti. Per convalidare i documenti XBLR, utilizza innanzitutto la classe XbrlDocument per caricare il file XBRL. Per utilizzare il metodo di convalida della classe XbrlInstance, inizializzare innanzitutto XbrlInstanceCollection con l'oggetto XbrlDocument XbrlInstances. Scorri ogni XbrlInstance.ValidationErrors per ottenere il codice di errore corretto e agire di conseguenza stampando i messaggi di errore personalizzati sulla console o scrivendo all'interno di un file.

{{% blocks/products/pf/feature-page-code h3="Python Codice per convalidare il file XBRL" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "validate-xbrl-instance-file.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Convalida iXBRL documento" %}}

Per la convalida iXLRB, caricalo tramite la classe InlineXbrlDocument e usa il suo metodo validate(). Nell'enumerazione ValidationErrorCode, i codici di errore di convalida sono definiti per ogni regola di convalida. Alcuni codici sono ContextPeriodNoStartTime, ContextPeriodNoEndTime, ContextPeriodStartAfterEnd, ContextInstantNoTime, ContextScenarioXbrlNamespace, ContextScenarioXbrlSubstitutionGroup ecc. Gli sviluppatori possono eseguire il debug e visualizzare i codici degli utenti finali o possono mostrare la direzione per risolvere il problema.

{{% blocks/products/pf/feature-page-code h3="Python Codice per convalidare iXBRL documento" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "validate-ixbrl-file.py" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}
{{< /blocks/products/pf/feature-page-wrap >}}
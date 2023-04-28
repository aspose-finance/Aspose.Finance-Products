---
title: Ověřit finanční přehledy prostřednictvím Python
url: /cs/python-net/validate/
description:  Python kód pro ověření finančních přehledů v souborech XBRL a iXBRL prostřednictvím knihovny Python.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Ověřit soubory finančního výkaznictví prostřednictvím Python" h2="Ověřování formátů finančních zpráv včetně XBRL a iXBRL v aplikacích založených na Python." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance za Python prostřednictvím .NET](https://products.aspose.com/finance/python-net/) je funkčně bohatý, rozšiřitelný a snadno použitelný zpracování finančních výkazů API. Vývojáři mohou snadno načítat, ověřovat, zobrazovat nebo vytvářet formáty XBRL a iXBRL pro finanční a obchodní řešení. API poskytuje třídy XbrlDocument a InlineXbrlDocument pro načítání souborů XBRL a iXBRL.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Ověřit dokument XBRL" %}}

Ověření souboru XBRL je potřeba pro řadu případů, jako je kontrola, zda jsou data ve správné struktuře a formátu. Chcete-li ověřit dokumenty XBLR, nejprve použijte třídu XbrlDocument k načtení souboru XBRL. Chcete-li použít metodu validate třídy XbrlInstance, nejprve inicializujte XbrlInstanceCollection pomocí objektu XbrlDocument XbrlInstances. Iterujte každou XbrlInstance.ValidationErrors, abyste získali správný chybový kód, a podle toho jednejte vytištěním přizpůsobených chybových zpráv na konzole nebo zápisem do souboru.

{{% blocks/products/pf/feature-page-code h3="Python Kód pro ověření souboru XBRL" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "validate-xbrl-instance-file.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Ověřit dokument iXBRL" %}}

Pro ověření iXLRB jej načtěte prostřednictvím třídy InlineXbrlDocument a použijte její metodu validate(). Ve výčtu ValidationErrorCode jsou pro každé ověřovací pravidlo definovány kódy chyb ověření. Několik kódů je ContextPeriodNoStartTime, ContextPeriodNoEndTime, ContextPeriodStartAfterEnd, ContextInstantNoTime, ContextScenarioXbrlNamespace, ContextScenarioXbrlSubstitutionGroup atd. Vývojáři mohou ladit a zobrazovat kódy jako koncoví uživatelé nebo mohou ukázat směr řešení problému.

{{% blocks/products/pf/feature-page-code h3="Python Kód pro ověření dokumentu iXBRL" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "validate-ixbrl-file.py" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}
{{< /blocks/products/pf/feature-page-wrap >}}
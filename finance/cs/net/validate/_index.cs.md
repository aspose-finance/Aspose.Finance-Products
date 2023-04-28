---
title: Ověřit finanční přehledy prostřednictvím .NET
url: /cs/net/validate/
description:  C# kód pro ověření finančních přehledů v souborech XBRL a iXBRL prostřednictvím knihovny .NET.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Ověřit soubory finančního výkaznictví prostřednictvím C#" h2="Ověřování formátů finančních zpráv včetně XBRL a iXBRL v aplikacích založených na .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) je funkčně bohatý, rozšiřitelný a snadno použitelný zpracování finančních výkazů API. Vývojáři mohou snadno načítat, ověřovat, zobrazovat nebo vytvářet formáty XBRL a iXBRL pro finanční a obchodní řešení. API poskytuje [XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) třída a  [InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) třída pro načítání souborů XBRL a iXBRL.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Ověřit dokument XBRL" %}}

Ověření souboru XBRL je potřeba pro řadu případů, jako je kontrola, zda jsou data ve správné struktuře a formátu. Chcete-li ověřit dokumenty XBLR, nejprve použijte třídu XbrlDocument k načtení souboru XBRL. Chcete-li použít [ověřit()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) metoda [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) třídu, nejprve inicializovat [XbrlInstanceCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) s objektem XbrlDocument XbrlInstances. Projděte každou z nich [XbrlInstance.ValidationErrors](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/properties/validationerrors) získat správný chybový kód a podle toho jednat tiskem přizpůsobených chybových zpráv na konzole nebo zápisem do souboru.

{{% blocks/products/pf/feature-page-code h3="C# Kód pro ověření souboru XBRL" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-xbrl-file.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Ověřit dokument iXBRL" %}}

Pro ověření iXLRB jej načtěte přes [InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) třídy a použijte její metodu Validate(). v [ValidationErrorCode](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.validator/validationerrorcode) při výčtu jsou pro každé ověřovací pravidlo definovány kódy chyb ověření. Několik kódů je ContextPeriodNoStartTime, ContextPeriodNoEndTime, ContextPeriodStartAfterEnd, ContextInstantNoTime, ContextScenarioXbrlNamespace, ContextScenarioXbrlSubstitutionGroup atd. Vývojáři mohou ladit a zobrazovat kódy jako koncoví uživatelé nebo mohou ukázat směr řešení problému.

{{% blocks/products/pf/feature-page-code h3="C# Kód pro ověření dokumentu iXBRL" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-ixbrl-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}
{{< /blocks/products/pf/feature-page-wrap >}}
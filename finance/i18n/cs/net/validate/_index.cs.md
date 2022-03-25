---
title: Ověřit finanční zprávy pomocí .NET
url: /cs/net/validate/
description:  C# kód pro ověření finančních zpráv v souborech XBRL a iXBRL prostřednictvím knihovny .NET.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Ověřit soubory účetního výkaznictví pomocí C#" h2="Ověření formátů finančních zpráv včetně XBRL a iXBRL v aplikacích založených na .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) Is a feature rich, extensible and easy to use financial report processing API. Vývojáři mohou snadno načíst, validovat, zobrazit nebo vytvořit formáty XBRL a iXBRL pro finanční a obchodní řešení. API poskytuje [Xbrldocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Třídy a  [Inlinexbrldokument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) Třída pro načtení souborů XBRL a iXBRL.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Ověřit dokument XBRL" %}}

Validace XBRL souboru je zapotřebí pro řadu případů, například pro kontrolu dat je ve správné struktuře a formátu. Chcete-li ověřit dokumenty xblr, nejprve použijte třídu xbrldocument pro načtení souboru XBRL. Pro použití [Validate ()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) Metoda [Xbrlinstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) Třída, nejprve intialize the [Xbrlinstancecollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) S objektem xbrldocument xbrlinstances. Iterate through each [Xbrlinstance. validationerrors](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/properties/validationerrors) Chcete-li získat správný chybový kód a jednat odpovídajícím způsobem vytisknutím vlastní chybové zprávy na konzoli nebo zápisu do souboru.

{{% blocks/products/pf/feature-page-code h3="C# kód pro ověření XBRL souboru" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-xbrl-file.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Ověřit dokument iXBRL" %}}

Pro validaci ixlrb, načíst přes [Inlinexbrldokument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) Class and use its validate () method. V [Validationerrorcode](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.validator/validationerrorcode) Pro každé pravidlo validace jsou definovány kódy chyb výčtu, validace. Málo kódů je contextperiodnostarttime, contextperiodnoendtime, contextperiodstartafterend, contextinstantnotime, contextscenarioxbrlnamespace, contextscenarioxbrlsubstitutiongroup etc. vývojáři mohou ladit a zobrazit kódy jako koncových uživatelů nebo mohou ukázat směr pro řešení problému.

{{% blocks/products/pf/feature-page-code h3="C# kód pro ověření dokumentu iXBRL" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-ixbrl-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}
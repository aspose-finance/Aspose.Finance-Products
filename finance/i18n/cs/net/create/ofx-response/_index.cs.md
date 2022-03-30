---
title: Vytvořit soubor odpovědí OFX prostřednictvím C#
description: Ukázkový kód pro vytvoření souboru odpovědí OFX. Použijte API ukázkový kód pro dávkové generování souborů odpovědí OFX v aplikacích založených na .NET. 
url: /cs/net/create/ofx-response/
family: finance
platformtag: net
feature: create
informat: OFX Response
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Vytvořit soubory odpovědí OFX prostřednictvím C#" h2="Vytvoření souborů odpovědí OFX bez nutnosti instalace sady Microsoft Office nebo jiného softwaru." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Jak vytvořit soubory odpovědí OFX" %}}

Postupujte podle kroků ve fragmentu kódu nebo jej vylepšete podle potřeb vaší aplikace poté, co jste v aplikaci měli požadavky na vytvoření.

1. Vytvořit [Třída OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) objekt.1. Přiřaďte relevantní vlastnosti pomocí různých tříd, které poskytuje API like [SignonResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [StatementTransactionResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse), [Výpis Transakce](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction)1. Pro soubory xml a sgml použijte ofxVersion V2x nebo V1x [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) jako parametr v metodě Uložit.1. Zavolej [Uložit metodu](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument/methods/save) poskytnutím cílového souboru a ofxVersion.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavek na vytvoření" %}}
Chcete-li pokračovat v OFXvytváření souboru odpovědí, .NET Finance API je hlavním požadavkem, který má být zahrnut do aplikace pro generování sestav. 
- Nainstalujte jej pomocí příkazového řádku jako ```nuget install Aspose.Finance``` nebo pomocí konzoly Správce balíčků sady Visual Studio s ```Install-Package Aspose.Finance```.
- Případně získejte offline instalační program MSI nebo knihovny DLL v souboru ZIP [stahování](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# kód pro vytvoření OFX souborů odpovědí" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Další možnosti tvorby" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX Soubor požadavku" description="Formát 1.03 nebo 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL Soubor" description="Rozšiřitelný jazyk pro obchodní výkaznictví" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
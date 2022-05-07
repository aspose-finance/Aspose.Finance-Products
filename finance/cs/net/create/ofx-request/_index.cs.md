---
title: Vytvořit soubor požadavku OFX prostřednictvím C#
description: Ukázkový kód pro vytvoření souboru požadavku OFX. Použijte API ukázkový kód pro dávkové generování souborů požadavků OFX v aplikacích založených na .NET. 
url: /cs/net/create/ofx-request/
family: finance
platformtag: net
feature: create
informat: OFX Request
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Vytvořit soubory požadavku OFX prostřednictvím C#" h2="OFX požaduje vytvoření souborů bez nutnosti instalace sady Microsoft Office nebo jiného softwaru." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Jak vytvořit soubory požadavku OFX" %}}

Po splnění požadavků na vytváření souborů OFX ve vaší aplikaci postupujte podle kroků ve fragmentu kódu nebo jej vylepšete podle svých požadavků.

1. Vytvořit [Třída OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) objekt.1. Přiřaďte relevantní vlastnosti pomocí různých tříd, které poskytuje API like [Žádost o přihlášení](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [Finanční instituce](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution), [StatementTransactionRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest)1. Pro soubory xml a sgml použijte ofxVersion V2x nebo V1x [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) jako parametr v metodě Uložit.1. Zavolej [Uložit metodu](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument/methods/save) poskytnutím cílového souboru a ofxVersion.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavek na vytvoření" %}}
Chcete-li pokračovat v OFXvytvoření souboru požadavku, .NET Finance API je hlavním požadavkem, který má být zahrnut do aplikace pro generování sestav. 
- Nainstalujte jej pomocí příkazového řádku jako ```nuget install Aspose.Finance``` nebo pomocí konzoly Správce balíčků sady Visual Studio s ```Install-Package Aspose.Finance```.
- Případně získejte offline instalační program MSI nebo knihovny DLL v souboru ZIP [stahování](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Kód C# pro vytvoření souborů požadavku OFX" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-request-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Další možnosti tvorby" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX Soubor odpovědí" description="Formát 1.03 nebo 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL Soubor" description="Rozšiřitelný jazyk pro obchodní výkaznictví" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
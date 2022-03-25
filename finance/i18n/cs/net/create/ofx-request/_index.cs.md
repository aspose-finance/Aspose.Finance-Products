---
title: Vytvořit soubor požadavku OFX prostřednictvím C#
description: Vzorový kód pro vytvoření souboru OFX požadavku. Použijte API příklad kódu pro vytváření souborů s požadavkem na dávku OFX v aplikacích založených na .NET. 
url: /cs/net/create/ofx-request/
family: finance
platformtag: net
feature: create
informat: OFX Request
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Vytvořit OFX soubory požadavku prostřednictvím C#" h2="OFX požadovat vytvoření souborů bez potřeby nainstalovaného microsoft office nebo jiného softwaru." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="How to create OFX request files" %}}

Po získání požadavků na vytváření souborů OFX v rámci vaší aplikace postupujte podle kroků v úryvu kódu nebo jej vylepšete podle vašich požadavků.

1. Vytvořit [Třída dokumentu ofxrequestdocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) Objekt.1. Přiřadit příslušné vlastnosti pomocí různých tříd poskytnutých API jako [Signonrequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [Finanční instituce](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution), [Vyžádání o transakci](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest)1. Použijte ofxversion v2x nebo v1x pro soubory xml a sgml od [Ofxversionenum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) As parameter in save method.1. Zavolejte [Uložit metodu](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument/methods/save) Poskytnutím cílového souboru a ofxversion.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavek vytvoření" %}}
.NET Finance API je hlavní požadavek, který je třeba zahrnout do aplikace generování sestav. 
- Nainstalujte ji na příkazovém řádku jako "nuget install Aspose.Finance" nebo přes konzolu správce balíků visual studio s "" install-package Aspose.Finance "".
- Alternativně získejte offline instalační program msi nebo dll v souboru zip z [Stahování](https://downloads.aspose.com/finance/net)A.{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# kód pro vytváření souborů požadavků OFX" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-request-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Další možnosti vytvoření" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX soubor odezvy" description="Formát 1.03 nebo 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL soubor" description="Extensible business reporting language" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
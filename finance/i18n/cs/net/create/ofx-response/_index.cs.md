---
title: Vytvořit soubor odezvy OFX prostřednictvím C#
description: Vzorový kód pro vytvoření souboru OFX response. Použít API příkladový kód pro generování souborů odezvy v dávce OFX v aplikacích založených na .NET. 
url: /cs/net/create/ofx-response/
family: finance
platformtag: net
feature: create
informat: OFX Response
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Vytvořit OFX soubory odezvy prostřednictvím C#" h2="OFX vytvoření souborů odezvy bez potřeby nainstalovaného microsoft office nebo jiného softwaru." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="How to create OFX response files" %}}

Postupujte podle kroků v úryvce kódu, nebo jej zdokonalte podle vašich potřeb aplikace poté, co máte požadavky na vytváření v rámci vaší aplikace.

1. Vytvořit [Třída ofxresponsedocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) Objekt.1. Přiřadit příslušné vlastnosti pomocí různých tříd poskytnutých API jako [Signonresponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [Prohlášení transakceresponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse), [Prohlášení transakce](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction)1. Použijte ofxversion v2x nebo v1x pro soubory xml a sgml od [Ofxversionenum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) As parameter in save method.1. Zavolejte [Uložit metodu](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument/methods/save) Poskytnutím cílového souboru a ofxversion.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavek vytvoření" %}}
Chcete-li pokračovat v vytváření souboru OFX response, .NET Finance API je hlavní požadavek, který je třeba zahrnout do aplikace generování sestav. 
- Nainstalujte ji na příkazovém řádku jako "nuget install Aspose.Finance" nebo přes konzolu správce balíků visual studio s "" install-package Aspose.Finance "".
- Alternativně získejte offline instalační program msi nebo dll v souboru zip z [Stahování](https://downloads.aspose.com/finance/net)A.{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# kód pro vytváření souborů odezvy OFX" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Další možnosti vytvoření" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX soubor požadavku" description="Formát 1.03 nebo 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL soubor" description="Extensible business reporting language" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
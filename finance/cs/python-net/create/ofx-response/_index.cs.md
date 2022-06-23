---
title: Vytvořit soubor odpovědí OFX prostřednictvím Python
description: Ukázkový kód pro vytvoření souboru odpovědí OFX. Použijte API ukázkový kód pro dávkové generování souborů odpovědí OFX v aplikacích založených na Python. 
url: /cs/python-net/create/ofx-response/
family: finance
platformtag: python
feature: create
informat: OFX Response
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Vytvořit soubory odpovědí OFX prostřednictvím Python" h2="Vytvoření souborů odpovědí OFX bez nutnosti instalace sady Microsoft Office nebo jiného softwaru." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Jak vytvořit soubory odpovědí OFX" %}}

Postupujte podle kroků ve fragmentu kódu nebo jej vylepšete podle potřeb vaší aplikace poté, co jste v aplikaci měli požadavky na vytvoření.

1. Vytvořte objekt třídy OfxResponseDocument.1. Přiřaďte relevantní vlastnosti pomocí různých tříd poskytovaných API, jako je SignonResponse, StatementTransactionResponse, StatementTransaction1. Použijte ofxVersion V2x nebo V1x pro soubory xml a sgml z OfxVersionEnum jako parametr v metodě ukládání.1. Zavolejte metodu uložení zadáním cílového souboru a ofxVersion.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavek na vytvoření" %}}
Chcete-li pokračovat ve vytváření souboru odpovědí OFX, ujistěte se, že splňujete následující předpoklady. 
- OS založený na Microsoft Windows nebo Linux.- Python 3.5 nebo novější.- Aspose.Finance pro Python odkazovaný ve vašem projektu.{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python kód pro vytvoření OFX souborů odpovědí" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Další možnosti tvorby" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-request/" name="OFX Soubor požadavku" description="Formát 1.03 nebo 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/xbrl/" name="XBRL Soubor" description="Rozšiřitelný jazyk pro obchodní výkaznictví" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
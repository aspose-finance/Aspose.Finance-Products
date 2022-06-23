---
title: Vytvořit soubor XBRL prostřednictvím Python
description: Ukázkový kód pro vytvoření souboru XBRL. Použijte API ukázkový kód pro dávkové generování XBRL souborů v aplikacích založených na Python. 
url: /cs/python-net/create/xbrl/
family: finance
platformtag: python
feature: create
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Vytvořit XBRL souborů prostřednictvím Python" h2="Vytvoření XBRL souborů bez nutnosti instalace sady Microsoft Office nebo jiného softwaru." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Jak vytvořit soubory XBRL" %}}

Postupujte podle kroků ve fragmentu kódu nebo jej vylepšete podle potřeb vaší aplikace pro generování rozšiřitelných souborů v jazyce obchodního reportingu XBRL. Ujistěte se, že máte ve své aplikaci požadavky na vytvoření.

1. Vytvořte instanci třídy XbrlDocument.1. Chcete-li vytvořit nový dokument instance XBRL XbrlInstanceCollection a XbrlInstance.1. Přidejte odkaz na schéma pomocí SchemaRefCollection1. V závislosti na povaze aplikace přidejte kontext, jednotku, položku, odkaz na poznámku pod čarou a další.1. Zavolejte metodu uložení zadáním cesty k cílovému souboru.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavek na vytvoření" %}}
Chcete-li pokračovat ve generování dokumentů XBRL, ujistěte se, že splňujete následující předpoklady. 
- OS založený na Microsoft Windows nebo Linux.- Python 3.5 nebo novější.- Aspose.Finance pro Python odkazovaný ve vašem projektu.{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python kód pro vytvoření XBRL souborů" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-xbrl-file-and-add-schema-reference.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Další možnosti tvorby" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-request/" name="Žádost OFX" description="Formát 1.03 nebo 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-response/" name="OFX Odpověď" description="Formát 1.03 nebo 2.2" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
---
title: Ověřit soubor XBRL prostřednictvím Python
description: Ukázkový kód pro ověření souboru XBRL. Použijte ukázkový kód API k ověření dávkových souborů XBRL v aplikacích založených na Python. 
url: /cs/python-net/validate/xbrl/
family: finance
platformtag: python
feature: validate
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Ověřit soubory XBRL prostřednictvím Python" h2="Ověřování finančních zpráv ve formátu XBRL bez nutnosti instalace sady Microsoft Office nebo jiného softwaru." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Jak ověřit soubory XBRL" %}}

Postupujte podle kroků ve úryvku kódu nebo jej vylepšete podle potřeb vaší aplikace pro ověřování dokumentů v rozšiřitelném jazyce podnikových výkazů XBRL. Ujistěte se, že máte ve své aplikaci požadavky na ověření.

1. Načtěte soubor XBRL pomocí instance třídy XbrlDocument.2. Pro kontrolu platnosti načteného souboru, aby se shodoval s [XBRL specifikace](http://www.xbrl.org/specification/inlinexbrl-part1/rec-2013-11-18/inlinexbrl-part1-rec-2013-11-18.html)
3. Pro kontrolu platnosti použijte metodu validate třídy XbrlInstance.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavek na ověření" %}}
Chcete-li pokračovat v ověřování dokumentů XBRL, ujistěte se, že splňujete následující předpoklady. 
- OS založený na Microsoft Windows nebo Linux.- Python 3.5 nebo novější.- Aspose.Finance pro Python odkazovaný ve vašem projektu.{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python kód pro ověření XBRL souborů" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "validate-xbrl-instance-file.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Další možnosti ověření" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/validate/ixbrl/" name="XBRL" description="Inline Extensible Business Reporting Language" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
---
title: Vytvořit soubor požadavku OFX prostřednictvím Python
description: Ukázkový kód pro vytvoření souboru požadavku OFX. Použijte API ukázkový kód pro dávkové generování souborů požadavků OFX v aplikacích založených na Python. 
url: /cs/python-net/create/ofx-request/
family: finance
platformtag: python
feature: create
informat: OFX Request
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Vytvořit soubory požadavku OFX prostřednictvím Python" h2="OFX požaduje vytvoření souborů bez nutnosti instalace sady Microsoft Office nebo jiného softwaru." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Jak vytvořit soubory požadavku OFX" %}}

Po splnění požadavků na vytváření souborů OFX ve vaší aplikaci postupujte podle kroků ve fragmentu kódu nebo jej vylepšete podle svých požadavků.

1. Vytvořte objekt třídy OfxRequestDocument.2. Přiřaďte příslušné vlastnosti pomocí různých tříd poskytovaných službou API, jako je SignonRequest, FinancialInstitution], StatementTransactionRequest
3. Použijte ofxVersion V2x nebo V1x pro soubory xml a sgml z OfxVersionEnum jako parametr v metodě Save.
4. Zavolejte metodu uložení zadáním cílového souboru a ofxVersion.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavek na vytvoření" %}}
Chcete-li pokračovat v žádosti o vytvoření souboru OFX, ujistěte se, že splňujete následující předpoklady. 
- OS založený na Microsoft Windows nebo Linux.- Python 3.5 nebo novější.- Aspose.Finance pro Python odkazovaný ve vašem projektu.{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Kód Python pro vytvoření souborů požadavku OFX" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-request-files.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Další možnosti tvorby" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-response/" name="OFX Soubor odpovědí" description="Formát 1.03 nebo 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/xbrl/" name="XBRL Soubor" description="Rozšiřitelný jazyk pro obchodní výkaznictví" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
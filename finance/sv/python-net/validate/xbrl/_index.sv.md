---
title: Validera filen XBRL via Python
description: Exempelkod för XBRL-filvalidering. Använd API exempelkod för att validera batch-XBRL-filer i Python-baserade applikationer. 
url: /sv/python-net/validate/xbrl/
family: finance
platformtag: python
feature: validate
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Validera XBRL filer via Python" h2="Validera finansiella rapporter i XBRL-format utan att behöva installera Microsoft Office eller någon annan programvara." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Så här validerar du XBRL-filer" %}}

Följ stegen i kodavsnittet eller förbättra det i enlighet med dina applikationsbehov för att validera utökningsbara dokument för affärsrapporteringsspråk XBRL. Se till att ha valideringskrav i din ansökan.

1. Ladda XBRL-filen med XbrlDocument class Instance.2. För att kontrollera giltigheten av den laddade filen, så att den måste matcha med [XBRL specifikation](http://www.xbrl.org/specification/inlinexbrl-part1/rec-2013-11-18/inlinexbrl-part1-rec-2013-11-18.html)
3. För att kontrollera validiteten, använd valideringsmetoden för XbrlInstance-klassen.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Valideringskrav" %}}
För att fortsätta med att validera XBRL dokument, se till att du har följande förutsättningar. 
- Microsoft Windows eller Linux-baserat operativsystem.- Python 3.5 eller senare.- Aspose.Finance för Python som refereras till i ditt projekt.{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python-kod för att validera XBRL filer" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "validate-xbrl-instance-file.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Andra valideringsalternativ" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/validate/ixbrl/" name="XBRL" description="Inline Extensible Business Reporting Language" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
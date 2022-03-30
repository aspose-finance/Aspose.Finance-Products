---
title: Validera filen XBRL via C#
description: Exempelkod för XBRL-filvalidering. Använd API exempelkod för att validera batch-XBRL-filer i .NET-baserade applikationer. 
url: /sv/net/validate/xbrl/
family: finance
platformtag: net
feature: validate
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Validera XBRL filer via C#" h2="Validera finansiella rapporter i XBRL-format utan att behöva installera Microsoft Office eller någon annan programvara." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Så här validerar du XBRL-filer" %}}

Följ stegen i kodavsnittet eller förbättra det i enlighet med dina applikationsbehov för att validera utökningsbara dokument för affärsrapporteringsspråk XBRL. Se till att ha valideringskrav i din ansökan.

1. Ladda XBRL fil med [XbrlDocument-klass](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Exempel.1. För att kontrollera giltigheten av den laddade filen, så att den måste matcha med [XBRL specifikation](http://www.xbrl.org/specification/inlinexbrl-part1/rec-2013-11-18/inlinexbrl-part1-rec-2013-11-18.html)1. För att kontrollera validiteten, använd [Bekräfta()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) metod av [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) klass.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Valideringskrav" %}}
För att fortsätta för att validera XBRL dokument är .NET Finance API huvudkravet för att inkluderas i ansökan. 
- Installera den via kommandoraden som ```nuget install Aspose.Finance``` eller via Package Manager Console of Visual Studio med ```Install-Package Aspose.Finance```.
- Alternativt kan du hämta offline MSI-installationsprogrammet eller DLL-filer i en ZIP-fil från [Nedladdningar](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C#-kod för att validera XBRL filer" offSpacer="" %}}

{{< gist "aspose-com-gists" "1272da1f804f8cef122600269db09fbb" "validate-xbrl-instance-file.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Andra valideringsalternativ" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/validate/ixbrl/" name="XBRL" description="Inline Extensible Business Reporting Language" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
---
title: Validera filen iXBRL via C#
description: Exempelkod för iXBRL-filvalidering. Använd API exempelkod för att validera batch-iXBRL-filer i .NET-baserade applikationer. 
url: /sv/net/validate/ixbrl/
family: finance
platformtag: net
feature: validate
informat: iXBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Validera iXBRL filer via C#" h2="Validera finansiella rapporter i iXBRL-format utan att behöva installera Microsoft Office eller någon annan programvara." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Så här validerar du iXBRL-filer" %}}

Följ stegen i kodavsnittet eller förbättra det i enlighet med dina applikationsbehov för att validera utökningsbara dokument för affärsrapporteringsspråk iXBRL. Se till att ha valideringskrav i din ansökan.

1. Ladda iXBRL fil med [InlineXbrlDocument-klass](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) Exempel.1. För att kontrollera giltigheten av den laddade filen, så att den måste matcha med [iXBRL specifikation](http://www.xbrl.org/specification/inlinexbrl-part1/rec-2013-11-18/inlinexbrl-part1-rec-2013-11-18.html)1. Använda sig av [Bekräfta()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument/methods/validate) metod för filens giltighet.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Valideringskrav" %}}
För att fortsätta för att validera iXBRL dokument är .NET Finance API huvudkravet för att inkluderas i ansökan. 
- Installera den via kommandoraden som ```nuget install Aspose.Finance``` eller via Package Manager Console of Visual Studio med ```Install-Package Aspose.Finance```.
- Alternativt kan du hämta offline MSI-installationsprogrammet eller DLL-filer i en ZIP-fil från [Nedladdningar](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C#-kod för att validera iXBRL filer" offSpacer="" %}}

{{< gist "aspose-com-gists" "1272da1f804f8cef122600269db09fbb" "validate-ixbrl-file.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Andra valideringsalternativ" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/validate/xbrl/" name="XBRL" description="Extensible Business Reporting Language" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
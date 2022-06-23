---
title: Visa XBRL fil via C#
description: Exempelkod för XBRL filvisning. Använd API exempelkod för att visa batch-XBRL-filer i .NET-baserade applikationer. 
url: /sv/net/view/xbrl/
family: finance
platformtag: net
feature: view
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Visa XBRL filer via C#" h2="Visa finansiella rapporter i formatet XBRL utan att behöva installera Microsoft Office eller någon annan programvara." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Så här visar du XBRL-filer" %}}

Följ stegen i kodavsnittet eller förbättra det efter dina programbehov för att läsa utökningsbara filer för affärsrapporteringsspråket XBRL. Se till att ha läskrav i din ansökan.

1. Skapa [XbrlDocument-klass](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Exempel.2. Skicka namnet på en giltig XBRL-fil som en parameter.
3. För att få den inre detaljen i filen, använd de relevanta klasserna som t.ex [SchemaRefCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemarefcollection), [Sammanhang](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context), [Enhet](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/unit) 
4. Visa denna information

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Läskrav" %}}
För att fortsätta för att visa XBRL dokument är .NET Finance API huvudkravet för att inkluderas i ansökan. 
- Installera den via kommandoraden som ```nuget install Aspose.Finance``` eller via Package Manager Console of Visual Studio med ```Install-Package Aspose.Finance```.
- Alternativt kan du hämta offline MSI-installationsprogrammet eller DLL-filer i en ZIP-fil från [Nedladdningar](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# kod för att läsa XBRL filer" offSpacer="" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "read-xbrl-file.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Andra visningsalternativ" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/view/ixbrl/" name="iXBRL" description="Inline Extensible Business Reporting Language" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
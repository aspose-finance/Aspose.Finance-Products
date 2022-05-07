---
title: Ler arquivo XBRL via C#
description: Código de amostra para leitura de arquivo XBRL. Use o código de exemplo API para ler arquivos em lote XBRL em aplicativos baseados em .NET. 
url: /pt/net/read/xbrl/
family: finance
platformtag: net
feature: read
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Leia XBRL Arquivos por meio de C#" h2="Lendo relatórios financeiros no formato XBRL sem precisar do Microsoft Office instalado ou qualquer outro software." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Como ler arquivos XBRL" %}}

Siga as etapas no snippet de código ou aprimore-o conforme as necessidades do seu aplicativo para ler arquivos extensíveis de linguagem de relatórios de negócios XBRL. Certifique-se de ter requisitos de leitura em seu aplicativo.

1. Crio [Classe XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Instância.1. Passe o nome de um arquivo XBRL válido como parâmetro.1. Para obter os detalhes internos do arquivo, use as classes relevantes, como [SchemaRefCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemarefcollection), [Contexto](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context), [Unidade](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/unit) 
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisito de leitura" %}}
Para prosseguir para a leitura de documentos XBRL, .NET Finance API é o principal requisito a ser incluído no aplicativo. 
- Instale-o via linha de comando como ```nuget install Aspose.Finance``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.Finance```.
- Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP de [Transferências](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# código para ler XBRL arquivos" offSpacer="" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "read-xbrl-file.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Outras opções de leitura" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/read/ixbrl/" name="iXBRL" description="Linguagem Extensível de Relatórios de Negócios Inline" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
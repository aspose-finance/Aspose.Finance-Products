---
title: Validar arquivo XBRL via C#
description: Código de amostra para validação de arquivo XBRL. Use o código de exemplo API para validar arquivos XBRL em lote em aplicativos baseados em .NET. 
url: /pt/net/validate/xbrl/
family: finance
platformtag: net
feature: validate
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Valide XBRL Arquivos por meio de C#" h2="Validação de relatórios financeiros no formato XBRL sem precisar do Microsoft Office instalado ou qualquer outro software." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Como validar arquivos XBRL" %}}

Siga as etapas no snippet de código ou aprimore-o de acordo com as necessidades do seu aplicativo para validar documentos de linguagem de relatório comercial extensível XBRL. Certifique-se de ter requisitos de validação em seu aplicativo.

1. Carregar arquivo XBRL usando [Classe XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Instância.1. Para verificar a validade do arquivo carregado, para que ele corresponda [XBRL especificação](http://www.xbrl.org/specification/inlinexbrl-part1/rec-2013-11-18/inlinexbrl-part1-rec-2013-11-18.html)1. Para verificar a validade, use [Validar()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) método de [XbrlInstanceName](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) classe.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisito de validação" %}}
Para prosseguir com a validação de documentos XBRL, .NET Finance API é o principal requisito a ser incluído no aplicativo. 
- Instale-o via linha de comando como ```nuget install Aspose.Finance``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.Finance```.
- Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP de [Transferências](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# código para validar XBRL arquivos" offSpacer="" %}}

{{< gist "aspose-com-gists" "1272da1f804f8cef122600269db09fbb" "validate-xbrl-instance-file.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Outras opções de validação" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/validate/ixbrl/" name="XBRL" description="Linguagem Extensível de Relatórios de Negócios Inline" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
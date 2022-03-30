---
title: Criar arquivo XBRL via C#
description: Código de amostra para criação de arquivo XBRL. Use o código de exemplo API para geração de arquivos em lote XBRL em aplicativos baseados em .NET. 
url: /pt/net/create/xbrl/
family: finance
platformtag: net
feature: create
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Crie arquivos XBRL por meio de C#" h2="XBRL criação de arquivos sem precisar do Microsoft Office instalado ou qualquer outro software." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Como criar arquivos XBRL" %}}

Siga as etapas no snippet de código ou aprimore-o conforme as necessidades do seu aplicativo para gerar arquivos extensíveis de linguagem de relatórios de negócios XBRL. Certifique-se de ter requisitos de criação em seu aplicativo.

1. Crio [Classe XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Instância.1. Para criar um novo documento de instância XBRL [XbrlInstanceCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) e [XbrlInstanceName](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance).1. Adicionar referência de esquema usando [SchemaRefCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemarefcollection)1. Dependendo da natureza do aplicativo, adicione contexto, unidade, item, link de nota de rodapé e muito mais.1. Ligar para [Salvar método](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) fornecendo o caminho do arquivo de destino.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisito de Criação" %}}
Para prosseguir com a geração de documentos XBRL, .NET Finance API é o principal requisito a ser incluído no aplicativo. 
- Instale-o via linha de comando como ```nuget install Aspose.Finance``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.Finance```.
- Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP de [Transferências](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# código para criação de XBRL arquivos" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-schema-reference.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Outras opções de criação" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX Solicitar" description="Formato 1.03 ou 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX Resposta" description="Formato 1.03 ou 2.2" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
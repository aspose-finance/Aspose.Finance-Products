---
title: Criar XBRL Arquivo via C#
description: Código de amostra para XBRL criação de arquivo. Use API código de exemplo para geração de arquivos em lote XBRL em aplicativos baseados em .NET. 
url: /pt/net/create/xbrl/
family: finance
platformtag: net
feature: create
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Criar XBRL Arquivos via C#" h2="XBRL criação de arquivos sem a necessidade de Microsoft Office instalado ou qualquer outro software." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Como criar XBRL arquivos" %}}

Siga as etapas no trecho de código ou aprimore-o a partir das necessidades do seu aplicativo para gerar arquivos extensíveis de linguagem de relatório de negócios XBRL. Certifique-se de ter requisitos de criação dentro do seu aplicativo.

1. Criar [Classe XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Instância.1. Para criar um novo documento de instância XBRL [Coleção XbrlInstanceCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) E [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance)...1. Adicionar referência de esquema usando [SchemaRefCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemarefcollection)1. Dependendo da natureza do aplicativo, adicione contexto, unidade, item, link de nota de rodapé e muito mais.1. Ligue para o [Salvar método](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) Fornecendo o caminho do arquivo de destino.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigência de criação" %}}
Para prosseguir para a geração de documentos XBRL, .NET Finance API é o principal requisito a ser incluído no aplicativo. 
- Instale-o via linha de comando como '''nogget install Aspose.Finance'' 'ou via Console do Package Manager do Visual Studio com '''Install-Package Aspose.Finance'''.
- Como alternativa, obtenha o instalador MSI offline ou DLLs em um arquivo ZIP de [Downloads](https://downloads.aspose.com/finance/net)...{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# código para XBRL criação de arquivos" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-schema-reference.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Outras opções de criação" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX Pedido" description="Formato 1.03 ou 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX Resposta" description="Formato 1.03 ou 2.2" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
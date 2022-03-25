---
title: Criar OFX arquivo de resposta via C#
description: Código de amostra para a criação do arquivo de resposta OFX. Use API código de exemplo para geração de arquivos de resposta em lote OFX em aplicativos baseados em .NET. 
url: /pt/net/create/ofx-response/
family: finance
platformtag: net
feature: create
informat: OFX Response
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Criar OFX Arquivos de Resposta via C#" h2="OFX criação de arquivos de resposta sem a necessidade de Microsoft Office instalado ou qualquer outro software." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Como criar OFX arquivos de resposta" %}}

Siga as etapas no trecho de código ou melhorá-lo a partir de suas necessidades de aplicação depois de ter os requisitos de criação dentro de seu aplicativo.

1. Criar [Classe OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) Objeto.1. Atribuir as propriedades relevantes usando diferentes classes fornecidas por API como [SignonResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [Declaração Transação Resposta](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse), [Declaração Transação](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction)1. Use o ofxVersion V2x ou V1x para arquivos xml e sgml respectivamente de [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) Como parâmetro no método Salvar.1. Ligue para o [Salvar método](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument/methods/save) Fornecendo o arquivo de destino e ofxVersion.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigência de criação" %}}
Para prosseguir para a criação do arquivo de resposta OFX, .NET Finance API é o principal requisito a ser incluído no aplicativo de geração de relatório. 
- Instale-o via linha de comando como '''nogget install Aspose.Finance'' 'ou via Console do Package Manager do Visual Studio com '''Install-Package Aspose.Finance'''.
- Como alternativa, obtenha o instalador MSI offline ou DLLs em um arquivo ZIP de [Downloads](https://downloads.aspose.com/finance/net)...{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# código para OFX criação de arquivos de resposta" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Outras opções de criação" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX Arquivo de solicitação" description="Formato 1.03 ou 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL Arquivo" description="Linguagem de relatórios de negócios extensível" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
---
title: Criar arquivo de resposta OFX por meio de C#
description: Código de amostra para criação do arquivo de resposta OFX. Use o código de exemplo API para geração de arquivos de resposta em lote OFX em aplicativos baseados em .NET. 
url: /pt/net/create/ofx-response/
family: finance
platformtag: net
feature: create
informat: OFX Response
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Crie OFX arquivos de resposta por meio de C#" h2="OFX criação de arquivos de resposta sem precisar do Microsoft Office instalado ou qualquer outro software." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Como criar OFX arquivos de resposta" %}}

Siga as etapas no trecho de código ou aprimore-o conforme as necessidades do seu aplicativo após ter os requisitos de criação em seu aplicativo.

1. Crio [Classe OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) objeto.1. Atribua as propriedades relevantes usando diferentes classes fornecidas por API como [Resposta do Signon](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [DeclaraçãoTransaçãoResposta](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse), [ExtratoTransação](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction)1. Use o ofxVersion V2x ou V1x para arquivos xml e sgml respectivamente de [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) como parâmetro no método Save.1. Ligar para [Salvar método](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument/methods/save) fornecendo o arquivo de destino e ofxVersion.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisito de Criação" %}}
Para prosseguir com a criação do arquivo de resposta OFX, .NET Finance API é o principal requisito a ser incluído no aplicativo de geração de relatório. 
- Instale-o via linha de comando como ```nuget install Aspose.Finance``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.Finance```.
- Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP de [Transferências](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# código para criação de arquivos de resposta OFX" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Outras opções de criação" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX Arquivo de solicitação" description="Formato 1.03 ou 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL Arquivo" description="Linguagem Extensível de Relatórios de Negócios" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
---
title: Criar OFX Solicitar arquivo via C#
description: Código de amostra para OFX criação de arquivo de solicitação. Use API código de exemplo para geração de arquivos de solicitação em lote OFX em aplicativos baseados em .NET. 
url: /pt/net/create/ofx-request/
family: finance
platformtag: net
feature: create
informat: OFX Request
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Criar OFX arquivos de solicitação via C#" h2="OFX solicitar a criação de arquivos sem precisar do Microsoft Office instalado ou de qualquer outro software." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Como criar OFX arquivos de solicitação" %}}

Depois de ter os requisitos de criação de OFX Request files dentro do seu aplicativo, siga as etapas no trecho de código ou aprimore-o a partir do seu requisito.

1. Criar [Classe OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) Objeto.1. Atribuir as propriedades relevantes usando diferentes classes fornecidas por API como [Solicitação de sinalização](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [FinancialInstituição](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution), [Pedido de Transação de Declaração](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest)1. Use o ofxVersion V2x ou V1x para arquivos xml e sgml respectivamente de [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) Como parâmetro no método Salvar.1. Ligue para o [Salvar método](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument/methods/save) Fornecendo o arquivo de destino e ofxVersion.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigência de criação" %}}
Para prosseguir para OFX Solicitar criação de arquivo, .NET Finance API é o principal requisito a ser incluído no aplicativo de geração de relatório. 
- Instale-o via linha de comando como '''nogget install Aspose.Finance'' 'ou via Console do Package Manager do Visual Studio com '''Install-Package Aspose.Finance'''.
- Como alternativa, obtenha o instalador MSI offline ou DLLs em um arquivo ZIP de [Downloads](https://downloads.aspose.com/finance/net)...{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# código para OFX criação de arquivos de solicitação" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-request-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Outras opções de criação" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX Arquivo de Resposta" description="Formato 1.03 ou 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL Arquivo" description="Linguagem de relatórios de negócios extensível" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
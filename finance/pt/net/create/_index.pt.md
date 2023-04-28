---
title: Crie relatórios financeiros por meio de .NET
url: /pt/net/create/
description:  C# código para criar relatórios financeiros em XBRL e OFX arquivos de solicitação ou resposta por meio da biblioteca .NET.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Crie arquivos de relatórios financeiros por meio de C#" h2="Criação de formatos de relatórios financeiros incluindo XBRL e OFX arquivo de solicitação ou resposta no formato 1.03 ou 2.2 em aplicativos baseados em .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) é um recurso rico em recursos, extensível e fácil de usar para criação e processamento de relatórios financeiros API. Os desenvolvedores podem criar facilmente a instância XBRL do zero, bem como adicionar referência de esquema, contexto, unidade, item, link de nota de rodapé, referência de função e 
referência de função de arco. API fornece classe relevante para cada recurso, como para contexto, os desenvolvedores podem usar [ContextoPeríodo](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextperiod), [ContextEntity](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextentity) e [Contexto](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context). 
Além disso, API também oferece suporte à criação de solicitação/resposta no formato de troca financeira aberta (OFX) no formato 1.03 ou 2.2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Criar arquivo XBRL adicionando item" %}}

Para criar o arquivo XBRL e adicionar item ao documento, o processo é criar [Classe XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) instância. Prepare configurações relevantes para o item usando classes API apropriadas, como [Classe SchemaRef](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemaref)classes de contexto relevantes conforme mencionado acima e [Aula de conceito](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/concept). Finalmente defina e inicialize [Classe do item](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/item) propriedades, bem como chamar o [Salvar método](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) para [criar XBRL](https://products.aspose.com/finance/net/create/xbrl/) arquivo em disco.

{{% blocks/products/pf/feature-page-code h3="C# Código para criar arquivo XBRL adicionando item" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-item.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Crie OFX arquivos de solicitação e resposta" %}}


Para gerar arquivos OFX, o API fornece [OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) e [OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) classes e desenvolvedores podem facilmente [criar OFX Solicitação](https://products.aspose.com/finance/net/create/ofx-request/) e arquivos de resposta nos formatos 1.03 e 2.2. Para inicializar as propriedades OfxRequestDocument, API também fornece outras classes, como [Solicitação de login](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [Instituição financeira](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution) e [DeclaraçãoTransaçãoSolicitação](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest) Aulas. Da mesma forma, para inicializar as propriedades OfxResponseDocument, API fornece classes de suporte, como [Resposta do Signon](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [DeclaraçãoTransaçãoResposta](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse) e [ExtratoTransação](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction). Abaixo estão os trechos de código para ambos os casos com o uso de classes apropriadas relevantes.

{{% blocks/products/pf/feature-page-code h3="C# Código para gerar OFX documentos de solicitação" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Código para gerar OFX documentos de resposta" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< /blocks/products/pf/feature-page-wrap >}}
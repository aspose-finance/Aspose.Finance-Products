---
title: Criar relatórios financeiros via .NET
url: /pt/net/create/
description:  C# código para criar Relatórios Financeiros em XBRL e OFX arquivos de solicitação ou resposta via .NET biblioteca.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Criar arquivos de relatórios financeiros via C#" h2="Criação de formatos de relatório financeiro incluindo XBRL e OFX arquivo de solicitação ou resposta no formato 1.03 ou 2.2 em .NET aplicativos baseados." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) É um recurso rico, extensível e fácil de usar criação e processamento de relatórios financeiros API. Os desenvolvedores podem criar facilmente XBRL instância do zero, bem como podem adicionar referência de esquema, contexto, unidade, item, link de nota de rodapé, referência de função e 
Referência do papel do arco. API fornece classe relevante para cada recurso, como para contexto, os desenvolvedores podem usar [Período de Contexto](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextperiod), [ContextEntidade](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextentity) E [Contexto](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context)... 
Além disso, API também oferece suporte à criação de formato de solicitação/resposta de troca financeira aberta (OFX) no formato 1.03 ou 2.2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Criar XBRL Arquivo Adicionando Item" %}}

Para criar XBRL arquivo e adicionar item ao documento, o processo é, criar [Classe XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Instância. Prepare as configurações relevantes para o item usando API classes apropriadas, como [Classe SchemaRef](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemaref), Classes de contexto relevantes como mencionado acima e [Conceito de classe](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/concept)... Finalmente definir e intializar [Classe de item](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/item) Propriedades, bem como chamar o [Salvar método](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) Para [Criar XBRL](https://products.aspose.com/finance/net/create/xbrl/) Arquivo em disco.

{{% blocks/products/pf/feature-page-code h3="C# Código para criar XBRL arquivo adicionando item" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-item.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Criar OFX Arquivos de Solicitação e Resposta" %}}


Para gerar OFX arquivos, o API fornece [OfxRequestDocumento](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) E [OfxResponseDocumento](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) Classes e desenvolvedores podem facilmente [Criar OFX solicitação](https://products.aspose.com/finance/net/create/ofx-request/) E arquivos de resposta em ambos os formatos 1.03 e 2.2. Para inicializar as propriedades do OfxRequestDocument, API também fornece outras classes, como [Solicitação de sinalização](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [FinancialInstituição](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution) E [Pedido de Transação de Declaração](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest) Aulas. Da mesma forma, para intializar as propriedades do OfxResponseDocument, API fornece classes de suporte, como [SignonResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [Declaração Transação Resposta](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse) E [Declaração Transação](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction)... Abaixo estão os trechos de código para ambos os casos com o uso de classes apropriadas relevantes.

{{% blocks/products/pf/feature-page-code h3="C# Código para gerar OFX Documentos de solicitação" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Código para gerar OFX documentos de resposta" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
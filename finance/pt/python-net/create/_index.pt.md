---
title: Crie relatórios financeiros por meio de Python
url: /pt/python-net/create/
description:  Python código para criar relatórios financeiros em XBRL e OFX arquivos de solicitação ou resposta por meio da biblioteca Python.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Crie arquivos de relatórios financeiros por meio de Python" h2="Criação de formatos de relatórios financeiros incluindo XBRL e OFX arquivo de solicitação ou resposta no formato 1.03 ou 2.2 em aplicativos baseados em Python." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance para Python via .NET](https://products.aspose.com/finance/python-net/) é um recurso rico em recursos, extensível e fácil de usar para criação e processamento de relatórios financeiros API. Os desenvolvedores podem criar facilmente a instância XBRL do zero, bem como adicionar referência de esquema, contexto, unidade, item, link de nota de rodapé, referência de função e 
referência de função de arco. API fornece classe relevante para cada recurso, como para contexto, os desenvolvedores podem usar ContextPeriod, ContextEntity e Context. 
Além disso, API também oferece suporte à criação de solicitação/resposta no formato de troca financeira aberta (OFX) no formato 1.03 ou 2.2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Criar arquivo XBRL adicionando item" %}}

Para criar o arquivo XBRL e adicionar um item ao documento, o processo é criar uma instância da classe XbrlDocument. Prepare configurações relevantes para o item usando classes API apropriadas, como a classe SchemaRef, classes de contexto relevantes, conforme mencionado acima, e a classe Concept. Por fim, defina e inicialize as propriedades da classe Item, bem como chame o método save para criar o arquivo XBRL no disco.

{{% blocks/products/pf/feature-page-code h3="Python Código para criar arquivo XBRL adicionando item" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-xbrl-file-and-add-item.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Crie OFX arquivos de solicitação e resposta" %}}


Para gerar arquivos OFX, o API fornece as classes OfxRequestDocument e OfxResponseDocument e os desenvolvedores podem facilmente [criar OFX Solicitação](https://products.aspose.com/finance/python-net/create/ofx-request/) e arquivos de resposta nos formatos 1.03 e 2.2. Para inicializar as propriedades OfxRequestDocument, API também fornece outras classes, como as classes SignonRequest, FinancialInstitution e StatementTransactionRequest. Da mesma forma, para inicializar as propriedades OfxResponseDocument, API fornece classes de suporte, como SignonResponse, StatementTransactionResponse e StatementTransaction. Abaixo estão os trechos de código para ambos os casos com o uso de classes apropriadas relevantes.

{{% blocks/products/pf/feature-page-code h3="Python Código para gerar OFX documentos de solicitação" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python Código para gerar OFX documentos de resposta" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
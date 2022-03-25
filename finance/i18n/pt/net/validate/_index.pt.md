---
title: Validar Relatórios Financeiros via .NET
url: /pt/net/validate/
description:  C# código para validar relatórios financeiros em XBRL e iXBRL arquivos via .NET biblioteca.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Validar arquivos de relatórios financeiros via C#" h2="Validando formatos de relatório financeiro incluindo XBRL e iXBRL em .NET aplicativos baseados." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) É um recurso rico, extensível e fácil de usar processamento de relatórios financeiros API. Os desenvolvedores podem facilmente carregar, validar, visualizar ou criar formatos XBRL e iXBRL para soluções financeiras e de negócios. API fornece [XbrlDocumento](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Classe e  [Documento InlineXbrl](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) Classe para carregar XBRL e iXBRL arquivos.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Validar XBRL Documento" %}}

A validação do arquivo XBRL é necessária para vários casos, como para verificar se os dados estão na estrutura e formato corretos. Para validar documentos XBLR, use em primeiro lugar a classe XbrlDocument para carregar o arquivo XBRL. Para usar o [Validar ()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) Método de [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) Classe, em primeiro lugar intializar o [Coleção XbrlInstanceCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) Com XbrlDocument objeto XbrlInstances. Iterar através de cada um [XbrlInstance. Erros de validação](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/properties/validationerrors) Para obter o código de erro correto e agir de acordo, imprimindo as mensagens de erro personalizadas no console ou escrevendo dentro de um arquivo.

{{% blocks/products/pf/feature-page-code h3="C# Código para validar XBRL arquivo" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-xbrl-file.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Validar iXBRL Documento" %}}

Para validação iXLRB, carregue-o via [Documento InlineXbrl](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) Classe e use seu método Validar (). Em [ValidaçãoErrorCode](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.validator/validationerrorcode) Enumeração, códigos de erro de validação são definidos para cada regra de validação. Poucos códigos são ContextPeriodNoStartTime, ContextPeriodNoEndTime, ContextPeriodStartAfterEnd, ContextInstantNoTime, ContextScenarioXbrlNamespace, ContextscenarioXbrlSubstitutionGroup etc. Os desenvolvedores podem depurar e exibir códigos como usuários finais ou podem mostrar a direção para resolver o problema.

{{% blocks/products/pf/feature-page-code h3="C# Código para validar iXBRL documento" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-ixbrl-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}
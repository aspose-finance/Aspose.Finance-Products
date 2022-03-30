---
title: Validar relatórios financeiros por meio de .NET
url: /pt/net/validate/
description:  C# código para validar relatórios financeiros em arquivos XBRL e iXBRL por meio da biblioteca .NET.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Validar arquivos de relatórios financeiros por meio de C#" h2="Validação de formatos de relatórios financeiros, incluindo XBRL e iXBRL em aplicativos baseados em .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) é um processamento de relatório financeiro rico em recursos, extensível e fácil de usar API. Os desenvolvedores podem facilmente carregar, validar, visualizar ou criar formatos XBRL e iXBRL para soluções financeiras e de negócios. API fornece [XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) classe e  [Documento InlineXbrl](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) classe para carregar arquivos XBRL e iXBRL.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Validar documento XBRL" %}}

A validação do arquivo XBRL é necessária para vários casos, como verificar se os dados estão na estrutura e no formato corretos. Para validar documentos XBLR, primeiro use a classe XbrlDocument para carregar o arquivo XBRL. Para usar o [validar()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) método de [XbrlInstanceName](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) classe, primeiro inicialize o [XbrlInstanceCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) com o objeto XbrlDocument XbrlInstances. Iterar através de cada [XbrlInstance.ValidationErrors](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/properties/validationerrors) para obter o código de erro correto e agir de acordo imprimindo as mensagens de erro personalizadas no console ou gravando em um arquivo.

{{% blocks/products/pf/feature-page-code h3="C# Código para validar arquivo XBRL" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-xbrl-file.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Validar documento iXBRL" %}}

Para validação do iXLRB, carregue-o via [Documento InlineXbrl](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) class e use seu método Validate(). Dentro [Código de erro de validação](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.validator/validationerrorcode) enumeração, os códigos de erro de validação são definidos para cada regra de validação. Alguns dos códigos são ContextPeriodNoStartTime, ContextPeriodNoEndTime, ContextPeriodStartAfterEnd, ContextInstantNoTime, ContextScenarioXbrlNamespace, ContextScenarioXbrlSubstitutionGroup etc. Os desenvolvedores podem depurar e exibir códigos de usuários finais ou podem mostrar a direção para resolver o problema.

{{% blocks/products/pf/feature-page-code h3="C# Código para validar documento iXBRL" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-ixbrl-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}
---
title: Validar relatórios financeiros por meio de Python
url: /pt/python-net/validate/
description:  Python código para validar relatórios financeiros em arquivos XBRL e iXBRL por meio da biblioteca Python.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Validar arquivos de relatórios financeiros por meio de Python" h2="Validação de formatos de relatórios financeiros, incluindo XBRL e iXBRL em aplicativos baseados em Python." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance para Python via .NET](https://products.aspose.com/finance/python-net/) é um processamento de relatório financeiro rico em recursos, extensível e fácil de usar API. Os desenvolvedores podem facilmente carregar, validar, visualizar ou criar formatos XBRL e iXBRL para soluções financeiras e de negócios. API fornece a classe XbrlDocument e a classe InlineXbrlDocument para carregar arquivos XBRL e iXBRL.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Validar documento XBRL" %}}

A validação do arquivo XBRL é necessária para vários casos, como verificar se os dados estão na estrutura e no formato corretos. Para validar documentos XBLR, primeiro use a classe XbrlDocument para carregar o arquivo XBRL. Para usar o método validate da classe XbrlInstance, primeiro inicialize o XbrlInstanceCollection com o objeto XbrlDocument XbrlInstances. Itere através de cada XbrlInstance.ValidationErrors para obter o código de erro correto e aja de acordo imprimindo as mensagens de erro personalizadas no console ou gravando em um arquivo.

{{% blocks/products/pf/feature-page-code h3="Python Código para validar arquivo XBRL" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "validate-xbrl-instance-file.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Validar documento iXBRL" %}}

Para validação do iXLRB, carregue-o via classe InlineXbrlDocument e use seu método validate(). Na enumeração ValidationErrorCode, os códigos de erro de validação são definidos para cada regra de validação. Alguns dos códigos são ContextPeriodNoStartTime, ContextPeriodNoEndTime, ContextPeriodStartAfterEnd, ContextInstantNoTime, ContextScenarioXbrlNamespace, ContextScenarioXbrlSubstitutionGroup etc. Os desenvolvedores podem depurar e exibir códigos de usuários finais ou podem mostrar a direção para resolver o problema.

{{% blocks/products/pf/feature-page-code h3="Python Código para validar documento iXBRL" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "validate-ixbrl-file.py" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}
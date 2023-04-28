---
title: 通过 Python 验证财务报告
url: /zh/python-net/validate/
description:  Python 代码通过 Python 库验证 XBRL 和 iXBRL 文件中的财务报告。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 Python 验证财务报告文件" h2="在基于 Python 的应用程序中验证财务报告格式，包括 XBRL 和 iXBRL。" >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance 通过 .NET 为 Python](https://products.aspose.com/finance/python-net/) 是一种功能丰富、可扩展且易于使用的财务报告处理API。开发人员可以轻松加载、验证、查看或创建用于财务和业务解决方案的 XBRL 和 iXBRL 格式。 API 提供用于加载 XBRL 和 iXBRL 文件的 XbrlDocument 类和 InlineXbrlDocument 类。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="验证 XBRL 文档" %}}

在许多情况下需要验证 XBRL 文件，例如检查数据的结构和格式是否正确。要验证 XBLR 文档，首先使用 XbrlDocument 类加载 XBRL 文件。要使用 XbrlInstance 类的 validate 方法，首先用 XbrlDocument 对象 XbrlInstances 初始化 XbrlInstanceCollection。遍历每个 XbrlInstance.ValidationErrors 以获得正确的错误代码，并通过在控制台上打印自定义错误消息或写入文件来采取相应措施。

{{% blocks/products/pf/feature-page-code h3="Python 验证 XBRL 文件的代码" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "validate-xbrl-instance-file.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="验证 iXBRL 文档" %}}

对于 iXLRB 验证，通过 InlineXbrlDocument 类加载它并使用它的 validate() 方法。在 ValidationErrorCode 枚举中，为每个验证规则定义了验证错误代码。很少有代码是 ContextPeriodNoStartTime、ContextPeriodNoEndTime、ContextPeriodStartAfterEnd、ContextInstantNoTime、ContextScenarioXbrlNamespace、ContextScenarioXbrlSubstitutionGroup 等。开发人员可以作为最终用户调试和显示代码，也可以显示解决问题的方向。

{{% blocks/products/pf/feature-page-code h3="Python 验证 iXBRL 文档的代码" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "validate-ixbrl-file.py" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}
{{< /blocks/products/pf/feature-page-wrap >}}
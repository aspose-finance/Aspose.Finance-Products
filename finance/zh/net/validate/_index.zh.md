---
title: 通过 .NET 验证财务报告
url: /zh/net/validate/
description:  C# 代码通过 .NET 库验证 XBRL 和 iXBRL 文件中的财务报告。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 C# 验证财务报告文件" h2="在基于 .NET 的应用程序中验证财务报告格式，包括 XBRL 和 iXBRL。" >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) 是一种功能丰富、可扩展且易于使用的财务报告处理API。开发人员可以轻松加载、验证、查看或创建用于财务和业务解决方案的 XBRL 和 iXBRL 格式。 API 提供 [Xbrl文档](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) 班级和  [内联XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) 用于加载 XBRL 和 iXBRL 文件的类。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="验证 XBRL 文档" %}}

在许多情况下需要验证 XBRL 文件，例如检查数据的结构和格式是否正确。要验证 XBLR 文档，首先使用 XbrlDocument 类加载 XBRL 文件。要使用 [证实（）](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) 的方法 [Xbrl实例](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) 类，首先初始化 [XbrlInstanceCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) 与 XbrlDocument 对象 XbrlInstances。遍历每个 [XbrlInstance.ValidationErrors](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/properties/validationerrors) 通过在控制台上打印自定义错误消息或在文件中写入来获取正确的错误代码并采取相应措施。

{{% blocks/products/pf/feature-page-code h3="C# 验证 XBRL 文件的代码" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-xbrl-file.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="验证 iXBRL 文档" %}}

对于 iXLRB 验证，通过加载它 [内联XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) 类并使用其 Validate() 方法。在 [验证错误代码](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.validator/validationerrorcode) 枚举，为每个验证规则定义验证错误代码。很少有代码是 ContextPeriodNoStartTime、ContextPeriodNoEndTime、ContextPeriodStartAfterEnd、ContextInstantNoTime、ContextScenarioXbrlNamespace、ContextScenarioXbrlSubstitutionGroup 等。开发人员可以作为最终用户调试和显示代码，也可以显示解决问题的方向。

{{% blocks/products/pf/feature-page-code h3="C# 验证 iXBRL 文档的代码" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-ixbrl-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}
{{< /blocks/products/pf/feature-page-wrap >}}
---
title: 通过 .NET 验证财务报告
url: /zh/net/validate/
description:  C# 代码，用于通过 .NET 库验证 XBRL 和 iXBRL 文件中的财务报告。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 C# 验证财务报告文件" h2="在基于 .NET 的应用程序中验证财务报告格式，包括 XBRL 和 iXBRL。" >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) 是一个功能丰富、可扩展且易于使用的财务报表处理 API。开发人员可以轻松地为财务和业务解决方案加载、验证、查看或创建 XBRL 和 iXBRL 格式。API 提供 [XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) 班级和  [InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) 用于加载 XBRL 和 iXBRL 文件的类。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="验证 XBRL 文档" %}}

对于许多情况，例如检查数据是否正确的结构和格式，需要对 XBRL 文件进行验证。要验证XBLR文档，首先使用XbrlDocument类加载 XBRL 文件。要使用 [验证 ()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) 方法 [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) 类，首先初始化 [XbrlInstanceCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) 使用XbrlDocument对象XbrlInstances。遍历每个 [XbrlInstance。验证错误](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/properties/validationerrors) 通过在控制台上打印自定义的错误消息或在文件中写入来获取正确的错误代码并采取相应的行动。

{{% blocks/products/pf/feature-page-code h3="验证 XBRL 文件的 C# 代码" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-xbrl-file.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="验证 iXBRL 文档" %}}

对于iXLRB验证，请通过 [InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) 类并使用其Validate() 方法。在 [验证错误代码](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.validator/validationerrorcode) 枚举，为每个验证规则定义了验证错误代码。很少有代码是contextperiodennostarttime、contextperiodenstartafterend、ContextInstantNoTime、ContextScenarioXbrlNamespace、contextscenarioxbrlsubutiongroup等。开发人员可以调试和显示最终用户的代码，也可以显示解决问题的方向。

{{% blocks/products/pf/feature-page-code h3="用于验证 iXBRL 文档的 C# 代码" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-ixbrl-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}
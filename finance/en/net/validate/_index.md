---
title: Validate Financial Reports via .NET
url: /net/validate/
description:  C# code to validate financial reports in XBRL and iXBRL files via .NET library.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Validate Financial Reporting Files via C#" h2="Validating financial report formats including XBRL and iXBRL within .NET based applications." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) is a feature rich, extensible and easy to use financial report processing API. Developers can easily load, validate, view or create XBRL and iXBRL formats for financial and business solutions. API provides [XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) class and  [InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) class for loading XBRL and iXBRL files.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Validate XBRL Document" %}}

Validation of XBRL file is needed for a number of cases such as to check data is in right structure and format. To validate XBLR documents, Firstly use XbrlDocument class to load the XBRL file. To use the [validate()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) method of [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) class, firstly intialize the [XbrlInstanceCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) with XbrlDocument object XbrlInstances. Iterate through each [XbrlInstance.ValidationErrors](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/properties/validationerrors) to get the right error code and act accordingly by printing the customized error messages on console or writing within a file.

{{% blocks/products/pf/feature-page-code h3="C# Code to Validate XBRL File" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-xbrl-file.cs" >}} 

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Validate iXBRL Document" %}}

For iXLRB validation, load it via [InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) class and use its Validate() method. In [ValidationErrorCode](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.validator/validationerrorcode) enumeration, validation error codes are defined for each validation rule. Few of codes are ContextPeriodNoStartTime, ContextPeriodNoEndTime, ContextPeriodStartAfterEnd, ContextInstantNoTime, ContextScenarioXbrlNamespace, ContextScenarioXbrlSubstitutionGroup etc. Developers can debug and display codes as of end users or can show the direction for resolving the issue.

{{% blocks/products/pf/feature-page-code h3="C# Code to Validate iXBRL Document" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-ixbrl-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate">}}
{{< /blocks/products/pf/feature-page-wrap >}}
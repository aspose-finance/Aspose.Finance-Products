---
title: Validate Financial Reports via Python
url: /python-net/validate/
description:  Python code to validate financial reports in XBRL and iXBRL files via Python library.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Validate Financial Reporting Files via Python" h2="Validating financial report formats including XBRL and iXBRL within Python based applications." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for Python via .NET](https://products.aspose.com/finance/python-net/) is a feature rich, extensible and easy to use financial report processing API. Developers can easily load, validate, view or create XBRL and iXBRL formats for financial and business solutions. API provides XbrlDocument class and  InlineXbrlDocument class for loading XBRL and iXBRL files.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Validate XBRL Document" %}}

Validation of XBRL file is needed for a number of cases such as to check data is in right structure and format. To validate XBLR documents, Firstly use XbrlDocument class to load the XBRL file. To use the validate method of XbrlInstance class, firstly intialize the XbrlInstanceCollection with XbrlDocument object XbrlInstances. Iterate through each XbrlInstance.ValidationErrors to get the right error code and act accordingly by printing the customized error messages on console or writing within a file.

{{% blocks/products/pf/feature-page-code h3="Python Code to Validate XBRL File" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "validate-xbrl-instance-file.py" >}} 

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Validate iXBRL Document" %}}

For iXLRB validation, load it via InlineXbrlDocument class and use its validate() method. In ValidationErrorCode enumeration, validation error codes are defined for each validation rule. Few of codes are ContextPeriodNoStartTime, ContextPeriodNoEndTime, ContextPeriodStartAfterEnd, ContextInstantNoTime, ContextScenarioXbrlNamespace, ContextScenarioXbrlSubstitutionGroup etc. Developers can debug and display codes as of end users or can show the direction for resolving the issue.

{{% blocks/products/pf/feature-page-code h3="Python Code to Validate iXBRL Document" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "validate-ixbrl-file.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate">}}
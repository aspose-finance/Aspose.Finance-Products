---
title: .NET 을 통해 재무 보고서 유효성 검사
url: /ko/net/validate/
description:  C# 코드는 .NET 라이브러리를 통해 XBRL 및 iXBRL 파일에서 재무 보고서를 확인합니다.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# 을 통해 재무보고 파일 검증" h2=".NET 기반 응용 프로그램 내에서 XBRL 및 iXBRL 을 포함한 재무 보고서 형식을 검증합니다." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) 풍부하고 확장 가능하며 재무 보고서 처리 API 를 사용하기 쉬운 기능입니다. 개발자는 금융 및 비즈니스 솔루션에 대해 XBRL 및 iXBRL 형식을 쉽게로드, 검증, 보기 또는 만들 수 있습니다. API 제공 [XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) 클래스와  [InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) XBRL 및 iXBRL 파일을 로드하는 클래스입니다.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="XBRL 문서 확인" %}}

XBRL 파일의 검증은 데이터가 올바른 구조 및 형식인지 확인하는 것과 같은 많은 경우에 필요합니다. XBLR 문서의 유효성을 확인하려면 먼저 XbrlDocument 클래스를 사용하여 XBRL 파일을 로드합니다. 를 사용하는 [검증 ()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) 의 방법 [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) 수업, 먼저 [XbrlInstanceCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) XbrlDocument 개체 xbrlinstances와 함께. 각각을 통해 반복 [XbrlInstance. ValidationErrors](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/properties/validationerrors) 올바른 오류 코드를 얻고 콘솔에서 사용자 정의 오류 메시지를 인쇄하거나 파일 내에서 작성하여 그에 따라 행동하십시오.

{{% blocks/products/pf/feature-page-code h3="XBRL 파일을 확인하는 C# 코드" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-xbrl-file.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="iXBRL 문서 확인" %}}

IXLRB 검증을 위해, 그것을 통해 로드하십시오 [InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) 클래스와 Validate () 메소드를 사용합니다. 에 [ValidationErrorCode](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.validator/validationerrorcode) 각 검증 규칙에 대해 열거, 검증 오류 코드가 정의됩니다. Conextperiodnostarttime, ContextPeriodNoEndTime, ContextPeriodNoEndTime, ContextInstantNoTime, ContextScenarioXbrlNamespace, contextscenarioxbrlstitutiongroup 등 코드는 거의 없습니다. 개발자는 최종 사용자로 코드를 디버깅하고 표시하거나 문제를 해결하기위한 방향을 표시 할 수 있습니다.

{{% blocks/products/pf/feature-page-code h3="iXBRL 문서 유효성을 확인하는 C# 코드" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-ixbrl-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}
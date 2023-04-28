---
title: .NET을(를) 통해 재무 보고서 확인
url: /ko/net/validate/
description:  C# 코드를 사용하여 .NET 라이브러리를 통해 XBRL 및 iXBRL 파일의 재무 보고서를 확인합니다.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C#을(를) 통해 Financial Reporting 파일 검증" h2=".NET 기반 애플리케이션 내에서 XBRL 및 iXBRL를 포함한 재무 보고서 형식 검증." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) 기능이 풍부하고 확장 가능하며 사용하기 쉬운 재무 보고서 처리 API입니다. 개발자는 금융 및 비즈니스 솔루션에 대한 XBRL 및 iXBRL 형식을 쉽게 로드, 검증, 확인 또는 생성할 수 있습니다. API 제공 [Xbrl문서](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) 수업과  [인라인Xbrl문서](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) XBRL 및 iXBRL 파일을 로드하기 위한 클래스입니다.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="XBRL 문서 확인" %}}

데이터가 올바른 구조와 형식인지 확인하는 것과 같은 여러 경우에 XBRL 파일의 유효성 검사가 필요합니다. XBLR 문서의 유효성을 검사하려면 먼저 XbrlDocument 클래스를 사용하여 XBRL 파일을 로드합니다. 사용하려면 [확인()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) 의 방법 [Xbrl인스턴스](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) 클래스, 먼저 초기화 [XbrlInstanceCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) XbrlDocument 개체 XbrlInstances와 함께. 각각을 통해 반복 [XbrlInstance.ValidationErrors](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/properties/validationerrors) 올바른 오류 코드를 얻고 콘솔에 사용자 정의 오류 메시지를 인쇄하거나 파일 내에 작성하여 그에 따라 조치하십시오.

{{% blocks/products/pf/feature-page-code h3="C# XBRL 파일을 검증하는 코드" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-xbrl-file.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="iXBRL 문서 확인" %}}

iXLRB 유효성 검사의 경우 다음을 통해 로드합니다. [인라인Xbrl문서](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) 클래스를 만들고 해당 Validate() 메서드를 사용합니다. ~ 안에 [유효성 검사 오류 코드](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.validator/validationerrorcode) 열거형, 유효성 검사 오류 코드는 각 유효성 검사 규칙에 대해 정의됩니다. 몇 가지 코드는 ContextPeriodNoStartTime, ContextPeriodNoEndTime, ContextPeriodStartAfterEnd, ContextInstantNoTime, ContextScenarioXbrlNamespace, ContextScenarioXbrlSubstitutionGroup 등입니다. 개발자는 최종 사용자의 코드를 디버그 및 표시하거나 문제 해결 방향을 표시할 수 있습니다.

{{% blocks/products/pf/feature-page-code h3="C# iXBRL 문서를 검증하는 코드" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-ixbrl-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}
{{< /blocks/products/pf/feature-page-wrap >}}
---
title: Python을(를) 통해 재무 보고서 확인
url: /ko/python-net/validate/
description:  Python 코드를 사용하여 Python 라이브러리를 통해 XBRL 및 iXBRL 파일의 재무 보고서를 확인합니다.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Python을(를) 통해 Financial Reporting 파일 검증" h2="Python 기반 애플리케이션 내에서 XBRL 및 iXBRL를 포함한 재무 보고서 형식 검증." >}}

{{% blocks/products/pf/feature-page-summary %}}

[.NET을(를) 통해 Python에 대한 Aspose.Finance](https://products.aspose.com/finance/python-net/) 기능이 풍부하고 확장 가능하며 사용하기 쉬운 재무 보고서 처리 API입니다. 개발자는 금융 및 비즈니스 솔루션에 대한 XBRL 및 iXBRL 형식을 쉽게 로드, 검증, 확인 또는 생성할 수 있습니다. API은 XBRL 및 iXBRL 파일을 로드하기 위한 XbrlDocument 클래스 및 InlineXbrlDocument 클래스를 제공합니다.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="XBRL 문서 확인" %}}

데이터가 올바른 구조와 형식인지 확인하는 것과 같은 여러 경우에 XBRL 파일의 유효성 검사가 필요합니다. XBLR 문서의 유효성을 검사하려면 먼저 XbrlDocument 클래스를 사용하여 XBRL 파일을 로드합니다. XbrlInstance 클래스의 validate 메소드를 사용하려면 먼저 XbrlDocument 객체 XbrlInstances를 사용하여 XbrlInstanceCollection을 초기화합니다. 각 XbrlInstance.ValidationErrors를 반복하여 올바른 오류 코드를 얻고 콘솔에 사용자 정의된 오류 메시지를 인쇄하거나 파일 내에 작성하여 적절하게 조치하십시오.

{{% blocks/products/pf/feature-page-code h3="Python XBRL 파일을 검증하는 코드" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "validate-xbrl-instance-file.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="iXBRL 문서 확인" %}}

iXLRB 유효성 검사의 경우 InlineXbrlDocument 클래스를 통해 로드하고 해당 validate() 메서드를 사용합니다. ValidationErrorCode 열거에서 각 유효성 검사 규칙에 대해 유효성 검사 오류 코드가 정의됩니다. 몇 가지 코드는 ContextPeriodNoStartTime, ContextPeriodNoEndTime, ContextPeriodStartAfterEnd, ContextInstantNoTime, ContextScenarioXbrlNamespace, ContextScenarioXbrlSubstitutionGroup 등입니다. 개발자는 최종 사용자의 코드를 디버그 및 표시하거나 문제 해결 방향을 표시할 수 있습니다.

{{% blocks/products/pf/feature-page-code h3="Python iXBRL 문서를 검증하는 코드" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "validate-ixbrl-file.py" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}
{{< /blocks/products/pf/feature-page-wrap >}}
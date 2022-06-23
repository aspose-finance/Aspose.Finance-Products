---
title: Python을(를) 통해 재무 보고서 만들기
url: /ko/python-net/create/
description:  Python 코드를 사용하여 XBRL에 재무 보고서를 만들고 OFX Python 라이브러리를 통해 요청 또는 응답 파일을 만듭니다.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Python을(를) 통해 Financial Reporting 파일 만들기" h2="Python 기반 애플리케이션 내에서 1.03 또는 2.2 형식의 XBRL 및 OFX 요청 또는 응답 파일을 포함한 재무 보고서 형식 생성." >}}

{{% blocks/products/pf/feature-page-summary %}}

[.NET을(를) 통해 Python에 대한 Aspose.Finance](https://products.aspose.com/finance/python-net/) 기능이 풍부하고 확장 가능하며 사용하기 쉬운 재무 보고서 작성 및 처리 API입니다. 개발자는 처음부터 XBRL 인스턴스를 쉽게 생성할 수 있을 뿐만 아니라 스키마 참조, 컨텍스트, 단위, 항목, 각주 링크, 역할 참조 및 
아크 역할 참조. API은 컨텍스트에 대해 개발자가 ContextPeriod, ContextEntity 및 Context를 사용할 수 있는 것과 같이 각 기능에 대한 관련 클래스를 제공합니다. 
또한 API은(는) 1.03 또는 2.2 형식의 개방형 금융 교환(OFX) 형식 요청/응답 생성도 지원합니다.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="항목을 추가하여 XBRL 파일 만들기" %}}

XBRL 파일을 생성하고 문서에 항목을 추가하기 위한 프로세스는 XbrlDocument 클래스 인스턴스를 생성하는 것입니다. SchemaRef 클래스, 위에서 언급한 관련 컨텍스트 클래스 및 개념 클래스와 같은 적절한 API 클래스를 사용하여 항목에 대한 관련 설정을 준비합니다. 마지막으로 Item 클래스 속성을 정의 및 초기화하고 save 메소드를 호출하여 디스크에 XBRL 파일을 생성합니다.

{{% blocks/products/pf/feature-page-code h3="항목을 추가하여 XBRL 파일을 만드는 Python 코드" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-xbrl-file-and-add-item.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="OFX 요청 및 응답 파일 만들기" %}}


OFX 파일을 생성하기 위해 API은 OfxRequestDocument 및 OfxResponseDocument 클래스를 제공하며 개발자는 [OFX 요청 생성](https://products.aspose.com/finance/python-net/create/ofx-request/) 및 1.03 및 2.2 형식의 응답 파일. OfxRequestDocument 속성을 초기화하기 위해 API은 SignonRequest, FinancialInstitution 및 StatementTransactionRequest 클래스와 같은 다른 클래스도 제공합니다. 마찬가지로 OfxResponseDocument 속성을 초기화하기 위해 API은 SignonResponse, StatementTransactionResponse 및 StatementTransaction과 같은 지원 클래스를 제공합니다. 다음은 적절한 적절한 클래스를 사용하는 두 경우 모두에 대한 코드 스니펫입니다.

{{% blocks/products/pf/feature-page-code h3="Python OFX 요청 문서를 생성하는 코드" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python OFX 응답 문서를 생성하는 코드" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
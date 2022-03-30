---
title: .NET을(를) 통해 재무 보고서 만들기
url: /ko/net/create/
description:  C# 코드를 사용하여 XBRL에 재무 보고서를 만들고 OFX .NET 라이브러리를 통해 요청 또는 응답 파일을 만듭니다.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C#을(를) 통해 Financial Reporting 파일 만들기" h2=".NET 기반 애플리케이션 내에서 1.03 또는 2.2 형식의 XBRL 및 OFX 요청 또는 응답 파일을 포함한 재무 보고서 형식 생성." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) 기능이 풍부하고 확장 가능하며 사용하기 쉬운 재무 보고서 작성 및 처리 API입니다. 개발자는 처음부터 XBRL 인스턴스를 쉽게 생성할 수 있을 뿐만 아니라 스키마 참조, 컨텍스트, 단위, 항목, 각주 링크, 역할 참조 및 
아크 역할 참조. API은 개발자가 사용할 수 있는 컨텍스트와 같은 각 기능에 대한 관련 클래스를 제공합니다. [컨텍스트 기간](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextperiod), [컨텍스트 엔터티](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextentity) 그리고 [문맥](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context). 
또한 API은(는) 1.03 또는 2.2 형식의 개방형 금융 교환(OFX) 형식 요청/응답 생성도 지원합니다.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="항목을 추가하여 XBRL 파일 만들기" %}}

XBRL 파일을 생성하고 문서에 항목을 추가하기 위한 프로세스는 다음과 같습니다. [XbrlDocument 클래스](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) 사례. 다음과 같은 적절한 API 클래스를 사용하여 항목에 대한 관련 설정을 준비합니다. [SchemaRef 클래스](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemaref)위에서 언급한 관련 컨텍스트 클래스 및 [컨셉 클래스](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/concept). 마지막으로 정의 및 초기화 [아이템 클래스](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/item) 속성 및 호출 [저장 방법](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) 에게 [생성 XBRL](https://products.aspose.com/finance/net/create/xbrl/) 파일을 디스크에 넣습니다.

{{% blocks/products/pf/feature-page-code h3="항목을 추가하여 XBRL 파일을 만드는 C# 코드" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-item.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="OFX 요청 및 응답 파일 만들기" %}}


OFX 파일을 생성하기 위해 API는 다음을 제공합니다. [Ofx요청 문서](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) 그리고 [OfxResponse문서](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) 클래스와 개발자는 쉽게 [OFX 요청 생성](https://products.aspose.com/finance/net/create/ofx-request/) 및 1.03 및 2.2 형식의 응답 파일. OfxRequestDocument 속성을 초기화하기 위해 API은 다음과 같은 다른 클래스도 제공합니다. [로그인 요청](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [금융 기관](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution) 그리고 [문트랜잭션요청](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest) 클래스. 마찬가지로 OfxResponseDocument 속성을 초기화하기 위해 API는 다음과 같은 지원 클래스를 제공합니다. [로그인 응답](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [문트랜잭션응답](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse) 그리고 [명세서트랜잭션](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction). 다음은 적절한 적절한 클래스를 사용하는 두 경우 모두에 대한 코드 스니펫입니다.

{{% blocks/products/pf/feature-page-code h3="C# OFX 요청 문서를 생성하는 코드" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# OFX 응답 문서를 생성하는 코드" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
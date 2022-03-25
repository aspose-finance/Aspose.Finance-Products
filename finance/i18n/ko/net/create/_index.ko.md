---
title: .NET 을 통해 재무 보고서 작성
url: /ko/net/create/
description:  C# 코드는 XBRL 에서 재무 보고서를 만들고 OFX 는 .NET 라이브러리를 통해 요청 또는 응답 파일을 만듭니다.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# 을 통해 재무보고 파일 만들기" h2="XBRL 및 OFX 을 포함하는 재무 보고서 형식 작성 또는 .NET 기반 응용 프로그램 내에서 1.03 또는 2.2 형식의 응답 파일." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) 풍부하고 확장 가능하며 재무 보고서 작성 및 처리 API 를 사용하기 쉬운 기능입니다. 개발자는 처음부터 쉽게 XBRL 인스턴스를 만들 수있을뿐만 아니라 스키마 참조, 컨텍스트, 단위, 항목, 각주 링크, 역할 참조 및 
아크 역할 참조. API 는 컨텍스트와 같은 각 기능에 대한 관련 클래스를 제공하며 개발자는 사용할 수 있습니다. [Context기간](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextperiod), [ContextEntity](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextentity) 과 [컨텍스트](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context). 
또한 API 은 개방형 금융 거래소 (OFX) 포맷 요청/응답 생성을 1.03 또는 2.2 형식으로 지원합니다.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="항목을 추가하여 XBRL 파일 만들기" %}}

XBRL 파일을 만들고 문서에 항목을 추가하려면 프로세스가 생성됩니다. [XbrlDocument class](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) 인스턴스. 다음과 같은 적절한 API 클래스를 사용하여 항목에 대한 관련 설정을 준비하십시오. [스키마 레프 클래스](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemaref)위에서 언급 한 관련 컨텍스트 클래스 및 [컨셉 클래스](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/concept). 마침내 정의 및 근면 화 [아이템 클래스](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/item) 속성 및 전화 [저장 방법](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) 에 [XBRL 만들기](https://products.aspose.com/finance/net/create/xbrl/) 디스크에 파일.

{{% blocks/products/pf/feature-page-code h3="항목을 추가하여 XBRL 파일을 만드는 C# 코드" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-item.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="OFX 요청 및 응답 파일 만들기" %}}


OFX 파일을 생성하기 위해 API 이 제공합니다. [OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) 과 [OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) 클래스와 개발자는 쉽게 할 수 있습니다. [OFX 요청 생성](https://products.aspose.com/finance/net/create/ofx-request/) 1.03 및 2.2 형식의 응답 파일. OfxRequestDocument 속성을 초기화하기 위해 API 는 다음과 같은 다른 클래스도 제공합니다. [SignonRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [금융 기관](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution) 과 [StatementTransactionRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest) 수업. 유사하게, OfxResponseDocument 속성을 intializing 위해 API 은 다음과 같은 지원 클래스를 제공합니다. [SignonResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [상태 트랜잭션 응답](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse) 과 [상태 거래](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction). 아래는 관련 적절한 클래스를 사용하는 두 경우 모두에 대한 코드 스 니펫입니다.

{{% blocks/products/pf/feature-page-code h3="OFX 요청 문서를 생성하는 C# 코드" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="OFX 응답 문서를 생성하는 C# 코드" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
---
title: C# 을 통해 OFX 요청 파일 생성
description: OFX 요청 파일 생성에 대한 샘플 코드입니다. .NET 기반 응용 프로그램 내에서 배치 OFX 요청 파일 생성에 API 예제 코드를 사용합니다. 
url: /ko/net/create/ofx-request/
family: finance
platformtag: net
feature: create
informat: OFX Request
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# 를 통해 OFX 요청 파일 생성" h2="OFX 는 Microsoft Office를 설치하거나 다른 소프트웨어를 필요로하지 않고 파일 생성을 요청합니다." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="OFX 요청 파일을 만드는 방법" %}}

응용 프로그램 내에서 OFX 요청 파일 생성 요구 사항이 있으면 코드 스니펫의 단계를 따르거나 요구 사항에 따라 향상 시키십시오.

1. 만들기 [OfxRequestDocument class](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) 객체.1. API 에서 제공하는 다른 클래스를 사용하여 관련 속성을 할당합니다. [SignonRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [금융 기관](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution), [StatementTransactionRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest)1. Xml 및 sgml 파일에 각각 ofxv2x 또는 V1x 를 사용하십시오. [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) 저장 방법의 매개 변수로.1. 전화 [저장 방법](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument/methods/save) 대상 파일과 ofxversion을 제공함으로써.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="창조 요구 사항" %}}
OFX 요청 파일 생성을 진행하려면 .NET Finance API 이 보고서 생성 응용 프로그램에 포함되어야 할 주요 요구 사항입니다. 
- 명령 줄을 통해 '''nuget Install Aspose.Finance ''또는 ''install-Package Aspose.Finance'' '가있는 비주얼 스튜디오의 패키지 관리자 콘솔을 통해 설치하십시오.
- 또는 ZIP 파일에서 오프라인 MSI 설치 프로그램 또는 dll을 가져옵니다. [다운로드](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="OFX 요청 파일 생성을위한 C# 코드" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-request-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="다른 생성 옵션" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX 응답 파일" description="1.03 또는 2.2 형식" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL 파일" description="확장 가능한 비즈니스 보고 언어" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
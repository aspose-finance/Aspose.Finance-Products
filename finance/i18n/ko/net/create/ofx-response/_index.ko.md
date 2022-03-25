---
title: C# 을 통해 OFX 응답 파일 생성
description: OFX 응답 파일 생성에 대한 샘플 코드입니다. .NET 기반 응용 프로그램 내에서 배치 OFX 응답 파일 생성에 API 예제 코드를 사용합니다. 
url: /ko/net/create/ofx-response/
family: finance
platformtag: net
feature: create
informat: OFX Response
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# 를 통해 OFX 응답 파일 생성" h2="OFX 응답 파일은 설치된 Microsoft 사무실 또는 다른 소프트웨어를 필요 없이 작성합니다." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="OFX 응답 파일을 만드는 방법" %}}

코드 스니펫의 단계를 따르거나 응용 프로그램 내에서 생성 요구 사항을 가진 후 응용 프로그램의 필요에 따라 향상 시키십시오.

1. 만들기 [OfxResponseDocument 클래스](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) 객체.1. API 에서 제공하는 다른 클래스를 사용하여 관련 속성을 할당합니다. [SignonResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [상태 트랜잭션 응답](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse), [상태 거래](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction)1. Xml 및 sgml 파일에 각각 ofxv2x 또는 V1x 를 사용하십시오. [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) 저장 방법의 매개 변수로.1. 전화 [저장 방법](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument/methods/save) 대상 파일과 ofxversion을 제공함으로써.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="창조 요구 사항" %}}
OFX 응답 파일 생성을 진행하려면 .NET Finance API 이 보고서 생성 응용 프로그램에 포함되어야 할 주요 요구 사항입니다. 
- 명령 줄을 통해 '''nuget Install Aspose.Finance ''또는 ''install-Package Aspose.Finance'' '가있는 비주얼 스튜디오의 패키지 관리자 콘솔을 통해 설치하십시오.
- 또는 ZIP 파일에서 오프라인 MSI 설치 프로그램 또는 dll을 가져옵니다. [다운로드](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="OFX 응답 파일 생성을위한 C# 코드" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="다른 생성 옵션" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX 요청 파일" description="1.03 또는 2.2 형식" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL 파일" description="확장 가능한 비즈니스 보고 언어" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
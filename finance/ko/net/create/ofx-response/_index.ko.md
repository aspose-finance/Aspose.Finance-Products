---
title: C#을(를) 통해 OFX 응답 파일 만들기
description: OFX 응답 파일 생성을 위한 샘플 코드입니다. .NET 기반 애플리케이션 내에서 일괄 OFX 응답 파일 생성을 위해 API 예제 코드를 사용합니다. 
url: /ko/net/create/ofx-response/
family: finance
platformtag: net
feature: create
informat: OFX Response
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C#을(를) 통해 OFX 응답 파일 만들기" h2="OFX Microsoft Office 또는 기타 소프트웨어를 설치하지 않고도 응답 파일을 생성할 수 있습니다." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="OFX 응답 파일을 만드는 방법" %}}

코드 스니펫의 단계를 따르거나 애플리케이션 내에서 생성 요구 사항을 확인한 후 애플리케이션 요구 사항에 따라 코드를 향상시킵니다.

1. 만들다 [OfxResponseDocument 클래스](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) 물체.1. 다음과 같이 API에서 제공하는 다양한 클래스를 사용하여 관련 속성을 할당합니다. [로그인 응답](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [문트랜잭션응답](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse), [명세서트랜잭션](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction)1. xml 및 sgml 파일에 대해 각각 ofxVersion V2x 또는 V1x를 사용하십시오. [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) Save 메소드의 매개변수로.1. 을 부르다 [저장 방법](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument/methods/save) 대상 파일과 ofxVersion을 제공함으로써.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="생성 요구 사항" %}}
OFX 응답 파일 생성을 진행하려면 .NET Finance API이(가) 보고서 생성 애플리케이션에 포함되어야 하는 주요 요구 사항입니다. 
- 명령줄을 통해 ```nuget install Aspose.Finance```로 설치하거나 Visual Studio의 패키지 관리자 콘솔을 통해 ```Install-Package Aspose.Finance```로 설치합니다.
- 또는 ZIP 파일에서 오프라인 MSI 설치 프로그램 또는 DLL을 가져옵니다. [다운로드](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="OFX 응답 파일 생성을 위한 C# 코드" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="기타 생성 옵션" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX 요청 파일" description="1.03 또는 2.2 형식" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL 파일" description="확장 가능한 비즈니스 보고 언어" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
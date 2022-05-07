---
title: C#을(를) 통해 XBRL 파일 만들기
description: XBRL 파일 생성을 위한 샘플 코드입니다. .NET 기반 애플리케이션 내에서 배치 XBRL 파일 생성을 위해 API 예제 코드를 사용하십시오. 
url: /ko/net/create/xbrl/
family: finance
platformtag: net
feature: create
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C#을(를) 통해 XBRL 파일 만들기" h2="XBRL Microsoft Office 또는 기타 소프트웨어를 설치하지 않고도 파일을 생성할 수 있습니다." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="XBRL 파일을 만드는 방법" %}}

코드 스니펫의 단계를 따르거나 확장 가능한 비즈니스 보고 언어 XBRL 파일을 생성하기 위해 애플리케이션 요구에 따라 코드를 향상시키십시오. 애플리케이션 내에 생성 요구 사항이 있는지 확인하십시오.

1. 만들다 [XbrlDocument 클래스](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) 사례.1. 새 XBRL 인스턴스 문서를 만들려면 [XbrlInstanceCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) 그리고 [Xbrl인스턴스](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance).1. 다음을 사용하여 스키마 참조 추가 [스키마 참조 컬렉션](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemarefcollection)1. 응용 프로그램 특성에 따라 컨텍스트, 단위, 항목, 각주 링크 등을 추가합니다.1. 을 부르다 [저장 방법](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) 대상 파일 경로를 제공하여.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="생성 요구 사항" %}}
XBRL 문서 생성을 진행하려면 .NET Finance API이(가) 애플리케이션에 포함되어야 하는 주요 요구사항입니다. 
- 명령줄을 통해 ```nuget install Aspose.Finance```로 설치하거나 Visual Studio의 패키지 관리자 콘솔을 통해 ```Install-Package Aspose.Finance```로 설치합니다.
- 또는 ZIP 파일에서 오프라인 MSI 설치 프로그램 또는 DLL을 가져옵니다. [다운로드](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XBRL 파일 생성을 위한 C# 코드" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-schema-reference.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="기타 생성 옵션" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX 요청" description="1.03 또는 2.2 형식" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX 응답" description="1.03 또는 2.2 형식" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
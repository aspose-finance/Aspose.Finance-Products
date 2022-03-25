---
title: C# 을 통해 XBRL 파일 만들기
description: XBRL 파일 생성을위한 샘플 코드. .NET 기반 응용 프로그램 내에서 배치 XBRL 파일 생성에 API 예제 코드를 사용합니다. 
url: /ko/net/create/xbrl/
family: finance
platformtag: net
feature: create
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# 를 통해 XBRL 파일 만들기" h2="Microsoft 사무실을 설치하거나 다른 소프트웨어를 필요로하지 않고 XBRL 파일 생성." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="XBRL 파일을 만드는 방법" %}}

코드 스니펫의 단계를 따르거나 확장 가능한 비즈니스 보고 언어 XBRL 파일을 생성하기위한 응용 프로그램의 필요에 따라 향상 시키십시오. 응용 프로그램 내에 생성 요구 사항이 있는지 확인하십시오.

1. 만들기 [XbrlDocument class](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) 인스턴스.1. 새 XBRL 인스턴스 문서를 만들려면 [XbrlInstanceCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) 과 [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance).1. 를 사용하여 스키마 참조 추가 [SchemaRefCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemarefcollection)1. 응용 프로그램 특성에 따라 문맥, 단위, 항목, 각주 링크 등을 추가합니다.1. 전화 [저장 방법](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) 대상 파일 경로를 제공합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="창조 요구 사항" %}}
XBRL 문서 생성을 진행하려면 .NET Finance API 가 응용 프로그램 내에 포함되어야 하는 주요 요건입니다. 
- 명령 줄을 통해 '''nuget Install Aspose.Finance ''또는 ''install-Package Aspose.Finance'' '가있는 비주얼 스튜디오의 패키지 관리자 콘솔을 통해 설치하십시오.
- 또는 ZIP 파일에서 오프라인 MSI 설치 프로그램 또는 dll을 가져옵니다. [다운로드](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XBRL 파일 생성을위한 C# 코드" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-schema-reference.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="다른 생성 옵션" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX 요청" description="1.03 또는 2.2 형식" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX 응답" description="1.03 또는 2.2 형식" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
---
title: C# 을 통해 XBRL 파일 읽기
description: XBRL 파일 읽기에 대한 샘플 코드입니다. API 예제 코드를 사용하여 .NET 기반 응용 프로그램 내에서 배치 XBRL 파일을 읽습니다. 
url: /ko/net/read/xbrl/
family: finance
platformtag: net
feature: read
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# 을 통해 XBRL 파일 읽기" h2="마이크로 소프트 오피스를 설치하거나 다른 소프트웨어를 필요로하지 않고 XBRL 형식의 재무 보고서를 읽습니다." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="XBRL 파일을 읽는 방법" %}}

코드 스니펫의 단계를 따르거나 확장 가능한 비즈니스 보고 언어 XBRL 파일을 읽기 위한 응용 프로그램의 필요에 따라 향상 시키십시오. 응용 프로그램 내에서 독서 요구 사항이 있는지 확인하십시오.

1. 만들기 [XbrlDocument class](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) 인스턴스.1. 유효한 XBRL 파일의 이름을 매개 변수로 전달합니다.1. 파일의 내부 세부 사항을 얻으려면 다음과 같은 관련 클래스를 사용하십시오. [SchemaRefCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemarefcollection), [컨텍스트](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context), [단위](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/unit) 
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="독서 요구 사항" %}}
XBRL 문서를 읽기 위해 진행하려면 .NET Finance API 가 응용 프로그램에 포함되어야하는 주요 요구 사항입니다. 
- 명령 줄을 통해 '''nuget Install Aspose.Finance ''또는 ''install-Package Aspose.Finance'' '가있는 비주얼 스튜디오의 패키지 관리자 콘솔을 통해 설치하십시오.
- 또는 ZIP 파일에서 오프라인 MSI 설치 프로그램 또는 dll을 가져옵니다. [다운로드](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XBRL 파일을 읽는 C# 코드" offSpacer="" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "read-xbrl-file.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="다른 독서 옵션" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/read/ixbrl/" name="iXBRL" description="인라인 확장 가능한 비즈니스 보고 언어" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
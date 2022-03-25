---
title: C# 을 통해 XBRL 파일 유효성 검사
description: XBRL 파일 유효성 검사 용 샘플 코드입니다. API 예제 코드를 사용하여 .NET 기반 응용 프로그램 내에서 배치 XBRL 파일을 확인합니다. 
url: /ko/net/validate/xbrl/
family: finance
platformtag: net
feature: validate
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# 을 통해 XBRL 파일 유효성 검사" h2="마이크로 소프트 오피스를 설치하거나 다른 소프트웨어를 필요로하지 않고 XBRL 형식으로 재무 보고서를 검증합니다." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="XBRL 파일을 확인하는 방법" %}}

코드 스니펫의 단계를 따르거나 확장 가능한 비즈니스 보고 언어 XBRL 문서를 검증하기 위한 응용 프로그램 요구 사항에 따라 개선하십시오. 응용 프로그램 내에서 검증 요구 사항이 있는지 확인하십시오.

1. 를 사용하여 XBRL 파일을 로드 [XbrlDocument class](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) 인스턴스.1. 로드 된 파일의 유효성을 확인하여 일치해야합니다. [XBRL 사양](http://www.xbrl.org/specification/inlinexbrl-part1/rec-2013-11-18/inlinexbrl-part1-rec-2013-11-18.html)1. 유효성을 확인하려면 사용 [검증 ()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) 의 방법 [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) 수업.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="검증 요건" %}}
XBRL 문서 유효성 검사를 진행하려면 .NET Finance API 이 응용 프로그램 내에 포함되어야 하는 주요 요건입니다. 
- 명령 줄을 통해 '''nuget Install Aspose.Finance ''또는 ''install-Package Aspose.Finance'' '가있는 비주얼 스튜디오의 패키지 관리자 콘솔을 통해 설치하십시오.
- 또는 ZIP 파일에서 오프라인 MSI 설치 프로그램 또는 dll을 가져옵니다. [다운로드](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XBRL 파일을 확인하는 C# 코드" offSpacer="" %}}

{{< gist "aspose-com-gists" "1272da1f804f8cef122600269db09fbb" "validate-xbrl-instance-file.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="다른 검증 옵션" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/validate/ixbrl/" name="XBRL" description="인라인 확장 가능한 비즈니스 보고 언어" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
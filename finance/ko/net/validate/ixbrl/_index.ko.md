---
title: C#을(를) 통해 iXBRL 파일 유효성 검사
description: iXBRL 파일 유효성 검사를 위한 샘플 코드입니다. API 예제 코드를 사용하여 .NET 기반 애플리케이션 내에서 배치 iXBRL 파일의 유효성을 검사합니다. 
url: /ko/net/validate/ixbrl/
family: finance
platformtag: net
feature: validate
informat: iXBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C#을(를) 통해 iXBRL 파일 유효성 검사" h2="Microsoft Office 또는 기타 소프트웨어를 설치하지 않고도 iXBRL 형식으로 재무 보고서를 검증합니다." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="iXBRL 파일을 확인하는 방법" %}}

코드 스니펫의 단계를 따르거나 확장 가능한 비즈니스 보고 언어 iXBRL 문서의 유효성을 검사하기 위해 애플리케이션 요구에 따라 코드를 향상시키십시오. 신청서에 검증 요구 사항이 있는지 확인하십시오.

1. 다음을 사용하여 iXBRL 파일 로드 [InlineXbrlDocument 클래스](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) 사례.1. 로드된 파일의 유효성을 확인하려면 다음과 일치해야 합니다. [iXBRL 사양](http://www.xbrl.org/specification/inlinexbrl-part1/rec-2013-11-18/inlinexbrl-part1-rec-2013-11-18.html)1. 사용 [확인()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument/methods/validate) 파일 유효성을 위한 방법.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="검증 요구 사항" %}}
iXBRL 문서의 유효성 검사를 진행하려면 .NET Finance API이(가) 애플리케이션에 포함되어야 하는 주요 요구 사항입니다. 
- 명령줄을 통해 ```nuget install Aspose.Finance```로 설치하거나 Visual Studio의 패키지 관리자 콘솔을 통해 ```Install-Package Aspose.Finance```로 설치합니다.
- 또는 ZIP 파일에서 오프라인 MSI 설치 프로그램 또는 DLL을 가져옵니다. [다운로드](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="iXBRL 파일의 유효성을 검사하는 C# 코드" offSpacer="" %}}

{{< gist "aspose-com-gists" "1272da1f804f8cef122600269db09fbb" "validate-ixbrl-file.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="기타 검증 옵션" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/validate/xbrl/" name="XBRL" description="확장 가능한 비즈니스 보고 언어" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
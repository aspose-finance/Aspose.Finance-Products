---
title: C#을(를) 통해 iXBRL 파일 보기
description: iXBRL 파일 보기를 위한 샘플 코드입니다. API 예제 코드를 사용하여 .NET 기반 애플리케이션 내에서 배치 iXBRL 파일을 봅니다. 
url: /ko/net/view/ixbrl/
family: finance
platformtag: net
feature: view
informat: iXBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C#을(를) 통해 iXBRL 파일 보기" h2="Microsoft Office나 다른 소프트웨어를 설치하지 않고도 iXBRL 형식으로 재무 보고서를 볼 수 있습니다." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="iXBRL 파일을 보는 방법" %}}

코드 스니펫의 단계를 따르거나 확장 가능한 비즈니스 보고 언어 iXBRL 문서를 보기 위해 애플리케이션 요구에 따라 코드를 향상시키십시오. 지원서에 읽기 요구 사항이 있는지 확인하십시오.

1. 만들다 [InlineXbrlDocument 클래스](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) 사례.2. 유효한 iXBRL 파일의 이름을 매개변수로 전달합니다.
3. 파일의 내부 세부 정보를 얻으려면 다음과 같은 관련 클래스를 사용하십시오. [인라인팩트](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinefact), [문맥](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context), [단위](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/unit) 
4. 이 정보를 보여주세요

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="읽기 요구 사항" %}}
iXBRL 문서 보기를 계속하려면 .NET Finance API이(가) 애플리케이션에 포함되어야 하는 주요 요구 사항입니다. 
- 명령줄을 통해 ```nuget install Aspose.Finance```로 설치하거나 Visual Studio의 패키지 관리자 콘솔을 통해 ```Install-Package Aspose.Finance```로 설치합니다.
- 또는 ZIP 파일에서 오프라인 MSI 설치 프로그램 또는 DLL을 가져옵니다. [다운로드](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="iXBRL 파일을 읽는 C# 코드" offSpacer="" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "read-ixbrl-file.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="기타 보기 옵션" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/view/xbrl/" name="XBRL" description="확장 가능한 비즈니스 보고 언어" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
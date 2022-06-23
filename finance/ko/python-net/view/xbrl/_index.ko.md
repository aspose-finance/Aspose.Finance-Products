---
title: Python을(를) 통해 XBRL 파일 보기
description: XBRL 파일 보기를 위한 샘플 코드입니다. API 예제 코드를 사용하여 Python 기반 애플리케이션 내에서 배치 XBRL 파일을 봅니다. 
url: /ko/python-net/view/xbrl/
family: finance
platformtag: python
feature: view
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Python을(를) 통해 XBRL 파일 보기" h2="Microsoft Office나 다른 소프트웨어를 설치하지 않고도 XBRL 형식으로 재무 보고서를 볼 수 있습니다." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="XBRL 파일을 보는 방법" %}}

코드 스니펫의 단계를 따르거나 확장 가능한 비즈니스 보고 언어 XBRL 파일을 읽기 위한 애플리케이션 요구에 따라 코드를 향상시키십시오. 지원서에 읽기 요구 사항이 있는지 확인하십시오.

1. XbrlDocument 클래스 인스턴스를 만듭니다.2. 유효한 XBRL 파일의 이름을 매개변수로 전달합니다.
3. 파일의 내부 정보를 얻으려면 SchemaRefCollection, Context, Unit과 같은 관련 클래스를 사용하십시오.
4. 이 정보를 보여주세요

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="읽기 요구 사항" %}}
XBRL 문서 보기를 계속하려면 다음 전제 조건이 있는지 확인하십시오. 
- Microsoft Windows 또는 Linux 기반 OS.- Python 3.5 이상.- 프로젝트에서 참조된 Python에 대한 Aspose.Finance.{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XBRL 파일을 읽는 Python 코드" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "read-xbrl-file.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="기타 보기 옵션" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/view/ixbrl/" name="iXBRL" description="인라인 확장 가능한 비즈니스 보고 언어" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
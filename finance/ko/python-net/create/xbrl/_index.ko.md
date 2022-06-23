---
title: Python을(를) 통해 XBRL 파일 만들기
description: XBRL 파일 생성을 위한 샘플 코드입니다. Python 기반 애플리케이션 내에서 배치 XBRL 파일 생성을 위해 API 예제 코드를 사용하십시오. 
url: /ko/python-net/create/xbrl/
family: finance
platformtag: python
feature: create
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Python을(를) 통해 XBRL 파일 만들기" h2="XBRL Microsoft Office 또는 기타 소프트웨어를 설치하지 않고도 파일을 생성할 수 있습니다." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="XBRL 파일을 만드는 방법" %}}

코드 스니펫의 단계를 따르거나 확장 가능한 비즈니스 보고 언어 XBRL 파일을 생성하기 위해 애플리케이션 요구에 따라 코드를 향상시키십시오. 애플리케이션 내에 생성 요구 사항이 있는지 확인하십시오.

1. XbrlDocument 클래스 인스턴스를 만듭니다.1. 새 XBRL 인스턴스 문서를 생성하려면 XbrlInstanceCollection 및 XbrlInstance.1. SchemaRefCollection을 사용하여 스키마 참조 추가1. 응용 프로그램 특성에 따라 컨텍스트, 단위, 항목, 각주 링크 등을 추가합니다.1. 대상 파일 경로를 제공하여 save 메소드를 호출하십시오.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="생성 요구 사항" %}}
XBRL 문서 생성을 진행하려면 다음 전제 조건이 있는지 확인하십시오. 
- Microsoft Windows 또는 Linux 기반 OS.- Python 3.5 이상.- 프로젝트에서 참조된 Python에 대한 Aspose.Finance.{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XBRL 파일 생성을 위한 Python 코드" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-xbrl-file-and-add-schema-reference.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="기타 생성 옵션" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-request/" name="OFX 요청" description="1.03 또는 2.2 형식" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-response/" name="OFX 응답" description="1.03 또는 2.2 형식" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
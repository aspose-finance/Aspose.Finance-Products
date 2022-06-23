---
title: Python을(를) 통해 OFX 응답 파일 만들기
description: OFX 응답 파일 생성을 위한 샘플 코드입니다. Python 기반 애플리케이션 내에서 일괄 OFX 응답 파일 생성을 위해 API 예제 코드를 사용합니다. 
url: /ko/python-net/create/ofx-response/
family: finance
platformtag: python
feature: create
informat: OFX Response
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Python을(를) 통해 OFX 응답 파일 만들기" h2="OFX Microsoft Office 또는 기타 소프트웨어를 설치하지 않고도 응답 파일을 생성할 수 있습니다." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="OFX 응답 파일을 만드는 방법" %}}

코드 스니펫의 단계를 따르거나 애플리케이션 내에서 생성 요구 사항을 확인한 후 애플리케이션 요구 사항에 따라 코드를 향상시킵니다.

1. OfxResponseDocument 클래스 개체를 만듭니다.1. SignonResponse, StatementTransactionResponse, StatementTransaction과 같이 API에서 제공하는 다양한 클래스를 사용하여 관련 속성을 할당합니다.1. 저장 메소드의 매개변수로 OfxVersionEnum의 ofxVersion V2x 또는 V1x를 xml 및 sgml 파일에 각각 사용합니다.1. 대상 파일과 ofxVersion을 제공하여 save 메소드를 호출합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="생성 요구 사항" %}}
OFX 응답 파일 생성을 진행하려면 다음 전제 조건이 있는지 확인하십시오. 
- Microsoft Windows 또는 Linux 기반 OS.- Python 3.5 이상.- 프로젝트에서 참조된 Python에 대한 Aspose.Finance.{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="OFX 응답 파일 생성을 위한 Python 코드" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="기타 생성 옵션" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-request/" name="OFX 요청 파일" description="1.03 또는 2.2 형식" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/xbrl/" name="XBRL 파일" description="확장 가능한 비즈니스 보고 언어" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}
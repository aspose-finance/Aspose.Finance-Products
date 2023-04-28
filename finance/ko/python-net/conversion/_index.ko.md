---
title: Python을(를) 통해 재무 보고서 변환
url: /ko/python-net/conversion/
description:  Python 코드는 Python 라이브러리를 통해 XBRL, iXBRL(인라인 xbrl) 및 OFX 파일 형식의 재무 보고서를 변환합니다.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Python을(를) 통해 재무 보고서 파일 변환" h2="재무 보고서 형식 변환은 XBRL, iXBRL 및 OFX 파일을 Python 기반 애플리케이션 내에서 1.03에서 2.2 형식으로 변환합니다." >}}

{{% blocks/products/pf/feature-page-summary %}}

[.NET을(를) 통해 Python에 대한 Aspose.Finance](https://products.aspose.com/finance/python-net/) 기능이 풍부하고 확장 가능하며 사용하기 쉬운 API입니다. 개발자는 사양에 부과된 구문 요구 사항을 준수해야 하는 validate() 메서드를 사용하여 XBRL 인스턴스, 링크 베이스 및 분류 스키마를 쉽게 확인할 수 있습니다. 또한 XBRL, iXBRL 형식을 읽고 처음부터 XBRL 인스턴스를 생성할 수 있습니다. 또한 **XBRL 형식**을 iXBRL 및 Microsoft Excel XLSX 파일로 변환할 수 있습니다. API은 또한 개방형 금융 교환(OFX) 형식 요청/응답 생성을 지원하고 OFX 파일 요청/응답을 1.03에서 2.2 형식으로 변환합니다.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="OFX 응답 및 요청 파일 변환" %}}

API은(는) 두 개의 클래스를 제공하여 OFX 요청 및 응답 파일 생성을 지원합니다. 1.03 및 2.2 형식의 OFX 요청 파일을 만들고 로드하기 위한 OfxRequestDocument와 1.03 및 2.2 형식의 OFX 응답 파일을 위한 OfxResponseDocument. 또한 OfxVersionEnum 1.x 버전, sgml 파일 형식 및 V2x 2.x 버전, xml 파일 형식인 V1x 멤버를 갖는 열거형입니다. OfxRequestDocument 클래스 또는 OfxResponseDocument 클래스의 save 메소드를 호출한 후 개발자는 1.03 sgml 파일에서 2.2 xml 형식으로 쉽게 변환할 수 있습니다.


{{% blocks/products/pf/feature-page-code h3="C# OFX 응답 파일을 변환하는 코드" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-ofx-response-from-1.03-to-2.2.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# OFX 요청 파일을 변환하는 코드" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-ofx-request-from-1.03-to-2.2.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL 재무 보고서 변환" %}}

API은(는) XBRL 파일을 iXBRL 및 Microsoft® Excel XLSX 형식으로 변환하는 것을 지원합니다. 변환 프로세스는 간단합니다. 먼저 XbrlDocument 클래스를 통해 파일을 로드합니다. SaveFormat에는 SaveOptions 클래스를 사용하여 XbrlDocument 클래스의 저장 메소드에서 매개변수로 사용합니다. iXBLR 파일로 저장할 때는 SaveFormat.IXBRL을 사용하고 XLSX 형식으로 내보낼 때는 SaveFormat.XLSX를 사용합니다.

{{% blocks/products/pf/feature-page-code h3="Python XBRL을(를) iXBRL(으)로 내보낼 코드" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-xbrl-to-ixbrl.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="XBRL에서 XLSX로의 변환을 위한 Python 코드" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-xbrl-to-xlsx.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}
{{< /blocks/products/pf/feature-page-wrap >}}
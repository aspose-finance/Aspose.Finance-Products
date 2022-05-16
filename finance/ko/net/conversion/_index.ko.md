---
title: .NET을(를) 통해 재무 보고서 변환
url: /ko/net/conversion/
description:  C# 코드는 .NET 라이브러리를 통해 XBRL, iXBRL(인라인 xbrl) 및 OFX 파일 형식의 재무 보고서를 변환합니다.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C#을(를) 통해 재무 보고서 파일 변환" h2="재무 보고서 형식 변환은 XBRL, iXBRL 및 OFX 파일을 .NET 기반 애플리케이션 내에서 1.03에서 2.2 형식으로 변환합니다." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) 기능이 풍부하고 확장 가능하며 사용하기 쉬운 API입니다. 개발자는 다음을 사용하여 XBRL 인스턴스, 링크베이스 및 분류 스키마를 쉽게 검증할 수 있습니다. [validate() 메서드](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) 사양에 부과된 구문 요구 사항을 준수해야 합니다. 또한 XBRL, iXBRL 형식을 읽고 처음부터 XBRL 인스턴스를 생성할 수 있습니다. 또한 **XBRL 형식**을 iXBRL 및 Microsoft Excel XLSX 파일로 변환할 수 있습니다. API는 또한 개방형 금융 교환(OFX) 형식 요청/응답 생성을 지원하고 OFX 파일 요청/응답을 1.03에서 2.2 형식으로 변환합니다.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="OFX 응답 및 요청 파일 변환" %}}

API은(는) 두 개의 클래스를 제공하여 OFX 요청 및 응답 파일 생성을 지원합니다. [Ofx요청 문서](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) 1.03 및 2.2 형식의 OFX 요청 파일 생성 및 로드 [OfxResponse문서](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) 1.03 및 2.2 형식의 OFX 응답 파일용. 또한, [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) 1.x 버전, sgml 파일 형식 및 V2x 2.x 버전, xml 파일 형식인 V1x 멤버가 있는 열거. OfxRequestDocument 클래스 또는 OfxResponseDocument 클래스의 Save 메서드를 호출한 후 개발자는 1.03 sgml 파일에서 2.2 xml 형식으로 쉽게 변환할 수 있습니다.


{{% blocks/products/pf/feature-page-code h3="C# OFX 응답 파일을 변환하는 코드" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-response-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# OFX 요청 파일을 변환하는 코드" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-request-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL 재무 보고서 변환" %}}

API은(는) XBRL 파일을 iXBRL 및 Microsoft® Excel XLSX 형식으로 변환하는 것을 지원합니다. 변환 프로세스는 간단합니다. 먼저 다음을 통해 파일을 로드합니다. [XbrlDocument 클래스](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument). 사용 [SaveOptions 클래스](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions) ~을위한 [저장 형식](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions/properties/saveformat), XbrlDocument 클래스의 Save 메소드에서 매개변수로 사용됩니다. iXBLR 파일로 저장하려면, [저장 형식.IXBRL](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveformat) 사용되며 XLSX 형식으로 내보내는 경우 SaveFormat.XLSX가 사용됩니다.

{{% blocks/products/pf/feature-page-code h3="C# XBRL을(를) iXBRL(으)로 내보낼 코드" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-ixbrl.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="XBRL에서 XLSX로의 변환을 위한 C# 코드" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-xlsx.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}
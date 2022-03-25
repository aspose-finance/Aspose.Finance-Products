---
title: .NET 을 통해 재무 보고서 변환
url: /ko/net/conversion/
description:  C# 코드는 XBRL, iXBRL 및 OFX 파일 fomats에서 .NET 라이브러리를 통해 재무 보고서를 변환합니다.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# 을 통해 재무 보고서 파일 변환" h2=".NET 기반 응용 프로그램 내에서 XBRL, iXBRL 및 OFX 파일을 1.03 2.2 형식으로 변환하는 재무 보고서 형식." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) 기능이 풍부하고 확장 가능하며 사용하기 쉬운 API 입니다. 개발자는 쉽게 XBRL 인스턴스, 링크 베이스 및 분류 스키마를 확인할 수 있습니다. [Validate () 방법](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) 사양에 부과 된 구문 요구 사항을 준수해야합니다. 또한 XBRL, iXBRL 형식을 읽고 처음부터 XBRL 인스턴스를 만들 수 있습니다. 또한 XBRL 형식 ** 을 iXBRL 및 Microsoft 엑셀 XLSX 파일로 변환 할 수 있습니다. API 는 또한 개방형 금융 교환 (OFX) 형식 요청/응답 생성을 지원하고 OFX 파일 요청/응답을 1.03 2.2 형식으로 변환합니다.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="OFX 응답 및 요청 파일 변환" %}}

API 은 두 클래스를 제공하여 OFX 요청 및 응답 파일 생성을 지원합니다. [OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) OFX 요청 파일을 1.03 및 2.2 형식으로 만들고 로드하기 [OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) 1.03 및 2.2 형식의 OFX 응답 파일의 경우. 게다가, [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) 1.x 버전, sgml 파일 형식 및 V2x 2.x 버전, xml 파일 형식 인 V1x 멤버가있는 열거. OfxRequestDocument class 또는 OfxResponseDocument 클래스의 저장 방법을 호출 한 후 개발자는 1.03 sgml 파일에서 2.2 xml 형식으로 쉽게 변환 할 수 있습니다.


{{% blocks/products/pf/feature-page-code h3="OFX 응답 파일을 변환하는 C# 코드" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-response-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="OFX 요청 파일을 변환하는 C# 코드" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-request-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL 재무 보고서 전환" %}}

API XBRL 파일을 iXBRL 및 microsoft로 변환 지원®엑셀 XLSX 형식. 변환 프로세스는 간단합니다. 먼저 파일을 통해 [XbrlDocument Class](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument). 사용 [SaveOptions 클래스](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions) 를 위해 [세이브 포맷](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions/properties/saveformat), XbrlDocument 클래스의 저장 방법에서 매개 변수로 사용됩니다. IXBLR 파일에 저장하기 위해, [Saveprant. IXBRL](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveformat) 사용되며 XLSX 형식으로 내보내기 위해 savewarch. Xlsx가 사용됩니다.

{{% blocks/products/pf/feature-page-code h3="XBRL 을 iXBRL 로 내보내는 C# 코드" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-ixbrl.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="XBRL 에서 XLSX 변환에 대한 C# 코드" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-xlsx.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}
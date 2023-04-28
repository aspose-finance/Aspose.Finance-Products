---
title: .NETを介して財務レポートを変換する
url: /ja/net/conversion/
description:  .NETライブラリを介してXBRL、iXBRL（インラインxbrl）、およびOFXファイル形式の財務レポートを変換するためのC#コード。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C#を介して財務レポートファイルを変換する" h2=".NETベースのアプリケーション内で、XBRL、iXBRL、およびOFXファイルを含む1.03から2.2形式への財務レポート形式の変換。" >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) は機能が豊富で、拡張可能で、使いやすいAPIです。開発者は、次を使用してXBRLインスタンス、リンクベース、および分類スキーマを簡単に検証できます。 [validate（）メソッド](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) これは、仕様で課せられた構文要件に準拠する必要があります。さらに、XBRL、iXBRL形式を読み取ったり、XBRLインスタンスを最初から作成したりできます。さらに、**XBRL形式**をiXBRLおよびMicrosoftExcelXLSXファイルに変換できます。 APIは、Open Financial Exchange（OFX）形式の要求/応答の作成もサポートし、OFXファイルの要求/応答を1.03から2.2形式に変換します。

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="OFX応答ファイルと要求ファイルを変換する" %}}

APIは、2つのクラスを提供することにより、OFX要求ファイルと応答ファイルの作成をサポートします。 [OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) 1.03および2.2形式のOFXリクエストファイルを作成およびロードするため [OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) 1.03および2.2形式のOFX応答ファイルの場合。さらに、 [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) 1.xバージョンのsgmlファイル形式のメンバーV1xとV2x2.xバージョンのxmlファイル形式のメンバーを持つ列挙。 OfxRequestDocumentクラスまたはOfxResponseDocumentクラスのSaveメソッドを呼び出した後、開発者は1.03sgmlファイルから2.2xml形式に簡単に変換できます。


{{% blocks/products/pf/feature-page-code h3="C#変換するコードOFX応答ファイル" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-response-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C#変換するコードOFXリクエストファイル" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-request-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL財務レポートの変換" %}}

APIは、XBRLファイルのiXBRLおよびMicrosoft®ExcelXLSX形式への変換をサポートしています。変換プロセスは簡単です。最初にファイルをロードします。 [XbrlDocumentクラス](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument)。使用 [SaveOptionsクラス](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions) 為に [SaveFormat](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions/properties/saveformat)、XbrlDocumentクラスのSaveメソッドのパラメーターとして使用されます。 iXBLRファイルに保存するには、 [SaveFormat.IXBRL](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveformat) が使用され、XLSX形式にエクスポートするには、SaveFormat.XLSXが使用されます。

{{% blocks/products/pf/feature-page-code h3="C#XBRLをiXBRLにエクスポートするコード" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-ixbrl.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C#XBRLからXLSXへの変換のコード" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-xlsx.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}
{{< /blocks/products/pf/feature-page-wrap >}}
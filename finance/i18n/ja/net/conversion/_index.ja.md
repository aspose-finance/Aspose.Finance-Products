---
title: .NET 経由で財務レポートを変換する
url: /ja/net/conversion/
description:  .NET ライブラリを介して XBRL 、 iXBRL 、および OFX ファイルの財務レポートを変換するための C# コード。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# 経由で財務レポートファイルを変換する" h2=".NET ベースのアプリケーション内で、 XBRL 、 iXBRL 、および OFX ファイルを1.03から2.2形式に変換する財務レポート。" >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) は、機能が豊富で拡張可能で使いやすい API です。開発者は、を使用して XBRL 個のインスタンス、リンクベース、および分類スキーマを簡単に検証できます。 [Validate () メソッド](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) 仕様で課せられた構文要件に準拠する必要があります。さらに、 XBRL 、 iXBRL 形式を読み取り、 XBRL インスタンスをゼロから作成できます。さらに、 XBRL 形式 ** を iXBRL およびMicrosoft Excel XLSXファイルに ** 変換できます。 API は、オープンファイナンシャルエクスチェンジ (OFX) 形式のリクエスト/レスポンスの作成もサポートしており、 OFX ファイルのリクエスト/レスポンスを1.03形式から2.2形式に変換します。

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="OFX 応答および要求ファイルを変換する" %}}

API は、2つのクラスを提供することにより、 OFX のリクエストおよびレスポンスファイルの作成をサポートしています。 [OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) OFX リクエストファイルを1.03および2.2形式で作成およびロードし、 [OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) 1.03および2.2形式の OFX 応答ファイルに対してさらに、 [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) メンバーV1xが1.xバージョン、sgmlファイル形式、およびV2x 2.xバージョン、xmlファイル形式の列挙。OfxRequestDocumentクラスまたはOfxResponseDocumentクラスのSaveメソッドを呼び出した後、開発者は1.03 sgmlファイルから2.2xml形式に簡単に変換できます。


{{% blocks/products/pf/feature-page-code h3="C# 応答ファイルを変換するコード OFX" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-response-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# リクエストファイルを変換するコード OFX" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-request-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL 財務レポートの変換" %}}

API は XBRL ファイルの iXBRL とMicrosoftへの変換をサポートしています®Excel XLSX形式。変換プロセスは簡単です。まず、 [XbrlDocumentクラス](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument)を使用します。を使用します。 [SaveOptionsクラス](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions) のための [SaveFormat](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions/properties/saveformat)、XbrlDocument ClassのSaveメソッドでパラメーターとして使用します。IXBLRファイルに保存するには、 [SaveFormat.IXBRL](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveformat) が使用され、XLSX形式にエクスポートするには、SaveFormat.XLSXが使用されます。

{{% blocks/products/pf/feature-page-code h3="C# XBRL を iXBRL にエクスポートするコード" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-ixbrl.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="XBRL からXLSXへの変換の C# コード" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-xlsx.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}
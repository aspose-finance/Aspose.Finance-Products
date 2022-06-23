---
title: Pythonを介して財務レポートを変換する
url: /ja/python-net/conversion/
description:  Pythonライブラリを介してXBRL、iXBRL（インラインxbrl）、およびOFXファイル形式の財務レポートを変換するためのPythonコード。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Pythonを介して財務レポートファイルを変換する" h2="Pythonベースのアプリケーション内で、XBRL、iXBRL、およびOFXファイルを含む1.03から2.2形式への財務レポート形式の変換。" >}}

{{% blocks/products/pf/feature-page-summary %}}

[.NET経由のPythonの場合はAspose.Finance](https://products.aspose.com/finance/python-net/) は機能が豊富で、拡張可能で、使いやすいAPIです。開発者は、仕様で課せられた構文要件に準拠する必要があるvalidate（）メソッドを使用して、XBRLインスタンス、リンクベース、および分類スキーマを簡単に検証できます。さらに、XBRL、iXBRL形式を読み取るだけでなく、XBRLインスタンスを最初から作成することもできます。さらに、**XBRL形式**をiXBRLおよびMicrosoftExcelXLSXファイルに変換できます。 APIは、Open Financial Exchange（OFX）形式の要求/応答の作成もサポートし、OFXファイルの要求/応答を1.03から2.2形式に変換します。

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="OFX応答ファイルと要求ファイルを変換する" %}}

APIは、2つのクラスを提供することにより、OFX要求ファイルと応答ファイルの作成をサポートします。 1.03および2.2形式のOFXリクエストファイルを作成およびロードするためのOfxRequestDocumentと、1.03および2.2形式のOFX応答ファイル用のOfxResponseDocument。さらに、1.xバージョンのsgmlファイル形式のメンバーV1xとV2x2.xバージョンのxmlファイル形式のメンバーを持つOfxVersionEnum列挙。 OfxRequestDocumentクラスまたはOfxResponseDocumentクラスのsaveメソッドを呼び出した後、開発者は1.03sgmlファイルから2.2xml形式に簡単に変換できます。


{{% blocks/products/pf/feature-page-code h3="C#変換するコードOFX応答ファイル" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-ofx-response-from-1.03-to-2.2.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C#変換するコードOFXリクエストファイル" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-ofx-request-from-1.03-to-2.2.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL財務レポートの変換" %}}

APIは、XBRLファイルのiXBRLおよびMicrosoft®ExcelXLSX形式への変換をサポートしています。変換プロセスは簡単です。最初にXbrlDocumentクラスを介してファイルをロードします。 XbrlDocumentクラスのsaveメソッドのパラメーターとして使用されるSaveFormatのSaveOptionsクラスを使用します。 iXBLRファイルに保存するには、SaveFormat.IXBRLが使用され、XLSX形式にエクスポートするには、SaveFormat.XLSXが使用されます。

{{% blocks/products/pf/feature-page-code h3="PythonXBRLをiXBRLにエクスポートするコード" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-xbrl-to-ixbrl.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="PythonXBRLからXLSXへの変換のコード" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-xbrl-to-xlsx.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}
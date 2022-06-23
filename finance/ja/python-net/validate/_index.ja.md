---
title: Pythonを介して財務レポートを検証する
url: /ja/python-net/validate/
description:  Pythonライブラリを介してXBRLおよびiXBRLファイルの財務レポートを検証するためのPythonコード。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Pythonを介して財務報告ファイルを検証する" h2="Pythonベースのアプリケーション内のXBRLおよびiXBRLを含む財務レポート形式の検証。" >}}

{{% blocks/products/pf/feature-page-summary %}}

[.NET経由のPythonの場合はAspose.Finance](https://products.aspose.com/finance/python-net/) は、豊富で拡張性があり、使いやすい財務レポート処理APIの機能です。開発者は、金融およびビジネスソリューション用のXBRLおよびiXBRL形式を簡単にロード、検証、表示、または作成できます。 APIは、XBRLおよびiXBRLファイルをロードするためのXbrlDocumentクラスとInlineXbrlDocumentクラスを提供します。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="XBRLドキュメントを検証する" %}}

XBRLファイルの検証は、データが正しい構造と形式であるかどうかを確認するなど、多くの場合に必要です。 XBLRドキュメントを検証するには、最初にXbrlDocumentクラスを使用してXBRLファイルをロードします。 XbrlInstanceクラスのvalidateメソッドを使用するには、最初にXbrlInstanceCollectionをXbrlDocumentオブジェクトXbrlInstancesで初期化します。各XbrlInstance.ValidationErrorsを繰り返して正しいエラーコードを取得し、それに応じて、カスタマイズされたエラーメッセージをコンソールに出力するか、ファイルに書き込みます。

{{% blocks/products/pf/feature-page-code h3="PythonXBRLファイルを検証するためのコード" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "validate-xbrl-instance-file.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="iXBRLドキュメントを検証する" %}}

iXLRB検証の場合は、InlineXbrlDocumentクラスを介してロードし、そのvalidate（）メソッドを使用します。 ValidationErrorCode列挙では、検証ルールごとに検証エラーコードが定義されます。 ContextPeriodNoStartTime、ContextPeriodNoEndTime、ContextPeriodStartAfterEnd、ContextInstantNoTime、ContextScenarioXbrlNamespace、ContextScenarioXbrlSubstitutionGroupなどのコードはほとんどありません。開発者は、エンドユーザーの時点でコードをデバッグおよび表示したり、問題を解決するための方向性を示したりできます。

{{% blocks/products/pf/feature-page-code h3="Python検証するコードiXBRLドキュメント" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "validate-ixbrl-file.py" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}
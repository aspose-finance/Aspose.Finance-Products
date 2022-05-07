---
title: .NETを介して財務レポートを検証する
url: /ja/net/validate/
description:  .NETライブラリを介してXBRLおよびiXBRLファイルの財務レポートを検証するためのC#コード。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C#を介して財務報告ファイルを検証する" h2=".NETベースのアプリケーション内のXBRLおよびiXBRLを含む財務レポート形式の検証。" >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) は、豊富で拡張性があり、使いやすい財務レポート処理APIの機能です。開発者は、金融およびビジネスソリューション用のXBRLおよびiXBRL形式を簡単にロード、検証、表示、または作成できます。 APIは提供します [XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) クラスと  [InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) XBRLおよびiXBRLファイルをロードするためのクラス。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="XBRLドキュメントを検証する" %}}

XBRLファイルの検証は、データが正しい構造と形式であるかどうかを確認するなど、多くの場合に必要です。 XBLRドキュメントを検証するには、最初にXbrlDocumentクラスを使用してXBRLファイルをロードします。を使用するには [検証（）](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) の方法 [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) クラス、最初に初期化します [XbrlInstanceCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) XbrlDocumentオブジェクトXbrlInstancesを使用します。それぞれを繰り返します [XbrlInstance.ValidationErrors](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/properties/validationerrors) 正しいエラーコードを取得し、それに応じて、カスタマイズされたエラーメッセージをコンソールに出力するか、ファイルに書き込むことで対応します。

{{% blocks/products/pf/feature-page-code h3="C#XBRLファイルを検証するためのコード" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-xbrl-file.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="iXBRLドキュメントを検証する" %}}

iXLRB検証の場合は、 [InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) クラスを作成し、そのValidate（）メソッドを使用します。の [ValidationErrorCode](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.validator/validationerrorcode) 列挙、検証エラーコードは、検証ルールごとに定義されます。 ContextPeriodNoStartTime、ContextPeriodNoEndTime、ContextPeriodStartAfterEnd、ContextInstantNoTime、ContextScenarioXbrlNamespace、ContextScenarioXbrlSubstitutionGroupなどのコードはほとんどありません。開発者は、エンドユーザーの時点でコードをデバッグおよび表示したり、問題を解決するための方向性を示したりできます。

{{% blocks/products/pf/feature-page-code h3="C#検証するコードiXBRLドキュメント" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-ixbrl-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}
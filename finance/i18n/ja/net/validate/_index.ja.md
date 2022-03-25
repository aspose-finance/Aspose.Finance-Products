---
title: .NET を介して財務レポートを検証する
url: /ja/net/validate/
description:  .NET ライブラリを介して XBRL および iXBRL ファイルの財務報告を検証するための C# コード。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# を介して財務報告ファイルを検証する" h2=".NET ベースのアプリケーション内で XBRL および iXBRL を含む財務報告の形式を検証します。" >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) は、豊富で拡張可能で使いやすい財務レポート処理 API の機能です。開発者は、金融およびビジネスソリューション用の XBRL および iXBRL 形式を簡単にロード、検証、表示、または作成できます。 API は [XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) クラスと  [InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) XBRL および iXBRL ファイルをロードするためのクラス。
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="XBRL ドキュメントの検証" %}}

XBRL ファイルの検証は、データが正しい構造と形式であることを確認するなど、多くの場合に必要です。XBLRドキュメントを検証するには、まずXbrlDocumentクラスを使用して XBRL ファイルをロードします。を使用するには、 [検証 ()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) メソッドの [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) クラス、最初に [XbrlInstanceCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) XbrlDocumentオブジェクトXbrlInstancesを使用します。それぞれをIterate [XbrlInstance.ValidationErrors](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/properties/validationerrors) 適切なエラーコードを取得し、コンソールにカスタマイズされたエラーメッセージを印刷するか、ファイル内に書き込むことによって、それに応じて行動します。

{{% blocks/products/pf/feature-page-code h3="C# ファイルを検証するコード XBRL" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-xbrl-file.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="iXBRL ドキュメントの検証" %}}

IXLRB検証の場合は、 [InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) クラスを作成し、そのValidate() メソッドを使用します。In [検証ErrorCode](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.validator/validationerrorcode) 列挙、検証エラーコードは、検証ルールごとに定義されます。いくつかのコードは、ContextPeriodNoStartTime、ContextPeriodNoEndTime、ContextPeriodStartAfterEnd、ContextInstantNoTime、ContextScenarioXbrlNamespace、ContextScenarioXbrlSubstitutionGroupなどです。開発者は、エンドユーザーとしてコードをデバッグして表示したり、問題解決の方向を示したりできます。

{{% blocks/products/pf/feature-page-code h3="C# ドキュメントを検証するコード iXBRL" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-ixbrl-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}
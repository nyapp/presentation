---
title: AI900(appented)
marp: true
header: 
author: YUKI TAMURA
theme: class
footer: AI900 対策講座
paginate: true
---
<!-- header: Azure AI Document Intelligence -->
# Introduction

Document intelligenceは、テキストの処理や情報の理解をサポートするAIの機S能を指します。これは光学文字認識（OCR）の拡張で、これによって書類を読み取った後の次のステップを自動化します。例えば、大量の領収書を処理し、データベースに手動で入力する必要がある場合では、手作業は遅くミスが発生しやすいです。Document intelligenceを使うと、スキャンした領収書の画像をOCRでデジタル化し、データベースのフィールドに対応する項目名と紐付けできます。具体的なデータとして、店舗名、住所、合計金額、税額などを識別できます。Azure AI Document Intelligenceは、事前構築モデルに加え、カスタムモデルを用いたドキュメントやフォームの分析機能をサポートします。

**"Prebuilt models"** 用意されている事前構築のモデル
**"Custom models"** カスタム作成するモデル

---
<!-- header: Azure AI Document Intelligence -->
# Azure AI Document Intelligence<br>が提供するラベル
## Key-value pair Label
**"key"** の例「住所」
**"value"** の例「123 Main Street」

機械学習モデルはバウンディングボックスの座標とテキストパターンを認識するように訓練されているため、文書や形式データを解釈できます。しかし、文書の形式が様々であるため、分析の自動化には課題があります。例えば、納税申告書と運転免許証にはどちらも名前が含まれますが、名前の位置は異なります。そのため、異なる形式に対して高品質な結果を得るために、個別の機械学習モデルを訓練する必要があります。一般的なドキュメント形式に対応する事前構築モデルを使うこともあれば、独自の形式に対応するためにモデルをカスタマイズすることもあります。テキスト読み取りとデータ記録の自動化により、業務を効率化し、顧客体験と意思決定を向上させることができます。次に、Azure AIサービスを使ってDocument Intelligenceを実装する方法を探ります。


![bg right](https://learn.microsoft.com/ja-jp/training/wwl-data-ai/analyze-receipts-form-recognizer/media/contoso-receipt-small.png)

---
<!-- header: Azure AI Document Intelligence -->

> 覚えてる？
# モデルの学習サイクル
## Key-value pair Label
**"key"** の例「住所」
**"value"** の例「123 Main Street」


![bg right 50%](https://www.mermaidchart.com/raw/f3681800-66c6-4041-845f-fc8146817c17?theme=light&version=v0.1&format=svg)

---


# Prebuilt models

    用途: 一般的な文書タイプ（請求書、名刺、IDドキュメントなど）を迅速かつ正確に処理するために使用されます。
    特徴: 事前に訓練されており、特定の文書タイプに特化したフィールド（例：請求書の合計金額、名刺の連絡先情報など）を認識し抽出するように設計されています。
    利点: 即時に使用可能で、一般的な文書処理タスクに対して高精度の結果を提供します。

# Custom models

    用途: 既存の事前訓練モデルでは対応できない特定のフィールドを識別するために使用されます。
    特徴: ユーザーが独自のデータセットを使用してモデルを訓練し、カスタマイズされたフィールドを抽出します。特殊な文書形式や業界固有の文書に対応できます。
    利点: 特定のニーズに応じた柔軟なモデルを構築でき、独自のフィールドやレイアウトに対応可能です。

# Document analysis

	用途: 一般的な文書のレイアウトや構造を理解し、関心領域とそれらの相互関係を解析するために使用されます。
	特徴: 文書全体の構造化データ表現を返し、関心領域（テキストブロック、テーブル、画像など）やそれらの相互関係を解析します。文書内のデータの位置関係やレイアウトを理解するために使用されます。
	利点: 複雑な文書の全体像を把握しやすくし、データの整理や相互関係の解析を支援します。

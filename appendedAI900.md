---
title: READMES
marp: true
header: 
author: YUKI TAMURA
theme: class
footer: AI900 対策講座
paginate: true
---
<!-- header: Azure AI Document Intelligence -->
# Introduction

Document intelligenceは、テキストの処理や情報の理解をサポートするAIの機能を指します。これは光学文字認識（OCR）の拡張で、これによって書類を読み取った後の次のステップを自動化します。例えば、大量の領収書を処理し、データベースに手動で入力する必要がある場合では、手作業は遅くミスが発生しやすいです。Document intelligenceを使うと、スキャンした領収書の画像をOCRでデジタル化し、データベースのフィールドに対応する項目名と紐付けできます。具体的なデータとして、店舗名、住所、合計金額、税額などを識別できます。Azure AI Document Intelligenceは、事前構築モデルに加え、カスタムモデルを用いたドキュメントやフォームの分析機能をサポートします。

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


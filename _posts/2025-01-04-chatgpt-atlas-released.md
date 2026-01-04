---
layout: post
title:  "OpenAIがChatGPT搭載AIブラウザ「Atlas」をリリース！～AIブラウザ戦争の新たな局面～"
date:   2025-01-04 12:00:00 +0900
categories: AI news
---

## 【導入】ChatGPT Atlasとは？

OpenAIが2025年10月26日、MacOS向けに「ChatGPT Atlas（アトラス）」というAIブラウザをリリースしました[^1]。

**ChatGPT Atlasの核心は、通常のAIアシスタントではなく「ChatGPTそのもの」がブラウザに搭載されている点**です。これは、AIブラウザ戦争にOpenAIが本格参戦したことを意味します[^2]。

[^1]: [AIブラウザの本命登場 OpenAI「ChatGPT Atlas」を使う - Impress Watch](https://www.watch.impress.co.jp/docs/topic/2058953.html)
[^2]: [ChatGPT Atlas（アトラス）とは？AI統合ブラウザの特徴をわかりやすく解説 - Mouse](https://www.mouse-jp.co.jp/mouselabo/entry/2025/10/22/100265)

## 【1. Atlasの主な機能と特徴】

ChatGPT Atlasには、以下のような機能があります：

### 主な機能
- **検索・要約・メール修正**：通常のAIブラウザと同様の基本機能[^3]
- **ChatGPTの機能を全面搭載**：
  - 画像生成、Deep Research、アプリ連携など、ChatGPTの全機能をブラウザからアクセス可能
  - チャット履歴はAtlasとChatGPTで完全に共有
- **UIの統一**：慣れ親しんだChatGPTのUIで操作可能
- **Google検索との切り替え**：`Command + Return`でGoogle検索を実行可能

[^3]: [ChatGPT Atlasの機能6選｜OpenAIの新ブラウザを徹底解説 - MoMo GPT](https://momo-gpt.com/column/chatgpt-atlas-function/)

### 他社製品との比較
| 機能 | ChatGPT Atlas | Perplexity Comet | The Browser Company Dia |
|------|---------------|-------------------|-------------------------|
| AI搭載 | ChatGPTそのもの | 独自AIアシスタント | 独自AIアシスタント |
| 履歴共有 | ✅ AtlasとChatGPT間で共有 | ❌ | ❌ |
| Agent mode | ✅（実験的） | ✅ | ✅ |

## 【2. Agent modeとその制約】

Atlasには「Agent mode」という、AIがブラウザを自動操作する機能があります[^4]。

### 可能な操作
- ECサイトでのショッピング
- ホテル予約
- ページ内でのクリックやスクロール

### 現状の課題
**「速度の遅さ」**が最大の問題です。
- 例：Amazonで「水」を検索し、商品を要約するタスクに**3分**を要した
- 実用化にはまだ程遠い状況

## 【3. セキュリティ問題と未解決の課題】

AIブラウザには深刻なセキュリティリスクが存在します[^5]。

### プロンプトインジェクション攻撃
- **画像内の隠れた命令**：白い文字で書かれた悪意ある命令がAIに実行される
- **攻撃例**：
  - 罠画像をスクリーンショットして質問 → Gmailを開き、メール履歴を攻撃者のサイトに送信
  - Redditの要約依頼 → 攻撃者のWebサイトにサインアップさせられる

OpenAIの最高情報セキュリティ責任者も、「**プロンプトインジェクションは未解決のセキュリティ問題**」と明言しています[^6]。

[^6]: [OpenAI CISO on prompt injection risks - Simon Willison](https://simonwillison.net/2025/Oct/22/openai-ciso-on-atlas/)

## 【4. 今後の展望とユーザーへの影響】

### 技術的進歩
- AIがPCを操作できるようになれば、あらゆる作業をAIが代行可能
- OpenAI、Google、多くの企業が開発に多大なリソースを投下

### 制約要因
- セキュリティ問題が技術的な制約以上にボトルネックに
- 信頼できるWebサイトのみにアクセス制限する必要
- 実用化には、ユーザーのセキュリティ意識向上も必要

[^4]: [それとも「過大評価」か？ 実際に触って分かったChatGPT Atlasの魔法の杖 - Business Insider Japan](https://www.businessinsider.jp/article/2601-chatgpt-atlas-review-magic-wand-or-overrated/)
[^5]: [How Prompt Injections Put AI Browsers Like ChatGPT Atlas At Risk - MediaNama](https://www.medianama.com/2025/12/223-explained-prompt-injections-ai-browsers-chatgpt-atlas/)

## 【まとめ】

### 重要なポイント
- ✅ ChatGPT AtlasはMacOSユーザー向けに無料で利用可能
- ✅ Agent modeは有料プランのみの提供
- ✅ セキュリティリスクは未解決の課題として残存

### ユーザーへの提案
1. **興味がある方は**：MacOSユーザーはFreeプランで試してみることをおすすめ
2. **注意点**：Agent modeの速度とセキュリティリスクを理解して使用
3. **将来展望**：AIブラウザ戦争の行方を注視し、適切な選択肢を選ぶ

Atlasのリリースは、AIブラウザ市場の新たな幕開けを意味します。技術的な進歩とセキュリティリスクのバランスが、今後の普及を左右するでしょう。
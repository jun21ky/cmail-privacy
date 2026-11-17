---
title: Cmail プライバシーポリシー
---

# プライバシーポリシー

**Cmail**（Mac アプリとコマンド `cmail`。以下「本アプリ」）における情報の取り扱いについて説明します。

**最終更新日: 2026年11月17日**

---

## まとめ

本アプリは、開発者が自分の Gmail を整理するために作った、自分専用のツールです。**開発者のサーバーはなく、メールの内容が開発者に送られることはありません。** メールはお使いの Mac と Google の間でやり取りされます。

---

## 1. Google アカウントから受け取る情報

Google アカウントでログインすると、本アプリは次の権限を使います。

| 権限 | 使い道 |
|---|---|
| メールの読み取り（gmail.readonly） | 受信トレイとスレッドを表示し、要約・翻訳する |
| 下書きの作成（gmail.compose） | 返信の下書きを Gmail に保存する |
| 送信（gmail.send） | 本人が確認した返信を送る |
| メールの変更（gmail.modify） | ラベルの付け替え・アーカイブ・既読にする・ゴミ箱に移す |
| 基本の設定（gmail.settings.basic） | フィルタ（振り分けのルール）を一覧・追加する |
| メールアドレスとプロフィール | どのアカウントでログインしたかを表示する |

## 2. 情報の保存

- ログインの情報（OAuth のトークン）は、Mac のキーチェーンにある鍵で暗号化して、Mac の中にだけ保存します
- メールの内容を本アプリが独自にサーバーへ保存することはありません

## 3. 情報の共有

- 要約・翻訳・返信の下書きのために、本人が使っている Claude Code（Anthropic 社）にメールの内容を渡すことがあります。これは本人の Claude のアカウントでの利用で、Anthropic のプライバシーポリシー（<https://www.anthropic.com/legal/privacy>）に従って扱われます
- それ以外の第三者に、Google から受け取った情報を販売・共有・転送することはありません。広告にも使いません

## 4. Google API サービスのユーザーデータに関するポリシー

本アプリが Google API から受け取った情報の使用と他のアプリへの転送は、限定的な使用の要件を含め、[Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy) に従います。

Cmail's use and transfer of information received from Google APIs to any other app will adhere to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the Limited Use requirements.

## 5. データの削除

- Google の許可は <https://myaccount.google.com/permissions> からいつでも取り消せます。取り消すと、Mac に残ったトークンは使えなくなります
- 本アプリを削除し、Mac の中の設定とキーチェーンの項目を消すと、保存された情報はすべてなくなります

## 6. 本ポリシーの変更

内容を変更する場合は、このページを更新し、冒頭の最終更新日を改めます。

## 7. お問い合わせ

<https://github.com/junhayashii0/cmail-privacy/issues>

---

## Summary (English)

Cmail is a personal tool with no developer-operated server. OAuth tokens are stored encrypted on the user's Mac. Gmail data is used only to display, summarize, translate, draft, send (after the user's review) and organize the user's own mail. To summarize and draft, message content may be passed to the user's own Claude Code (Anthropic). Data is not sold, shared with other third parties, or used for advertising. Access can be revoked at <https://myaccount.google.com/permissions>.

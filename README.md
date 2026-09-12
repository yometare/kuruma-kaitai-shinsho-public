# 車の解体新書 Public Site v0.1

公開用の静的サイトソースです。

## 想定公開repo

`yometare/kuruma-kaitai-shinsho-public`

GitHub Pages想定URL:

- Top: `https://yometare.github.io/kuruma-kaitai-shinsho-public/`
- Privacy Policy: `https://yometare.github.io/kuruma-kaitai-shinsho-public/privacy/`
- Support: `https://yometare.github.io/kuruma-kaitai-shinsho-public/support/`
- Account deletion: `https://yometare.github.io/kuruma-kaitai-shinsho-public/account-deletion/`

## 現在の状態

公開準備版です。

- 公開上の運営名: 車の解体新書 運営
- 公開サポートメール: kuruma.kaitai.support@gmail.com
- Production構成: 未確定
- 本番Account deletion: 未接続
- 法的な運営主体 / Store Developer名: 未確定

各HTMLには `noindex, nofollow` を設定しています。

## 公開直前に必ず行うこと

1. Production構成と実装をPrivacy Policyへ反映する
2. 本番Account deletion E2Eを完了する
3. 法的な表示要件を確認する
4. App Store App Privacy / Google Play Data Safetyと本文を一致させる
5. 公開版の文面へ更新する
6. `noindex, nofollow` を外すかどうか最終判断する
7. 公開URLをアプリSettings / Store metadataへ反映する
8. Apple / Googleの最新公式要件を再確認する

## 技術方針

- 素のHTML / CSSのみ
- JavaScriptなし
- Analyticsなし
- 広告なし
- Cookieを独自発行しない
- OSのLIGHT / DARK設定へ追従


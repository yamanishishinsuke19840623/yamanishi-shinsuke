# 山西伸典 スポンサーLP

## フォルダ構成

```
クライアント/山西伸典/
  index.html      ← LP本体（ブラウザで直接開ける）
  photos/         ← ここに写真を入れる
  README.md       ← このファイル
```

---

## 写真の入れ方

`photos/` フォルダに以下のファイル名で画像を入れると自動で表示されます。

| ファイル名 | 用途 |
|-----------|------|
| `hero.jpg` | ヒーロー（上部大きい写真・顔写真推奨） |
| `profile.jpg` | プロフィール欄の写真 |
| `fugu.jpg` | ふぐ料理・山西水産の写真 |
| `community.jpg` | 地域活動・イベントの写真 |
| `ai.jpg` | AI教育・セミナーの写真 |
| `family.jpg` | 家族・プライベートの写真 |

**写真がない場合は絵文字で自動表示されます。**

---

## Formspree 設定（メールフォームを本格化する場合）

1. https://formspree.io/ にアクセスして無料登録
2. 「New Form」を作成 → 受信メールアドレスに `yamanishishinsuke19840623@gmail.com` を設定
3. 発行されたエンドポイントURL（例: `https://formspree.io/f/xxxxxxxx`）をコピー
4. index.html の `submitForm()` 関数内の `mailtoLink` 部分をFormspree送信に書き換え（または秘書に依頼）

---

## GitHub Pages で公開する方法

1. `クライアント/山西伸典/` フォルダを git init
2. GitHub にリポジトリ作成（例: `yamanishi-shinsuke`）
3. `git push` してPages有効化（Settings → Pages → Deploy from branch）
4. 発行されたURLをシェア！

または `/lp-update` スキルを使うと自動化できます。

---

## 金額・プランを変更する方法

index.html を開いてCtrl+F で検索:
- `¥30,000` → ライトプランの金額
- `¥100,000` → スタンダードプランの金額
- `¥300,000` → プレミアムプランの金額

---

## 更新履歴

- 2024-05: 初版作成 by AI秘書ナナ（cc-booster）

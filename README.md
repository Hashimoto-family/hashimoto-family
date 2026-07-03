# 橋本家 台帳（家族ページ）

GitHub Pagesで公開する家族用サイトです。バインダーのインデックスタブのように
「Home」「Travel」を切り替えて閲覧できます。
スマホでもアップロードしやすいよう、全ファイルをフォルダなしのフラット構成にしています。

## 構成
```
index.html          ← Home（トップページ）
travel.html          ← Travelタブ（旅のしおり一覧）
hawaii-2026.html      ← ハワイ旅行(2026/7)のしおり本体
style.css            ← 共通スタイル（タブナビ・台帳デザイン）
```

## スマホでのアップロード手順（GitHub Web UI）

1. このzipをダウンロードし、スマホの「ファイル」アプリなどで展開（解凍）する
2. 作成したリポジトリのページを開き、`Add file` → `Upload files`（または
   最初の画面にある `uploading an existing file` リンク）をタップ
3. ファイル選択画面で、展開したフォルダの中から
   `index.html` `travel.html` `hawaii-2026.html` `style.css` の**4つを一度に選択**
   （複数選択できない場合は1つずつ選んで都度Commitでも可）
4. 画面下の `Commit changes` をタップして保存
5. リポジトリの `Settings` → 左メニュー `Pages` を開き、
   `Source` を `Deploy from a branch`、ブランチを `main`、フォルダを `/ (root)` にして保存
6. しばらくすると公開URL（`https://<ユーザー名>.github.io/<リポジトリ名>/`）で閲覧できます

## 今後の拡張
- `index.html` の「＋ 準備中」タブを増やして、新しいセクション
  （例: 家計、思い出アルバムなど）を追加できます
- 旅行が増えたら `travel.html` にカードを追加し、
  `<新しい旅の名前>.html` を作成してリンクしてください（フォルダは作らずルート直下でOK）

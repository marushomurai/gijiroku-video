# 議事録を動画にするスキル（gijiroku-video）

会議の議事録を貼って「議事録を動画にして」と頼むと、図や数字が場面ごとに動いて、ブラウザが読み上げる議事録ページができます。
Codex と Claude のどちらでも使えます。有料のキーは要りません。

## 入れ方

### Codex

Codex の入力欄に次の1行を貼って送信し、Codex を再起動してください。

```
$skill-installer install https://github.com/marushomurai/gijiroku-video/tree/main/gijiroku-video
```

### Claude（アプリ・claude.ai）

1. [gijiroku-video.zip をダウンロード](https://github.com/marushomurai/gijiroku-video/releases/latest/download/gijiroku-video.zip)（ダウンロードした zip は解凍しないでください）
2. Claude で [Customize → Skills](https://claude.ai/customize/skills) を開き、「＋」→「Create skill」→「Upload a skill」を選んで zip をアップロード
3. 一覧に出た gijiroku-video がオンになっていることを確認

設定の「コード実行とファイル作成」がオフだとスキルは使えません。同じアカウントの Claude Code にも自動で入ります。

## 使い方

1. 議事録・文字起こし・メモを貼って「議事録を動画にして」と頼む
2. できたページの「▶ 読み上げつきで再生」を押す
3. 場面や目次をタップすると、そこから再生できます

## 注意

- 読み上げの声はブラウザと OS で変わります。声が出ない環境でも、文字と動きだけで中身が分かります。
- 社外秘の内容が入ったページは社内だけで共有してください。

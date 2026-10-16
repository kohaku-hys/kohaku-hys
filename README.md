# 林 琥珀 / Kohaku Hayashi

福岡工業大学 工学部 電子情報工学科の2年生です（2025年入学）。
半導体の学外プログラムや海外研修に参加しながら、Claude Code で大学生活の道具を作って自分で使っています。
作ったスキルの一部は [claude-code-skills](https://github.com/kohaku-hys/claude-code-skills) で公開していて、その作り方は [Zenn](https://zenn.dev/ai_daigakusei) に書いています。

## 作った物

### 公開しているもの

| 名前 | 何をするか | 技術 |
| --- | --- | --- |
| [claude-code-skills](https://github.com/kohaku-hys/claude-code-skills) | Claude Code のスキル24個と、スキルから呼ぶエージェント13体。実験レポート（Word）、編集できるスライド、議事録、ES、メールなどを、確認の質問から仕上げの検査まで同じ手順で作る | Markdown, Python |

### 自分の PC で動かしているもの（コードは非公開）

| 名前 | 何をするか | 技術 |
| --- | --- | --- |
| 壁紙の上の Google カレンダー | 週の予定を壁紙の上に出し、予定の10分前に「今やってる？」と聞く（[記事](https://zenn.dev/ai_daigakusei/articles/google-calendar-desktop-widget)） | Python (tkinter), Google Apps Script |
| Telegram の双方向 bot | スマホのボタンで PC のファイル整理を承認したり、メモや質問を PC の Claude に送ったりする | Python, Telegram Bot API, Claude Code CLI |
| Telegram から Claude Code を操作するブリッジ | VS Code で動いている Claude Code に外から指示を送り、Claude からの質問にもそこからボタンで答える | Python, Claude Code hooks |
| タスクバーを歩くクロードくん | Claude Code の会話ログを読んで動くマスコット。集中タイマーと締切の旗が付いている | Python (tkinter, Pillow) |
| 授業のリアルタイム文字起こし | 対面授業の音声を手元の PC で文字にし、3分ごとに専門用語の解説を挟む。時間割を見て授業中だけ動く | Python, faster-whisper |
| 授業動画から予習レポート | 授業動画を Chrome DevTools Protocol で取り込み、数式入りの Word の予習レポートにする（[記事](https://zenn.dev/ai_daigakusei/articles/claude-code-cdp-sharepoint-automation)） | Python, python-docx |
| PC から Echo をしゃべらせる | PC のスクリプトから日本の Amazon Echo に話させる（[記事](https://zenn.dev/ai_daigakusei/articles/alexa-speak-from-pc-japan)） | Python, Node.js |

### チームや授業で作ったもの

| 名前 | 何をするか | 技術 |
| --- | --- | --- |
| Q-Trip（Q-Quest GROW、4人チーム） | 焼きなまし法で巡回セールスマン問題を解き、九州の旅行ルートを組む Web アプリ。DEMODAY ではこのアプリで福岡市を回るシミュレーション動画を発表した | Next.js, TypeScript |
| エンドレス シューティングゲーム（授業のチーム制作） | 縦スクロールのシューティングゲーム。チームのリーダーとして main の部分を書いた | C++, DxLib |
| AI 電子鼻の測定キット（台湾での国際 PBL） | ガスセンサの値を段階ごとに記録し、それをグラフにする | Arduino, Python |
| 学習管理の Discord bot（個人。2026年6月に運用を終了） | ポモドーロ、タスク管理、Google Calendar 連携、Claude API の応答を1つにまとめた bot | Python, discord.py, SQLite |

## 半導体

- 九州大学 価値創造型半導体人材育成センターのプログラムを3つ修了しました
  - 高周波デバイス計測セミナー（2025年9月）
  - プロセス・デバイスシミュレーション実習（2025年9月、TCAD）
  - 集積回路設計・評価ハンズオンセミナー（2025年9月〜2026年3月、設計から試作チップの測定まで）
- 半導体設計ゲーム「THE GAME」（IBM 九州DXセンター、2025年11月）

## 海外での研修・交流

- タイ KMITL 短期派遣研修（2026年2月、約2週間）
- シンガポール SAIL Program（2026年3月、テマセク・ポリテクニック）
- 台湾 国立宜蘭大学との国際 PBL「AI 電子鼻」（2026年8月、英語で最終発表）
- 韓国 昌原国立大学の gPBL（2026年9月、英語で成果発表）
- 台湾 亜洲大学の学生との交流会（2025年8月）

## 学内の活動

- GCP（Global Challenge Program、学内の英語プログラム）に参加し、2026年6月に4期生に選ばれました
- GSL（Global Student Leaders）リーダー
- ピアサポーター（2026年3月の新入生オリエンテーションのスライドを作成）
- 工大サミット連携 PBL（広島、2026年9月。全体発表とポスター発表）
- 学内の英語スピーチコンテスト FIT TALKS 2025 に出場。FIT TALKS 2026 は上級部門にエントリーしています

## 使っている技術

- よく使う: Python, Claude Code
- 授業やチームで使った: C / C++ (DxLib), TypeScript (Next.js), Arduino, Raspberry Pi
- 半導体の実習で使った: TCAD, KLayout

## 連絡先

- Mail: <khk589go@gmail.com>
- Zenn: <https://zenn.dev/ai_daigakusei>

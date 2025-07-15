# Nmap のクイックスタート

## 言語

🇨🇳 [简体中文](README_zh.md) 🇪🇸 [Español](README_es.md) 🇫🇷 [Français](README_fr.md) 🇩🇪 [Deutsch](README_de.md) 🇯🇵 [日本語](README_ja.md) 🇷🇺 [Русский](README_ru.md) 🇰🇷 [한국어](README_ko.md) 🇧🇷 [Português](README_pt.md) 🇺🇸 [English](README.md) 

[![Nmap のクイックスタート](https://cover-creator.labex.io/quick-start-with-nmap.png?lang=ja)](https://labex.io/ja/courses/quick-start-with-nmap)

[![Start-Learning](https://img.shields.io/badge/Start-Learning-whitesmoke?style=for-the-badge)](https://labex.io/ja/courses/quick-start-with-nmap)

このコースでは、コンピュータネットワーク上のホストとサービスを発見するために使用される強力なネットワークスキャンツールである Nmap について学びます。

![Cybersecurity](https://img.shields.io/badge/Cybersecurity-whitesmoke?style=for-the-badge&logo=cybersecurity)
![Nmap](https://img.shields.io/badge/Nmap-whitesmoke?style=for-the-badge&logo=nmap)


## 演習

|   インデックス | 名前                                                      | 難易度   | 練習                                                                                                                                  |
|----------------|-----------------------------------------------------------|----------|---------------------------------------------------------------------------------------------------------------------------------------|
|             01 | 📖 🟢 Nmap のインストールと基本的な使い方を学ぶ           | 中級     | <a target='_blank' href='https://labex.io/ja/tutorials/nmap-learn-nmap-installation-and-basic-usage-415924'>ラボを開始</a>            |
|             02 | 🎯 🟢 ローカル環境でのサービスバージョンの検証            | 初級     | <a target='_blank' href='https://labex.io/ja/tutorials/nmap-verify-service-version-locally-548693'>チャレンジを開始</a>               |
|             03 | 📖 🟢 Nmap の基本的なコマンド構文を学ぶ                   | 初級     | <a target='_blank' href='https://labex.io/ja/tutorials/nmap-learn-nmap-basic-command-syntax-415919'>ラボを開始</a>                    |
|             04 | 🎯 🟢 Luna サーバー上のオープンポートの発見               | 初級     | <a target='_blank' href='https://labex.io/ja/tutorials/nmap-find-open-port-on-luna-server-548697'>チャレンジを開始</a>                |
|             05 | 📖 🟢 Nmap スキャンと出力分析を学ぶ                       | 初級     | <a target='_blank' href='https://labex.io/ja/tutorials/nmap-learn-nmap-scanning-and-output-analysis-415926'>ラボを開始</a>            |
|             06 | 🎯 🟢 Nmap の出力を XML 形式で保存する                    | 初級     | <a target='_blank' href='https://labex.io/ja/tutorials/nmap-save-nmap-output-to-xml-548705'>チャレンジを開始</a>                      |
|             07 | 📖 🟢 Nmap におけるターゲット指定テクニックを学ぶ         | 初級     | <a target='_blank' href='https://labex.io/ja/tutorials/nmap-learn-target-specification-techniques-in-nmap-415935'>ラボを開始</a>      |
|             08 | 🎯 🔵 ファイルからのターゲットのスキャン                  | 初級     | <a target='_blank' href='https://labex.io/ja/tutorials/nmap-scan-target-from-file-548715'>チャレンジを開始</a>                        |
|             09 | 📖 🔵 Nmap の冗長度レベルでネットワークスキャンを徹底解説 | 初級     | <a target='_blank' href='https://labex.io/ja/tutorials/nmap-explore-nmap-verbosity-levels-for-network-scanning-415939'>ラボを開始</a> |
|             10 | 🎯 🔵 秘密のポートを解き明かせ                            | 初級     | <a target='_blank' href='https://labex.io/ja/tutorials/nmap-uncover-the-secret-port-548724'>チャレンジを開始</a>                      |
|             11 | 📖 🔵 Nmap SYN スキャンによるネットワークセキュリティ対策 | 初級     | <a target='_blank' href='https://labex.io/ja/tutorials/nmap-conduct-nmap-syn-scans-for-network-security-415934'>ラボを開始</a>        |
|             12 | 📖 🔵 Nmap を使用した UDP ポートスキャンを実行する        | 初級     | <a target='_blank' href='https://labex.io/ja/tutorials/nmap-perform-udp-port-scanning-with-nmap-415938'>ラボを開始</a>                |
|             13 | 🎯 🔵 オープン UDP ポートの発見                           | 初級     | <a target='_blank' href='https://labex.io/ja/tutorials/nmap-find-open-udp-port-548746'>チャレンジを開始</a>                           |
|             14 | 📖 🔵 Nmap の OS とバージョン検出テクニックを学ぶ         | 初級     | <a target='_blank' href='https://labex.io/ja/tutorials/nmap-learn-nmap-os-and-version-detection-techniques-415925'>ラボを開始</a>     |
|             15 | 🎯 🔵 Linux サーバーのバージョンを特定する                | 初級     | <a target='_blank' href='https://labex.io/ja/tutorials/nmap-identify-linux-server-version-548747'>チャレンジを開始</a>                |

## 環境

LabEx は、コーディングとテクノロジーに特化したインタラクティブな実践学習プラットフォームです。ラボ、AI 支援、仮想マシンを組み合わせて、ビデオなしの実践的な学習体験を提供します。

![](https://tutorial-screenshot.getvm.io/images/vm-1725247253.png)

- 動画なしの独自の実践ラボによる厳格な「実践による学習」アプローチ。
- ブラウザ内のインタラクティブなオンライン環境で、自動化されたステップバイステップのチェック機能。
- スキルツリーベースのシステムによる構造化されたコンテンツ組織。
- 30 のスキルツリーと 6,000 以上のラボを含む成長し続ける学習リソース。
- 最新の AI モデルを基盤とした学習アシスタント Labby による対話型学習体験。

詳細について [LabEx VM](https://support.labex.io/using-labex/virtual-machine).

## その他

- 🔗 [Cybersecurity プログラミングコース](https://github.com/labex-labs/awesome-programming-courses)
- 🔗 [Cybersecurity プログラミングプロジェクト](https://github.com/labex-labs/awesome-programming-projects)
- 🔗 [Cybersecurity 無料チュートリアル](https://github.com/labex-labs/cybersecurity-free-tutorials)


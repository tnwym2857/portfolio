bash

cat /home/claude/portfolio_README.md
出力

# エンジニアリング・データ分析ポートフォリオ

製造業（生産管理・品質管理）約10年の実務経験と、独学で身につけたPython・データ分析・
Web開発のスキルを掛け合わせ、データから課題を発見し改善提案につなげる力を磨くことを
目指しています。

Python・統計学・自動化技術・Web開発を中心に、以下の成果物を作成しました。

## ■ 成果物一覧（ポートフォリオ）

### ① 製造ラインKPI可視化・分析
製造業での生産管理・品質管理の実務経験をもとに、日々の生産実績データから
不良率・稼働率・OEE（設備総合効率）などのKPIを算出し、可視化するプロジェクトです。
不良原因のパレート分析から、ラインごとの改善ポイントを見つける仮説を提示しています。

リポジトリ： https://github.com/tnwym2857/manufacturing-kpi-analysis

### ② 小売店 売上分析＆Excelレポート自動生成
小売店の売上データをもとに、分析（pandas / matplotlib）から
定例レポート作成の自動化（openpyxl）までを一貫して行うプロジェクトです。
前職で手作業で行っていたレポート作成業務を、Pythonでどれだけ自動化できるかを検証しました。

リポジトリ： https://github.com/tnwym2857/sales-report-automation

### ③ 統計的検定による意思決定の検証
「新しい治具は本当に不良率を下げていると言えるか？」という製造現場の問いを、
t検定・効果量・信頼区間を使って検証し、意思決定への提案までつなげたプロジェクトです。
検定の前提確認や、ノンパラメトリック検定による頑健性チェックも行っています。

リポジトリ： https://github.com/tnwym2857/statistical-analysis

## ■ 使用技術一覧

- Python
- pandas / numpy
- matplotlib / seaborn
- scipy（統計的検定）
- openpyxl（Excel自動化）
- Jupyter Notebook

## ■ Web開発の実績（Django / FastAPI）

データ分析と並行して、Djangoを用いたWebアプリケーション開発にも取り組んでいます。

- ECサイト（VegeKet）：商品管理・カート・注文機能、Stripe決済連携
  https://github.com/tnwym2857/vegeket-ec-site
- SNS風アプリケーション
  https://github.com/tnwym2857/sns-app-tiktok-style
- Todo管理アプリ
  https://github.com/tnwym2857/django-todo-app

いずれもGitHub上で公開しており、READMEに開発中に直面した課題と解決プロセスを
まとめています。現在はFastAPIを学習中で、今後はDjangoで開発したECサイトの
FastAPI移行にも取り組む予定です。

## ■ 今後の学習計画

- FastAPIを用いたWebアプリケーション開発（学習中）
- SQL（BigQuery / MySQL）
- Tableau / Power BI
- 機械学習（scikit-learn）
- 英語（技術ドキュメントを読めるレベルを目指し、段階的に学習中）

## ■ 目標

製造業での実務経験とデータ分析スキルを掛け合わせ、現場の課題をデータで可視化し、
改善につなげられるエンジニア・データアナリストとしてキャリアを築いていきたいと
考えています。

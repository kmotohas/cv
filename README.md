# 職務経歴書
Tue, May 13, 2020

## 個人データ
- 本橋 和貴 (MOTOHASHI Kazuki, Ph.D)
    - 博士（理学）
    - kmotohas (at) gmail.com

## 希望職務

大学院修士課程時代にイタリアのジェノバ大学に4ヶ月程度在籍、実験のために4・5回程度ドイツのDESY研究所に出張、博士課程時代にはスイスのCERN研究所に2年間程度常駐していたので海外（ヨーロッパ）生活は慣れています。

## スキル

研究室時代からデータ分析をやっている。
他にも機械学習・ディープラーニングや、バックエンドよりのコードを書くこともある。
フロントエンドはあまり経験がない。

### プログラミング

#### Python

- 2013年頃より主にデータ分析・機械学習用途で利用。
    - PyROOT / TensorFlow / Keras / Sci-kit Learn
    - spaCy / Hugging Face 
    - matplotlib / seaborn
- 自律走行ロボット向けソフトウェア開発。
    - ROS
- PythonベースのWebアプリ開発。API開発。
    - django / Fast API / Flask / Streamlit
    - SQLAlchemy

#### C/C++

- 2011年頃より主にデータ分析用途で利用。
    - ROOT

#### Java

- Deeplearning4jを用いたディープラーニングモデル開発。
- Spring Boot、特にSpring Cloud Data Flowを用いたディープラーニングアプリケーション開発。

#### JavaScript / TypeScript

独学したのみで実務経験はなし。
ReactやElectronを用いてデモアプリ開発。

### その他

- AWSを用いたシステム・ネットワーク設計
    - 触ったことあるAWSサービス
        - コンピューティング: EC2 / Lambda
        - ストレージ: S3
        - データベース: RDS
        - ネットワーキングとコンテンツ配信: VPC / API Gateway / Route 53
        - 開発者用ツール: Cloud9
        - 管理とガバナンス: CloudWatch
        - Machine Learning: Amazon Sage Maker
        - 分析: Elasticsearch Searvice
        - セキュリティ、ID、およびコンプライアンス: IAM
        - アプリケーション統合: Simple Notification Service
        - カスタマーエンゲージメント: Simple Email Service
        - コンテナ: Elastic Container Registry / Elastic Container Service
- ビジネス英会話
    - TOEIC 855 (2018年3月時点)

## 出版物

- \[監訳\] [詳説 Deep Learning − 実務者のためのアプローチ](https://www.oreilly.co.jp/books/9784873118802/)
    - オライリー・ジャパン
    - 2019年8月発行
        - 監訳を担当。ディープラーニング全般の解説および、Deeplearning4jを用いたモデル開発、ハイパーパラメーターチューニング、Apache Sparkとの統合に関する書籍。
- \[共著\] [自然言語処理技術 ～目的に応じた手法選択／精度向上手法／業務活用への提言](https://johokiko.co.jp/publishing/BC200202.php)
    - 情報機構
    - 2020年3月発行
        - 第三章「ハンズオンで学ぶ文書分類モデルの作成とツールの利用方法」の執筆を担当。ニュース記事の分類をテーマに、spaCyを用いた単語バッグやCNNベースの分類モデル開発方法を解説。また、Hugging Faceを用いて日本語BERTモデルをファインチューニングすることで分類モデルを開発する手法も解説。

## 職歴 (現職)

### Konduit株式会社・旧Skymind株式会社019/03-現在)

Deeplearning4jを開発したAdam Gibson氏率いるAIスタートアップ。

#### Senior Engineer

プリセールスやソリューションエンジニアのような立ち位置。
お客様に対してディープラーニングでできることを説明したり、アイディアワークショップを開いたり、製品の紹介などしている。

2019年に月一で開催していた「実践者向けディープラーニング勉強」ではメインスピーカーを担当。
ディープラーニングの理論およびアプリケーション開発などに関して非専門家向けに解説。

### DEEPCORE Inc. (2019/04-現在)

ソフトバンクグループ系列のAIインキュベーション会社。

#### Technical Advisor at KERNEL (業務委託)

コミュニティメンバーに対してAWSのGPUインスタンスを提供しているのでそれの管理や、PoC環境の構築を担当。
その他、必要に応じてAWS上でシステム構築や、コミュニティメンバーに対する技術支援など。

### KBE Inc. (2020/01-現在)

人事向けのITサービスを開発するスタートアップ。

#### 機械学習エンジニア (業務委託)

Slack botベースの人材検索サービス [researcHR](https://researchr.work/) メイン開発者の一人。

- 機械学習ベースの自然言語処理技術を用いた人材DBの曖昧検索を行う部分のアルゴリズムの開発
    - Elasticsearchの全文検索アルゴリズムと組み合わせて検索スコアを計算
- PythonライブラリのFast API + SQLAlchemyを用いたバックエンド開発。（現在はdjangoに移行）
- サービスのUIとしてのSlack bot開発。

## 職歴 (現職以前)

### ソフトバンク株式会社 (2017/04-2019/02)

#### AIロボットエンジニア

自律走行ロボット用に、ROSと画像認識を利用したアプリケーションを作成。

- エレベーターの操作パネルを認識し、行きたい階のボタンを操作するロボットアプリケーションの開発
    - CEATEC 2017 にて展示 https://www.youtube.com/watch?v=Zl9qvw1Brbs
    - Fetch Robotics社のR&D用ロボット Fetch を利用
- 応用としてナビゲーション＋エレベーターを利用したビル巡回デモも開発
    - https://www.youtube.com/watch?v=-b8Md1SncV8

ロボット以外の業務・活動

- あるサービスの解約率を予測するモデルの開発
- 5Gベンダーと共同で、Mobile Edge Computingのデモ開発、性能評価、ダッシュボードに可視化
    - ローカルのカメラで取得した画像をリモートサーバーで動いている物体検知アルゴリズムに5G経由で送信し、結果を取得するシステムの構築
- 社内認定制度 Technical Meister にディープラーニング領域で認定
- 社内AIコミュニティ SB-AI部 発足。現在643名程度在籍。

### DEEPCORE Inc. (2018/05-2019/02)

2018年5月より一部出向。ソフトバンク株式会社退社後は業務委託として契約を継続している。（上記参照）

#### クラウドインフラエンジニア

起業家を集めるコミュニティ "KERNEL" における技術サポート。
AWSのGPUインスタンスやGPUサーバーの管理など。

### 日本学術振興会 (2015/04-2017/03)

#### 特別研究員 (DC2)

東京工業大学 大学院 博士課程在籍時にDC2に採用。

LHC-ATLAS実験のデータ解析による新粒子探索を行った。
ATLAS Week 2016では最優秀ポスター賞を取得。

### 欧州原子核研究機構・CERN (2012/07-2012/09)

#### インターンシップ

東京工業大学 大学院 修士課程在籍時にCERN Summer Student Program 2012参加。

Linear Collider Groupに所属し、ハドロンカロリメーターのビーム試験データの解析を行った。

## 学歴

2017年 東京工業大学 理工学研究科 基礎物理学専攻 博士課程 修了

博士論文: [Search for long-lived gluinos using high-track-multiplicity displaced vertices with the ATLAS detector at √s = 13 TeV](https://t2r2.star.titech.ac.jp/rrws/file/CTT100759109/ATD100000413/)

- 投稿論文、()内は出版年
    - ATLAS Collaboration (2018), [Search for long-lived, massive particles in events with displaced vertices and missing transverse momentum in √s = 13 TeV pp collisions with the ATLAS detector](https://doi.org/10.1103/PhysRevD.97.052012), Phys. Rev. D 97, 052012
    - K. Motoahshi (2015), [IBL modules construction experience and developments for future upgrade](http://iopscience.iop.org/article/10.1088/1748-0221/10/04/C04027), PIXEL2014
    - K. Motoahshi et al. (2014), [Evaluation of KEK n-in-p planar pixel sensor structures for very high radiation environments with testbeam](https://www.sciencedirect.com/science/article/pii/S0168900214006457), HSTD-9 2013

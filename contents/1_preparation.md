# 第1回：環境構築

## 講義概要

### カリキュラム

![カリキュラム](./figs/1/1-1.png)

### 必修内容

1. Microsoft Office (Word, Excel, PowerPoint): 2年生から始まるインターンシップを想定
2. Python: 多くの大学で1年生から必修化されている．本学科でも秋学期のフレッシュマンセミナーIIで実施する．

### スケジュール

1. Mac利用環境の構築とタイピングの練習
2. 情報セキュリティ、情報モラル（プライバシー保護、著作権、不正利用）
3. Wordによる文書作成1
4. Wordによる文書作成2と生成系AI
5. 演習：Wordによる文書作成
6. 文章作成術
7. レポート・論文作成法
8. 演習：Wordによるレポート作成
9. PowerPointによるプレゼン資料作成
10. 演習：PowerPointによるプレゼン資料作成
11. Texによる文書作成1
12. Texによる文書作成2
13. 演習：Texによる数式のある文書作成

### 成績評価

- <span style="color:red">平常点40点・課題点60点の計100点</span>で成績を評価する．
- <span style="color:red">欠席を1回するごとに平常点から10点減点</span>し，<span style="color:red">遅刻を1回するごとに平常点から5点減点</span>する．
体調不良・法事・部活動の大会などのやむを得ない事情により講義を欠席する場合には事務に連絡すること．
連絡のあった回については平常点の減点を行わない．
- なお，欠席回の課題は課題点に加算されるため，後日提出すること．
- 本学の規程（[学則・学位規程・ガバナンスコード｜城西大学](https://www.josai.ac.jp/about/information/gakusokukitei/)）に従い，<span style="color:red">5回以上欠席した場合には単位が与えられない（Z評価）</span>．
欠席届のあった回についても欠席回数にカウントされるため注意すること．
<!-- - 本学の規程（[令和７年度城西大学学則](https://www.josai.ac.jp/media/32-daigakubinran2025.pdf) 第40条2項）に従い，<span style="color:red">5回以上欠席した場合には単位が与えられない（Z評価）</span>． -->
- 他の学生の講義の受講を阻害する行為を行なった学生は平常点から減点する．
- 全ての講義が終了した段階で<span style="color:red">平常点と課題点の総点が60点以上にならなかった場合には単位は与えられない（F評価）</span>．

### 準備学習等の指示

- <span style="color:red">各自のMacBookを持参すること</span>．各回の課題では各自のMacBookを使用する．
- MacBookは充電をしておくこと．

### 出席登録

- 毎回WebClassで出席登録を行う．
- 講義の始めにパスワードを掲示するため，これを入力することで出席登録を完了する．
- 登録可能時間は講義開始時刻から15分間(11:00-11:15)とし，それ以降15分間(11:15-11:30)での登録は遅刻扱いとする．また，それ以降の登録はできないため欠席扱いとなる．

## コンピュータ環境の整備

### 到達目標

1. Anaconda（Pythonの利用ツール）のインストール
2. Microsoft Officeのインストール
3. MacTeX（TeXを実行するためのソフトウェア）のインストール<br>
   ※ TeX: 主に数式を含む文書の組版を行うプログラミング言語
4. Visual Studio Code (VSCode) のインストール
5. タイピング練習

## Anacondaのインストール

- Anaconda：Anaconda社が提供するデータサイエンス，科学技術計算ができるソフト
- 秋学期にパッケージに含まれるJupyter Notebookを使ってPython（プログラミング言語の1つ）のプログラミングを行う

### 手順

1. MacのCPU・メモリの構成を確認する．

![2-1-1](./figs/1/2-1-1.png)

![2-1-2](./figs/1/2-1-2.png)

2. Anacondaのページにアクセスする．

![2-1-3](./figs/1/2-1-3.png)

3. 自分のMacのチップに合わせてダウンロードする．

![2-1-4](./figs/1/2-1-4.png)

4. ダウンロードしたパッケージを確認し，インストールする．

![2-1-5](./figs/1/2-1-5.png)

![2-1-6](./figs/1/2-1-6.png)

![2-1-7](./figs/1/2-1-7.png)

![2-1-8](./figs/1/2-1-8.png)

![2-1-9](./figs/1/2-1-9.png)

![2-1-10](./figs/1/2-1-10.png)

![2-1-11](./figs/1/2-1-11.png)

![2-1-12](./figs/1/2-1-12.png)

![2-1-13](./figs/1/2-1-13.png)

![2-1-14](./figs/1/2-1-14.png)

![2-1-15](./figs/1/2-1-15.png)

5. インストールを確認し，ソフトを開く．

![2-1-16](./figs/1/2-1-16.png)
<!-- ⭐️要確認⭐️Launchpadがあるかを確認する -->

![2-1-17](./figs/1/2-1-17.png)

![2-1-18](./figs/1/2-1-18.png)

## Microsoft Officeのインストール

- [https://www.josai.ac.jp/inforesearch/office_desktop/](https://www.josai.ac.jp/inforesearch/office_desktop/)にアクセスし，記載の手続きに従う．

![2-2](./figs/1/2-2.png)

## MacTeXのインストール

- [https://tug.org/mactex/mactex-download.html](https://tug.org/mactex/mactex-download.html
)にアクセスし，下画像の⭕️をクリックする．

![2-3](./figs/1/2-3.png)

## Visual Studio Codeのインストール

- [https://code.visualstudio.com/download](https://code.visualstudio.com/download)にアクセスし，下画像の⭕️をクリックする．

![2-4](./figs/1/2-4.png)

## タイピング練習

- PCを使いこなすにあたり，タイピングをスムーズにできることは大前提必要な技術である．
- 本講義では毎回20分間，タイピング練習の時間を設ける．

### 方法

- 指はホームポジションに置き，ここから各指で所望のキーをタイプする．

![ホームポジション](https://upload.wikimedia.org/wikipedia/commons/6/67/TouchTyping_HomePosition_QWERTY.png)

出典：[https://upload.wikimedia.org/wikipedia/commons/6/67/TouchTyping_HomePosition_QWERTY.png](https://upload.wikimedia.org/wikipedia/commons/6/67/TouchTyping_HomePosition_QWERTY.png)

```{tip} 練習のポイント
- 始めは正確さを追求，9割以上正確にタイプできるようになったら速さを上げる．
- 数学・スポーツ・タイピング，技術を習得する分野のいずれにおいても共通する考え方．
```

### 練習サイト

- 寿司打（スシダ）[https://sushida.net/](https://sushida.net/)

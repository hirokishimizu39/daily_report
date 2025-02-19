## 取り組んだ課題一覧
- JS Primer 文字列とUnicode編
- 【書籍】TypeScriptとReact/Next.jsでつくる実践Webアプリケーション開発　を読む
- Notionにポートフォリオのドキュメント作成（エレベーターピッチ・要件定義〜実装計画など・DB設計・API設計・リソース設計）

## わかったこと（わからなかったこと）
- Code Point
    - Unicode→Unit Code つまり、文字(絵文字など含む)に対して、一意のcode(ID)を割り当てている。
    - そのIDをCode Pointという
    - `console.log("あ".codePointAt(0)); // => 12354`
- Code Unit(JSのエンコードした後の値)
    - ある1つの文字に対応するIDであるCode Pointを、16ビット（2バイト）のCode Unitで表現するのがUTF-16というエンコード方式
    - UTF = Unicode Transform Format
    - しかし、16ビット（2バイト）で表現できる範囲は、6万5536種（2の16乗）
- サロゲートペア（2つのCode Unitの組み合わせ（合計4バイト）で1つの文字(Code Point)を表現したもの）
    - 現在、Unicodeに登録されているCode Pointは10万種を超えているため、すべての文字とCode Unitを1対1の関係で表すことができない。
    - このような場合に、UTF-16では2つのCode Unitの組み合わせ（合計4バイト）で1つの文字（1つのCode Point）を表現します。この仕組みを**サロゲートペア**と呼ぶ。

## 次やること
- JS
  - JavaScript Primer - 迷わないための入門書 #jsprimerを読む
  - JavaScriptでToDo Listを作る
- React初級
  - Reactの公式チュートリアルをやる
- React中級
  - Reactに入門した人のためのもっとReactが楽しくなるステップアップコース完全版
  - ReactでToDo Listを作る
- React上級
  - 【Reactアプリ開発】3種類のReactアプリケーションを構築して、Reactの理解をさらに深めるステップアップ講座 | Udemyを見る。
  - ReactでTrelloクローンアプリケーションを作ってReactをマスターしよう！ | Udemyを見る
- ReactとDjangoでSPAアプリケーションの作り方を学ぶ
  - [基礎編]React Hooks + Django REST Framework API でフルスタックWeb開発
  - Django with React | An Ecommerce Website
  - Full Stack - React Django DRF Channels Project - djChat
- **2/30 TypeScript, Next.js**
  - 動画版 TypeScriptの基本を見る
  - TypeScript入門『サバイバルTypeScript』〜実務で使うなら最低限ここだけはおさえておきたいこと〜 を読む
  - 【Next.js入門】ReactフレームワークのNext.jsでマイクロブログを構築しながら基礎と本質を学ぶ講座 | Udemyを見る

## 感じたこと
- 早くSPAを作りたい！
- プログラミングができることは幸せ

## 学習時間
- **プログラミング学習時間**
_*5h<br>
(今週: 30h, 今月: 95.5h)**_

- 趣味(英語・読書・ジム)
  - 英語 0.5h<br>(estimated total hour：2523.5h)
    - 洋書 0h
    - Immersion English 0.5h
  - 読書 0.5h<br>(estimated total read: 218books)
    - プロテスタンティズムの倫理と資本主義の精神
  - ジム 0h<br>(estimated total hour: 302) **2025目標: SQ: 150kg, BP: 100kg, DF: 160kg**
    - SQ107.5kg

# 2025目標
1: Python,TypeScript,React,Next.js,Docker,AWS ECS,Fargate,Terraformを使ったポートフォリを完成させる。<br>
2: TypeScript,React,AWS(or GCP)を使っているプロジェクトで働きはじめる。<br>
3: 8月末に学習時間1000hに到達する。年末に1500hを達成する。<br>

# プログラミング学習時間合計
_**2024**_<br>
10月合計: 130.5h<br>
11月合計: 97h<br>
12月合計: 46h<br>
_**2025**_<br>
1月合計: 71.5h<br>
2月合計WIP: <br>
_**1月までの総合計時間**_: 380h

====================
PyCharm 活用術 (ja)
====================

.. s6:: styles

   'h1': {textAlign:'center', margin:'30% auto', fontSize:'140%'}


私は誰？
==========

.. figure:: images/face.png

http://about.me/shimizukawa, @shimizukawa


* Sphinxの共同メンテナ (2011-)
* PyCon JP 2014 会計
* 共著書・共訳書

  * Sphinxをはじめよう (2013)
  * Pythonプロフェッショナルプログラミング (2012)
  * エキスパートPythonプログラミング (2010)


.. s6:: styles

   'div[0]': {width:'15%', position:'absolute', top:'0', right:'1em'},
   'ul': {fontSize:'70%'},


.. s6:: effect slide


PyConJP2014に出したProposal
============================

#. **Sphinx** ドキュメント翻訳と処理の自動化
#. **Sphinx** のautodocで自動ドキュメンテーションしよう
#. **Sphinx** の開発で心がけていること
#. PyCharm活用術
#. IPython Notebookを使ったコーディング

.. s6:: styles

   'ol': {fontSize:'80%'},
   'ol/li': {display:'none'}

.. s6:: actions

    ['ol/li[0]', 'fade in', '0.3'],
    ['ol/li[1]', 'fade in', '0.3'],
    ['ol/li[2]', 'fade in', '0.3'],
    ['ol/li[3]', 'fade in', '0.3'],
    ['ol/li[4]', 'fade in', '0.3'],

.. s6:: effect slide



自分もプロポーザル出したよ
============================

#. Sphinxドキュメント翻訳と処理の自動化
#. Sphinxのautodocで自動ドキュメンテーションしよう
#. Sphinxの開発で心がけていること
#. **PyCharm活用術** => *採用*
#. IPython Notebookを使ったコーディング

.. s6:: styles

   'ol': {fontSize:'80%'},

Sphinxじゃない！
=================

.. s6:: styles

   'h2': {textAlign:'center', margin:'30% auto', background:'none', fontSize:'150%'}

PyCharmを仕事でもSphinx開発でも、ものすごく使っているので、今日は、PyCharmのすばらしさを伝える発表をします！
===============================================================================================================

.. s6:: styles

   'h2': {textAlign:'center', margin:'0% auto', background:'none', fontSize:'150%'}


お題
========

* PyCharm 活用術

* 利用バージョン: PyCharm 3.4 Pro版

* 題材: PyCon JP 2014のサイトの開発環境
  https://bitbucket.org/pyconjp/pyconjp-website

* `PyCharm機能一覧`__ (`の野良和訳`__)

.. __: http://www.jetbrains.com/pycharm/features/
.. __: https://dl.dropboxusercontent.com/u/284189/pycharm-features-ja/PyCharm%20Python-Django%20IDE%20Features.htm

.. s6:: effect slide

Agenda
=======

* PyCharmで出来ること
* PyCharmで出来ないこと
* PyCharmを導入した感想
* プロジェクトの設定
* エディタの機能
* デバッグ
* テスト実行
* Vagrant連携
* リモートデプロイ
* リモートデバッグ
* データベース連携

.. s6:: styles

   'ul': {fontSize:'70%'},

.. s6:: effect slide

PyCharmで出来ること1
====================

* Python2.x, 3.x 対応
* syntaxチェック, ハイライト
* 強力なコード補完
* virtualenvの作成と管理
* パッケージのインストール, アップデート
* VCS連携
* デバッグ実行

.. s6:: styles

   'ul': {fontSize:'70%'},

.. s6:: effect slide


PyCharmで出来ること2
====================

* ssh越しのリモートデバッグ
* Databaseの操作
* Vagrant起動, ssh接続サポート
* Python,JS同時デバッグ
* 統合されたコンソール操作
* キーバインディングの変更(標準, Emacs, Vim, ...)
* 豊富なプラグイン(標準プラグイン, 3rd-partyプラグイン)
* プラグイン作成(Javaで作る)

.. s6:: styles

   'ul': {fontSize:'70%'},

.. s6:: effect slide


PyCharmで出来ないこと
======================

* プラグイン作成(Javaを勉強したら出来る)
* 単一ファイルを編集するエディタ代わりの使用
* reSTの3スペースインデント(4スペースになっちゃう)

.. s6:: effect slide


PyCharmを導入した感想
=======================

* 環境構築を色々頑張らなくてもよい
* ほとんどの人にデフォルトである程度の利便性を提供できる
* 多くの機能が提供され、難が無い。ただし、ものすごい機能も無い。
* トリッキーな使い方をするとはまる。
* Geek的な面白みは無い
* Vimから乗り換えても良いと感じた(乗り換えた)
* 慣れないJSでのsyntax check, 補完等がうれしい
* メモリをたくさん消費する
* 機能が多くて全てを使いこなすのは大変かも

.. s6:: styles

   'ul': {fontSize:'65%'},
   'ul/li': {display:'none'},

.. s6:: actions

   ['ul/li[0]', 'fade in', '0.3'],
   ['ul/li[1]', 'fade in', '0.3'],
   ['ul/li[2]', 'fade in', '0.3'],
   ['ul/li[3]', 'fade in', '0.3'],
   ['ul/li[4]', 'fade in', '0.3'],
   ['ul/li[5]', 'fade in', '0.3'],
   ['ul/li[6]', 'fade in', '0.3'],
   ['ul/li[7]', 'fade in', '0.3'],
   ['ul/li[8]', 'fade in', '0.3'],

.. s6:: effect slide

ライセンス
===============

* Pro版(企業)
* Pro版(個人)
* Pro版(アカデミック)
* Pro版(OSS)
* コミュニティー版

http://www.jetbrains.com/pycharm/buy/license-matrix.jsp

.. s6:: effect slide

Pro版(企業)
============

* $199/1人
* 利用者付替問わず
* 商用・非商用利用可能
* 1年間バージョンアップ無料

.. s6:: effect slide

Pro版(個人)
============

* $99/本人
* 本人以外利用不可
* 商用・非商用利用可能
* 1年間バージョンアップ無料

.. s6:: effect slide


コミュニティー版
=================

* 無料
* Apache2ライセンス
* 機能が少ない: Web開発サポート(Django, Flask, Google App Engine, Pyramid, web2py), 言語サポート(JavaScript, CoffeeScript, TypeScript, CSS, Cython, Template languages, ...), リモート開発サポート, データベースサポート

.. s6:: effect slide

DEMO
=======


最初にプロジェクト設定が必要
=============================

* 使用するPythonインタプリタの選択
* ソースコードディレクトリの選択(source, template, ignore)
* リポジトリ連携(hg, git, ...)
* ちょっとしたカスタマイズ: pep8警告, プラグイン追加

.. s6:: effect slide


エディタの機能
===============

* 認識できるフォーマット: py, html, css, js, Djangoテンプレート, reST, ...
* 編集差分表示
* 変数補完
* 属性補完
* import補完
* 関数引数の表示
* リネーム
* コード整形

.. s6:: effect slide

デバッグ
=========

* プログラムの実行設定
* ブレークポイント
* ステップ実行
* 条件付きブレーク
* 依存ライブラリのソースコード閲覧、ブレーク
* Djangoテンプレートでブレーク

.. s6:: effect slide


テスト実行
===========

* テストの実行設定
* pytestやnoseのランナーが入っている
* 失敗したテストだけ再実行
* カバレッジ表示

.. s6:: effect slide

Vagrant連携
============

* Vagrantの起動・リロード・終了
* Vagrantfileを利用したssh接続

.. s6:: effect slide

リモートデプロイ
=================

* ソースコードの同期
* 上書き同期の注意点

  * リポジトリ更新で変更されたファイルが同期されないことがある
  * リポジトリ更新で削除されたファイルがリモートから消えない

.. s6:: effect slide

リモートデバッグ
=================

* VMへはsshで接続して開発を行うためGUIエディタ,IDEが利用できない場合が多い
* ssh越しでのデバッグの効率が良くない

PyCharmでは

* リモートインタプリタを設定
* プログラムの実行設定
* リモート実行
* リモート環境の依存ライブラリのソースコード閲覧, break

.. s6:: effect slide

データベース連携
=================

* DBに接続してスキーマやデータの表示
* データの編集
* リモートサーバーのDBにも接続
* ER図の表示
* SQLコンソールでSQL文を書く

.. s6:: effect slide


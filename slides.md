# Theme取得ライブラリの開発

<div style="text-align:center;">

<small>何故かVivliostyle Pubの担当になった<br>
フリー プログラマ</small>
</div>

 高井 歩 / @AyumuTakai


# 現状の問題点

<style>
#products { height: 60%; margin:0 auto -30%; display:block; }
</style>



複数のプロダクトで同じ機能をそれぞれ独自に実装又はファイルを複製して使用している

* ただでさえ少ないマンパワーを有効に活かせていない
* 同じVivliostyleプロジェクトを処理しても、プロダクトごとに結果が異なる可能性がある

![](products.png){id="products"}

# 提案

* 共通部分のライブラリ(npmパッケージ)化で開発効率を上げる<br><br>
* 手始めにテーマ管理機能を独立したライブラリにする<br><br>
* CLIやCreate Bookなどの主要な機能を内包することになるPubをベースに開発を進めて行く<br><br>
* 新しいプロダクトの開発につながるかも


&nbsp;  


&nbsp;

&nbsp;  
  
&nbsp;

# 予定している機能

* 公式テーマの一覧取得
* npmでタグ付けされているテーマの一覧取得
* HTTPサーバ,GitHubなどからテーマを取得
* ローカルファイルからテーマを取得
* テーマファイルやパッケージのダウンロード
* テーマが正しい形式かチェック
* ダウンロード元の更新確認

&nbsp;  

&nbsp;

&nbsp;  
  
&nbsp;

# アンケート(1)

## よく使うテーマの形式は?

* 自作のCSSファイル
* 自作のNodeパッケージ
* 公開されているテーマをそのまま
* 公開されているテーマを改変して

# アンケート(2)

## どのようにテーマを管理してますか?

* Vivliostyleプロジェクトに同梱
* テーマはGitHub(public)で別管理
* テーマはGitHub(private)で別管理
* テーマはGitHub以外で別管理

&nbsp;

# ご協力ありがとうございました

&nbsp;

&nbsp;

&nbsp;  
  
&nbsp;

&nbsp;▽ふ
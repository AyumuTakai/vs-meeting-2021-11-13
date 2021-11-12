# Theme取得ライブラリの開発

 高井 歩 / @AyumuTakai
<div style="text-align:center;">

何故かVivliostyle Pubの担当になった<br>
プログラマ

</div>

# 現状の問題点

<style>
#products { height: 60%; margin:0 auto -30%; display:block; }
</style>



* 複数のプロダクトで同じ機能をそれぞれ独自に実装又はファイルを複製して使用している
* 同じVivliostyleプロジェクトを処理しても、プロダクト毎に結果が異なる可能性がある

![](products.png){id="products"}

# 提案

* 共通部分のライブラリ(npmパッケージ)化で開発効率を上げる
* 手始めにテーマ管理機能を独立したライブラリにする
* CLIやCreate Bookなどの主要な機能を内包することになるPubをに進めて行く

&nbsp;

&nbsp;  
  
&nbsp;

&nbsp;  


&nbsp;

&nbsp;  
  
&nbsp;


# 想定している機能

* npmにvivliostyle-themeとしてタグ付けされているパッケージの一覧取得
* URLを指定してHTTPサーバ,GitHub,ローカルファイルなどからテーマを取得
* テーマファイルやパッケージのダウンロード
* ダウンロード元のアップデートのチェック

# アンケート

1. よく使うテーマの形式は?
1. どうやってテーマを管理してますか?
# Theme取得ライブラリの開発

 高井 歩 / @AyumuTakai
<div style="text-align:center;">

<small>何故かVivliostyle Pubの担当になった<br>
プログラマ</small>

</div>

# 現状の問題点

<style>
#products { height: 60%; margin:0 auto -30%; display:block; }
</style>



* 複数のプロダクトで同じ機能をそれぞれ独自に実装又はファイルを複製して使用している<br><br>
* 同じVivliostyleプロジェクトを処理しても、プロダクト毎に結果が異なる可能性がある

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


# 想定している機能

* 公式テーマの一覧取得
* npmでタグ付けされているテーマの一覧取得
* HTTPサーバ,GitHubなどからテーマを取得
* ローカルファイルからテーマを取得
* テーマファイルやパッケージのダウンロード
* テーマのバリデーション
* ダウンロード元の更新チェック


&nbsp;  

&nbsp;

&nbsp;  
  
&nbsp;

# アンケート

1. よく使うテーマの形式は?<br><br>
1. どうやってテーマを管理してますか?

&nbsp;

ご協力をお願い致します。

&nbsp;

&nbsp;

&nbsp;  
  
&nbsp;

&nbsp;
# Visual Studio 2017 でプロジェクトを作成する

メニューの「新規」から「新しいプロジェクト」を選択します．
ダイアログが表示されるので，左側から「Visual C++」の中の「Windows デスクトップ」を選択し，
中央で「Windows デスクトップウィザード」を選択します．
「ソリューションのディレクトリを作成」はチェックを外しておきましょう．

![project1](/img/proj1-2017.png)

Visual Studio 2013 のように「Windows コンソールアプリケーション」を選択するとハマりますので気をつけましょう．

ウィザードより，

- 「アプリケーションの種類」を「コンソールアプリケーション (.exe)」
- 「追加のオプション」で
  - 「空のプロジェクト」をチェックする
  - 「プリコンパイル済みヘッダー」のチェックを外す（外さなくてもよい）
  - 「セキュリティ開発ライフサイクル (SDL) をチェック」のチェックを外す

と設定します．

![project1](/img/proj2-2017.png)

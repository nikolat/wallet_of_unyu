========================================================================
【ソフト名称】Wallet of Unyu
【 制 作 者 】Don
【 動作環境 】Windows11 23H2 + SSP/2.6.61
【 タ イ プ 】「伺か」用プラグイン
【 取扱種別 】フリーウェア
【 配布月日 】2023-03-26
【 配 布 元 】https://nikolat.github.io/
【  備  考  】後述
========================================================================
■概要

  UNYUとは、伺かの世界で広く流通している暗号通貨です。
  昔はゆうかもなか1箱10個入りが1,800UNYUで買えたと伝えられています。
  これはUNYUを自由に出し入れできるお財布プラグインです。

■一般的な暗号通貨との違い

- 暗号化されていません。取引履歴はセーブファイルに平文で記録されています。
- 誰でも自由に発行できます。5000兆UNYU欲しい。
- もちろん日本円その他通貨と交換はできません。

■使用方法

- ウォレットに入金する
  \![raiseplugin,c58b6320-caf8-11ed-a901-0800200c9a66,OnWalletOfUnyu,set,10000,バイト代だよ！ご苦労さま！]
  [response]
  ID: OnWalletOfUnyu
  Reference0: set
  Reference1: 10000

- ウォレットから出金する
  \![raiseplugin,c58b6320-caf8-11ed-a901-0800200c9a66,OnWalletOfUnyu,set,-1800,ゆうかもなか一丁！まいどあり！]
  [response]
  ID: OnWalletOfUnyu
  Reference0: set
  Reference1: 8200

- 現在の所持金を確認する
  \![raiseplugin,c58b6320-caf8-11ed-a901-0800200c9a66,OnWalletOfUnyu,get]
  [response]
  ID: OnWalletOfUnyu
  Reference0: get
  Reference1: 8200

- メニューを開く
  \![raiseplugin,c58b6320-caf8-11ed-a901-0800200c9a66,OnWalletOfUnyu,menu]
  [response]
  ID: OnWalletOfUnyu
  Reference0: menu
  Reference1: 8200

■更新履歴

2023-03-26  Ver1.0  ・新規作成
2024-03-09  Ver1.1  ・取引毎にセーブファイルを保存(SSPクラッシュ時の保険)

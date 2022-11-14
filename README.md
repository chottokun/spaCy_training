# spaCyの使い方のお勉強 
spaCyは自然言語処理の道具が一揃い揃っている。便利すぎるので使いたい。spaCy3からBERTも（気軽に）使える様になったので、いろんなモデルが使える様にチャレンジ。追加の事前学習をやってみたかった。

- 東北大BERTモデルを使う  
  - [Spacy_with_tf_learning01.ipynb](https://github.com/chottokun/spaCy_training/blob/450a7ee3f2e11f75c55b9cfcb75adad8ec2a8704/Spacy_with_tf_learning01.ipynb)　　
  - https://www.ogis-ri.co.jp/otc/hiroba/technical/similar-document-search/part15.html  
を参考に順に実施してみたが、手間取った。変更しつつ実行。固有表現まで学習。  

- 事前学習モデルの追加学習
  - https://github.com/chottokun/spaCy_training/blob/main/BERT_Further_PRETRAIN_.ipynb  
  - train.txt に追加学習用のデータを用意させて学習。テストでは、まだlossは下がりそうだった。本番？ではじっくりとかなぁ・・・。  

- MobileBERT（JP)に追加学習してみる。
  - 扱いは東北大モデルと変わらず。



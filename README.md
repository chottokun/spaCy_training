# spaCy_training
spaCyの使い方のお勉強。  
spaCyは自然言語処理の道具が一揃い揃っている。便利すぎるので使いたい。spaCy3からBERTも（気軽に）使える様になったので、いろんなモデルが使える様にチャレンジしてみた。

- 東北大BERTモデルを使う  
https://github.com/chottokun/spaCy_training/blob/main/Spacy_with_tf_learning01.ipynb　　
　　
https://www.ogis-ri.co.jp/otc/hiroba/technical/similar-document-search/part15.html  
を参考に順に実施してみたが、手間取った。変更しつつ実行。  　
固有表現まで学習まで完了。  

- 事前学習モデルの追加学習
https://github.com/chottokun/spaCy_training/blob/main/BERT_Further_PRETRAIN_.ipynb  
train.txt に追加学習用のデータを用意させて学習。  
テストでは、まだlossは下がりそうだった。本番？ではじっくりとかなぁ・・・。  


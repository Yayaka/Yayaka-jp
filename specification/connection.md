# コネクション

それぞれのホストは, 異なる2つのホスト間で最初に通信やパケット交換を行う際に*コネクション*確立させなければなりません.  
Yayakaプロトコルは, それらを行う方法や各コネクションサブプロトコルを定義しません.  

## 通信の確立

通信の確立で, ホスト情報で指定された共通の通信プロトコルを用いることが出来ます.
ホストは, ホスト情報で指定されていないコネクションを無視すべきです(SHOULD).
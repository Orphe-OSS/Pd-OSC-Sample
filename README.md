# Pd-OSC-Sample
OrpheをOSC経由で操作したりセンサの値を取得するサンプルです。
ご利用になるためにはOrphe Hub.appが必要です。

Orphe Hub.appはFacebookグループの[Orphe Developers Community](https://www.facebook.com/groups/1757831034527899/)に参加いただくことでダウンロードすることが出来ます。

- Receiver.pd: 受信したセンサ値をナンバーボックスに表示するサンプル
<img width="500" alt="screen shot 2017-07-07 at 15 16 28" src="https://user-images.githubusercontent.com/1403143/27948880-6638454e-6336-11e7-9493-79f606c0446a.png">

- Sender.pd: Orpheの光を操作するサンプル
<img width="500" alt="screen shot 2017-07-07 at 15 16 28" src="https://user-images.githubusercontent.com/1403143/27948912-807c8c80-6336-11e7-89ae-eef93b50e106.png">

- oscTimeInterval.pd: PdからOSCメッセージを送る間隔を最短20msに制限するパッチ

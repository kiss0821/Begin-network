# Begin-network
# 小規模オフィスネットワーク構築

## 概要
Packet Tracerを用いて、小規模オフィスを想定したネットワークを構築する。
部門ごとのVLAN分割、ルーティング、DHCP、ACLによるアクセス制御を実装し、
基本的なネットワーク設計と検証を行う。

## 目的
- VLANの理解を深める
- Inter-VLAN Routingの動作を確認する
- ACLによる通信制御を実践する
- CCNA学習内容をポートフォリオとして可視化する

## 想定環境
- Router 1台
- Switch 2台
- PC 6台
- VLAN 10: 営業部
- VLAN 20: 管理部
- VLAN 30: 来客用

## 使用技術
- VLAN
- Trunk
- Inter-VLAN Routing
- DHCP
- ACL

## 実装予定
- [○] VLAN作成
- [ ] トランク設定
- [ ] ルーティング設定
- [ ] DHCP設定
- [ ] ACL設定
- [ ] 疎通確認
- [ ] 構成図作成
- [ ] 検証結果まとめ

## 検証予定
- 同一VLAN間で疎通できること
- 別VLAN間でルーティングできること
- 来客用VLANから社内VLANへアクセスできないこと

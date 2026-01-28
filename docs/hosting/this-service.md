---
sidebar_position: 1
---

# このサービスについて

SakanaCloudLab Hostingは、SakanaCloudLabが提供するホスティングサービスです。
このカテゴリでは、SakanaCloudLab Hostingの使用方法、機能、およびベストプラクティスについて説明します。左側のサイドバーからトピックを選択して、詳細をご覧ください。

SakanaCloudLabは届出電気通信事業者ではありません。
当組織は、完全に無償で提供される非営利のホスティングサービスを運営しています。

## 利用用途
SakanaCloud Lab Hostingは、以下のような用途に適しています：
- ウェブサイトのホスティング
- Minecraftサーバーのホスティング ←ベスト！
- Minecraftプロキシサーバーのホスティング
- アプリケーションのデプロイメント
- データベースのホスティング

## サーバースペック
SakanaCloud Lab Hostingでは、3つの種類のノードを提供しています。この中から必要な分のリソースを割り当て提供します。：
- **Node1**: 9コアCPU、100GB RAM、500GB SSDストレージ
    - **CPU**: Intel(R) Xeon(R) CPU E5-2640 v4
    - **RAM**: 100GB DDR4 ECC
    - **ストレージ**: 500GB SATA SSD
    - **ネットワーク**: 1Gbps
    - **パネル内表記**: node1

- **Node2**: 9コアCPU、100GB RAM、687.94 GiB HDDストレージ
    - **CPU**: Intel(R) Xeon(R) CPU E5-2640 v4
    - **RAM**: 100GB DDR4 ECC
    - **ストレージ**: 687.94 GiB SATA HDD
    - **ネットワーク**: 1Gbps
    - **パネル内表記**: hddnode
    - **備考**: Node1と同じ物理サーバーに収容されています。主な違いはストレージがHDDである点です。

- **Node3**: 10コアCPU、70GB RAM、500GiB HDDストレージ
    - **CPU**: Intel(R) Core(TM) i7-10700
    - **RAM**: 70GB DDR4
    - **ストレージ**: 500 GiB SATA HDD
    - **ネットワーク**: 1Gbps
    - **パネル内表記**: node3

## バックアップについて
SakanaCloud Lab Hostingでは、必要に応じてサーバーのバックアップ機能を提供しています。
現在hddnode、node3にのみバックアップ機能が提供されています。バックアップは、同一ネットワーク上にあるNASに保存されます。

バックアップが必要な場合は、Discordサーバー内の#利用者サポート チャンネルでお問い合わせください。
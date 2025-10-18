---
layout: ../layout/Layout.astro
---

## ホスト

| ホスト名 | リージョン | 管理者 | 収容ルータ |
| - | - | - | - |
| maple.yude.jp | nrt1 (Chiba, Japan) | yude <i@yude.jp> | nrt1gw1.ops.yude.jp |
| wheel.yude.jp | nrt1 (Chiba, Japan) | yude <i@yude.jp> | nrt1gw1.ops.yude.jp |
| rakka.yude.jp | nrt1 (Chiba, Japan) | yude <i@yude.jp> | nrt1gw1.ops.yude.jp |
| bway.yude.jp | hnd1 (Tokyo, Japan) | yude <i@yude.jp> | hnd1gw1.ops.yude.jp |
| whale.yude.jp | hnd1 (Tokyo, Japan) | yude <i@yude.jp> | hnd1gw1.ops.yude.jp |
| dune.yude.jp | ttj1 (Tottori, Japan) | yude <i@yude.jp> | ttj1gw1.ops.yude.jp |
| hitachi.yude.jp | ibr1 (Ibaraki, Japan) | 百谷涼花 <i@pepepper.net> | - |
| ruby.yude.jp | mte1 (Shimane, Japan) | KusaReMKN <mkn@kusaremkn.com> | gateway.local.kusaremkn.com |
| brick.yude.jp | nja1 (Kanagawa, Japan) | Sgch <sgchsgch.net> | - |
| shrimp.yude.jp | toy1 (Toyama, Japan) | もやしくん <moyashim-25.com> | - |
| katsu.yude.jp | hnd2 (Tokyo, Japan) | はやぶさ <i@h4y4bus4.com> | - |
| mikan.yude.jp | oci1 (Osaka, Japan) | Oracle Cloud Infrastructure | - |
| dekopon.yude.jp | oci1 (Osaka, Japan) | Oracle Cloud Infrastructure | - |

## サービスホスト

| ホスト名 | オペレーティングシステム | 役割 |
| - | - | - |
| maple.yude.jp | Proxmox Virtual Environment | ハイパーバイザ |
| sh.maple.yude.jp | Ubuntu Server LTS | Docker Compose |
| kube-04.ops.yude.jp | Ubuntu Server LTS | Kubernetes master node |
| yudetel.tail5b1c5.ts.net <br /> com.ops.yude.jp | Ubuntu Server LTS | YUDETEL |
| wheel.yude.jp <br /> kube-03.ops.yude.jp | Ubuntu Server LTS | Kubernetes master node |
| rakka.yude.jp <br /> kube-02.ops.yude.jp | Ubuntu Server LTS | Kubernetes master node |
| bway.yude.jp | Proxmox Virtual Environment | ハイパーバイザ |
| sh.bway.yude.jp | Ubuntu Server LTS | Docker Compose |
| whale.yude.jp | Proxmox Virtual Environment | ハイパーバイザ |
| dune.yude.jp | Raspberry Pi OS | データバックアップ (DR) |
| pear.yude.jp | UGREEN NAS OS | データバックアップ (DR) |
| hitachi.yude.jp | Proxmox Virtual Environment  | ハイパーバイザ |
| sh.bway.yude.jp | Ubuntu Server LTS | Docker Compose |
| ruby.yude.jp | Ubuntu Server LTS | サービスホスト |
| brick.yude.jp | Raspberry Pi OS | なし |
| shrimp.yude.jp | Proxmox Virtual Environment | なし |
| katsu.yude.jp | Ubuntu Server LTS | なし |
| mikan.yude.jp | Ubuntu Server LTS | オーバーレイネットワーク |
| dekopon.yude.jp | Ubuntu Server LTS | L2TPv3 over IPsec |

+++
title = "はじめに"
date = 2022-02-02T09:09:41+09:00
weight = 1
chapter = false
# pre = "<b>X. </b>"
+++
---

* この手順書はOracle WebLogic Kubernetes Operatorを使用してKubernetesクラスタにWebLogic Serverドメインを作成する手順と、  
  Operatorの機能を理解することを目的とする

* Operator v3.0からドメインタイプとしてModel-in-imageが追加されたModel-in-imageでは、ドメイン構成はモデルファイルで定義するため環境間での移行が容易であり、  
  ドメインの作成および更新時にドメイン構成に動的な変更が可能となる
  
* 本資料は、以下のOracleドキュメントのチュートリアルに沿って作成されたものである  
  https://oracle.github.io/weblogic-kubernetes-operator/

* この手順書に沿って作業をするにあたって以下の事項を前提とする
  - Docker/Podman、Kubernetes、Helm を理解し操作できること
  - OKE（Oracle Container Engine for Kubernetes）クラスタを利用できること


![aa](https://octodex.github.com/images/dojocat.jpg)

以上
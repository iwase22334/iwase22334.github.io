---
title: "UMA"
layout: single
permalink: /uma/
toc: true

tech_info: 
  - excerpt: "`Python`/`Keras`/`Pandas`/`PostgreSQL`/`Terraform`/`Ansible`/`EC2`/`S3`"
---

{% include feature_row id="tech_info" type="right" %}

## サンプルサイト
[https://iwase22334.github.io/sample-umasec.com/](https://iwase22334.github.io/sample-umasec.com/)


## 概要

機械学習により各馬の走破タイムを出力する。
さらに走破タイムをもとに各馬の勝率を計算する。

![勝率ページ](/assets/images/uma-screenshot.png)


## 仕組み

### 予測

シンプルなニューラルネットワークにより走破時間を算出。
走破時間を出力するのではなく、走破時間の分布を出力させることで、勝率を計算できるようにしている点がポイント。

### システム

以下の図のように、データベースを解析し、ウェブページを自動生成する。 

![アークてくちゃ](/assets/images/uma-architecture.svg)

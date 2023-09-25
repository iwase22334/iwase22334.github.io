---
title: "JBDRAWER"
layout: single
permalink: /jbdrawer/
toc: true
---

## 概要

入力された画像を手書き風にして出力するAI。
図はイメージ。

![概要](/assets/images/jbdrawer-abstruct.svg)


## 仕組み

Deep Q-Networkを使いペイントソフトの操作を学習する。
ポイントは、報酬の計算にニューラルネットワークを使い、入力画像と出力画像の類似度をもとに報酬を決定するところ。

![仕組み](/assets/images/jbdrawer-logic.svg)

## システム

学習にはApe-X DQNのアーキテクチャを採用する。
これにより、経験の生成を並列に行えるようにし、学習効率を向上させる。

![アーキテクチャ](/assets/images/jbdrawer-architecture.svg)


## 結果

単純な図形で試した結果を示す。左側が入力画像、右側が出力画像。
現状一筆書きでかける画像のみ描画できる。
途中で図形が途切れているのは打ち切りまでの操作回数が足りていないため。

![結果](/assets/images/jbdrawer-result.svg)

---
title: "WORKS"
layout: splash
permalink: /works/
date: 2016-03-23T11:48:41-04:00
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/header-works.jpg
  actions:
    - label: "BOOTH"
      url: "https://tapoh.booth.pm/"
  caption: ""
excerpt: "フリーソフトウェアを配信しています"

tech_info: 
  - excerpt: "使用技術 `Rust`/`Tauri`/`React`/`TypeScript`/`tokio`/`axum`/`OAuth2` "

feature_row_time_signal:
  - image_path: /assets/images/time-signal-thumbnail.jpg
    alt: "time signal image"
    title: "鳩時計時報"
    excerpt: "作業に集中しすぎてしまう方 生活にメリハリを持たせたい方へ。 つくよみちゃんたちが読み上げるシンプルな時報アプリ。 一時間ごとに時間を読み上げます。 声は選択することが可能です。<br>
            ソース: [https://github.com/tapoh22334/hatodokei](https://github.com/tapoh22334/hatodokei)"
    url: "https://www.microsoft.com/store/apps/9N65C3J2BSMD"
    btn_label: "Microsoft Store"
    btn_class: "btn--primary"

feature_tuiyomi:
  - image_path: /assets/images/tuiyomi-thmbnail.jpg
    alt: "tuiyomi thumbnail image"
    title: "ついよみ"
    excerpt: 'ツイッターのタイムラインを読み上げます。作業用BGMにどうぞ。
    利用には次のうちいずれかの音声合成ソフトが必要です(VOICEVOX v0.13.1, COEIROINK v1.6.0, LMROID v1.3, SHAREVOX v0.1.7, ITVOICE v1.0.1)<br>
    ソース: [https://github.com/tapoh22334/twradio](https://github.com/tapoh22334/twradio)'
    url: "https://tapoh.booth.pm/items/4503494"
    btn_label: "BOOTH"
    btn_class: "btn--primary"

intro: 
  - excerpt: 'シンプルな時計。windowsガジェット風のUI'

feature_timer:
  - image_path: assets/images/minipomo-window-capture.png
    alt: "minipomo image"
    title: "minipomo"
    excerpt: "一番シンプルなポモドーロタイマー
    常に最前面に表示されタイマーに素早くアクセスできます。
    "
    url: "https://tapoh.booth.pm/items/4253271"
    btn_label: "BOOTH"
    btn_class: "btn--primary"

  - image_path: assets/images/sstimer-window-capture.jpg
    alt: "sstimer image"
    title: "sstimer"
    excerpt: "一番シンプルなタイマー。
    ダイヤルタイマーのように直感的に操作可能です。
    スライダーで時間設定とタイマー開始を同時に行います。
    "
    url: "https://tapoh.booth.pm/items/4374429"
    btn_label: "BOOTH"
    btn_class: "btn--primary"

---

{% include feature_row id="tech_info" type="center" %}

{% include feature_row id="feature_row_time_signal" type="left" %}

{% include feature_row id="feature_tuiyomi" type="right" %}

{% include feature_row id="intro" type="center" %}

{% include feature_row id="feature_timer" %}


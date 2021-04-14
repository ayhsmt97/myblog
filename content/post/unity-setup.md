---
title: "Unity のセットアップ"
date: 2021-04-12T16:30:47+09:00
description: "Unity のセットアップ手順"
draft: false
hideToc: false
enableToc: true
enableTocContent: true
tocPosition: inner
tocLevels: ["h2", "h3", "h4"]
tags:
- Unity
- 環境構築
series:
-
categories:
- 環境構築
image: images/unity-setup/image.png
---

## はじめに

せっかくブログを作ったので、Unity のセットアップ手順を備忘録として残しておきます。
死ぬほど適当なので丁寧に説明されている他サイトを参考にするのが良いでしょう。

## 環境

Manjaro Linux ユーザーです。

```Bash
OS: Manjaro 20.2.1 Nibia
Kernel: x86_64 Linux 5.4.95-1-MANJARO
Resolution: 1920x1080
DE: KDE 5.78.0 / Plasma 5.20.5
```

## セットアップ

### Unity Hub のダウンロード

[公式](https://unity3d.com/jp/get-unity/download) の「Unity Hub をダウンロード」ボタンから Unity Hub の AppImage をダウンロードします。
この Unity Hub から Unity を開いたりプロジェクトを作成したりできるそうです(無知)。

### Unity のアカウント作成

Unity のアカウントを作ります。
今のところは個人使用のみの予定なので ライセンスは Personal としました。

### Unity のインストール

インストールタブから Unity をインストールします。
私は現在の LTS バージョンらしい 2020.3.2f1 を選択しました。

#### モジュールの追加

Unity インストールの際に一緒にモジュールを追加できます。
後で必要なものを入れればいいやと思い、とりあえず何も入れないでおきました。

## 結果

わーいできた

{{< img src="/images/unity-setup/unity-hub.png" alt="Unity Hub の画面">}}

---
layout: post
title: 情報処理安全確保支援士試験を解いた話です！
subtitle: 2回落ちてるけどやっぱり難しい！！！
cover-img: /assets/img/path.jpg
thumbnail-img: /assets/img/thumb.png
share-img: /assets/img/path.jpg
tags: [情報処理安全確保支援士試験]
---

こんにちは！  
H.N.です。  
今回は情報処理安全確保支援士試験の令和元年の午前IIの問題を解いた話をします。

## きっかけ

令和2年春の国家試験はコロナウィルスの影響で中止になってしまい、秋の試験はどうなるのだろうと思っていたのですが通常通り実施されるようです。  
私は過去2回落ちている情報処理安全確保支援士試験に3度目の正直で合格しようと頑張って勉強しているところです。

久しぶりに午前IIの問題を解いたところ、合格点は越えたのですがぎりぎりだったので、復習も兼ねて記事にしようと思います。

## 勉強になったところ

* **FIDO(Fast IDentity Online) UAF(Universal Authentication Framework)**  
  ファイドと読みます。  
  公開鍵暗号方式を使用したクライアント認証技術でオンラインサービスがクライアントを認証する際に用いられます。  
  利用者がディジタル署名を行うことで利用者の認証をします。
  
  ---
  
* **XMLディジタル署名**  
XML文書にディジタル署名を埋め込むことができるのですが、種類が3種類あります。
  * **Detached Signature(デタッチ署名)**  
    署名要素と署名対象要素が独立している場合に用いられます。  
    外部のファイルや、要素に親子関係がない場合など。
  * **Enveloped Signature(エンベロープ署名)**  
    署名要素が署名対象要素の子要素である場合に用いられます。  
    対象文書の中に署名が格納される場合など。
  * **Enveloping Signature(エンベローピング署名)**  
    署名要素が署名対象要素の親要素である場合に用いられます。  
    署名の中に対象文書が格納される場合など。
    
  ---
   
* **CVSS(Common Vulnerability Scoring System)**  
  日本語では共通脆弱性評価システムです。  
  * **基本評価基準**  
    脆弱性自体の深刻度を評価する指標です。
  * **現状評価基準**  
    脆弱性の現在の深刻度を評価する基準です。
  * **環境評価基準**  
    製品利用者の利用環境も含め、最終的な脆弱性の深刻度を評価する基準です。
  
  この3つの基準から脆弱性を定量的に評価します。
  
  ---

* **IPパケットの再構築について**  
  IPパケットは機器によって扱えるパケットサイズが決まっているので、分割は送信元ホストでも中継ルータでも行われます。  
  しかし、パケットの再構築については中継ルータへの負荷軽減のため宛先ホストのみで行われます。

## 感想

こんなに午前IIの問題って難しかったですっけ？？？  
勉強していないとどんどん忘れてしまうのを身をもって感じました。

めげずに一日一試験を目標に頑張っていこうと思います！

以上、「情報処理安全確保支援士試験を解いた話です！」でした。
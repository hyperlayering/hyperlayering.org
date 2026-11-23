---
title: MapそのものがWebになったら？ — SotM Asia 2026でHyper-Layeringを紹介
author: satoru-takagi
date: 2026-11-24
description: SotM Asia 2026のキーノートでHyper-Layeringを紹介。OpenStreetMapの先にある、Web全体を地図の材料として活用する可能性について考えます。
# Use Table of Contents for long posts only.
showToc: false
---

2026年9月7日、大阪で開催された **[State of the Map Asia 2026](https://stateofthemap.asia/)** にて、Hyper-Layeringについてキーノート講演を行いました。タイトルは **“What if the Map itself became the Web?”** です。

講演では、1990年代から続くHyper-Layeringの歩みを振り返りながら、現在の **Layers as Web Apps（LaWA）**、そしてこれからのHLAについて紹介しました。

Hyper-Layeringの基本的な考え方は、独立したWebリソースを、それぞれの独立性を保ったまま、ブラウザ上で地図のレイヤーとして組み合わせることです。情報をあらかじめ一つのシステムに集めて統合するのではなく、提供元がそれぞれの情報やサービスを独立して運用しながら、利用者が必要に応じて組み合わせられるようにします。

当日は実際のシステムやデモを交えながら、防災情報やテーマ別の地図、異なる図法を持つ地図の重ね合わせ、QuadTree Composite Tiling、クライアントサイドでの空間処理など、Hyper-Layeringの実装と利用事例を紹介しました。また、最後にはHyper-Layeringの次の段階として、Webそのものを地図の材料にしていくHLA 3.0の方向性についても触れました。

## SotM AsiaでHyper-Layeringを紹介する意味

SotM AsiaでHyper-Layeringについて話すことには、私たちにとって一つの意味があります。

OpenStreetMapは、誰もが地図を利用し、編集し、共有できるようにすることで、地図をオープンなものにしてきました。では、そのオープンな地図の上で、さらにできることはないでしょうか。

Hyper-Layeringが目指しているのは、地図データだけでなく、地図を構成するさまざまなWebリソースも、それぞれの独立性を保ちながら自由に組み合わせられるようにすることです。OpenStreetMapが開いてきた地図の世界を、さらにWeb全体へと広げていく。そのためには、地図を一つのシステムの中で完結させるのではなく、Web上にある独立した情報やサービスを、そのまま地図の材料として利用できることが重要になります。

![From OpenStreetMap to an Open Map Web](/assets/updates/what-if-the-map-itself-became-the-web-%E2%80%94-introducing-hyper-layering-at-sotm-asia-2026/20261124-074924.webp "From OpenStreetMap to an Open Map Web")

今回のキーノートでは、こうした考え方を **“What if the Map itself became the Web?”** という問いに込めて、OSMコミュニティの皆さんと共有しました。私たちにとっても、Hyper-Layeringのこれからを考える良い機会になりました。

講演のスライドとデモを公開しています。講演で紹介した内容や実際の動作に興味を持っていただけた方は、ぜひご覧ください。

- **Slides and Demo:** [SotM Asia 2026 — What if the Map itself became the Web?](https://hyperlayering.github.io/presentations/SOTMasia2026/)

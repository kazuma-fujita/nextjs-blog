---
title: "Two Forms of Pre-rendering"
date: "2020-01-01"
---

Next.js には、**静的生成**と**サーバー側レンダリング**の 2 つの形式の事前レンダリングがあります。違いは、ページの HTML を生成する**時期**にあります。

-**静的生成**は、**ビルド時**に HTML を生成する事前レンダリング方法です。事前にレンダリングされた HTML は、リクエストごとに*再利用*されます。 -**サーバー側レンダリング**は、**各リクエスト**で HTML を生成する事前レンダリングメソッドです。

重要なのは、Next.js を使用すると、各ページに使用する事前レンダリングフォームを**選択**できることです。
# framer-motion-nextjs-elements

[![License: ISC](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/license/isc-license-txt)

## Description

`framer-motion-nextjs-elements` is a collection of pre-configured Framer Motion elements/components optimized for Next.js. This package allows you to use animations in your Next.js application without converting your server components to client components, preserving the benefits of server-side rendering (SSR).

## Prerequisite
```sh
npm install framer-motion
```

## Installation
```sh
npm install framer-motion-nextjs-elements
```

## Usage/Examples
Import the components you need from `framer-motion-nextjs-elements` and use them in your Next.js server components just like regular HTML elements, without needing to use `"use client"`.

```jsx
import { MDiv } from 'framer-motion-nextjs-elements';

const MyComponent = () => (
  <MDiv
    initial={{ opacity: 0 }}
    animate={{ opacity: 1 }}
    transition={{ duration: 1 }}
    className="container"
  >
    <div>Hello World!</MSpan>
  </MDiv>
);

```


  ## Component Mapping

The following table provides a mapping between standard HTML elements, their Framer Motion components, and the corresponding components provided by this package:

| HTML Element       | Framer Motion Component | framer-motion-nextjs-elements |
|--------------------|-------------------------|--------------------------------|
| `<a>`              | `<motion.a>`            | `<MA>`                         |
| `<abbr>`           | `<motion.abbr>`         | `<MAbbr>`                      |
| `<address>`        | `<motion.address>`      | `<MAddress>`                   |
| `<area>`           | `<motion.area>`         | `<MArea>`                      |
| `<article>`        | `<motion.article>`      | `<MArticle>`                   |
| `<aside>`          | `<motion.aside>`        | `<MAside>`                     |
| `<audio>`          | `<motion.audio>`        | `<MAudio>`                     |
| `<b>`              | `<motion.b>`            | `<MB>`                         |
| `<base>`           | `<motion.base>`         | `<MBase>`                      |
| `<bdi>`            | `<motion.bdi>`          | `<MBdi>`                       |
| `<bdo>`            | `<motion.bdo>`          | `<MBdo>`                       |
| `<big>`            | `<motion.big>`          | `<MBig>`                       |
| `<blockquote>`     | `<motion.blockquote>`   | `<MBlockquote>`                |
| `<body>`           | `<motion.body>`         | `<MBody>`                      |
| `<br>`             | `<motion.br>`           | `<MBr>`                        |
| `<button>`         | `<motion.button>`       | `<MButton>`                    |
| `<canvas>`         | `<motion.canvas>`       | `<MCanvas>`                    |
| `<caption>`        | `<motion.caption>`      | `<MCaption>`                   |
| `<cite>`           | `<motion.cite>`         | `<MCite>`                      |
| `<code>`           | `<motion.code>`         | `<MCode>`                      |
| `<col>`            | `<motion.col>`          | `<MCol>`                       |
| `<colgroup>`       | `<motion.colgroup>`     | `<MColgroup>`                  |
| `<data>`           | `<motion.data>`         | `<MData>`                      |
| `<datalist>`       | `<motion.datalist>`     | `<MDatalist>`                  |
| `<dd>`             | `<motion.dd>`           | `<Mdd>`                        |
| `<del>`            | `<motion.del>`          | `<MDel>`                       |
| `<details>`        | `<motion.details>`      | `<MDetails>`                   |
| `<dfn>`            | `<motion.dfn>`          | `<MDfn>`                       |
| `<dialog>`         | `<motion.dialog>`       | `<MDialog>`                    |
| `<div>`            | `<motion.div>`          | `<MDiv>`                       |
| `<dl>`             | `<motion.dl>`           | `<MDl>`                        |
| `<dt>`             | `<motion.dt>`           | `<MDt>`                        |
| `<em>`             | `<motion.em>`           | `<MEm>`                        |
| `<embed>`          | `<motion.embed>`        | `<MEmbed>`                     |
| `<fieldset>`       | `<motion.fieldset>`     | `<MFieldset>`                  |
| `<figcaption>`     | `<motion.figcaption>`   | `<MFigcaption>`                |
| `<figure>`         | `<motion.figure>`       | `<MFigure>`                    |
| `<footer>`         | `<motion.footer>`       | `<MFooter>`                    |
| `<form>`           | `<motion.form>`         | `<MForm>`                      |
| `<h1>`             | `<motion.h1>`           | `<MH1>`                        |
| `<h2>`             | `<motion.h2>`           | `<MH2>`                        |
| `<h3>`             | `<motion.h3>`           | `<MH3>`                        |
| `<h4>`             | `<motion.h4>`           | `<MH4>`                        |
| `<h5>`             | `<motion.h5>`           | `<MH5>`                        |
| `<h6>`             | `<motion.h6>`           | `<MH6>`                        |
| `<head>`           | `<motion.head>`         | `<MHead>`                      |
| `<header>`         | `<motion.header>`       | `<MHeader>`                    |
| `<hgroup>`         | `<motion.hgroup>`       | `<MHgroup>`                    |
| `<hr>`             | `<motion.hr>`           | `<Mhr>`                        |
| `<html>`           | `<motion.html>`         | `<MHtml>`                      |
| `<i>`              | `<motion.i>`            | `<MI>`                         |
| `<iframe>`         | `<motion.iframe>`       | `<MIframe>`                    |
| `<img>`            | `<motion.img>`          | `<MImg>`                       |
| `<input>`          | `<motion.input>`        | `<MInput>`                     |
| `<ins>`            | `<motion.ins>`          | `<MIns>`                       |
| `<kbd>`            | `<motion.kbd>`          | `<MKbd>`                       |
| `<keygen>`         | `<motion.keygen>`       | `<MKeygen>`                    |
| `<label>`          | `<motion.label>`        | `<MLabel>`                     |
| `<legend>`         | `<motion.legend>`       | `<MLegend>`                    |
| `<li>`             | `<motion.li>`           | `<MLi>`                        |
| `<link>`           | `<motion.link>`         | `<MLink>`                      |
| `<main>`           | `<motion.main>`         | `<MMain>`                      |
| `<map>`            | `<motion.map>`          | `<MMap>`                       |
| `<mark>`           | `<motion.mark>`         | `<MMark>`                      |
| `<menu>`           | `<motion.menu>`         | `<MMenu>`                      |
| `<menuitem>`       | `<motion.menuitem>`     | `<MMenuitem>`                  |
| `<meta>`           | `<motion.meta>`         | `<MMeta>`                      |
| `<meter>`          | `<motion.meter>`        | `<MMeter>`                     |
| `<nav>`            | `<motion.nav>`          | `<MNav>`                       |
| `<noscript>`       | `<motion.noscript>`     | `<MNoscript>`                  |
| `<object>`         | `<motion.object>`       | `<MObject>`                    |
| `<ol>`             | `<motion.ol>`           | `<MOl>`                        |
| `<optgroup>`       | `<motion.optgroup>`     | `<MOptgroup>`                  |
| `<option>`         | `<motion.option>`       | `<MOption>`                    |
| `<output>`         | `<motion.output>`       | `<MOutput>`                    |
| `<p>`              | `<motion.p>`            | `<MP>`                         |
| `<param>`          | `<motion.param>`        | `<MParam>`                     |
| `<picture>`        | `<motion.picture>`      | `<MPicture>`                   |
| `<pre>`            | `<motion.pre>`          | `<MPre>`                       |
| `<progress>`       | `<motion.progress>`     | `<MProgress>`                  |
| `<q>`              | `<motion.q>`            | `<MQ>`                         |
| `<rp>`             | `<motion.rp>`           | `<MRp>`                        |
| `<rt>`             | `<motion.rt>`           | `<MRt>`                        |
| `<ruby>`           | `<motion.ruby>`         | `<MRuby>`                      |
| `<s>`              | `<motion.s>`            | `<MS>`                         |
| `<samp>`           | `<motion.samp>`         | `<MSamp>`                      |
| `<script>`         | `<motion.script>`       | `<MScript>`                    |
| `<section>`        | `<motion.section>`      | `<MSection>`                   |
| `<select>`         | `<motion.select>`       | `<MSelect>`                    |
| `<small>`          | `<motion.small>`        | `<MSmall>`                     |
| `<source>`         | `<motion.source>`       | `<MSource>`                    |
| `<span>`           | `<motion.span>`         | `<MSpan>`                      |
| `<strong>`         | `<motion.strong>`       | `<MStrong>`                    |
| `<style>`          | `<motion.style>`        | `<MStyle>`                     |
| `<sub>`            | `<motion.sub>`          | `<MSub>`                       |
| `<summary>`        | `<motion.summary>`      | `<MSummary>`                   |
| `<sup>`            | `<motion.sup>`          | `<MSup>`                       |
| `<table>`          | `<motion.table>`        | `<MTable>`                     |
| `<tbody>`          | `<motion.tbody>`        | `<MTbody>`                     |
| `<td>`             | `<motion.td>`           | `<MTd>`                        |
| `<textarea>`       | `<motion.textarea>`     | `<MTextarea>`                  |
| `<tfoot>`          | `<motion.tfoot>`        | `<MTfoot>`                     |
| `<th>`             | `<motion.th>`           | `<MTh>`                        |
| `<thead>`          | `<motion.thead>`        | `<MThead>`                     |
| `<time>`           | `<motion.time>`         | `<MTime>`                      |
| `<title>`          | `<motion.title>`        | `<MTitle>`                     |
| `<tr>`             | `<motion.tr>`           | `<MTr>`                        |
| `<track>`          | `<motion.track>`        | `<MTrack>`                     |
| `<u>`              | `<motion.u`             | `<MU>`                         |
| `<ul>`             | `<motion.ul`            | `<MUl>`                        |
| `<var>`            | `<motion.var`           | `<MVar>`                       |
| `<video>`          | `<motion.video`         | `<MVideo>`                     |
| `<wbr>`            | `<motion.wbr`           | `<MWbr>`                       |
| `<webview>`        | `<motion.webview`       | `<MWebview>`                   |

## Why Use This Package?

When using Framer Motion directly in Next.js, you often need to convert server components to client components with `"use client"`, which can limit the benefits of SSR. This package provides ready-to-use animated components that work seamlessly with Next.js server components, allowing you to leverage the power of SSR and dynamic animations together.
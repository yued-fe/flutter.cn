---
title: Test drive
title: 开发体验初探
prev:
  title: Set up an editor
  title: 编辑工具设定
  path: /docs/get-started/editor
next:
  title: Write your first Flutter app
  title: 编写第一个 Flutter 应用
  path: /docs/get-started/codelab
toc: false
---

This page describes how to create a new Flutter app from templates, run it, and experience "hot reload" after you make changes to the app.

本篇教程将介绍如何通过模板来创建一个新的 Flutter 应用，如何运行这个应用，以及如何在你对代码做出修改之后，通过 hot reload 来加载所修改的内容。

Select your development tool of choice for writing, building, and running
Flutter apps.

请选择您用作编写、构建以及运行 Flutter 应用代码的开发工具。

{% comment %} Nav tabs {% endcomment -%}
<ul class="nav nav-tabs" id="editor-setup" role="tablist">
  <li class="nav-item">
    <a class="nav-link active" id="androidstudio-tab" href="#androidstudio" role="tab" aria-controls="androidstudio" aria-selected="true">Android Studio / IntelliJ</a>
  </li>
  <li class="nav-item">
    <a class="nav-link" id="vscode-tab" href="#vscode" role="tab" aria-controls="vscode" aria-selected="false">Visual Studio Code</a>
  </li>
  <li class="nav-item">
    <a class="nav-link" id="terminal-tab" href="#terminal" role="tab" aria-controls="terminal" aria-selected="false">Terminal & editor</a>
  </li>
</ul>

{% comment %} Tab panes {% endcomment -%}
<div class="tab-content">
  {% include_relative _androidstudio.md %}
  {% include_relative _vscode.md %}
  {% include_relative _terminal.md %}
</div>

## Next step

## 下一篇

You'll next learn some core Flutter concepts by creating a small app.

你将会通过创建一个简单的应用来学习一些 Flutter 的核心概念。

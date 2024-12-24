+++
title = 'flowchart'
date = 2024-12-17T05:25:05+07:00
type = 'xpage'
draft = false
categories = ['pages']
tags = ['slide-lib']
authors = ['viridi']
url = '24l13'
+++
<!--more-->

+ A simple flowchart can be as follow.
{{< mermaid >}}
flowchart LR
  B --> I --> C
  C --"Y"--> P1
  C --"N"--> P2
  P1 & P2 --> O --> E
  B(["Begin"])
  I[/"Input"/]
  C{"Condition"}
  P1["Process 1"]
  P2["Process 2"]
  O[/"Output"/]
  E(["End"])
{{< /mermaid >}}
+ Shapes are begin/end, I/O, condition, process.

{{< ref >}}
Maciej Duraj, "Basic overview of creating flowcharts using Mermaid", CKEditor, 8 Mar 2000, {{< url "https://ckeditor.com/blog/basic-overview-of-creating-flowcharts-using-mermaid/" >}} [20241222].
{{< /ref >}}

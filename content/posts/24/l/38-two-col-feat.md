+++
title = 'two-col feat'
date = '2024-12-28T05:20:42+07:00'
draft = false
type = 'xpage'
tags = ['shortcode']
authors = ['viridi']
math = true
url = '24l38'
+++
<!--more-->

{{< twocolumn >}}
{{< scatter >}}
B_XLABEL x
B_YLABEL y
B_SLABEL Data-1
B_PCOLOR #68c
B_PRADII 7
B_LVISIB true
B_LCOLOR #ddf

2, 5
3, 0
4, -3
5, -4
6, -3
7, 0 
8, 5
{{< /scatter >}}

- Left column (default).
```
a + b
```
- Mermaid is not shown.
{{< /twocolumn >}}

{{< twocolumn col="right" markdown="yes" >}}
{{< mermaid >}}
flowchart LR
A --> B --> C --> D --> E --> F --> G
{{< /mermaid >}}


- Right column. 1 2 3 4 5 6 7 8
a | b | c
:-: | :-: | :-:
1 | 2 | 3

$$
y = a x^2 + b x + c
$$

{{< /twocolumn >}}


{{< ref >}}
Author, "Title", Source, Date, {{< url "https://url.com" >}} [20241124]
{{< /ref >}}

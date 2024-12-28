+++
title = 'two-col scatter md'
date = '2024-12-28T07:33:26+07:00'
draft = false
type = 'xpage'
tags = ['shortcode']
authors = ['viridi']
math = true
url = '24l39'
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
{{< /twocolumn >}}

{{< twocolumn col="right" markdown="yes" >}}
- Equation
$$
y = a x^2 + b x + c
$$
- Coefficients
a | b | c
:-: | :-: | :-:
1 | -10 | 21
{{< /twocolumn >}}

{{< ref >}}
Author, "Title", Source, Date, {{< url "https://url.com" >}} [20241124]
{{< /ref >}}

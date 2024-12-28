+++
title = 'two-col code result'
date = '2024-12-28T09:04:30+07:00'
draft = false
type = 'xpage'
tags = ['shortcode']
authors = ['viridi']
math = true
url = '24l42'
+++
<!--more-->

{{< twocolumn markdown="yes" >}}
```py
row = 3
col = 5

for r in range(9, 9 + row):
  for c in range(2, 2 + col):
    s = f'{(r * c):02d}'
    print(s, end=' ')
  print()
print()
print('End')
```
{{< /twocolumn >}}

{{< twocolumn col="right" markdown="yes" >}}
```batch
18 27 36 45 54
20 30 40 50 60
22 33 44 55 66

End
```
{{< /twocolumn >}}

{{< ref >}}
dudung, OneCompiler, 28 Dec 2024, {{< url "https://onecompiler.com/python/434bvb68k" >}} [20241228].
{{< /ref >}}

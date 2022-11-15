---
layout: post
title: HelloWorld Post
date: 2022-08-06 18:48 +0200
categories: [test_cat, test_cat2]
tags: [test]     # TAG names should always be lowercase
mermaid: true
math: true
---


# Title test

Here is a `paragraph` with some unordered list:
* item 1
* item 2

But we can also create ordered lists:
1. ordered 1
2. ordered 2

## Code blocks

```python
my_str = "Hello "
my_str += "World!"
print(my_str)
```

```bash
a="test"
echo $a
```

```console
$ env |grep SHELL
SHELL=/usr/local/bin/bash
PYENV_SHELL=bash
```

## MathJax

> Check [here](https://math.meta.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference) for a lot of examples.
{: .prompt-tip }


$$ a * b = c ^ b $$

$$ 2^{\frac{n-1}{3}} $$

$$ \int_a^b f(x)\,dx. $$

$$ \sum_{i=0}^n i^2 = \frac{(n^2+n)(2n+1)}{6} $$

$$
  f(n) =
\begin{cases}
n/2,  & \text{if $n$ is even} \\
3n+1, & \text{if $n$ is odd}
\end{cases}
$$


$$
  \begin{pmatrix}
    a & b\\
    c & d\\
  \hline
    1 & 0\\
    0 & 1
  \end{pmatrix}
$$

## Mermaid JS

> Official [website](https://mermaid-js.github.io/mermaid/#/) is great ! Plus there is a [Live Editor](https://mermaid-js.github.io/mermaid-live-editor/)
{: .prompt-tip }

### Flowcharts

```mermaid
flowchart LR
    A[Hard edge] -->|Link text| B(Round edge)
    B --> C{Decision}
    C -->|One| D[Result one]
    C -->|Two| E[Result two]
```

### Sequence Diagram

```mermaid
sequenceDiagram
    Alice->>John: Hello John, how are you?
    John-->>Alice: Great!
    Alice-)John: See you later!
```

### State diagram

```mermaid
stateDiagram-v2
    [*] --> Still
    Still --> [*]
%% this is a comment
    Still --> Moving
    Moving --> Still %% another comment
    Moving --> Crash
    Crash --> [*]
```

### Pie chart

```mermaid
pie showData
    title Key elements in Product X
    "Calcium" : 42.96
    "Potassium" : 50.05
    "Magnesium" : 10.01
    "Iron" :  5
```
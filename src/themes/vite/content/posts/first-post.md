+++
title = "示例页面"
date = 2025-09-23
summary = "A showcase of various Markdown elements including Chinese text (中文内容), lists, code blocks, images, and more, styled by Tailwind CSS."
+++

## English

We hold these truths to be self-evident, that all men are created equal, that they are endowed by their Creator with certain unalienable Rights, that among these are Life, Liberty and the pursuit of Happiness.—That to secure these rights, Governments are instituted among Men, deriving their just powers from the consent of the governed,—That whenever any Form of Government becomes destructive of these ends, it is the Right of the People to alter or to abolish it, and to institute new Government, laying its foundation on such principles and organizing its powers in such form, as to them shall seem most likely to effect their Safety and Happiness. Prudence, indeed, will dictate that Governments long established should not be changed for light and transient causes; and accordingly all experience hath shewn, that mankind are more disposed to suffer, while evils are sufferable, than to right themselves by abolishing the forms to which they are accustomed. But when a long train of abuses and usurpations, pursuing invariably the same Object evinces a design to reduce them under absolute Despotism, it is their right, it is their duty, to throw off such Government, and to provide new Guards for their future security.

## 中文

我们认为下面这些真理是不证自明的：人人生而平等，造物主赋予他们若干不可剥夺的权利，其中包括生命权、自由权和追求幸福的权利。为了保障这些权利，人们才在他们之间建立政府，而政府之正当权力，则来自被统治者的同意。任何形式的政府，只要破坏上述目的，人民就有权利改变或废除它，并建立新政府；新政府赖以奠基的原则，得以组织权力的方式，都要最大可能地增进民众的安全和幸福。的确，从慎重考虑，不应当由于轻微和短暂的原因而改变成立多年的政府。过去的一切经验也都说明，任何苦难，只要尚能忍受，人类都宁愿容忍，而无意废除他们久已习惯了的政府来恢复自身的权益。但是，当政府一贯滥用职权、强取豪夺，一成不变地追逐这一目标，足以证明它旨在把人民置于绝对专制统治之下时，那么，人民就有权利，也有义务推翻这个政府，并为他们未来的安全建立新的保障。

## 列表与链接

下面是无序列表:

- Item one
- Item two
  - Nested item
- Item three

下面是有序列表:

1.  First item
2.  Second item
3.  Third item

这是一个[链接](https://www.example.com)

## 引用

> Simplicity is the ultimate sophistication.

## 表格

| A   | B   | C   | D   |
| --- | --- | --- | --- |
| 1   | 2   | 3   | 4   |
| 甲  | 乙  | 丙  | 丁  |

## 媒体

这是一张来自 WikiMedia 的图片！

![Cat!](https://upload.wikimedia.org/wikipedia/commons/thumb/c/c7/Tabby_cat_with_blue_eyes-3336579.jpg/250px-Tabby_cat_with_blue_eyes-3336579.jpg)

## 代码块

```python
def hello(name: str) -> None:
    print(f"Hello {name}!")

if __name__ == "__main__":
    hello("world")

# >> Hello world!
```

This concludes the showcase.

## 块级公式

块级公式会单独占据一行并居中显示，适合展示更复杂的表达式。例如：

$$
\nabla \cdot \mathbf{E} = \frac{\rho}{\varepsilon_0} \\
\nabla \cdot \mathbf{B} = 0 \\
\nabla \times \mathbf{E} = -\frac{\partial \mathbf{B}}{\partial t} \\
\nabla \times \mathbf{B} = \mu_0 \left( \mathbf{J} + \varepsilon_0 \frac{\partial \mathbf{E}}{\partial t} \right)
$$

$$
\int_a^b f(x) \, dx = F(b) - F(a)
$$

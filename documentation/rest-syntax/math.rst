.. vim: syntax=rst


数学符号和公式
==========================================

行间公式
~~~~~~~~~~~~~~~

使用 ``..math`` 标记。

.. math::
   :label: 33

   (a + b)^2  &=  (a + b)(a + b) \\
              &=  a^2 + 2ab + b^2

.. math:: 
   :label: abc

   {{n!} \over {r!\left( {n - r} \right)!}}

.. math:: (a + b)^2 = a^2 + 2ab + b^2
   :label: a


可以给每个公式加上序号。


行内公式
~~~~~~~~~~~~~~~

使用 ``:math:`` 标记。

这是一个行内公式：:math:`(a + b)^2 = a^2 + 2ab + b^2`。

公式引用
~~~~~~~~~~~~~~~~

带有 ``label`` 属性的公式会自动在右侧有序号，以便引用。

可以使用 ``:eq:`` 和 ``:math:numref:`` 来对具有 label 属性的公式进行引用。

参考：

1. https://www.sphinx-doc.org/en/master/usage/restructuredtext/directives.html#math

2. https://www.sphinx-doc.org/en/master/usage/restructuredtext/domains.html#the-math-domain

3. https://www.sphinx-doc.org/en/master/usage/restructuredtext/roles.html#math
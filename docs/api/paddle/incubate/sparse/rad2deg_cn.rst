.. _cn_api_paddle_incubate_sparse_rad2deg:

rad2deg
-------------------------------

.. py:function:: paddle.incubate.sparse.rad2deg(x, name=None)


逐元素将输入 :attr:`x` 从弧度转换为度，要求 输入 :attr:`x` 为 `SparseCooTensor` 或 `SparseCsrTensor` 。

数学公式：

.. math::
    rad2deg(x) = 180/ \pi * x

参数
:::::::::
    - **x** (SparseTensor) - 输入的稀疏 Tensor，可以为 Coo 或 Csr 格式，数据类型为 float32、float64。
    - **name** (str，可选) - 具体用法请参见 :ref:`api_guide_Name`，一般无需设置，默认值为 None。

返回
:::::::::
多维稀疏 Tensor, 数据类型和稀疏格式与 :attr:`x` 相同 。


代码示例
:::::::::

COPY-FROM: paddle.incubate.sparse.rad2deg

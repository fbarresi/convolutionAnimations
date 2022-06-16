# Convolution animations

A technical report on convolution arithmetic in the context of deep learning.
Forked from: [github.com/vdumoulin/conv_arithmetic](https://github.com/vdumoulin/conv_arithmetic)

The code and the images of this tutorial are free to use as regulated by the 
licence and subject to proper attribution:

* \[1\] Vincent Dumoulin, Francesco Visin - [A guide to convolution arithmetic
  for deep learning](https://arxiv.org/abs/1603.07285)
  ([BibTeX](https://gist.github.com/fvisin/165ca9935392fa9600a6c94664a01214))



## Convolution explainations

_N.B.: Blue maps are inputs, green maps are outputs, gray overlay is the kernel._

<table style="width:100%; table-layout:fixed;">
  <tr>
    <td><img width="150px" src="gif/no_padding_no_strides.gif"></td>
    <td><img width="150px" src="gif/same_padding_no_strides.gif"></td>
    <td><img width="150px" src="gif/full_padding_no_strides.gif"></td>
  </tr>
  <tr>
    <td><b>valid</b> convolution</td>
    <td><b>same</b> convolution<br/>Just enough padding is added to keep the size of the output equal to the size of the input</td>
    <td><b>full</b> convolution<br/>Padding is added to make every kernel element visit every single input element</td>
  </tr>
</table>


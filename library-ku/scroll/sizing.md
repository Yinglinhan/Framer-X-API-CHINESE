# Sizing

Scroll组件要求你把所有内容都放到其内部的的Frame元素中，然后计算你滚动产生的偏移量。为了能使它正常工作，它需要能计算内容的总的尺寸。

组件本身会利用ResizeObserver尝试去自动测量组件内的子元素的尺寸，如果它不可用，会有其他的替代方案。但是如果你使用contentwidth和contentHeight，它就会选择不用不去自动测量，如果你想提高滚动动画的性能，那么你可以选择这样做，避免了自动测量的造成的性能损耗。


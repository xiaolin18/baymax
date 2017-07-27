#主要知识点

## z-index: 设置元素的堆叠顺序，堆叠顺序越大越向上；

## border-radius：以百分比确定元素的圆角；

## transform：旋转div;

## position
### 1、static: 默认值，元素出现在正常的流中,不会被特殊定位，top、left、bottom、right、z-index不会起作用；
### 2、relative(相对定位): 不添加额外属性则会和static属性表现一样；
###    添加额外属性top、bottom、left、right、z-index会起作用,但是其他元素的位置不会发生改变，也不会去弥补他移动后遗留下的空隙；
### 3、fixed: 固定定位，元素相对于视窗定位，left、top、right、bottom会起作用，此时脱离文档流，不会保留它原本在页面应有的空隙；
### 4、absolute: absolute与fixed相似，但是它是相对于最近的一个positioned祖先元素，如果没有positioned祖先元素，则相对于文档的body元
###    素，并且会随页面的滚动而移动。positioned元素是指：position值不是static的元素。

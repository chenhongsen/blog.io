#DOM节点
###节点有12种，分别用1-12代表
菜鸟先知道三种：<br>元素节点1（就是各种标签）<br>
属性节点2（就是各种属性“id、class”）<br>
文本节点3（空格、换行符）<br>

##childNodes

#####表示父元素的所有子节点，返回的是一个数组（有长度有下标）

##children

#####类似children，表示父元素的所有子节点中的元素节点

##firstChild \ firstElementChild

#####单个节点，带Element只读元素节点。<br>（lastChild \ lastElementChild也一样）

##nextSibling \ nextElementSibling
#####指定元素的下一个兄弟节点，带Element的只读元素节点。<br>
#####(previousSibling \ previousElementSibling也一样，前一个兄弟）

##ParentNode
#####获取父元素

##offsetParent
#####获取最近的一个有定位的父元素，配合offsetWidth、offsetHeight、offsetLeft、offsetTop使用
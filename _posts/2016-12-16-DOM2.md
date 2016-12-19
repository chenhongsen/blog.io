#DOM操作
<style>
p{color:'red'};
</style>

##获取元素某个属性的值

###语法：元素.getAttribute("属性名")；

    oLi.getAttribute('id')

##修改元素某个属性的值 
###语法：元素.setAttribute("属性名","修改的值")；
    oLi.setAttribute('id','love');

##创建节点

###语法：<br>元素节点：document.createElement("标签类名")；<br>文本节点：document.createTextNode("文本内容")；
    var divChild = document.createElement('div');
    var txt = document.createTextNode(text);

##添加节点
####将游离的节点添加到某个地方
###追加节点:appendChild()
###语法：父元素.appendChild(子节点)
    var divChild = document.createElement('div');
    pa.appendChild(divChild);

##插入节点:insertBefore()
###语法：父元素.insertBefore(插入的节点，原有的节点)；   
    oUl.insertBefore(pb,oLi);

##删除节点
###语法：父元素.removeChild(子节点)；    
    oUl.removeChild(oUl.children[0]);

##替代节点
###语法：父元素.replaceChild(新节点，旧节点)；
    oUl.replaceChild(pa,oUl.children[0]);
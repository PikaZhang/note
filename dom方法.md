document.createElement(tagName)
>通过标签名的形式创建一个元素

parentNode.appendChild(childNode)
>往一个节点里边添加一个子节点，注意是添加在最后

parentNode.insertBefore(childNode1,childNode2)
>往一个节点的指定子节点前边插入一个节点
>如上:childNode1插入到childNode2前边。

parentNode.removeChild(childNodes)
>从一个节点中删除指定的子节点

parentNode.replaceChild(node,childNode)
>node用来替换的节点，childNodes被替换的子节点，两个参数必须写

node.cloneNode(boolean)
>克隆一个节点
>ture:克隆元素和元素包含的子孙节点
>false:克隆元素但不包含元素的子孙节点

node.parentNode
>父节点

node.offsetParent
>定位父级

node.children 
>子元素

node.childNodes
>子节点

node.previousElementSibing
>上一个兄弟元素

previousSibling 
>上一个兄弟节点，包括空白节点

node.nextElementSibling 
>下一个兄弟节点

nextSibling 
>下一个兄弟节点，包括空白节点

node.firstElementChild
>获取node中第一个子节点

node.lastElementChild

>获取node中最后一个子节点

el.getBoundingClientRect()
>获取元素的盒模型信息，返回值对象
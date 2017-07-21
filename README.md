[Demo](https://binbaozhang.github.io/Flex-demo/)

## Flex 布局

* Flex 是 Flexible Box 的缩写，以为弹性布局，为盒装模型提供最大的灵活性
* 任何一个容器都可以指定为 Flex 布局
* 行内元素也可以使用 Flex 布局：display : inline-flex
* Webkit 内核的浏览器，必须加上 -webkit 前缀：display : -webkit-flex
* 设置 Flex 布局之后，子元素的 float、clear、vertical-align 属性将失效

### 设置在容器上的6个属性：
>* flex-direction
>* flex-wrap
>* flex-flow
>* justify-content
>* align-items
>* align-content
    
### 设置在项目上的6个属性：
>* order    
>* flex-grow    
>* flex-shrink    
>* flex-basis    
>* flex    
>* align-self
    
## 参考链接

* [深入理解 flex-grow & flex-shrink & flex-basis](https://segmentfault.com/a/1190000006741711)
* [阮一峰 Flex 布局教程：语法篇](http://www.ruanyifeng.com/blog/2015/07/flex-grammar.html)

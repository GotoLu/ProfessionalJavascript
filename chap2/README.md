#### 在HTML中使用JavaScript
1. script标签
  * 该标签具备6个属性
     * async 立即下载脚本，但是不影响页面的其它操作，比如加载其它资源或者下载其它脚本。只对外部脚本生效
     * charset src属性指定的代码的字符集，较少人使用
     * defer 脚本可以延迟到文档完全被解析和显示后再执行
     * language 已废弃
     * src 包含要执行代码的外部脚本
     * type 可以看做language的代替属性，由于约定俗成，目前一直text/javascript。当没有指定type时，默认仍然是text/javascript
  * 使用了src属性的script标签内部不应该包含js代码，即使包含了js代码也会被忽略
  * 标签位置   
    传统的做法是把所有的script元素放在页面的head元素中。
2. 
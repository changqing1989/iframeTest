# iframeTest
iframe跨域，父子之间方法相互调用
## a.html(端口8094)的iframe里内嵌b.html（端口：8093）
点击b.html(端口8093)新增地址按钮，能触发a.htm(端口8094)的方法（使其另一个iframe里加载c.html(端口：8093)）;
点击c.html(端口：8093)里的保存按钮，能触发b.html里的方法（refresh）;

<!-- YAML
added: v0.9.4
-->

当流或其底层资源（比如文件描述符）被关闭时触发。
表明不会再触发其他事件，也不会再发生操作。

不是所有可写流都会触发 `'close'` 事件。

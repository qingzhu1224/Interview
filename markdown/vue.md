### vue文档 ###

- 动态组件

- 父子之间通信

- 基础组件的自动化全局注册

- 注意在 JavaScript 中对象和数组是通过引用传入的，所以对于一个数组或对象类型的 prop 来说，在子组件中改变这个对象或数组本身将会影响到父组件的状态。


- 事件名使用始终使用`kebab-case`的事件名。

``
<my-component v-on:my-event="doSomething"></my-component>

``
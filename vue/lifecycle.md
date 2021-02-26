# 生命周期 *lifecycle*

生命周期是VUE实例从创建到销毁的过程，过程中有多个钩子(*hooks*)可以被调用，以便开发者在生命周期中加入自己的实现。

## 图示

红框为可使用的hooks

![image](lifecycle.png "lifecycle.png")

<br>

## 示例

~~~typescript
created: function () {
    // `this` points to the vm instance
    console.log('a is: ' + this.a)
}
~~~

RequireComponent的使用：

当你添加的一个用了RequireComponent组件的脚本，需要的组件将会自动被添加到game object（游戏物体）。这个可以有效的避免组装错误。举个例子一个脚本可能需要刚体总是被添加在相同的game object（游戏物体）上。用RequireComponent属性的话，这个过程将被自动完成，因此你可以永远不会犯组装错误。

用法：在新建的类前面加 [RequireComponent(typeof(Rigidbody))]
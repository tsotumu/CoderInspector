# Android Studio辅助开发插件
## 检测代码问题
### 解密检测
 目前代码中用到了加密字符串。需要检测在引用的地方有没有对其解密。
 其步骤如下：
 * 获取当前类的成员列表。
 * 根据获取的列表，分别在工程中查找其引用。
 * 查看引用的地方有无解密。
 * 对没有解密的地方，弹出对话框，提示错误。
 * 对没有解密的地方，自动添加上解密语句。
### format检测
 format错误，会导致程序崩溃，且错我不容易被发现。
 * 检测翻译错误
 * 检测代码里面的format格式错误
## 资料
# [github资料](https://github.com/JetBrains/intellij-sdk-docs)
# [官方文档](http://www.jetbrains.org/intellij/sdk/docs/tutorials/tree_structure_view.html)

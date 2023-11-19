## 如何修复来自 Tailwind CSS 的 unknownAtRules 警告

* 如果使用 VSCode 处理使用 Tailwind CSS 的项目，则可能会在导入 Tailwind CSS 的 CSS 文件中看到警告。

规则 @tailwind 未知
规则 @tailwind 未知
警告很容易被遗漏，除非你使用像 Error Lens 这样的插件，它以内联方式显示错误和警告。然后，警告就变得难以忽视。

那么，如何解决“规则@tailwind未知”警告呢？有几种解决方案可以尝试：

1.设置 Tailwind CSS IntelliSense 插件
2.配置 VSCode 以忽略它们
3.将您自己的描述添加到 Tailwind 的规则中
* 如果您使用的是错误镜头，请禁用警告
1.安装 Tailwind CSS IntelliSense 插件
> 要修复“规则@tailwind未知”警告，请首先安装 Tailwind CSS IntelliSense 插件。

>完成后，您需要将CSS文件与Tailwind CSS相关联。

1. 打开导入 Tailwind CSS 的 CSS 文件
2. 按 Shift + P 并搜索“更改语言模式”
3. 在 VSCode 中更改语言设置
4. 在搜索栏中，输入“tailwindcss”并选择它。
5. 在 VSCode 中选择语言模式
> 现在您的 CSS 文件已与 Tailwind CSS 相关联，警告应该消失了。
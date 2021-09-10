## my-vscode-plugin项目的demo文件

地址:https://github.com/80666881/my-vscode-plugin

### 支持功能

- 最外层package.json的dependencies下按住command能显示提示`(hoverProvider)`

- 点击dependencies能跳转到node_modules下的同名目录的README.md`(registerDefinitionProvider)`

- 在js中输入this.dependencies.，会自动提示package.json的包(aaa,abc)`(completionItemProvider)`

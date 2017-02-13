### Sublime 3或2 Users in Mac

我使用 [Package Control](https://packagecontrol.io/installation)，所有我安装的包在 [Package Control.sublime-settings 文件](https://github.com/schwinnn/sublime-config/Package%20Control.sublime-settings)
 中都列出了。

### 安装步骤

－ 在新系统上 sublime 3/2 安装好之后

```console
cd ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/User/
git clone git@github.com:schwinnn/sublime-config.git
mv sublime-config/* .
rm -rf sublime-config
```

- 到 https://packagecontrol.io/installation 安装 packagecontrol 。这样所有的包会自动安装上。（ ctrl 跟 导引号 来呼叫出 command console ）

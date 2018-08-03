# cz-zh

Status:
[![version](https://img.shields.io/badge/Version-v0.4.0-green.svg)](http://git.cd.romens.cn/npm/cz-conventional-changelog-romens)

Part of the [commitizen](https://github.com/commitizen/cz-cli) family. Prompts for [conventional changelog](https://github.com/stevemao/conventional-changelog-angular/blob/master/index.js) standard.

基于[cz-conventional-changelog](https://www.npmjs.com/package/cz-conventional-changelog)制作的定制化工具

## 安装
~~~shell
$ npm install -g cz-zh
~~~


## 使用
运行下面的命令，使其支持 我们根据Angular规范定制后 的 Commit message 格式。
~~~shell
$ echo '{ "path": "cz-zh" }' > ~/.czrc
~~~

以后，凡是用到`git commit`命令，一律改为使用`git cz`。这时，就会出现选项，用来生成符合格式的 Commit message。


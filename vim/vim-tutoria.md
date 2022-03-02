

# VS Code VIM 插件高效使用

> 文章来源于：[VS Code VIM 插件高效使用](https://www.ohyee.cc/post/note_vim) 有删改

![](./imgs/vim-sheet.gif)

## 权威推荐

[Vim Cheat Sheet](https://vim.rtorr.com/lang/zh_cn)

## VSCode 化

> 相关资料插件，可以参考：[vscode键盘侠养成记](https://juejin.cn/post/6844904099880632328)

由于 VSCode 本身存在一些功能可能与 Vim 冲突，以尽可能提高代码效率需要根据实际需要来决定是使用 VSCode 特性或是 Vim 特性。

插件支持：

- File Utils
- [JavaScript (ES6) code snippets](https://github.com/xabikos/vscode-javascript)
- [ES7 React/Redux/GraphQL/React-Native](https://github.com/dsznajder/vscode-react-javascript-snippets)

安装以后，需要去了解这些 snippets 有哪些 快捷代码的方式；

相关操作：

- `ctr + 0` 聚焦左侧目录栏
- `ctr + shift + e` 聚焦至文件编辑器首行
- `ctr + p` 快速切换文件
- `ctr + `\` 切换至 命令终端

## 模式

*   普通模式
*   插入模式
*   VISUAL 模式

## 光标移动

光标相关移动

*   `h` 左
*   `j` 下
*   `k` 上
*   `l` 右
*   `ctrl + o` 移动到上一光标位置
*   `ctrl + i` 移动到下一光标位置

行相关移动

*   `0`  行开头
*   `$`  行尾
*   `^`  行开头（非空格）
*   `g_`  行尾（非空格）

词句相关移动

*   `w` 下一个词开始
*   `b` 上一个词开始
*   `e` 下一个词结束
*   `W` 下一个词开始（无视标点）
*   `B` 上一个词开始（无视标点）
*   `E` 上一个词结束（无视标点）
*   `(` 句首
*   `)` 句尾

块相关移动

*   `{` 移动到块开始
*   `}` 移动到块结束

屏幕相关移动

*   `ctrl + b` 向上一屏幕
*   `ctrl + f` 向下一屏幕
*   `ctrl + u` 向上半屏幕
*   `ctrl + d` 向下半屏幕
*   `H` 当前屏幕第一行
*   `M` 当前屏幕中间行
*   `L` 当前屏幕最后一行

语言相关一种

*   `gd` 跳转到定义

文件相关移动

*   `gf`  跳转到文件
*   `gg`  文件头
*   `G`  文件尾
*   ` N gg`  第 N 行
*   `N G`  第 N 行
*   `: + N`第 N 行

历史移动

*   `g;` 上一个修改位置
*   `g,` 下一个修改位置
*   `ctrl + o` 上一个跳转位置
*   `ctrl + i` 下一个跳转位置

## 窗口移动

*   `ctrl + w, h` 左边的窗口
*   `ctrl + w, j` 下边的窗口
*   `ctrl + w, k` 上边的窗口
*   `ctrl + w, l` 右边的窗口
*   `ctrl + w, w` 切换窗口
*   `:bp` 上一个标签
*   `:bn` 下一个标签

## 剪切/粘贴

*   `d` 剪切
*   `y` 复制
*   `p` 粘贴
*  ` P` 粘贴到上一行
*   `"_d` 删除（不放置到剪切板）
*   `"0p` 粘贴（忽略剪切的内容）

## 折叠

*   `zc` 折叠代码块
*   `zo` 展开代码块
*   `za` 切换折叠
*   `zR` 展开所有
*   `zM` 折叠所有

## 常用功能

*   `gu` 小写转换
*   `gU` 大写转换




## 参考资料

*   [vim 移动跳转](https://mapan1984.github.io/tool/2016/04/22/Vim-%E7%A7%BB%E5%8A%A8%E8%B7%B3%E8%BD%AC/)
*   [vim技巧：在不同文件buffer间切换，在多窗口跳转和改变窗口大小 - SegmentFault 思否](https://segmentfault.com/a/1190000021070194)
*   [史上最全Vim快捷键键位图（入门到进阶） | 菜鸟教程](https://www.runoob.com/w3cnote/all-vim-cheatsheat.html)
*   [Vim/ROADMAP.ZH.md at master · VSCodeVim/Vim](https://github.com/VSCodeVim/Vim/blob/master/ROADMAP.ZH.md)
*   [vim书签管理 | Y & Y](https://blog.xyxu.top/2018-06-11-vim-mark.html)
*   [vim字符串替换及小技巧](http://xstarcd.github.io/wiki/vim/vim_replace_encodeing.html)




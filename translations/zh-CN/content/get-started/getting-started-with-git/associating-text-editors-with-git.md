---
title: 关联文本编辑器与 Git
intro: 使用文本编辑器打开文件并通过 Git 编辑。
redirect_from:
  - /textmate
  - /articles/using-textmate-as-your-default-editor
  - /articles/using-sublime-text-2-as-your-default-editor
  - /articles/associating-text-editors-with-git
  - /github/using-git/associating-text-editors-with-git
  - /github/getting-started-with-github/associating-text-editors-with-git
  - /github/getting-started-with-github/getting-started-with-git/associating-text-editors-with-git
versions:
  fpt: '*'
  ghes: '*'
  ghae: '*'
  ghec: '*'
shortTitle: 关联文本编辑器
---

{% mac %}

## 使用 Atom 作为编辑器

1. 安装 [Atom](https://atom.io/)。 更多信息请参阅 Atom 文档中的“[安装 Atom](https://flight-manual.atom.io/getting-started/sections/installing-atom/)”。
{% data reusables.command_line.open_the_multi_os_terminal %}
3. 输入此命令：
  ```shell
  $ git config --global core.editor "atom --wait"
  ```

## Using {% data variables.product.prodname_vscode %} as your editor

1. Install [{% data variables.product.prodname_vscode %}](https://code.visualstudio.com/) ({% data variables.product.prodname_vscode_shortname %}). For more information, see "[Setting up {% data variables.product.prodname_vscode_shortname %}](https://code.visualstudio.com/Docs/setup/setup-overview)" in the {% data variables.product.prodname_vscode_shortname %} documentation.
{% data reusables.command_line.open_the_multi_os_terminal %}
3. 输入此命令：
  ```shell
  $ git config --global core.editor "code --wait"
 ```

## 使用 Sublime Text 作为编辑器

1. 安装 [Sublime Text](https://www.sublimetext.com/)。 更多信息请参阅 Sublime Text 文档中的“[安装](https://docs.sublimetext.io/guide/getting-started/installation.html)”。
{% data reusables.command_line.open_the_multi_os_terminal %}
3. 输入此命令：
  ```shell
  $ git config --global core.editor "subl -n -w"
  ```

## 使用 TextMate 作为编辑器

1. 安装 [TextMate](https://macromates.com/)。
2. 安装 TextMate 的 `mate` shell 实用程序。 更多信息请参阅 TextMate 文档中的“[`mate` 和 `rmate`](https://macromates.com/blog/2011/mate-and-rmate/)”。
{% data reusables.command_line.open_the_multi_os_terminal %}
4. 输入此命令：
  ```shell
  $ git config --global core.editor "mate -w"
  ```
{% endmac %}

{% windows %}

## 使用 Atom 作为编辑器

1. 安装 [Atom](https://atom.io/)。 更多信息请参阅 Atom 文档中的“[安装 Atom](https://flight-manual.atom.io/getting-started/sections/installing-atom/)”。
{% data reusables.command_line.open_the_multi_os_terminal %}
3. 输入此命令：
  ```shell
  $ git config --global core.editor "atom --wait"
  ```

## Using {% data variables.product.prodname_vscode %} as your editor

1. Install [{% data variables.product.prodname_vscode %}](https://code.visualstudio.com/) ({% data variables.product.prodname_vscode_shortname %}). For more information, see "[Setting up {% data variables.product.prodname_vscode_shortname %}](https://code.visualstudio.com/Docs/setup/setup-overview)" in the {% data variables.product.prodname_vscode_shortname %} documentation.
{% data reusables.command_line.open_the_multi_os_terminal %}
3. 输入此命令：
  ```shell
  $ git config --global core.editor "code --wait"
 ```

## 使用 Sublime Text 作为编辑器

1. 安装 [Sublime Text](https://www.sublimetext.com/)。 更多信息请参阅 Sublime Text 文档中的“[安装](https://docs.sublimetext.io/guide/getting-started/installation.html)”。
{% data reusables.command_line.open_the_multi_os_terminal %}
3. 输入此命令：
  ```shell
  $ git config --global core.editor "'C:/Program Files (x86)/sublime text 3/subl.exe' -w"
  ```

## 使用 Notepad++ 作为编辑器

1. 从 https://notepad-plus-plus.org/ 安装 Notepad++。 更多信息请参阅 Notepad++ 文档中的“[入门指南](https://npp-user-manual.org/docs/getting-started/)”。
{% data reusables.command_line.open_the_multi_os_terminal %}
3. 输入此命令：
  ```shell
  $ git config --global core.editor "'C:/Program Files (x86)/Notepad++/notepad++.exe' -multiInst -notabbar -nosession -noPlugin"
  ```
{% endwindows %}

{% linux %}

## 使用 Atom 作为编辑器

1. 安装 [Atom](https://atom.io/)。 更多信息请参阅 Atom 文档中的“[安装 Atom](https://flight-manual.atom.io/getting-started/sections/installing-atom/)”。
{% data reusables.command_line.open_the_multi_os_terminal %}
3. 输入此命令：
  ```shell
  $ git config --global core.editor "atom --wait"
  ```

## Using {% data variables.product.prodname_vscode %} as your editor

1. Install [{% data variables.product.prodname_vscode %}](https://code.visualstudio.com/) ({% data variables.product.prodname_vscode_shortname %}). For more information, see "[Setting up {% data variables.product.prodname_vscode_shortname %}](https://code.visualstudio.com/Docs/setup/setup-overview)" in the {% data variables.product.prodname_vscode_shortname %} documentation.
{% data reusables.command_line.open_the_multi_os_terminal %}
3. 输入此命令：
  ```shell
  $ git config --global core.editor "code --wait"
 ```

## 使用 Sublime Text 作为编辑器

1. 安装 [Sublime Text](https://www.sublimetext.com/)。 更多信息请参阅 Sublime Text 文档中的“[安装](https://docs.sublimetext.io/guide/getting-started/installation.html)”。
{% data reusables.command_line.open_the_multi_os_terminal %}
3. 输入此命令：
  ```shell
  $ git config --global core.editor "subl -n -w"
  ```

{% endlinux %}

---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://source.unsplash.com/collection/94734566/1920x1080
# apply any windi css classes to the current slide
class: 'text-center'
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
# some information about the slides, markdown enabled
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# persist drawings in exports and build
drawings:
  persist: false
# use UnoCSS (experimental)
css: unocss
---

# 有用なCLIツールたちの紹介

森田 太郎


<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---

# もくじ

1. **Tmux**: CLIタブ, パネルツール
2. **FZF**: いろいろ使えるfuzzy finderツール
3. **Zoxide**: 便利なディレクトリ移動ツール
3. **StarShip**: Rust製のプロンプト
4. **bat**: きれいなcat
5. **git-delta**: きれいなgit diffツール
6. **exa**: きれいなlsツール
<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/guide/syntax#embedded-styles
-->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
layout: two-cols
---

# Tmux
- ターミナル画面を複数のセッション、ウィンドウ、ペインに分割


<img src="http://livedoor.blogimg.jp/adways04/imgs/f/2/f24fd8cf.png" width=600 />

[tmux (github)](https://github.com/tmux/tmux)
::right::


---
layout: two-cols
---

# FZF
- Fuzzy Finder(あいまい検索)
- カスタマイズ次第でいろいろ使える

[fzf (github)](https://github.com/junegunn/fzf)

::right::
![fzf]( https://cdn-ak.f.st-hatena.com/images/fotolife/y/yiskw713/20220103/20220103192114.png )

---

# Zoxide
- zoxide is a smarter cd command, inspired by z and autojump.

[zoxide (github)](https://github.com/ajeetdsouza/zoxide)

<img src="https://github.com/ajeetdsouza/zoxide/blob/main/contrib/tutorial.webp?raw=true" width=600 />

---
layout: two-cols
---

# StarShip
- きれいなプロンプト。terminalの飾り
- git branchとかgit statusが表示される

<br />

<img src="https://cdn-ssl-devio-img.classmethod.jp/wp-content/uploads/2020/09/prompt_eyecatch-960x504.png" width=600 />

[starship homepage](https://starship.rs/ja-jp/)

---

# Bat
- catのきれい版, ファイルの内容をきれいに表示
- Rust製

<br />

<img src="https://camo.githubusercontent.com/7b7c397acc5b91b4c4cf7756015185fe3c5f700f70d256a212de51294a0cf673/68747470733a2f2f696d6775722e636f6d2f724773646e44652e706e67" width=400 />

[bat (github)](https://github.com/sharkdp/bat)

---

# Git-delta
- git diffのきれい版
- Rust製

<br />

<img src="https://user-images.githubusercontent.com/52205/87230973-412eb900-c381-11ea-8aec-cc200290bd1b.png" width=600 />

[git-delta (github)](https://github.com/dandavison/delta)


---

# Exa

- lsきれい版, ファイルパーミッションとか表示される

<img src="https://github.com/ogham/exa/blob/master/screenshots.png?raw=true" width=600 />

[exa (github)](https://github.com/ogham/exa)

# @vuepress/theme-blog

[![NPM version](https://badgen.net/npm/v/@vuepress/theme-blog)](https://npmjs.com/package/@vuepress/theme-blog) [![NPM downloads](https://badgen.net/npm/dm/@vuepress/theme-blog)](https://npmjs.com/package/@vuepress/theme-blog)
[![NPM LICENSE](https://badgen.net/npm/license/@vuepress/theme-blog)](https://github.com/vuepressjs/vuepress-theme-blog/blob/master/LICENSE)
 
## Sites

- [Documentation](https://vuepress-theme-blog.ulivz.com) - clone this repo and run `yarn && yarn docs:dev`
- [Live Example](https://example.vuepress-theme-blog.ulivz.com/) - clone this repo and run `yarn && yarn example:dev`
- [Live Example - ULIVZ's space](https://ulivz.com/)
- [Live Example - Billyyyyy3320's space](https://billyyyyy3320.com/)



## Install

```bash
yarn add @vuepress/theme-blog -D
# OR npm install @vuepress/theme-blog -D
```


## Usage

```js
// .vuepress/config.js
module.exports = {
  theme: '@vuepress/blog',
  themeConfig: {
    // Please head documentation to see the available options.
  }
}
```

## Author

**@vuepress/theme-blog** © [ULIVZ](https://github.com/ulivz), Released under the [MIT](./LICENSE) License.<br>

> [github.com/ulivz](https://github.com/ulivz) · GitHub [@ULIVZ](https://github.com/ulivz) · Twitter [@_ulivz](https://twitter.com/_ulivz)


# VuepressQuickStarter

## 公式レポジトリからファイルをダウンロード後、yarnコマンドを実行してnode_modulesをインストールします。
yarn

## yarn upgradeコマンドを実行してnode_modulesを最新版にします。
yarn upgrade

## 動くか確認します。
yarn example:dev(exampleのディレクトリ名はblog等適切なものに修正したいところですが、後回しにします)
http://localhost:8080/

## build
yarn blog:build

## deploy
### NetlifyURL
https://vuepress-blog-quickstarter.netlify.app/

### build command
yarn blog:build

### publish directory
blog/.vuepress/dist

## Google Analitics
Vuepressのプラグインを使うより、NetlifyのSnippets Injectionを使う方が簡単。

## Google Search Console
NetlifyのSnippets Injectionを使うのが一番簡単。
<div align="left">
  <b>基于element-ui,有以下修改：</b>
  <ul>
    <li>1.直接修改了基础颜色配置，不用每个系统再单独引入。</li>
    <li>2.input/select/cascader在不可输入状态下，统一增加title属性。</li>
    <li>3.input输入数字时，不需要鼠标滚轮滚动修改数字的效果。</li>
  </ul>
</div>

> A Component Library for PUMC based on element-ui.

## Links
- Homepage and documentation
  - [International users](http://element.eleme.io/#/en-US)
  - [Chinese users](http://element-cn.eleme.io/#/zh-CN)
  - [Spanish users](http://element.eleme.io/#/es)
  - [French users](http://element.eleme.io/#/fr-FR)
- [awesome-element](https://github.com/ElementUI/awesome-element)
- [FAQ](./FAQ.md)
- [Customize theme](http://element.eleme.io/#/en-US/component/custom-theme)
- [Preview and generate theme online](https://elementui.github.io/theme-chalk-preview)
- [Element for React](https://github.com/elemefe/element-react)
- [Element for Angular](https://github.com/ElemeFE/element-angular)
- [Atom helper](https://github.com/ElemeFE/element-helper)
- [Visual Studio Code helper](https://github.com/ElemeFE/vscode-element-helper)
- Starter kit
  - [element-starter](https://github.com/ElementUI/element-starter)
  - [element-in-laravel-starter](https://github.com/ElementUI/element-in-laravel-starter)
- [Design resources](https://github.com/ElementUI/Resources)
- Gitter
  - [International users](https://gitter.im/element-en/Lobby)
  - [Chinese users](https://gitter.im/ElemeFE/element)

## Install
```shell
npm install dt-element-ui -S
```

## Quick Start
``` javascript
import Vue from 'vue'
import Element from 'dt-element-ui'

Vue.use(Element)

// or
import {
  Select,
  Button
  // ...
} from 'dt-element-ui'

Vue.component(Select.name, Select)
Vue.component(Button.name, Button)
```
For more information, please refer to [Quick Start](http://element.eleme.io/#/en-US/component/quickstart) in our documentation.

## Browser Support
Modern browsers and Internet Explorer 10+.

## Contribution
Please make sure to read the contributing guide ([中文](https://github.com/ElemeFE/element/blob/master/.github/CONTRIBUTING.zh-CN.md) | [English](https://github.com/ElemeFE/element/blob/master/.github/CONTRIBUTING.en-US.md) | [Español](https://github.com/ElemeFE/element/blob/master/.github/CONTRIBUTING.es.md) | [Français](https://github.com/ElemeFE/element/blob/master/.github/CONTRIBUTING.fr-FR.md)) before making a pull request.

[![Let's fund issues in this repository](https://issuehunt.io/static/embed/issuehunt-button-v1.svg)](https://issuehunt.io/repos/67274736)

## Special Thanks
English documentation is brought to you by SwiftGG Translation Team:
- [raychenfj](https://github.com/raychenfj)
- [kevin](http://thekevin.cn/)
- [曾小涛](https://github.com/zengxiaotao)
- [湾仔王二](https://github.com/wanzaiwanger)
- [BlooDLine](http://www.ibloodline.com/)
- [陈铭嘉](https://chenmingjia.github.io/)
- [千叶知风](http://mpc6.com/)
- [梁杰](http://numbbbbb.com)
- [Changing](https://github.com/sunzhuo11)
- [mmoaay](https://github.com/mmoaay)

Spanish documentation is made possible by these community developers:
- [adavie1](https://github.com/adavie1)
- [carmencitaqiu](https://github.com/carmencitaqiu)
- [coderdiaz](https://github.com/coderdiaz)
- [fedegar33](https://github.com/fedegar33)
- [Gonzalo2310](https://github.com/Gonzalo2310)
- [lesterbx](https://github.com/lesterbx)
- [ProgramerGuy](https://github.com/ProgramerGuy)
- [SantiagoGdaR](https://github.com/SantiagoGdaR)
- [sigfriedCub1990](https://github.com/sigfriedCub1990)
- [thechosenjuan](https://github.com/thechosenjuan)

French documentation is made possible by these community developers:
- [smalesys](https://github.com/smalesys)
- [blombard](https://github.com/blombard)


## develop
1.Use npm run dist, get lib file.
2.If you want change css,edit it in packages/theme-chalk file, then use npm run build, get css file.The css file won't work util you npm run dist again.

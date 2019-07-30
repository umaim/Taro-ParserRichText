# Taro-ParserRichText

适用于 Taro 的小程序富文本组件，是对 [Parser](https://github.com/jin-yufeng/Parser) 的一个 Taro 组件封装

**目前只适用于微信小程序**

## 用法

1. 将 `ParserRichText` 文件夹复制到项目 `components` 文件夹中
2. 在需要富文本渲染的页面/组件中导入组件 `import ParserRichText from '组件路径';`
3. 需要使用的地方使用 `ParserRichText` 组件即可，访问 [Parser](https://github.com/jin-yufeng/Parser) 了解参数详情及注意事项
4. 在 [NervJS/taro#3885](https://github.com/NervJS/taro/issues/3885) 未解决之前，需要在 config/index.js 文件中添加 config.copy.patterns 复制组件到目标文件夹。参考：[config/index.js#L32](https://github.com/xPixv/SteamCN-Mini-Program/blob/f6ca35869f434127f9d88eb7db3977adb7fd1eb0/config/index.js#L32)

**可访问 [Parser](https://github.com/jin-yufeng/Parser) 原仓库了解更多参数详解及注意事项**

## Demo 示例

本组件用于 [SteamCN 论坛微信小程序](https://github.com/xPixv/SteamCN-Mini-Program) 主贴内容及回复内容的富文本渲染，可在此项目中参考使用方法及预览效果

组件中使用：https://github.com/xPixv/SteamCN-Mini-Program/blob/master/src/components/ReplyCard/replyCard.tsx

页面中使用：https://github.com/xPixv/SteamCN-Mini-Program/blob/master/src/pages/thread/thread.tsx

## 反馈及建议

欢迎 [提出 issue](https://github.com/xPixv/Taro-ParserRichText/issues) 及 PR

## 开源许可

[MIT](https://github.com/xPixv/Taro-ParserRichText/blob/master/LICENSE)

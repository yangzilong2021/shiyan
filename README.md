## Happy Birthday

使用 CSS3，HTML5 设计的“生日快乐” 动画。

URL: http://yifanzheng.github.io/birthday/index.html

### 运行

环境：Node.js

```
npm install
```
&&

```
npm run server-node
```
在浏览器中访问 http://localhost:8080/index.html 。

### 配置内容

在 `config-data.js` 文件中，可修改想要的数据。

```js
var configData = {
  // 祝福标题，内容最好 7 条。默认没有
  title: [
    "G",
    "o",
    "d",
    ".",
    "G",
    "a",
    "o"
  ],

  // 生日祝福的内容，内容条数任意。每句话尽量不要超过 15 个字，不然展示效果可能不太好。
  contents: [
    "送给小丽",
    "祝小丽生日快乐",
    "天天开心",
    "自己与家人身体时刻健康",
    "能一直拥有一个好心态",
    "一路上顺顺利利，平平安安",
    "愿你所愿皆成真",
    "愿你心中烦扰随风散",
    "愿你走的路平平坦坦",
    "愿你，一直好好的",
    "注意休息，晚安"
  ],

  // 按钮描述，默认英文。可以修改成自己喜欢的。
  btn_text: {
    turn_on: "开始",
    play: "音乐",
    bannar_coming: "好像少点东西",
    balloons_flying: "气球？",
    cake_fadein: "蛋糕？",
    light_candle: "蜡烛？",
    wish_message: "生日快乐",
    story: "A MESSAGE FOR YOU",
  }
}
```

### 动画演示

![演示](asset/imgs/show.gif)


### 最后

修改数据，送上生日祝福，可以使用 GitHub Page 将项目发布网上，将链接做成二维码，可以使用微信扫码浏览哟。


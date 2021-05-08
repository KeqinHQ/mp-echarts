# ECharts for miniprogram

此项目为开源项目 [ecomfe/echarts-for-weixin](https://github.com/ecomfe/echarts-for-weixin) 的封装，克勤开发团队自用。

## Quick Start

在小程序 miniprogram 目录执行

```shell
npm i @keqin/mp-echarts --save
```

然后在“工具” -> “构建 npm” 菜单中完成构建。

在小程序 js 中按以下语法可以导入 ECharts 库：

```javascript
import * as echarts from '@keqin/mp-echarts/echarts';
```

在 json 文件中引入 components 的语法为

```json
{
  "usingComponents": {
    "ec-canvas": "@keqin/mp-echarts/ec-canvas"
  }
}
```

npm 包版本号与内置的 ECharts 版本一致。

## 文档

- ec-canvas 小程序语法参考 [ecomfe/echarts-for-weixin](https://github.com/ecomfe/echarts-for-weixin) 
- ECharts 语法可参考 [ECharts 官网](https://echarts.apache.org/zh/index.html)


# Pico Page 文档配图

## 官网首屏

`hero-home.jpg` 于 2026-10-19 从 https://picopage.wulu.zone/ 截取，浏览器视口为 1280 × 720。图中书库和正文为演示数据，非设备实拍。

## 按键与触摸操作

`operation-guide.svg` 是可维护的合成图源文件，内嵌设备模型和正文截图，不依赖外部图片。`operation-guide.png` 为等尺寸导出版本。文档中仅显示这张合并后的操作图，最大宽度为 640 px，窄屏等比缩小，点击可查看原图。

- 设备机身为 AI 生成的 Read Pico 正视模型，非设备实拍；屏幕使用 Pico Page 原始固件截图（https://picopage.wulu.zone/assets/screens/reading.webp），书籍与阅读数据为演示内容。
- 按键行为依据 Pico Page 内置使用说明 `firmware/components/reader_app/help_content.h`；虚线仅用于图注引线和区域标记，不是产品界面。
- 触摸区域依据 `firmware/components/reader_app/app.cpp` 的 `help_regions()`。基准画布为 684 × 1216：正文横向边界为 205 / 479，页脚从 y=1128 开始，页脚左右边界为 x=540。图中分区按屏幕截图的显示比例换算。
- 修改标注后应重新导出 PNG，核对引线、文字和区域边界；不重新生成或改写屏幕内容。

## 发布地址

MDX 使用主仓库 `main` 分支的公开原始文件地址。图片需与文档一并合入主仓库；PR 预览时可使用对应分支的原始文件地址。

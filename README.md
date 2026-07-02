# myAnkiDecks

个人（AI）制作的anki牌组归档。

## 牌组列表

| 目录 | 牌组 | 说明 | 制作方式 |
|------|------|------|----------|
| 汽车车标学习 | 汽车车标学习卡片.apkg | 汽车品牌车标识别学习卡片（100 个品牌，按中/日/德/美/欧/韩 6 大派系分 6 个子牌组） | 车标图片取自开源数据集 [filippofilip95/car-logos-dataset](https://github.com/filippofilip95/car-logos-dataset) 的 optimized 版 PNG；品牌清单（中英文名、国家、分类）人工整理于 `brands.json`；每个品牌的「定位」「Logo 记忆法」文字由 AI 编写；最后用 Python（genanki）自动打包成 `.apkg` |

## 使用方法

1. 下载对应的 `.apkg` 文件。
2. 在 Anki 桌面版中选择「文件 → 导入」，或直接双击 `.apkg` 文件。
3. 牌组将出现在 Anki 中，可直接开始学习。

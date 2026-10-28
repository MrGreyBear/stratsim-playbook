# 07 BoD 作业经验

我们课程每一轮由一位组员向董事会（BoD）汇报，要交三样东西：Strategy data worksheet、Financial data worksheet、One-Page BoD Executive Summary。下面是我们做作业时踩过的坑。你们课程的模板可能不一样，以老师的说明为准。

例子在 [examples/](../examples/)（第 4 轮的版本，已匿名）。

## 通用

- **从老师给的空白模板开始填**，不要拿组员填过的版本改。组员的版本可能有前几轮的公式错误，也容易留下别人的名字和签名。
- 模板里带的**示例页**（比如名字里有 START、P1C1 的页）是给你对照用的，不用交。里面留着 `<fill in>`，会显示 #VALUE! 或红色警告，交之前可以删掉。
- Financial worksheet 的说明写的是**个人作业**：每一轮的数据都要填，包括不是你负责的那几轮。还没发生的轮次（比如你汇报第 4 轮时的第 5、6 轮）不要显示。
- 数据一定要回模拟器核对，不要只抄组员的表。我们核对时发现前几轮有好几个格子填错了。

## Strategy data worksheet

- Key Factors 用的是**上一期**的数据（汇报第 4 轮，就填第 3 轮的结果）。
- Strategy for Exec. Summary 那张表：
  - **跨好几年的项目要合并格子**：比如新车第 1 轮开工、第 3 轮上市，就把这三轮合并成一格。还没上市的新车，也一直合并到上市那一轮。
  - **不同的项目用不同的底色**：major、minor、新车、降成本各一种颜色，再在表下面写一行颜色说明。
  - 正在开发的新车也要列出来，并给它一个优先级。

## Financial data worksheet

| 格子 | 去模拟器哪里找 | 容易错的地方 |
|---|---|---|
| Extraordinary Items: Inventory Writeoff | Income Statement → Extraordinary Items 子页 | 只填 **Inventory Writeoff** 那一行。Extraordinary Items 的合计里还有 Market Research（买调研报告的钱），不要一起填进来 |
| Inventory Disposed | Income Statement → Cost of Goods Sold 子页 | 只有车型升级、换 platform 的那一年才有 |
| Market Cap、行业最高 / 最低 | 门户网站的 Results 页 | 模拟器里 Competition → Financial Summary 的数字可能差 1（四舍五入），以模板指定的页面为准 |
| Dealer Price | Income Statement → Sales Breakdown | = MSRP − 经销商折扣 |
| 每辆车的变动成本、单车广告促销 | Product Contribution → **Per Unit** 子页 | 不要用 Total 页的总额 ÷ 销量，四舍五入会差几十块 |
| 竞品价格区间 | Focus Group（价格四舍五入到千） | — |
| 正负号 | 跟着模板第一列（Start）走 | 成本类（COGS、OpEx、超产能费、税）一般记成负数 |

## One-Page BoD Executive Summary

- 三张图都用截图：StratSim Results 页、Strategy for Exec. Summary 那张表、Summary of Financial Results 那张表。
- 一页放不下就缩小图片和页边距，模板也说可以调间距。
- 截图前把还没发生的轮次去掉或盖住。

## 如果你用脚本或 LibreOffice 处理 Excel

我们用 LibreOffice 重算公式以后，组员在 Excel 里打开，看到满屏的黑色虚线。原因是 LibreOffice 存档时，会在每一页写入一个网格线颜色设置（`<sheetView>` 里的 `colorId="64"`），Excel 碰到自定义颜色的网格线就画成虚线。把每个 `xl/worksheets/sheet*.xml` 里 `<sheetView>` 的 `colorId` 和 `defaultGridColor` 两个属性删掉就好了，不要用 openpyxl 重新存（会丢掉算好的公式值）。

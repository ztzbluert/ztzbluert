# CST 代码
#税法学习/巴西
CST Code 是 Tax Situation Code，由三个阿拉伯数字组成的序列，用于定义公司运营不同方面的税收。
CST 代码有多种类型，例如：
* CST – IPI：指工业化产品税
* CST – ICMS：指商品和服务流通税
* CST – PIS/Cofins：指社会融合计划和对社会保障融资的贡献。
⠀
在 ICMS 的 CST 代码的情况下，数字的组成遵循 ABB 逻辑
* 数字 A 来自表 A，该表描述了商品的原产地。
* 数字 （BB） 来自表 B，它描述了 ICMS 的征收方式：全部、部分、税收[替代](https://www.contabilix.com.br/contabilidade-online/o-regime-de-icms-st-para-as-empresas-do-simples-nacional/)等。
⠀
适用于在正常制度下计算税款的公司（推定利润和实际利润）。
表 A – 货物原产地
|  **法典**   |   **描述**   |
|---|---|
|   0   |   国家/地区，代码 3、4、5 和 8  中指示的除外   |
|   1   |   国外 – 直接进口，代码 6 中指示的除外   |
|   2   |   国外 – 在国内市场获得，代码 7  中指示的除外   |
|   3   |   进口含量大于 40% （40%）  且小于或等于 70% （70%） 的国内商品或商品   |
|   4   |   按照第 288/1967 号法令和第  8,248/1991 号、第 8,387/1991 号、第 10,176/2001 号和第 11,484/2007 号法律规定的基本生产流程 （PPB）  进行生产的国家   |
|   5   |   进口含量小于或等于 40% （40%）  的国内商品或商品   |
|   6   |   国外 – 直接进口，无国家类似物，包含在  CAMEX Resolution 和天然气清单中   |
|   7   |   国外 –  在国内市场收购，无国家类似产品，列入 CAMEX Resolution 和天然气清单   |
|   8   |   国家、商品或商品与导入内容。   |
表 B – ICMS 税收
| **法典**   |   **描述**   |
|---|---|
|   0   |   全额征税   |
|   10   |   通过税收替代对 ICMS 征税和收费   |
|   20   |   减少计算基数   |
|   30   |   免税或不征税，并通过税收替代收取  ICMS。   |
|   40   |   豁免   |
|   41   |   不征税   |
|   50   |   带悬架   |
|   51   |   递 延   |
|   60   |   以前通过税收替代收取的 ICMS   |
|   70   |   减少计算基数和通过税收替代征收 ICMS   |
|   90   |   其他。   |
## 代码应用举例

假设某家公司在国内市场（不在 Camex Resolution 的清单上）收购了外国商品并将其转售给第三方。
CST 代码应该如何启动？

重要信息： 销售将减少 ICMS 计算基础。

要找出第一个数字，我们需要翻到表 A。

根据上述表格中的信息，我们将使用数字 2（国外 – 在国内市场获得，代码 7 中指示的除外）。

要找出 CST 代码的最后两位数字，我们需要查看表 B。

我们已经知道，销售将以减少计算基础进行，根据上述表格，该计算基础对应于数字 20。

然后，我们必须在发票上输入以下 CST 代码：

* CST/ICMS 220 – 在国内市场购买的外国商品（表 A 中的数字 2），按 ICMS 计算基础减税（表 B 中的数字 20）。

⠀
Simples Nacional 中的操作状态代码 – CSOSN

CSOSN，即 Simples Nacional Operation Situation Code，适用于选择简化税制的公司。
|   **101**   |   **由 Simples Nacional  征税，获得信贷许可**   |   **此代码对允许在 Simples  Nacional 中指示 ICMS 汇率和相应信用额度的操作进行分类**   |
|---|---|---|
|   102   |   未经信贷许可被 Simples  Nacional 征税   |   此代码对不允许指示 Simples  Nacional 应付的 ICMS 汇率和信用金额的操作进行分类，并且未包含在代码 103、203、300、400、500 和 900 的假设中   |
|   103   |   Simples Nacional  的总收入范围的 ICMS 豁免   |   该代码对那些选择 Simples  Nacional 的人所从事的操作进行了分类，根据 2006 年第 123 号补充法的条款，对总收入范围授予豁免   |
|   201   |   由 Simples Nacional  征税，获得信贷许可，并通过税收替代方式收取 ICMS   |   此代码对允许指示 Simples  Nacional 应付的 ICMS 汇率和抵免金额以及通过税收替代收取 ICMS 的操作进行分类   |
|   202   |   由 Simples Nacional  征税，未经信贷许可，并通过税收替代方式收取 ICMS   |   此代码对不允许显示 Simples  Nacional 应付的 ICMS 汇率和抵免金额的操作进行分类，并且未包含在代码 103、203、300、400、500 和 900  的假设中，以及通过税收替代收取 ICMS 的操作   |
|   203   |   Simples Nacional  的总收入范围和 ICMS 代缴税的 ICMS 豁免   |   该代码对那些选择 Simples  Nacional 的人所从事的操作进行了分类，根据 2006 年第 123 号补充法的条款，这些操作考虑豁免总收入范围，并通过税收替代征收 ICMS。   |
|   300   |   免疫的   |   此代码对那些选择具有 ICMS 豁免权的  Simples Nacional 的人所执行的操作进行了分类   |
|   400   |   不被 Simples Nacional  征税   |   该代码对选择 Simples  Nacional 的人在 Simples Nacional 内不受 ICMS 税的约束所进行的操作进行分类   |
|   500   |   之前通过税收替代（替换）或预期收取的  ICMS   |   本准则对在税收替代条件或预期情况下受税收替代制度约束的运营进行了分类   |
|   900   |   其他   |   此代码包括不属于代码  101、102、103、201、202、203、300、400 和 500 的其他操作。   |
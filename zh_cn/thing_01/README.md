# 审慎行事

> _"无论你从事何种工作，都应审慎行事并考虑后果。" Anon_

在迭代的开始，无论计划看起来有多舒适，你都无法避免有时会面临压力。如果你发现自己需要在“正确地做”和“快速地做”之间做出选择，通常会选择“快速地做”，以理解你稍后会回来修复它。当你向自己、团队和客户作出这个承诺时，你是认真的。但是，新的问题往往会出现在下一次迭代中，你会变得专注于它们。这种被推迟的工作被称为技术债务，它不是你的朋友。具体来说，在 Martin Fowler 的[技术债务分类](https://martinfowler.com/bliki/TechnicalDebtQuadrant.html)中，这种被推迟的工作被称为有意的技术债务，不应与无意的技术债务混淆。

技术债务就像一笔贷款：短期内你从中受益，但是你必须付出利息，直到完全还清为止。代码中的捷径会使添加功能或重构代码变得更加困难。它们是缺陷和脆弱测试用例的滋生地。你离它越久，它就会变得越糟。当你着手原始修复时，可能会有一整堆不太正确的设计选择叠加在原始问题上，使代码更加难以重构和更正。事实上，只有当情况变得如此糟糕以至于必须解决它时，你才会真正回来解决它。而且到那时，它往往是如此难以解决，你真的无法承受时间或风险。

有时你必须承担技术债务来满足截止日期或实现一个功能的薄片。尽量避免这种情况，但如果情况绝对需要，那么继续前进。但是（这是一个大但是），你必须跟踪技术债务并快速偿还，否则情况会迅速恶化。一旦你决定妥协，就编写一个任务卡或将其记录在你的问题跟踪系统中，以确保它不会被遗忘。

如果你计划在下一次迭代中偿还技术债务，成本将是最小的。未偿还的债务将会产生利息，应跟踪这些利息以使成本可见。这将强调项目技术债务对业务价值的影响，从而使偿还的优先级得到适当的确定。如何计算和跟踪利息的选择将取决于特定的项目，但你必须跟踪它。

尽快偿还技术债务。否则会不明智。

By [Seb Rose](http://programmer.97things.oreilly.com/wiki/index.php/Seb_Rose)

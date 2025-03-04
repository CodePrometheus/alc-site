+++
author = "王皓月"
title = "Apache 项目网站商标原则"
date = "2021-03-01"
description = "介绍了Apache项目网站商标在使用过程中需要注意的原则问题"
tags = [
    "Apache Policy"
]
+++
# Apache 项目网站商标原则

翻译: 王皓月

原文地址: http://www.apache.org/foundation/marks/pmcs

本文定义了商标原则，定义了 Apache®projects 网站显示的元素，以及如何正确地对待 Apache 和其他组织的商标。[PMC 商标责任](http://www.apache.org/foundation/marks/responsibility.html)还解释了 PMC 成员应该以何种方式管理项目商标。

# 项目网站和 URL 原则：使用 * .APACHE.ORG

- Apache 项目必须在 `apache.org` 域上托管官方网站，包括由项目 PMC 监督的内容（包括顶级网站，下载和 Wiki），并确保 ASF 基础架构团队可以维护服务，同时告知用户该内容是官方的并且来自 ASF 和项目 PMC，而不是来自第三方。
- 任何 *ProjectName* 的主页都必须由 `http[s]://ProjectName.apache.org` 提供服务，以确保商标一致，且允许自动生成链接（例如 [https://projects.apache.org](https://projects.apache.org/)）。项目的所有主链接都必须直接指向主页，而不是其他站点或域。
- 项目可以自由地使用基础架构支持的[技术](http://www.apache.org/dev/project-site.html)来管理和部署网站，并且可以自由使用设计中的外观。未来，我们可能会要求项目添加特定的样式或者图形元素（从多种变体中选择），以使其返回链接 www.apache.org，这将有助于用户更好地了解 Apache 项目之间的联系。
- 拥有悠久的开源开发历史和庞大的用户群新社区进入 Apache 孵化器前，应该阅读[使用 non-apache.org 域的限制](http://www.apache.org/foundation/marks/pmcs#nonapache)。

# 项目命名和描述原则

*存在[新项目名称](http://www.apache.org/dev/project-names)的选择准则，但尚未进行审查并合并到此原则文档中。*

- 任何项目或产品名称的主要商标必须采用“Apache *Projectname* ”的形式，这样可以确保在用户心中，项目或产品与 ASF 相关联，并确保第三方不能轻易滥用项目名称。项目或产品的每个页面中第一个最重要的引用，以及页面标题中的引用，都必须使用其名称的“Apache *Projectname* ”形式。其他引用可以根据主题使用“ Apache *Projectname* ”或“ *Projectname* ”。
- 该产品的每个产品主页和任何概述下载页面都必须包含对该产品的突出引用，称为“ Apache Foo 软件”，并且必须包含对该软件产品本身的用途和功能的简短描述。例如：

> Apache Xerces XML 解析库软件提供了 XML 1.0解析规范的完整实现，并且易于配置，符合当前标准。

该描述对于页面的新读者非常有用，并有助于 ASF 维护软件产品商标的完整列表。仅在与特定种类的商品关联时，商标才重要：在案例中，这是 ASF 和 PMC 提供的可实际下载的软件产品。

请注意，共享关于商标 @ 的示例描述是有帮助的，可以确保它是正确的商标商品描述。 例如，在过去 Apache Tomcat 的网站上，它是“实现”和“协作”，而不是具有功能的产品。 Apache Spam Assassin 的网站将自己描述为一个“项目”和“版本”，并将其称为“it”。 两者都没有包含正确的商标商品描述（即执行功能的计算机软件）。 虽然这种商标描述风格有时在技术文档中显得笨拙，但这是我们强制实施商标原则的一种重要方法。对于每个项目，只需要在网站上的显眼位置进行即可。

- 项目和产品名称应该使用一致的大写字母和形容词，而不是名词或动词，这是所有商标应该使用的。 在项目主页和下载页面上进行此操作很重要；在网站或技术产品文档的其他地方，它是不需要的。
- 我们认为所有项目、子项目和产品的名称都是 ASF 的商标。尽管并非所有暴露出的产品名称（即“ Foo”）都可能是 ASF 的专有商标，但所有“Apache Foo”形式的名称都应该是 ASF 的专有商标。

**术语**：**项目**或**子项目**是由 PMC 管理的社区和任何相关产品；同一商标指南适用于两者。**产品**是一种特定的、可下载的软件产品，我们的用户可能希望以某种方式进行使用。产品商标有一些具体的要求。注意，大多数项目和子项目发布的产品名称相同（例如 Apache Foo 项目发布了一个名为 Apache Foo 的软件产品)。

# 网站导航链接原则

无论您的项目网站使用哪种主导航系统，它都必须具有指向主网站 `www.apache.org` 关键页面的文本链接。这些链接可以出现在项目或子项目的所有顶级页面使用的主导航系统中。

- “许可证”应链接到： `www.apache.org/licenses/`
- “赞助”或“捐赠”应链接到： `www.apache.org/foundation/sponsorship.html`
- “赞助商”、“感谢”或“感谢我们的赞助商”应链接到： `www.apache.org/foundation/thanks.html`
- “安全性”应该链接到项目的特定页面，该页面详细描述用户如何安全地报告潜在漏洞，或者链接到主页面  [www.apache.org/security/](http://www.apache.org/security/)
- 所有项目都必须有指向 ASF 主页 `www.apache.org` 的链接。这可能是主导航系统中的精选链接，也可能是主页文本中的文本链接。最佳做法是在首页上包含简短的句子或段落，以表明该项目是 Apache 项目，是更大的开发人员和用户社区的一部分。

如果您对指向 ASF 主页的链接有更适合项目 Web 展示的建议，请告知商标@。

**包括指向第三方的“感谢”链接**-如果您的项目通常有公司捐赠软件许可证或支持项目提交人，请遵循[公司认可准则](http://www.apache.org/foundation/marks/linking)。重要的是要确保与正式赞助计划相关的材料以截然不同的方式公开展示此类页面。

# HTTPS 还是 HTTP？

项目可以免费使用 http，https 或协议的相关链接作为网站导航链接所需的强制链接。

建议（但不是要求）项目：

- 使用 https 链接，使用 http 时目标自动切换到 https
- 对所有其他目标使用协议相关链接

# 商标归属原则

- 所有项目或产品主页必须具有所有可用的 Apache 商标的显著商标归属。其他项目页面应显示其上任何标记的归属。例如：

> Apache Foo、Foo、Apache、Apache 羽毛 logo 和 Apache Foo 项目 logo 是 Apache 软件基金会在美国和其他国家的注册商标。

它可能出现在页面页脚或任何其他合适的位置。

- 在每个项目或产品主页的顶部，以及项目名称出现的每个页面的顶部横幅上，无论是标题文本还是在运行文本中第一次出现的名称，都应该在“Apache Foo”项目名称的首要位置旁边添加合适的™或®符号。这突出了我们的商标主张，并强调了它对我们的重要性。
- 必须对网站上引用的任何其他组织的商标给予正确的归属。当在 ASF 项目网站上显示时，所有非 ASF 商标都必须归所有人所有。可以针对每个引用的标记专门执行此操作，或者一般地，在网页的页脚中执行此操作。具体举例：

> FooBar 和 FooBar logo 是 Yoyodyne，Inc. 的商标。

要提供通用的商标归属（以涵盖使用大量商标的情况，或者在我们不确定哪些词是哪个组织的商标的情况下），您可以添加：

> 提及的所有其他标记可能是其各自所有者的商标。

# LOGO和图形原则

- Logo 也是识别商标的重要方式。对于项目的官方 logo（如果有，特别是使用 ASF 羽毛 logo），请确保在图形有一个小的“TM”符号与它相邻。对于包含项目 logo 的页面，请确保在属性中“... 和项目 logo 是商标...”。
- 项目可以选择在 logo 中使用 Apache 羽毛。有关正确的 Apache [视觉标识和羽毛图形](http://www.apache.org/foundation/press/kit/#links)的详细信息，请使用press @。

# 技术支持...Logo

鼓励项目将主 logo 改为“Powered By ...”或“Project Inside” logo。第三方可以使用此 logo 来表示他们使用了相关产品构建产品或服务。虽然我们必须确保主要产品 logo 与 Apache 项目提供的产品相关联，但我们允许第三方与自己的产品一起更广泛地使用[“Powered by ...” logo](http://www.apache.org/foundation/marks/faq/#poweredby) 。

[由 Apache 支持的 logo](http://www.apache.org/foundation/press/kit/#poweredby) 可供所有项目使用（或请求更新）。

# 项目元数据

所有项目都必须为项目本身或它们所制作的所有产品版本提供 DOAP（项目描述）文件或条目，或者提供结构化的数据，以便 projects.apache.org 网站可以找到它。按照[指南](https://projects.apache.org/about.html)制作 DOAP 文件并注册，可以使 ASF 更好地以各种方式展示其所有项目和产品。

更新 [Apache 商标列表](http://www.apache.org/foundation/marks/list/)，简要描述每个软件产品。未来，我们希望从所有产品的 DOAP 文件中生成此列表。

# 其他商标要求

如果您的项目有特定软件语言的子项目，请确保恰当地命名项目。例如，“Apache Xerces Perl”不合适，因为它没有正确地使用商标“Perl”。更好的项目名称是“Apache Xerces for Perl”。例如，ASF 可以允许名为 FooBar 的第三方发布名为“Foo Bar Software for Apache Xerces”或“Bar Foo Services for Apache Xerces”的软件产品。由于 Xerces 是我们的商标，因此 ASF 不允许 FooBar 使用名称“Foo Bar Xerces”或“BarFoo Xerces”。“ Perl”（[Perl Foundation 商标](https://www.perlfoundation.org/trademarks.html)）一词的使用也是如此。

**注册商标** 如果PMC想要请求对其项目商标进行合法注册，请注册其商标，请遵循 [REGREQUEST 指南](http://www.apache.org/foundation/marks/register#register)。

## 与项目相关的 NON-APACHE.ORG 域名

为了确保商标一致，以及用户知道 ASF 和 PMC 提供的官方内容，所有的项目都必须托管在 ProjectName.apache.org 域中，并由 PMC 管理所有内容。

**重要说明：**项目不得使用第三方拥有的域名托管官方项目内容。必须迁移内容，或者将域注册转移到 ASF。

如果进入 Apache 孵化器的新社区使用了很长时间的现有域名，并且拥有庞大的用户群，那么一旦该被孵化项目毕业进入 TLP，可能会请求保留这些名称以供有限使用。

**非 apache.org 域的孵化步骤**

- 在孵化期间，PPMC 必须与 Apache Infrastructure 合作，将所有需要的域名注册正式转移到 ASF。作为一个非营利组织，ASF 期望这些域名是会被捐赠给 ASF 的。

  创建 INFRA JIRA 来向 ASF 申请接管捐赠的域名所有权。

- PPMC 应该将其打算如何使用非 apache.org 域名的计划发送给 Brand Management / trademarks @ 进行批准。

- 在孵化期间，PPMC 必须将所有面向开发的信息以及主要项目主页转换为官方 ProjectName.apache.org 主页。在项目毕业之前，需要完成这些转换。

**使用 non-apache.org 域要考虑的因素**

- 主要的开发主页必须托管在 ProjectName.apache.org，该主页包含潜在贡献者在决定是否加入该项目前需要了解的所有常见事项。
- 向潜在贡献者推广该项目的主要链接应该始终直接指向 ProjectName.apache.org 资源，而不是非 apache.org 域。
- 在大多数情况下，non-apache.org 域应该简单地重定向到 ProjectName.apache.org/path 域内的某个地方，除非被孵化项目有使用非 apache.org 域的充分理由：

-- 在项目进入 ASF 之前，用户和贡献者社区就已经非常熟悉该域。

-- 域仅用于提供终端用户级别的信息。

-- 该域在外观上与 Apache 网站一样都是 Apache 商标，并为所有可能的贡献者话题（例如下载，API文档，邮件列表等）提供直接指向 project.ao/path 的清晰链接。

**non-apache.org 域批准示例**

这些是例外，大多数新项目并非如此：

- openoffice.org 是一个面向用户的门户网站，具有悠久的历史和数百万的用户。继续作为用户门户为现有的非技术用户提供服务很重要。
- groovy-lang.org 是长期运行的面向用户的门户。该域仍被用作终端用户门户，包括 Groovy 语言本身的信息。开发人员信息（供 Groovy 代码库的贡献者使用），讨论和下载都在 groovy.apache.org 网站上。

# 项目商标清单

所有 Apache 顶级项目都应该完全符合这些指南。任何不符合要求的项目都必须使用商标 @，以确保它们符合要求。所有孵化器项目要么在毕业前符合所有要求，要么制定具体的短期行动计划，以在毕业后短期内完成要求（如果网站更新存在技术问题等）。

如有品牌问题，请直接与商标 @ 联系 - 不再需要在董事会报告中包括此内容。

**项目品牌报告清单** - [项目网站基础](http://www.apache.org/foundation/marks/pmcs#websites)：主页为 project.apache.org

- [项目命名和描述](http://www.apache.org/foundation/marks/pmcs#naming)：使用正确的 Apache 形式描述产品等。
- [网站导航链接](http://www.apache.org/foundation/marks/pmcs#navigation)：包括导航栏链接，包括 www.apache.org 的链接
- [商标属性](http://www.apache.org/foundation/marks/pmcs#attributions)：包括页脚中所有 ASF 商标的归属
- [Logo 和图形](http://www.apache.org/foundation/marks/pmcs#graphics)：包括 TM，在您的网站上使用一致的产品 logo
- [项目元数据](http://www.apache.org/foundation/marks/pmcs#metadata)：DOAP 文件签入且更新
- [阅读 PMC 商标职责](http://www.apache.org/foundation/marks/responsibility.html)

# 理由

该原则有助于提升和改善 ASF 中所有项目的形象，并表明所有 Apache® 项目都是“开发人员和用户社区”的一部分，我们认为这是我们成功的重要因素。虽然每个项目都按照 Apache Way 的准则来管理自己的事务，但一个一致的公共品牌和网络的存在，能够将所有的项目与知名的 `www.apache.org` 主页联系在一起，通过确保终端用户和未来贡献者了解如何找到官方项目资源，这将使我们都受益。

同样，在我们的项目页面上正确显示 Apache 名称和 logo 有助于维护我们对其所包含商标的合法权利。使用合适的 ™ 和 ® 符号，并正确使用商标来指代真实软件产品，是我们告诉世界（和律师）这些商标对我们有价值的关键方式。

**有问题吗** 有疑问的 Apache Committer 可以联系[商标委员会](http://www.apache.org/foundation/marks/contact#pmc)。[官方的商标原则](http://www.apache.org/foundation/marks/)解释了其他组织应该如何引用 Apache 项目商标和 logo。还提供了 [ASF 商标列表](http://www.apache.org/foundation/marks/list)和 [潜在商标滥用准则](http://www.apache.org/foundation/marks/reporting.html)。

Apache 孵化器中的孵化项目有详细的[孵化项目商标指南](http://incubator.apache.org/guides/branding.html)。有关这些指南的问题直接发送至 general@incubator 列表。毕业进入顶级项目之前，孵化项目必须遵守所有项目商标要求。

# 重要说明

**本 ASF 政策声明中的任何内容不得解释为允许任何第三方声称与 Apache 软件基金会或其任何项目有任何关联，或暗示 ASF 对任何第三方产品、服务或事件的任何批准或支持。**

本文档针对 ASF 的内部社区和管理我们项目的 PMC，并且不覆盖或替代我们的[正式商标政策](http://www.apache.org/foundation/marks/)。如果您有一个未解决的问题或者想进一步了解，请[与我们联系](http://www.apache.org/foundation/marks/contact#pmc)。可获取更多有关商标法律和政策的更多[资源](http://www.apache.org/foundation/marks/resources)。

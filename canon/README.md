# canon / 索引

持续更新——会增，也会减。读完之后觉得放错了的，会拿掉。

每一篇入选前都尽量按两个维度看过：文字本身在时间下游仍然站得住；作者在这件事上花过很长时间，付过代价，写的时候没有在做姿态。宁缺毋滥。

选文时也留意 vidyā 几个内核的交叉——死亡与有限性、跨领域的意外通用性、语言对思想的有损压缩——一篇文章在这些维度上触及越深，越可能值得在这里出现。

分类依据是"这篇文章对读者做了什么"，而非学科——这样加入任何领域的内容（科学、文学、宗教、艺术）都能直接归位，不必每次重排。一篇好文章往往同时让你**看见**、让你**造物**、让你**反躬**、让你**立命**；我把它放在它最主要做的那件事下。每一类内部按"沉淀的厚度"和"对其他文章的解释力"排列——越靠前的，越能改变你读后面文章的方式。

---

## 推荐起点

最先读这三篇。每篇打开一扇不同的门——读完之后，你看 canon 任何一篇的方式都会变。

1. **[You and Your Research](career/hamming_you_and_your_research.md)** — Hamming
2. **[The Tacit Dimension](inquiry/polanyi_tacit_dimension.md)** — Polanyi
3. **[Simple Made Easy](languages/hickey_simple_made_easy.md)** — Hickey

Hamming 给你 canon 的第一条定向——"在重要的问题上工作"。Polanyi 解释了为什么 canon 是这种形态。Hickey 给你一把可以一辈子带在身上的尺。

> Hardy 的《一位数学家的辩护》原在第二位，与 Hamming 互为对立。当前 canon 内的版本被发现是压缩摘要，违反项目原则，已撤下。详见 `trace/_deleted.md`。合格中译出现前，这条张力暂不在 canon 内。
>
> **Polanyi 当前文件疑似压缩**（24k 字 vs 完整中译预期 50–60k 字），尚未与原文逐段核对。这条推荐成立的前提是文件忠实——目前这个前提未被验证。详见该文件顶部状态块。

---

## 一、看见

这一类做同一件事：给你一副新的眼镜。读完之后，从前看过的东西看着不一样了——不一定看到了更多，而是看见了从前不在视野里的东西。这是 canon 最大的一类。真正值得读的写作，多数本质上是在给你新的看法。

### [The Tacit Dimension](inquiry/polanyi_tacit_dimension.md) — Michael Polanyi, 1966
三篇讲座，核心命题是开篇一句话："我们知道的，比我们能说出的多。"默会知识有从-至结构：我们从线索出发，抵达我们正在关注的对象；线索本身退入背景，成为身体的延伸。Naur 的《作为理论建构的编程》直接引用了这个框架——程序员头脑中的"理论"，就是波兰尼意义上的默会知识。这解释了为什么接手别人代码如此之难：那些知识从未被写下来过。
> **当前文件状态**：疑似压缩，待与原文核对。详见文件顶部状态块。

### [Programming as Theory Building](languages/naur_programming_as_theory_building.md) — Peter Naur, 1985
Naur 是 ALGOL 60 的设计者之一，BNF 范式（Backus-Naur Form）的共同命名者，2005 年图灵奖。本文的核心命题是：程序不是源码。程序是程序员脑子里共同持有的一种理解——借用哲学家 Ryle 的概念，Naur 称之为 theory。代码只是这个 theory 的有损书面投影。团队解散，程序就死了；文档留下来，但 theory 带不走。这解释了为什么接手别人的代码如此之难，为什么修改总是把结构改坏，以及为什么有时候推倒重写比修复更便宜。

### [Augmenting Human Intellect: A Conceptual Framework](vision/engelbart_augmenting_human_intellect.md) — Douglas Engelbart, 1962
Engelbart 是鼠标、超文本、协同编辑的发明者；1968 年他主持的演示后来被称为 "the Mother of All Demos"，一次性预演了之后五十年的个人计算图景。他一生在做同一件事：让人类的集体智识被工具放大。本文是他这件事的纲领——提出 H-LAM/T 框架：人与他的语言、人工物、方法论、训练共同构成一个增智系统。我们今天习以为常的工作方式，几乎都可以追溯到这份纲领。
> **当前文件状态**：占位，仅含元数据与译者按，正文待翻译。原文为 SRI 完整技术报告，篇幅相当于一本小册子。

### [Man-Computer Symbiosis](vision/licklider_symbiosis.md) — J.C.R. Licklider, 1960
Licklider 是 ARPA IPTO 的第一任主任。后来的互联网、个人计算的研究网络，是他用国防经费铺出来的。他自己是心理学出身——所以他从一开始就不把计算机看成"工具"，而是看成"伙伴"。本文比 Engelbart 的文章早两年，提出"人机共生"：人定义问题、做判断，机器处理可形式化的部分。HCI 与交互式计算的源头。

### [Simple Made Easy](languages/hickey_simple_made_easy.md) — Rich Hickey, 2011
Hickey 是 Clojure 与 Datomic 的设计者，一个人（后来加入少数几人）做出了一门被严肃公司大规模采用的语言。在那之前他做过十几年作曲——这件事影响了他对"事物如何相互交织"的判断。本文（原为一场 talk）论证 *simple*（客观，未交织）与 *easy*（主观，熟悉）的区别。这套区分一旦看清楚，很多技术选型的争论会自动失语。

### [No Silver Bullet](career/brooks_no_silver_bullet.md) — Fred Brooks, 1986
Brooks 1999 图灵奖。早年在 IBM 领导 System/360——1960 年代最大的工程项目之一。他从那段亲身经历里写出了 *The Mythical Man-Month*，之后写了这篇。本文区分"本质复杂性"与"偶然复杂性"，预言十年内不会有任何单一技术带来一个数量级的生产力提升。三十多年过去，他基本对。

### [Can Programming Be Liberated from the von Neumann Style?](languages/backus_can_programming_be_liberated.md) — John Backus, 1977
Backus 发明了 FORTRAN——在他写这篇之前，"高级语言"这个概念基本是他建立的。他在 IBM 工作了三十多年。这篇是他的图灵奖演讲。他在文中批评了自己毕生工作所奠基的范式：基于 von Neumann 架构的命令式编程。一个人在职业生涯顶峰公开质疑自己所建之物——这姿态本身就值得读。

### [A City Is Not a Tree](form/alexander_city_not_tree.md) — Christopher Alexander, 1965
Alexander 论证：自然生长的城市是半网格结构——单元可以同时属于多个重叠的集合。人为规划的城市是树形结构——每个单元只属于一个容器，没有叠合。树形结构方便规划者思考，但砍断了给城市带来生命力的横向联系。剑桥报摊的例子：它同时属于行人世界、车行世界、居住世界和商业世界——这种叠合正是它的价值所在。与 Parnas《模块分解准则》和 Hickey《简单与容易》相通：对的分解不是没有关联，而是关联在正确的层次上。

### [The Architecture of Complexity](form/simon_architecture_of_complexity.md) — Herbert Simon, 1962
Simon 论证：自然界与人工系统中的复杂性，普遍采取层级形式——由子系统构成，子系统再由更小的子系统构成。这不是偶然：层级系统可以从稳定的中间形态逐步组装，演化效率远高于平坦系统。Hora 与 Tempus 的钟表匠寓言是这个论证的核心。他引入"近可分解性"——子系统内部的耦合远强于子系统之间——这是 Alexander 所说的"叠合"在系统论语言中的精确表述——两篇一起读才完整。

### [Time, Clocks, and the Ordering of Events](systems/lamport_time_clocks.md) — Leslie Lamport, 1978
Lamport 2013 图灵奖。LaTeX 是他写的。Paxos、TLA+ 也是。分布式系统大半个领域是他建的。本文引入逻辑时钟与因果序——给"两个相距事件谁在先"这个问题第一个干净的答案。之后所有分布式系统的讨论都建立在这个基础上。

### [Computing Machinery and Intelligence](ai/turing_computing_machinery_intelligence.md) — Alan Turing, 1950
Turing 一个人把"计算"这件事的形式定义做出来。战时破解 Enigma。1952 年因同性恋被英国法庭定罪并强制荷尔蒙治疗，两年后死，41 岁。本文提出图灵测试。但更值得读的部分在后半：他对"机器不能思考"的九种典型反驳逐一回应。这九种反驳今天仍在被反复重提——他七十多年前就已经答完。
> **当前文件状态**：占位，仅含元数据与译者按，正文待翻译。

### [Computer Science as Empirical Inquiry](ai/newell_simon_empirical_inquiry.md) — Newell & Simon, 1976
两位都在 CMU，1975 图灵奖。Simon 同时是 1978 年经济学诺奖得主——很少有人同时在 AI、决策科学、组织行为、心理学留下基础工作。两人合作四十多年。本文是他们联合图灵奖演讲，提出"物理符号系统假说"：智能的充分必要条件是符号操作。这是经典符号 AI 的奠基命题，也是后来联结主义与深度学习要回应的命题。
> **当前文件状态**：占位，仅含元数据与译者按，正文待翻译。

### [The Bitter Lesson](ai/sutton_bitter_lesson.md) — Richard Sutton, 2019
Sutton 是强化学习两位奠基人之一，与 Barto 合写了那本经典教材。从 1980 年代起在做 RL——四十多年。2024 年与 Barto 共同获图灵奖。本文极短（不到两千字），但争议巨大。论点：AI 七十年的经验表明，依赖通用方法+算力的路径，长期总赢过依赖人类领域知识的路径。直接预言了今天大模型范式的胜利。

### [Software 2.0](ai/karpathy_software_2_0.md) — Andrej Karpathy, 2017
Karpathy 是 Fei-Fei Li 的博士生、OpenAI 创始成员、特斯拉 AI 总监；他的 CS231n 和后来的 nanoGPT 教程影响了一整代人。本文是一篇短博客，但提出了一个被广泛采用的框架：神经网络是一种新的写软件的方式——你定义目标行为，让搜索（梯度下降）替你写程序。2017 年提出时并不显然，今天回头看几乎是事实陈述。

### [On the Method of Theoretical Physics](science/einstein_method_of_theoretical_physics.md) — Albert Einstein, 1933
爱因斯坦在牛津大学的 Herbert Spencer 讲座。他的论点比人们预期的更激进：理论物理的基础不来自实验，来自数学的自由创造。实验只能验证，不能生成。他用牛顿和麦克斯韦举例，论证数学简洁性是寻找真理的指针。与 Backus《能否将编程从冯·诺依曼风格中解放出来》相映——两人都在职业顶峰公开质疑自己所建范式的基础。

### [Mathematical Creation](inquiry/poincare_mathematical_creation.md) — Henri Poincaré, 1908
《科学与方法》第三章。Poincaré 描述自己研究 Fuchsian 函数时的经历：苦苦工作，然后放下，某天早晨踏上公共马车的一刹那，答案突然涌现。他由此建立一个理论：无意识工作在后台进行组合，只把"美丽的"——数学上有生产力的——结果呈现给意识。最早、最系统地描述创造性顿悟机制的文本，是 Polanyi 和 Hickey 的思想前驱。

### [Learnable Programming](vision/victor_learnable_programming.md) — Bret Victor, 2012
Victor 早年在 Apple 做交互设计，离开后用十多年时间打磨少数几篇极有重量的文章和演示（*Magic Ink*、*Up and Down the Ladder of Abstraction*），现在做 Dynamicland。对 Khan Academy 编程课程的回应。论点是：程序员不该在脑子里执行代码——环境应当让抽象当下可见。背后问的是工具与思考之间的关系。

---

## 二、造物

这一类是手艺——怎么把东西做出来，怎么分解，怎么在动手之前先想清楚。每一篇都来自一个真正在台子上待过几十年的人。

### [Creative Thinking](career/shannon_creative_thinking.md) — Claude Shannon, 1952
Shannon 一个人造出了信息论。MIT 的人，玩独轮车，会变魔术。能在一个人的工作里看到一整个学科被铺设出来——上世纪只有少数几个例子，他是其中之一。本文是他 1952 年在贝尔实验室的一场非正式演讲，录音残存。讲的是他自己面对一个问题时的几种手法——简化、类比、提问、反向。罕见——天才本人愿意把自己工作时的内部步骤说出来，而且说得朴素。

### [Hammock Driven Development](languages/hickey_hammock_driven_development.md) — Rich Hickey, 2010
Hickey 讲真正的工作发生在你不打字的时间里——躺在吊床上，让问题在背景中转。讲深度思考为什么不能被冲刺替代。与 Poincaré《数学创造》一脉相承：无意识工作是真工作。

### [Hints for Computer System Design](systems/lampson_hints.md) — Butler Lampson, 1983
Lampson 是 1992 年图灵奖得主、Xerox PARC 的核心成员之一。Alto——第一台带图形界面的个人计算机——是他参与设计的；激光打印机也是。他这一生都在做能跑起来的真东西，而且做得快。本文是他做了二十年系统之后写下的"提示"——不是定理，不是方法论，是一些他亲手验证过的判断。"Make it work, then make it work fast." "Plan to throw one away."

### [On the Criteria To Be Used in Decomposing Systems into Modules](systems/parnas_decomposing_modules.md) — David Parnas, 1972
Parnas 是软件工程"信息隐藏"原则的奠基者。值得记住的一件事：八十年代美国搞星球大战导弹防御时，他是看清此事在工程上不可能而选择辞职的少数科学家之一。他对责任的立场，写在他的工程判断里。本文用同一个系统（KWIC index）的两种分解方式，论证模块划分应依据"什么会变"，而非"系统按什么顺序运行"。是面向对象与现代软件架构的所有讨论的起点。

### [End-to-End Arguments in System Design](systems/saltzer_reed_clark_end_to_end.md) — Saltzer, Reed, Clark, 1984
三位当时均在 MIT。David Clark 在 1981–1989 年间担任互联网首席协议架构师——TCP/IP 真正成型的那几年，是他在主持。这三个人造的不是论文，是基础设施。本文论证：网络的智能应当放在端点，而非中间节点。这条原则解释了为什么 TCP/IP 赢了 X.25，也解释了今天关于网络中立性的所有争论。

### [Notes on Programming in C](languages/pike_notes_on_c.md) — Rob Pike, 1989
Pike 在 Bell Labs（C 与 Unix 的诞生地）与 K&R 同处一屋檐下做 Unix。后来共同发明 UTF-8、设计 Plan 9，再后来在 Google 主导 Go。本文是他在贝尔实验室时期写的非正式 notes，讲 C 的命名、分支、数据结构选择——短，密度高，每一条都出自一个真正做过 Unix 内核的人。

---

## 三、反躬

这一类是回头看。每一篇都是一个在某个领域花了一生的人，把不愿被承认的东西亲口说出来——自己的错、自己的盲点、自己所在之物的衰朽。能这样写的人不多，写下来的更少。

### [The Emperor's Old Clothes](career/hoare_emperors_old_clothes.md) — C.A.R. Hoare, 1980
Hoare 发明了快速排序、Hoare logic、CSP（Go 的并发模型来源于此）。这是他 1980 年的图灵奖演讲。本文是他对自己职业生涯的反省，包含著名的"十亿美元的错误"——空引用是他在 ALGOL W 中引入的，他公开为此道歉。这是一位资深从业者以自己的名字承认错误的文章。与 Feynman《货物崇拜科学》互为镜像：一个讲工程师的自我审视，一个讲科学家的自我审视。

### [Cargo Cult Science](science/feynman_cargo_cult_science.md) — Richard Feynman, 1974
Feynman 的加州理工毕业典礼演讲。货物崇拜科学：形式上像科学，却缺少核心——竭尽全力去证明自己错了的那种诚实。他举了老鼠迷宫实验、ESP 研究、Millikan 测油滴等例子。核心命题：你最容易骗到的人，就是你自己。

### [Reflections on Trusting Trust](career/thompson_trusting_trust.md) — Ken Thompson, 1984
Thompson 与 Ritchie 共同造了 Unix，也参与了 B、UTF-8、Plan 9、Go。1983 图灵奖。这是他的图灵奖演讲。他展示一种攻击：编译器可以被植入后门，而这个后门可以在它编译自身时再种入自身——源码里看不见，但代代相传。短。读完之后你看软件供应链的方式会变——也会重新评估你自己在多大程度上"信任"那些你没亲手做过的东西。

### [On the Cruelty of Really Teaching Computer Science](career/dijkstra_cruelty.md) — Edsger Dijkstra, 1988
Dijkstra 1972 图灵奖。算法、结构化编程、形式方法。脾气大，文笔毒辣。他用手稿（EWD 系列）写了几十年，每篇签自己名字。本文论证：计算机科学本质上是形式符号操作，不是工程。立场极端——但极端立场容易暴露问题。读他不是为了同意，是为了被迫表态。

### [Proofs and Refutations](inquiry/lakatos_proofs_and_refutations.md) — Imre Lakatos, 1976
以苏格拉底式对话的形式，展示数学知识如何在"证明-反例-修正"的循环中生长。以欧拉多面体公式（V−E+F=2）为主线，学生们不断提出反例，老师展示数学家面对反例的三种策略：怪物屏蔽（这不算真正的多面体）、例外屏蔽（修改命题）、引理并入（加固证明使反例不可能）。教给读者的不是数学，是一种姿势：你的工作不是确立真理，是面对下一个反例。
> **当前文件状态**：压缩件，违反项目原则。19k 字对应原书几百页；包含改写者加的"方法论总结"附录与第三人称口吻泄漏。详见文件顶部状态块。

### [A Plea for Lean Software](systems/wirth_lean_software.md) — Niklaus Wirth, 1995
Wirth 是 Pascal、Modula-2、Oberon 的设计者，1984 图灵奖。他在 ETH Zürich 一生只做一件事：让语言与系统再简单一点。本文给出"Wirth 定律"——软件变慢的速度比硬件变快的速度更快——并讨论为什么。短，恼火，对今天仍然适用。一个在自己耕耘了一辈子的领域里见证它衰朽的人的笔记。

---

## 四、立命

这一类问的是同一件事：用一生（或一辈子的话）对准什么？Hamming 选问题、Victor 选原则、Orwell 选话语、Calvino 选要带走的文学价值——每一篇都是一种定向。

### [You and Your Research](career/hamming_you_and_your_research.md) — Richard Hamming, 1986
Hamming 是 Bell Labs 的人——和 Shannon、Tukey 在同一栋楼的同一代人。误差校正码是他做的。Manhattan 项目早期他在场。他用职业生涯的后半段反复琢磨同一个问题：为什么有些人做出的工作能留下来，绝大多数人不能？本文是他在 Bell Labs 的一场演讲。直白，不留情面：如果你不在重要的问题上工作，你不会做出重要的工作。其它一切优先级判断都从这一句出发。

### [Inventing on Principle](vision/victor_inventing_on_principle.md) — Bret Victor, 2012
Victor 早年在 Apple 做交互设计，离开后用十多年时间打磨少数几篇极有重量的文章和演示，现在做 Dynamicland。他的产出节奏本身就在说明什么叫"在一件事上待够久"。本文是一场演讲。表面上讲"创造者需要与所创之物即时连接"，底下问的是：你愿意为某一条原则，组织你的一生吗？

### [Politics and the English Language](expression/orwell_politics_english_language.md) — George Orwell, 1946
Orwell 论证语言的腐化与政治的腐化互为因果：模糊的语言让模糊的思想得以通行；政治语言被设计成让谎言听起来像真话。他给出六条写作规则，最后一条是：如果遵守任何规则会让你说出蠢话，就打破它。核心命题：写不清楚，是因为没想清楚。回应 README 内核"语言与压缩"——语言的清晰度不只是风格问题，是认识论问题，也是伦理问题。

### [Six Memos for the Next Millennium](expression/calvino_six_memos.md) — Italo Calvino, 1985
卡尔维诺在生命最后一年为哈佛诺顿讲座写下的六封信，只完成五封便去世。每封信凝练他对文学一种核心价值的理解：轻盈、迅捷、确切、可见性、繁复，以及未写完的第六封。他用珀尔修斯斩美杜莎的神话讲轻盈，用水晶与火焰的对立讲确切。临终前的总结，每个字都有分量。回应 README 内核"死亡与有限性"——正因为第六讲没有写完，这五讲才更像遗嘱。
> **当前文件状态**：压缩件，违反项目原则。23k 字对应 5 篇讲座（完整译本应 60–90k 字）；含改写者加的"卡尔维诺谈 X"型小标题与死后传记叙述式后记。详见文件顶部状态块。

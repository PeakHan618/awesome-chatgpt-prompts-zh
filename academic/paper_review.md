### 审阅提交稿件：逐步指南

用一句话总结，审阅的目的是确定一份提交的稿件是否能够为社区带来足够的价值并贡献新知识。该过程可以分解为以下几个主要的审稿任务：

阅读论文：仔细阅读整篇论文非常重要，同时查找任何相关的工作和引用，这将帮助你全面评估它。确保给自己足够的时间进行这一步骤。
在阅读时，考虑以下几点：
工作目标：论文的目标是什么？是为了更好地解决已知的应用或问题，引起对新应用或问题的关注，还是介绍和/或解释新的理论发现？或者是这些的结合？不同的目标将需要不同的考虑，以评估潜在的价值和影响。
优点：提交的稿件是否清晰、技术上正确、实验严谨、可复现，是否提出了新的发现（例如理论上、算法上等）？
缺点：它在b点列出的任何方面都弱吗？
注意潜在的偏见，并尽量对论文对整个ICLR社区可能持有的价值和兴趣持开放态度，即使它对你来说可能不是很感兴趣。
回答四个关键问题，以便做出接受或拒绝的建议：
论文具体解决了什么问题？
方法是否具有充分的动机，包括在文献中的位置是否得当？
论文是否支持其主张？这包括确定结果（无论是理论上的还是实证的）是否正确，以及它们是否具有科学严谨性。
这项工作的意义是什么？它是否为社区贡献了新知识和足够的价值？注意，这并不一定要求有最先进的结果。当提交的稿件令人信服地展示了新的、相关的、有影响力的知识（包括对实践者的实证、理论等）时，它们就为ICLR社区带来了价值。
撰写并提交你的初步审稿，按照以下方式组织：
总结论文声称的贡献。保持积极和建设性。
列出论文的优点和缺点。尽可能全面。
明确陈述你的初步建议（接受或拒绝），并给出一到两个选择的关键原因。
为你的建议提供支持论据。
提出你希望作者回答的问题，以帮助你澄清对论文的理解，并提供你需要的额外证据，以便对你的评估有信心。
提供额外的反馈，旨在改进论文。明确这些点是为了帮助，而不一定是你决策评估的一部分。
完成CoE报告：ICLR采用了以下道德准则（CoE）。在提交你的审稿时，你将被要求为论文完成一个CoE报告。报告是一个简单的表格，有两个问题。第一个问题是是否有潜在的CoE违规行为。第二个问题仅在有潜在违规行为时相关，并要求审稿人解释为什么可能存在潜在违规行为。为了回答这些问题，因此在开始审稿之前阅读CoE非常重要。

参与讨论：ICLR的讨论阶段与AI/ML社区的大多数会议不同。在这个阶段，审稿人、作者和领域主席进行异步讨论，作者被允许修改他们的提交以解决出现的问题。在这个阶段积极参与至关重要。保持开放的态度，准备改变你最初的建议（无论是更积极还是更消极）的评分。
边缘论文会议：今年，我们引入了一个新程序，让AC（领域主席）与审稿人（仅针对边缘案例）进行（虚拟）会议讨论。AC将联系安排这次会议。这是为了确保审稿人之间的积极讨论，并做出深思熟虑的决定。AC将安排会议并促进讨论。为了进行有成效的讨论，在会议之前熟悉其他审稿人的反馈非常重要。请注意，我们将利用未能参加这次会议的审稿人的信息（紧急情况除外）。
提供最终建议：更新你的审稿，考虑在讨论阶段收集的新信息，以及对提交的任何修订。陈述你的推理以及在讨论阶段什么改变了/没有改变你的建议。

审稿示例
以下是来自以前会议的两个样本审稿，它们给出了我们认为是倾向于接受和倾向于拒绝情况下的好审稿的例子。

倾向于接受的论文审稿
摘要：
本文在低秩适应（LoRA）框架的基础上，通过引入fLoRA，对基础模型进行微调，允许在同一批次中为不同的特定任务请求提供不同的适配器。作者通过实证展示了他们的方法在多语言代码生成和语音识别任务的准确性方面保持了LoRA的优势，同时促进了更高的吞吐量和更低的延迟。

稳健性：3个好评
呈现：3个好评
贡献：3个好评
优点：
论文清晰地介绍了问题和与现有技术相比的贡献。这项贡献对于应对实时服务场景中使用基础模型的实际挑战具有重要意义，特别是考虑到全球范围内的请求。论文在理论和技术上看起来是健全的，呈现清晰，背景明确，易于理解。

缺点：
我没有发现主要的缺点。次要评论在以下部分指出。

问题：
我建议从摘要中删除引用。
您能否在论文中明确澄清“表达能力”的定义？
关于贡献3（引言）：由于fLoRA允许针对微调的任务特定适配器，您是否期望与fLoRA相比有更高的准确性，而不仅仅是等效的？在哪些情况下，您预计fLoRA可能在准确性上牺牲了与LoRA相比？
图1：这个图很有用，但如果将不同部分（1,2,3,4）框起来，或者至少避免它们之间的重叠，将有助于清晰度。此外，在点1处指出了4个任务描述，相应的4个结果在点4处显示，而只有2个适配器和权重计算在点2和3处显示。在我看来，保持子图示例数量一致会更清晰。
在LoRA中，适应后的基础模型的权重矩阵由W0和DeltaW的SUM表示，而在fLoRA中，每个示例的特定权重矩阵是作为W0和DeltaWi的逐元素MULTIPLICATION计算的。这正确吗？
在第3.2段中，您说“只要上述不等式成立，fLoRA的计算成本就低于bmm LoRA”。您能否详细说明您预计（7）低于1的场景？
请在第4节评论结果时插入对表1和2的引用。
表1：我建议突出显示每行最好的改进（例如加粗文本）。
我会将第5节（相关工作）移到引言之后，因为它为所呈现的方法提供了一些有用的背景。
伦理审查标志：不需要伦理审查。
评分：8：接受，好论文
信心：2：您愿意为您的评估辩护，但很可能您没有理解提交的核心部分，或者您不熟悉相关工作的一些部分。数学/其他细节没有仔细检查。
行为守则：是

倾向于拒绝的论文审稿
摘要：
提出了一个将公平性整合到PATE中的框架。所提出的方法是对PATE的简单适应，将公平性约束纳入模型的查询拒绝机制。

稳健性：3个好评
呈现：4个优秀
贡献：2个公平
优点：
论文解决了ML中的一个高度相关的问题，涉及公平性和隐私的理论和实践影响。
所提出的框架是对现有PATE的简单适应。简单性在我看来是一个加分项。
缺点：
公平性是通过在聚合器中添加平等约束来“执行”的，该聚合器作为基于公平性的拒绝抽样步骤。这个一般想法在过去的其他作品中已经被提出，包括作者引用的作品，以及作者进行比较的作品。因此，很难理解所提出的框架有什么新意。明确提及会有帮助。
缺少与使用其他框架相比何时使用所提出框架的讨论（见下文我的问题）。
实验分析应该改进。一些图表具有误导性，例如，不同的算法使用相同的颜色（见下文我的问题）。
问题：
我无法判断IPP（推理时添加的拒绝步骤）对总体结果的影响。您能否提供一些消融研究，展示在不同数据集上，有和没有IPP的情况下，框架在不同多数/少数分布下的表现如何？
如果出现某些分布偏移，框架将如何工作？这在我的上述问题中尤为重要。
附录中报告的其他数据集的趋势发生了逆转，例如，DP-Fermi产生了比FairPATE更好的权衡。您能讨论为什么吗？数据集的哪个特征使这成为可能？
图2和3使用橙色表示两种不同的算法（Tran等人（图2）和Jagielski等人（图3））。作者应该在所有图表中报告所有算法，或解释它们的缺席。
为什么Tran和Jagielski等人没有在UTK数据集实验中报告？
论文《在公平性、隐私和效用的帕累托前沿上行走的无偏见学习》讨论了类似的话题（尽管这项工作的贡献是不同的），它可以被添加到您的相关工作部分。
次要评论：

引用的许多论文都出现在会议上。但作者引用了它们的arxiv版本。我建议相应地更新引用。

伦理审查标志：不需要伦理审查。
评分：5：略低于接受阈值
信心：4：您对您的评估有信心，但并不完全确定。您可能没有理解提交的一些部分，或者您不熟悉相关工作的一些部分，这是不太可能的，但并非不可能。
行为守则：是

---
请根据上述审稿指南，以教授的身份为上传的论文撰写一份专业的审稿意见。
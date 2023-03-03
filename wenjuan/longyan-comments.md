# reply to prof long email

Question: Can someone provide a definition of "grassroots" or "citizen-organized/led" foundations?
Answer: philanthropic organizations can be classified into small grassroots organizations and large government-supported organizations based on their government background and resources.
1. How do we differentiate organizations based on their government background:
   1. Organizations that belong to charity societies (慈善会) or the Red Cross, as well as those whose names start with "China," are considered government-backed organizations. Others are grassroots organizations.
   2. Ideally, we should use "government subsidy income" to distinguish different organizations, but the financial data we have contains a large number of missing values in the "government subsidy income" column. Therefore, we cannot reliably use this financial data to differentiate organizations.
2. How do we differentiate organizations based on their resources:
  1. Total asset: Obtain the first quartile of the total asset. Organizations with total assets greater than the first quartile are considered large organizations with abundant resources, while others are grassroots organizations. Changing to the second quartile does not change the results.
  2. Net asset: same as above.
  3. Number of employees: same as above.

In summary, regardless of the perspective used to measure (in fact, we have completed seven tests and obtained consistent results), organizations with weak government backgrounds and few resources exhibit stable results: their discourse is more positive, but their actions are more active.

Question: Have you also measured foundations' connections with the government?
Answer: Yes. Organizations that belong to charity societies (慈善会) or the Red Cross, as well as those whose names start with "China," are considered government-backed organizations. Others are grassroots organizations. Due to incomplete financial data, we cannot use government subsidy income to measure the connections between organizations and the government.

Question: I understand how actions are measured. But how do you calculate who did more?
Answer: We consider the "non-information activities" manual coding as actions, and we trained a new text classifier to determine whether each article in the dataset is related to actions. For example, for organizations with different government backgrounds, we can use the model to determine the proportion of articles related to actions published by grassroots organizations and government-backed organizations. We found that grassroots organizations always publish significantly more articles related to actions than government-backed organizations.

<!-- Question: could any of you tell me what the definition of "grassroots" or "citizen-organized/led" foundations is? 
回答:慈善组织根据政府背景和资源被分为小型草根和大型政府支持的组织。
- 我们如何用政府背景区分组织: 
  - 那些机构类型属于慈善会或红十字，以及名字以"中国"开头的组织，是有政府背景的组织。其它为草根组织。
  - 理想上我们应该用"政府补助收入"区分不同的组织，但是我们掌握的财务数据表上，"政府补助收入"这一列有大量的缺失值。因此我们没办法以可靠的方式利用这个财务数据对组织进行区分。
- 我们如何用资源区分组织:
  - 总体产合计: 得到总资产合计的第一个分位数。那些大于第一个分位数的组织被视作总资产资源丰富的大组织，其它为草根组织。换成第二个分位数结果不会改变。
  - 净资产合计: 得到净资产合计的第一个分位数。那些大于第一个分位数的组织被视作净资产资源丰富的大组织，其它为草根组织。换成第二个分位数结果不会改变。
  - 员工人数: 得到员工人数的第一个分位数。那些大于第一个分位数的组织被视作员工资源丰富的大组织，其它为草根组织。换成第二个分位数结果不会改变。
总之，不论从哪个角度衡量(实际上完成了7个测试并且结果一致)，那些政府关联弱、资源少的的组织展现了稳定的结果: 它们话语更正面但行动又更积极。

Question: I also need to know if you have measured foundations' connections with the government.
回答:是的。那些机构类型属于慈善会或红十字，以及名字以"中国"开头的组织，被视作是有政府背景的组织。其它为草根组织。因为财务数据不完整，我们无法利用政府补助收入进行衡量。

Question: I understand how actions are measured. But how do you calculate who did more?
回答:我们将"non-information activities"这个人工编码视作行动，我们新训练了一个文本分类器。借此，我们能够利用模型知道数据集中的每一篇文章是否是与行动有关。以政府背景为例，我们就能够知道在拥有不同政府背景的组织所发表的文章中，与行动有关的文章占多大的比例。我们发现，草根组织发表的与行动有关的文章占比总是显著多于拥有政府背景的组织。 -->
 


<!-- 如何对结果进行解释:
- 对"protective disguise"这个框架的担忧: 陈锐的理解是以极其正面的话语表达为基础争取自己生存上的合法性，从而为在疫情中的行动创造更多的空间和自由。Yan认为如果按照这个理解，那"protective disguise"可能就不是一个最好的解释框架。她认为在灾难中，公民组织是被政府所需要的，也就是说这些组织不需要为自己争取合法性才能行动。(Yan之前读摘要的时候以为"protective disguise"是用以形容这些组织以正面的话语来为之后一些政府不能接受的行动作掩护)。
- 另一种可能的替代解释框架: 
  - 陈锐提出用了第一个版本的结论里面写的解释，即这些草根机构实际上在用正面话语和更积极的行动从政府那里积攒了合法性，为未来的生存争取了更多空间。Yan Long认为这种解释可以并补充了几点。第一，不仅是从政府那里获取合法性，而且也获得了来自民众的社会信任，这也是其生存的最重要支撑之一。
  - 第二，除了从未来生存的角度看，另一种补充解释是这些组织在2020年需要证明自己的生存价值。2020年对于中国NGO来说是无比困难的一年，在面临经济来源紧张等因素带来的倒闭挑战时，这些组织更加需要用行动证明自己的生存价值。
  - 第三，除了未来生存空间和证明当前的生存价值之外，最后一个可能性就是这些草根机构可能在本质上相对于以红十字会代表的GONGOs就是更加在乎公众的福利和利益。

理论框架以及文献对话:
- 首先，Yan Long认为我们的结果总体来说是好的，尤其是草根组织的行动更多。但是如果以这个为重点，主要与公民社会的文献对话，最终在期刊投稿上可能结果会很惨。
- 相反，Yan Long认为现有的论文草稿中写的当今政治传播研究喜欢从个人角度出发而忽视组织视角的批评是成立且重要的。比如，周雪光的新颖性就在于从组织的角度出发研究国家与社会的关系，打破了之前的研究习惯，这一点让他与大量研究形成了有趣的区别。事实上，现在的政治传播讨论的方式是以(国家vs个人)这种二元的角度切入。但是在这二者之间，组织的语言、行动实际上是有相当的影响力的。总之，可以找一些从组织角度研究政治传播的教授并利用它们的工作作为理论支撑和批评。
- 除了从组织角度批评政治传播，还可以深挖文娟所说的"丧事喜办"。传统上，文献喜欢把"丧事喜办"的文化作为一个自上而下的过程来看待，认为是政府或国家驱动了中国在灾难面前的丧事喜办。这个过程中组织与个人是被动的角色。然而，Yan Long认为可以探讨另一种可能性:组织和个人可能在某种文化的驱动下，"主动"参与到丧事喜办的构建中。
  - 参考Bin Xu, Cultural response to disasters -->


How to Interpret the Results:

Concerns about the "protective disguise" framework: Chen Rui's understanding is based on expressing legitimacy in extremely positive terms to create more space and freedom for action in the pandemic. Yan believes that if this understanding is followed, "protective disguise" may not be the best explanatory framework. She believes that in disasters, citizen organizations are needed by the government, which means that these organizations do not need to fight for legitimacy to act. (Yan initially thought when reading the abstract that "protective disguise" was used to describe these organizations using positive language to cover up some government-unacceptable actions).

Another possible alternative explanatory framework:
- Chen Rui proposed using the explanation written in the first version of the conclusion, that these grassroots organizations are actually using positive language and more active actions to accumulate legitimacy from the government, and to gain more space for survival in the future. Yan Long believes that this explanation can be supplemented in several ways. First, not only is legitimacy obtained from the government, but also social trust from the public, which is also one of the most important supports for their survival.
- Second, in addition to looking at future survival space, another supplementary explanation is that these organizations in 2020 need to prove their survival value. 2020 was an extremely difficult year for Chinese NGOs, and these organizations needed to use actions to prove their survival value in the face of challenges such as economic sources of stress that threatened to shut them down.
- Third, in addition to future survival space and proving their current survival value, the final possibility is that these grassroots organizations may, in essence, be more concerned about the welfare and interests of the public compared to GONGOs represented by the Red Cross.


Theoretical Framework and Literature Dialogue:
- First, Yan Long believes that our overall results are good, especially in terms of grassroots organization actions. However, if this is the focus and the main converstion is with civil society literature, which could lead to a dismal result in journal submissions.
- Instead, Yan Long believes that **the criticism in the current paper draft that political communication research tends to overlook the organizational perspective in favor of individual perspectives is valid and important**. For example, Zhou Xueguang's novelty lies in studying the relationship between the state and society from an organizational perspective, breaking the previous research habit and creating an interesting difference with a large amount of research. In fact, the current political communication discussion is approached from a binary perspective of (state vs. individual). However, between these two, organizational language and actions actually have considerable influence. In short, we can find professors who study political communication from an organizational perspective and use their work as theoretical support and criticism.
- **In addition to criticizing political communication from an organizational perspective, it is also possible to delve deeper into the "celebrating funerals as weddings" phenomenon mentioned by Wenjuan**. Traditionally, the literature likes to view the cultural aspects of "celebrating funerals as weddings" as a top-down process, believing that the government or the state drove China's celebrations of funerals as weddings in the face of disasters, with organizations and individuals playing passive roles. However, Yan Long believes that it is possible to explore another possibility: that organizations and individuals may "actively" participate in the construction of the celebrations of funerals as weddings under certain cultural drivers.
  - See Bin Xu, Cultural response to disasters for reference.

期刊推荐:
- 不想写很多理论就China Quarterly 或者 Modern China
- American Journal of Cultural Sociology

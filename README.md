    在大学学习的这两年，我发现同学们的学习状态比较差，跟在高中时完全不一样，上课认真听讲的同学非常少，下课后老师布置的作业也很少主动的去完成实现，即使是安排在网络上的视频课程也大多敷衍了事，或者放在一边干脆不管。根据我们小组成员的分析，在课堂上学习时，同学们大多都在干别的事情，对老师讲的知识不太感兴趣，认为书本上的知识太过乏味。基于这一点，我们尝试将在大三开设的操作系统课程与flash结合起来，做一个基于flash的辅助教学系统，希望能在以后的研究中逐步实现我们的这个想法，增强同学们对知识的渴望、对学习的热爱。
目前，计算机辅助教学的基本模式有以下几种：
    1、教师讲解、演示模式：这种模式适合将优秀教师的教学经验，用形象、直观的动画，配以清晰的讲解，有效的让学生思考和理解概念性的知识。但其教学内容的过程有教师控制，学生无法直接参与交互，而且无法适应学习程度不同的学生。 
    2、学生操作、练习模式：这种模式要求学生一人一机，依照自己的进度进行操作与联系，不断检验自己掌握知识的程度，促进学生较好的巩固所学的知识。
    3、网络教学模式（基于多媒体网络电子教室的一种模式）：这种教育模式基本上达到了人机交互双向互动式的教学目的，大大提高了教学信息传播的数量，质量、速度、并且通过互动作用提高了传播的有效性，是教师在控制教师机的过程中仍能保障有效的课堂教学管理，突出了学生的主题作用，从而提高了课堂教学效率。这种模式需要比较多的好的适合不同学生的教学软件，从而完全由市场来提供是不可能的，需要教师具备一定的制作教学软件的能力。
    4、小组互助合作学习模式：“互助合作小组”是一种新型的结构-功能联合体，由两名以上学生根据性别、才能取向、个人特征、学业成绩、家庭社会背景、特长爱好、能力等诸方面的合理差异而建立的相对稳定的学习小组。
个性化教学、个别化学习模式：个别教学是指旨在满足每一位同学的要求，适应每个学生现有水平的教学形式。
2、研究方法与实验方案：
1、构建操作系统课程知识数据库：
    首先，我们将仔细学习操作系统知识，在学习过程中我们将所有的知识点以及遇到的课后习题、考试题目收集起来，按照每一个章节、每一个小节把知识点进行分类、筛选，挑出比较有代表性的、综合性的问答题、选择题等进行再分类，构建成表格的形式放入MySQL数据库中，形成一个比较完备的操作系统知识的试题库。
2、Flash应用及UI界面设计
在动画方面，我们将采用多种游戏方式进行与玩家用户的交互动作。在游戏形式的选择上，我们将引用近几年比较流行的游戏模式，增加游戏模式的多样性，缓解玩家用户的疲劳感乏味感。
在UI设计上，我们可以借鉴现在网络上最流行的游戏——英雄联盟中人物场景的设计思路，再添加一些与计算机方面有些联系的元素，比如添加0、1数字。我们将发挥我们的想象力、创造力，设计出能够吸引广大同学们注意力的造型与图案。
    
3、后台实现：
在后台程序设计语言的选择上，我们使用php写后台程序。其中php的AMFPHP、ZENDAMF作为Flash和PHP的中间交互层，使数据传递类型更多、更方便，并由php对flash传递的数据进行数据处理，与mysql数据库进行数据传输。
4、学习与游戏的结合：
    小组内部进行学习讨论，细剖每个主要知识点，做到对操作系统非常了解。结合我们对知识点的了解，为每个知识点设计出最形象有趣的游戏动作。在设计上，我们将结合我们小组成员所有人的建议，并请教田老师进去指导。
     

3、关键及创新点
（1）操作系统课程详细的内容整理与关键内容的分类筛选
 计算机操作系统概述
 进程管理
 存储管理
 设备管理
 文件管理
 并发程序设计
以上为操作系统课程的主要内容章节，我们对每个大章节下的主要内容进行再分解，将每个知识从文字的形式转化为图片、动画的形式。对于不同属性形式的知识我们进一步作出分类，制成表格的形式存放在数据库中，由mysql数据库进行管理。
（2）整个项目的核心关键，在于将游戏与课程知识的结合。我们小组的成员将会致力于研究操作系统课程知识的游戏形式，发挥我们的想象力来完成项目。我们现在初拟为闯关的形式：
 我们将设计出六大地图，分别对应着操作系统知识的六大分类。在大地图的大框架下我们继续细分为多个关卡，每个关卡我们都将设计出形象的互动游戏，让玩家在闯关中学习到知识，并且体现到乐趣。
 设计副本环节。在副本情境中增加课程中没有的着重强调和要求的强化知识和拓展知识。当玩家完成通过副本环节完成副本任务的要求后，系统会自动奖励给玩家一定数量的“加分政策”，并直接作用到总成绩中。借此增加玩家的积极性。

 设计对抗比拼环节。玩家在一个特定的连接中参与对抗比赛的随机抽选，与抽取到的对方玩家进行对抗，例如知识抢答形式。当双方玩家对抗结束后，系统自动对每个玩家做出奖励。对抗比赛设计出游戏的相关限制：例如，每个小关卡每个玩家只能匹配2此，当用户在对抗性比赛中得分低于一定程度时时，系统自动判断为不合格，取消其加分政策，。为了防止降低玩家的积极性，分将数上线设定到很低的程度。
 设备管理
 文件管理
 并发程序设计

（3）如何去较准确的评估游戏玩家对课程内容的掌握程度：
我们设计出关卡任务，在玩家通过了一个大地图后开设一个检验测试，主要以题目问答的形式对所学知识进行测试，当玩家通过测试后你才能解锁下一个大地图。这个测试主要以检验功能为主，题目难度设定为一般，内容大多为之前关卡中的游戏过程学习到的知识。在测试时，我们将采用时间、准确度的双重评分标准。在准确性上，我们以百分制的形式，按照百分比的正确率给出在准确性上得到的分数。在时间上我们将时间属性作为一种参考，分非常快、比较快、一般、比较慢、非常慢五类，分别对应着1.0、0.9、0.8、0.7、0.6。在得到准确性和实践上的得分后，最终的得分 = 准确性 * 时间。
注：在时间上，我们设置一个时间锁，控制玩家的答题时间，当触发时间锁时，数据库将自动关闭，停止玩家继续答题，立即评断为不合格，并给出玩家的最终得分 = 答对的题目数 / 总题目数 * 0.6 ，在提示出成绩后，根据玩家的体验情况给出适当的建议，建议玩家继续努力。
（4）利用玩家的完成任务的情况记录，合理的做出奖励与惩罚，增加游戏的趣味性、吸引力，能够吸引玩家进行更加深入的学习。

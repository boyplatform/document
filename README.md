# document
some documents&amp;descriptions regarding boy platform.

# 开发者序言
    杆细胞形成不同的细胞，不同的细胞自动组成了生物的组织器官，而组织器官互相协同配合组成了生物个体，生物个体在与大自然的交互中
形成种群，生物种群间形成了完整的食物链，在与大自然交互的过程中生物信息被不断改写并代代相传，食物链中的每个物种都在时间的长河中不断
进化和蜕变最终孕育更好的下一代，至此世间万物，生生不息。在大自然中存在着的这种在未知中孕育已知、在偶然中孕育必然的隐式非线性并行计算模式一
直以来都是我们探索与追求的终极最优计算方案。
    
	从电子管计算机到大规模集成电路微型计算机，从微型计算机单机到客户端-服务器架构的出现，从单点服务器到分布式服务器集群，从分布式服务器集群到云计算。
 从虚拟机技术到如今的虚拟容器技术。虽然计算的载体和计算的方式在不断演化和进步，但我们离所追求的终极计算方案仍有距离。云计算在过去的10年中得到
 了长足发展与进步，但是显然它并非终极方案。区块链的出现为计算方案的演进提供了一个新的方向与可能性，但或许只有其部分特性可被运用到我们对终极计算方案
 的探索中去。
    
	创建本平台框架的主要目的在于利用微服务相关技术框架和概念试验多节点模态分布式计算平台的可行性。目前平台下共有6个repo，每个repo中都开发了一款有特定
功能的微服务并且支持通过多节点部署组成微服务集群，框架中每款微服务都配有一个与之同时运行在节点上的MYSQL LOCALDB数据库，不同款微服务的LOCALDB数据库表结构
也不尽相同，在实践和理解过程中可把LOCALDB视为“大脑”而把不同款微服务视为“不同物种”，“不同物种”有不同的“大脑”；在代码设计层面，每款微服务都增加了一个CrystalBlock
概念模型，这个概念模型主要用于承载与微服务集群节点间协同运行规则相关的逻辑代码---每款不同微服务构成的集群可视为一个模态(动态)区块，而维系整个模态区块协同运行的
隐式规则/算法便可被置于CrystalBlock这个概念模型中，根据模态区块为保障协同运行可能涉及的不同服务器行为规则类型，crystalBlock又被划分出了Common,evironmentInteract,
fuzzyExperience,learn,selfExpress,selfSensor,social,task,teach等多个子模块，它们将被用于承载对应类型的服务器行为规则，然后每一类服务器行为规则下都会有若干具体服务器行为
名称模块，最后每一个服务器具体行为名称模块下则有三个描述不同服务器行为方式的代码文件DeamonThreads,decideAndAction,interact---DeamonThreads主要承载一些为确保当前服务器行为
模态区块一致性而需要被定时执行的方法代码、interact主要承载当前服务器行为执行过程中集群节点间需要进行的参考数据信息交互代码，这些参考数据信息往往会影响服务器行为的最终执行结果、
decideAndAction则主要承载与服务器行为最终执行相关的代码。在diskData与Memory微服务功能中，我用前述共识规则机制实现了模态区块集群选择master节点以及数据操作“区块验证+节点同步”的功能，
在此仅供大家学习和参考。
    
	路漫漫，一切探索才刚开始，希望能有机会在网络间找到对这个后端平台框架感兴趣的同仁共同完善它，如在使用或实践过程中遇到任何问题，可随时电邮联系，
我的MAIL地址是: coldboardcoldtree@126.com 

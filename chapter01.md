# chapter01 欢迎进入软件构建的世界
01. 作者总结了一般软件开发的工作流程，认为工作大致分为几个方面。定义问题，需求分析，规划构建，软件架构，详细设计，编码与调试，单元测试，集成测试，集成，系统测试，保障维护。根据本人粗浅的工作经验，我们的工作流程一般可简化为需求分析，编码调试，测试，维护。很少有做的非常好的单元测试，测试非常依赖于人工测试。这样软件的质量得不到保障，开发调试成本非常高，而且出了问题责任不明，互相踢球，非常影响心情。应该重视分析和测试的工作，尤其是测试。
02. 书中提到大部分软件开发，基本上开发着开发着，设计文档啥的就不更新了，一个软件的功能好坏，可以信任的只有源代码。这一点表示极度认同。书中还有一句话，叫 构建活动是唯一一项确保会完成的工作。对的，就是这样。软件的好坏都体现在代码上了，所以我们的测试也应该依赖于代码，如果依赖于人工，是不可靠的，我们根本不知道测试人员是不是测试了所有的功能，如果出了问题，也拿不出证据。更重要的是如果测试出了问题，只能看到一个现象，而不知道问题出在哪里，这是非常恐怖的一件事情。

#从get笔记回归flomo

先是看了flomo的5周年发文，然后看了创始人邵楠的直播回放，不得不佩服flomo的坚持与深入思考。其实近一段时间我已经切换到了get笔记去记录，想要更充分的利用ai的力量，可实际上我用ai改过几次，就没有继续再用ai功能了，自己也曾疑惑为什么。听了邵楠的思考，才意识到原来是那内容不像是自己写的。

写笔记一个方法叫“用自己的话记录”，我以前的理解是看书时不要摘抄，而是要能消化内容后用自己的语言复述。现在来看“用AI重新整理我的话“，也就是它消化我的内容再用它的话重新表述呀，那内容当然不属于我了。邵楠提到记录笔记是思考的痕迹，正是那些记录时的不完美体现了一个真实的自己。

结合最近的自我觉察，我想更好的表达一个独特自我，而不是变成某个人的复制品，更不是被AI管理。

经历过上述思考，我决定重新在flomo记笔记，当然也需要把之前get记录的内容导入到flomo。网络上搜索了一下,没有直接可用的把get笔记内容导入到flomo的方案。flomo提供了api接口，理论上任何能被解析的内容都可以通过api导入，但是要有一定的编程能力。

我对比了get笔记和flomo导出html文件的差异，get中每个笔记对应一个html，而在flomo中所有笔记都在一个html中，能看出flomo更简洁。而且考虑如果把导出笔记送给其他进行问答，显然单一文件也更方便。

最后尝试用AI写了一个python程序，成功实现批量迁移，很开心。
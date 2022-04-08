# chinese_dataset

收集各任务，各领域中文数据



- CLTS数据集: A Chinese Long Text Summarization Dataset， 新闻数据集，可用作摘要

出处：https://github.com/lxj5957/CLTS-Dataset

样例：

```
Sample 1
{"summarization":"每到冬至，进补这件事就会被提上议程。甘味厚重、工序繁复的保养品等曾一度被认为是进补主流，但现在，视环境、气候、习惯等而定的清补也逐渐进入了人们的视线。"}
{"article":"当我们在讨论冬令进补时，你会想到什么？用了不少滋补品的膏方，还是经过漫长炖煮而成的羊肉煲？实际上，随着生活条件的改善，传统的厚重型滋补方式并不能覆盖所有人的需求，温和而清润的滋补法，有时候可能会更有效果。红枣黑芝麻粥，原料：大米、红枣、黑芝麻。做法：1、黑芝麻下锅用小火炒香后，将其打碎成粉末，备用；2、红枣洗净，备用；3、大米淘洗干净，用冷水浸泡半小时，之后将水倒掉；4、锅里加入足量的冷水，放入红枣和大米，大火烧开后转小火煮到浓稠，之后加入黑芝麻粉，顺时针搅拌后稍煮一会即可食用。Tips：1、红枣数量不宜多，以4-5颗/天为推荐；考究的可以先去核再煮，但实际上不去核也没事；2、黑芝麻容易炒焦，如果控制不好火候的话，买现成的最方便；3、如果喜欢吃甜口的，可以适当加入一些冰糖调味。白菜萝卜汤，原料：大白菜叶、白萝卜。做法：1、大白菜叶子洗净后切段，备用；2、白萝卜取中段，洗净后去皮切成1cm左右的萝卜条，备用；3、锅内入适量水，之后放入萝卜条，半熟后再加入大白菜段，中火煮开后再转小火慢煮3分钟左右，即可食用。Tips：1、据说这一款素菜汤能够帮助清肠，可以考虑将其作为晚餐的代餐来食用；2、不放盐的原因在于冬季饮食味道厚重，过多盐分的摄入可能造成人看上去会比较肿，但要是觉得口感太淡，可以适当考虑加少量盐调味。"}
```

链接: https://pan.baidu.com/s/1JXoN7tu326mkh7gZmHUkrA?pwd=nwmu 提取码: nwmu 


- 清华新闻（THUCNews），新闻数据集可用于标题生成，文本领域分类

清华新闻（THUCNews）数据是清华大学自然语言处理实验室整理，根据新浪新闻RSS订阅频道2005~2011年间的历史数据筛选过滤生成，在原始新浪新闻分类体系的基础上，重新整合划分出14个候选分类类别：财经、彩票、房产、股票、家居、教育、科技、社会、时尚、时政、体育、星座、游戏、娱乐。

出处： http://thuctc.thunlp.org/#%E4%B8%AD%E6%96%87%E6%96%87%E6%9C%AC%E5%88%86%E7%B1%BB%E6%95%B0%E6%8D%AE%E9%9B%86THUCNews

样例：

每个类别对应一个文件夹，每个文件夹中有多个文件，每个文件即是一篇新闻，第一行是新闻的标题。该数据集也可用于标题生成任务

```
马晓旭意外受伤让国奥警惕 无奈大雨格外青睐殷家军
　　记者傅亚雨沈阳报道 来到沈阳，国奥队依然没有摆脱雨水的困扰。7月31日下午6点，国奥队的日常训练再度受到大雨的干扰，无奈之下队员们只慢跑了25分钟就草草收场。
　　31日上午10点，国奥队在奥体中心外场训练的时候，天就是阴沉沉的，气象预报显示当天下午沈阳就有大雨，但幸好队伍上午的训练并没有受到任何干扰。
　　下午6点，当球队抵达训练场时，大雨已经下了几个小时，而且丝毫没有停下来的意思。抱着试一试的态度，球队开始了当天下午的例行训练，25分钟过去了，天气没有任何转好的迹象，为了保护球员们，国奥队决定中止当天的训练，全队立即返回酒店。
　　在雨中训练对足球队来说并不是什么稀罕事，但在奥运会即将开始之前，全队变得“娇贵”了。在沈阳最后一周的训练，国奥队首先要保证现有的球员不再出现意外的伤病情况以免影响正式比赛，因此这一阶段控制训练受伤、控制感冒等疾病的出现被队伍放在了相当重要的位置。而抵达沈阳之后，中后卫冯萧霆就一直没有训练，冯萧霆是7月27日在长春患上了感冒，因此也没有参加29日跟塞尔维亚的热身赛。队伍介绍说，冯萧霆并没有出现发烧症状，但为了安全起见，这两天还是让他静养休息，等感冒彻底好了之后再恢复训练。由于有了冯萧霆这个例子，因此国奥队对雨中训练就显得特别谨慎，主要是担心球员们受凉而引发感冒，造成非战斗减员。而女足队员马晓旭在热身赛中受伤导致无缘奥运的前科，也让在沈阳的国奥队现在格外警惕，“训练中不断嘱咐队员们要注意动作，我们可不能再出这样的事情了。”一位工作人员表示。
　　从长春到沈阳，雨水一路伴随着国奥队，“也邪了，我们走到哪儿雨就下到哪儿，在长春几次训练都被大雨给搅和了，没想到来沈阳又碰到这种事情。”一位国奥球员也对雨水的“青睐”有些不解。

```

链接: https://pan.baidu.com/s/1dJysoN8MomIiUR-MfLvmhg?pwd=2zw9 提取码: 2zw9 复制这段内容后打开百度网盘手机App，操作更方便哦


2. 搜狗新闻（SogouCS），新闻数据集可用作摘要，标题生成

出处：https://www.sogou.com/labs/resource/cs.php （下载不成功）

以下是处理过的版本，来自https://zhuanlan.zhihu.com/p/341398288

样例：


- 闲聊数据集，整合多个来源

出处：https://github.com/codemayq/chinese_chatbot_corpus

文件名： raw_chat_corpus.zip



## 预训练语言模型数据

https://github.com/brightmart/nlp_chinese_corpus

https://github.com/pluto-junzeng/C4-zh


https://github.com/liuhuanyong/ChineseDiachronicCorpus



header 1 | header 2
---|---
row 1 col 1 | row 1 col 2
row 2 col 1 | row 2 col 2
row 1 col 1 | row 1 col 2
row 2 col 1 | row 2 col 2



## 

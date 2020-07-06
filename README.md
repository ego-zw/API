
|文档名称|speak—产品需求文档|
|--|--|
|产品名称|speak|
|产品描述|一款帮助学生自评英语发音并且给出不同维度的测评，和帮助老师建立班级，集体管理学生们的口语练习和成绩的app|
|产品版本|1.0|
|文件现状|进行中|
|文件作者|张威|

### 加值宣言
目前市场中针对英语口语发音测评和帮助教师管理班级学生的app还非常之少，具有较大的市场空间。speak app将**采用阿里云市场中声希科技有限公司的发音测评API**去模拟真人老师，不仅告诉用户读错了，而且从音素层面标记出用户是什么错的，**帮助用户快速发现问题，提高学习效率**。支持单词和句子评测，**提供美音，英音，混合口语评测。三种严格程度可选，含有完整度，准确度，流利度三大维度的测评。** **同时利用有道智能语音合成API，去讲英语单词或者句子，以美式发音和英式发音做范读。**这些技术的综合运用可以解决学生们在口语练习是不知道自己真实的口音和没有正确的英语示范朗读的问题。

## 一、需求概述

### 1. 产品背景
随着世界全球化的进程越来越向前，人们对于掌握英语能力的需求越来越高。**其中对英语口语能力的需求的增长速度最高**。很多人群都有兴趣去学习英语发音，但是由于没有即时的对自己英语发音系统的测评和检测，导致许多人们丧失了学习英语口语的兴趣。并且**市场上app中对于英语释放朗读的不规范，导致学生们时而学习英式发音，时而学习美式发音**。这些都是学生们在学习英语口语中出现的问题。

### 2. 产品市场
经过对市场上英语口语练习类的app的调查，发现通过语音合成出示范英语朗读的app有很多，但是区分性别，区分英式发音和美式发音的app较少。同时市场上提供英语发音测评的app非常少，并且能够从音素层面（每个单词的音标上）标记出用户是什么错的测评更是凤毛麟角。

### 3. 市场概述
#### 3.1全球英语口语测评及练习类应用市场概述
> 以有考试培训需求的用户群体为口语测评的受众群体，其对应的市场规模推导如下。据国家统计局数据显示，2014年K12学生人数为1.6亿人，2016年全国在校大学生人数为2599.1万人，2016年出国留学群体约50万人，在校研究生人数为200.4万人。假设考四、六级大学生30%的人群使用移动在线口语测评产品，平均每人客单价500元。据此，预计2016年在线口语测评市场规模约283亿元。目前口语测评付费率比较低，未来商业化发展空间巨大。

从目前来看，全球的英语练习及口语测评已能完全满足日常生活的使用需要，其中也有根据阅读、单词、写作、口语进行区分了的应用，但是在专业的口语练习app的很少有专业的去对英语口语进行测评的。目前对英语口语进行专业测评的有百词斩咸蛋英语，但是其app还没有帮助教师进行班级口语管理的功能。专业英语口语测评、练习还有帮助老师管理班级的应用还未出现，整个行业还在拓展探索专业化的阶段.

#### 3.2 市场特征
- 英语学习类app市场广阔，增数量众多,目前已经处于行业饱和的时期。
- 口语成绩测评类app发展初期，目前直接针对口语测评的工具甚少，发展空间广阔。还未出现行业龙头。
- 对产品技术要求较高，需要专业权威的对口语进行测评，要考虑到语速、语调、口音等等问题。

#### 3.3. 发展优势
- 目前英语口语测评app市场广阔，竞争对手很少，竞争力小；
- 对英语口语测评有需求的市场广阔，痛点明显，具有一定的开发价值；
- 专业级的测评，口语从音素层面标记出用户的问题所在；
- 增加班级管理功能，易受到教师喜爱并推广。

## 二、核心价值（最小可行性产品）
着眼于解决用户在专业英语测评的最基本需求，speak将提供给用户专业的英语测评，专业的英语示范朗读和班级管理等服务功能。

### 用户痛点
1. 没有专业的英语测评工具，不能直观的了解自己的英语口语水平；
2. 没有专业的英语示范朗读，不知道该去哪学习的专业的英语朗读，很容易学到不那么正确的英语读音；
3. 没有班级管理功能，教师在教导学生的英语口语能力时不能管理和了解学生的英语口语学习的情况和口语能力。

## 三、用户分析
1. **目标用户群：**
- 核心用户：15-25岁较为年轻的学习英语的群体
- 主要用户：主要用户26-45岁的英语教师群体
2. **用户画像及使用场景**

**使用场景**：小光是一名正在读大二的大学生，在大一的时候已经通过了英语四级，有想要出国留学的想法，正在备考六级和雅思。目前比较难以提升的是自己的英语口语能力，去专业的补习班的话又价格太高了，小光不想花家里太多的钱，想要在专业的手机app上学习。

**使用场景**：windy是一名大学口语班的英语老师，由于课堂的时间有限，她不能去很好的测试每位同学的英语口语能力并且去告知每位同学的问题出现在哪。她想要有个好用专业的app去管理每位学生的英语口语测评和监测口语练习的作业情况。

## 四、核心价值与用户痛点
|用户痛点|API加值|
|:--:|:--:|
|无法准确的测评自己的英语口语水平|阿里云市场中声希科技有限公司的发音测评API|
|没有专业的英语范读|有道智能语音合成API|
|没有区分英式发音和美式发音的范读|有道智能语音合成API|

## 五、人工智能概率性与用户痛点

阿里云市场中声希科技有限公司的发音测评API和有道智能语音合成API有以下优势：
|英语口语测评技术优势/用户痛点|智能语音合成技术优势/用户痛点|
|:--:|:--:|
|1. 音素层的口语测评：声希科技独家MDD评测系统，模拟真人老师，不仅告诉用户读错了，而且从音素层面（声标中）标记出用户是什么错的，支持单词和句子评测，提供美音，英音，混合口语评测。|1. 标准流利的英语范读：专业级的api，生成的英语泛读准确度和专业度俱佳。|
|2. 三种严格程度：有宽松、中等、严格三种测评的严格度，满足不同口语水平的用户。|2. 多重选择：具有男生和女生的选择，满足不同性别的用户群体。具有英式发音和美式发音的选择，满足用户对不同发音的需求。|
|3. 三大维度：含有完整度，准确度，流利度三大维度的测评。|3. 文本的语音合成：能够满足千变万化的句子朗读，具有很强的时效性和即时性。|

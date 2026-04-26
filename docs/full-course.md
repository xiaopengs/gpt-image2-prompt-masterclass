# GPT Image 2 提示词大师课

> 从零基础到专业级，系统掌握 AI 图像提示词的完整指南

---

## 课程简介

本教程是一套系统化的 GPT Image 2 提示词写作指南，涵盖从入门概念到大师级方法论的完整知识体系。基于 [awesome-gpt-image-2-prompts](https://github.com/EvoLinkAI/awesome-gpt-image-2-prompts) 社区项目中大量创作者的实践案例，经过系统整理和深度解析而成。

**课程特色：**
- 4 篇 12 章，从入门到大师的完整路径
- 覆盖人像 / 海报 / UI / 产品 / 创意五大核心场景
- 含专业词汇表、美学描述体系、100+ 案例深度拆解
- 30+ 实战练习，边学边练

---

## 目录

### 入门篇（第一至四章）

1. **什么是 GPT Image 2？** — AI 图像生成的演进、核心能力、与其他工具对比
2. **提示词基础——万能公式** — 六维度拆解法、10 个常见新手错误
3. **专业词汇速查表** — 摄影术语、美学词汇、风格词汇、光线词汇
4. **美学描述入门** — 色彩理论、构图法则、氛围营造、从照片到文字

### 进阶篇（第五至八章）

5. **人像摄影提示词大师课** — 模板、光线控制、皮肤质感、姿势指导、胶片风格
6. **海报与插画创作** — 复古 / 新中式 / 极简 / 赛博朋克四大风格
7. **UI 截图与社交媒体模拟** — 手机截图、直播界面、游戏 UI 还原
8. **产品摄影与商业应用** — 材质表达、背景选择、电商主图写法

### 大师篇（第九至十一章）

9. **高级技巧与创意实验** — 风格混合、IP 角色还原、历史场景、360° 全景、超现实主义
10. **提示词工程学——系统化方法论** — C.L.E.A.R. 框架、迭代优化、JSON 结构化提示词
11. **行业应用与变现路径** — 自媒体配图、电商产品图、设计师工作流、课程售卖

### 附录

- **附录 A：100 个经典提示词模板速查**
- **附录 B：专业术语中英对照表**
- **附录 C：推荐资源与学习路径**

---


> 从零开始，学会用文字"画"出你想要的一切

---

## 第一章：什么是 GPT Image 2？

### 1.1 从"画笔"到"说话"——AI图像生成的演进

人类想"凭空创造图像"这个愿望，其实由来已久。从远古时期在洞穴墙壁上画野牛，到文艺复兴时期达芬奇用画笔勾勒蒙娜丽莎，再到摄影师用镜头凝固瞬间——每一次技术革命，都让"创造图像"这件事变得更方便一点。

但真正颠覆游戏规则的，是AI。

**第一代：GAN时代（2014-2020）**

在AI绘画的"史前时代"，人们就已经开始尝试让计算机生成图像了。但早期的方法要么效果粗糙，要么生成速度极慢，很难实用化。直到2014年，GAN的出现才真正点燃了AI图像生成的火种。

你可能听说过"深度伪造"（Deepfake）这个词。它的底层技术叫GAN（生成对抗网络），由Ian Goodfellow在2014年提出。GAN的工作原理很有意思——它就像两个小孩在比赛：一个小孩负责"造假画"，另一个小孩负责"辨别真假"。造假画的小孩越来越厉害，辨别的小孩也越来越厉害，最终造假画的小孩画出了足以乱真的作品。

但GAN有个大问题：你很难精确控制它画什么。就像你让一个孩子"画个好看的东西"，他可能画朵花，也可能画只恐龙——你说了不算。

**过渡期：CLIP与文本-图像对齐（2021）**

在GAN和扩散模型之间，有一个关键的技术突破值得一提——OpenAI在2021年发布的CLIP模型。CLIP的全称是"Contrastive Language-Image Pre-training"，翻译过来就是"对比语言-图像预训练"。

听起来很复杂？其实原理很简单：CLIP学会了"理解文字和图片之间的对应关系"。给它一句话和一张图片，它就能判断这句话和这张图片是否匹配。

为什么这很重要？因为有了CLIP，AI就不再只是"随机画图"了——它能够判断"我画的这幅图是否符合人类的描述"。这就像是给一个画家配了一个"艺术评论家"，评论家在旁边不断给反馈："这个颜色不太对""构图需要调整"。有了这种反馈机制，AI的画技才真正开始突飞猛进。

**第二代：扩散模型登场（2021-2022）**

2021年前后，一种叫"扩散模型"（Diffusion Model）的新技术横空出世。它的原理听起来有点反直觉：先给一张清晰的图片逐步加噪点，直到变成一团乱码；然后训练AI学会"反向操作"——从乱码中一点点还原出清晰的图片。

这就像是教会一个人"如何从混沌中重建秩序"。

代表性产品包括：
- **DALL-E 2**（OpenAI，2022年）：第一次让普通人体验到了"输入文字，得到图片"的魔法
- **Stable Diffusion**（Stability AI，2022年）：开源之王，让AI绘画走向大众
- **Midjourney**（2022年）：以艺术感和美感著称，迅速成为设计师和艺术爱好者的宠儿

**第三代：DALL-E 3与GPT Image 2（2023-2025）**

2023年，OpenAI发布了DALL-E 3，最大的进步是"听懂人话"的能力大幅提升。你不再需要写那些像咒语一样晦涩的提示词，用自然语言描述你想要的画面就行。

然后，2025年，**GPT Image 2**来了。

它不是一个简单的"升级版"，而是一次范式级的跃迁。如果说DALL-E 3是一个"会画画的助手"，那GPT Image 2更像是一个"全能的视觉创意总监"——它不仅能画，还能理解你的意图、处理文字、模仿各种风格，甚至在一张图中完成复杂的排版和设计。

### 1.2 GPT Image 2的核心能力和特点

那么，GPT Image 2到底强在哪里？我们一个一个来说。

#### ① 令人惊叹的文字渲染能力

这是GPT Image 2最让老玩家兴奋的一点。在之前的AI绘画工具中，"让AI在图片里写正确的字"简直是个噩梦——你会得到各种奇奇怪怪的乱码字母。但GPT Image 2可以准确地渲染中英文文字，甚至能在海报、UI界面、书籍封面中完美排版。

举个例子，社区用户@MrLarus用GPT Image 2生成了一张"科学百科全书信息图"，里面的文字、标注、数据排版全都准确无误——这在以前是几乎不可能的。

#### ② 超强的写实人像

GPT Image 2生成的写实人像已经到了"以假乱真"的程度。社区用户@BubbleBrain创作的一系列人像作品——从便利店霓虹灯下的少女，到日式温泉旅馆的和服美人——皮肤纹理、光线反射、发丝细节都极其逼真。

打个比方：如果把GPT Image 2生成的人像和真实照片混在一起，你可能需要仔细分辨才能看出区别。

#### ③ 多风格无缝切换

从日系动漫风到油画，从水彩插画到赛博朋克，从复古海报到现代UI设计——GPT Image 2几乎能模仿任何视觉风格。而且不只是表面模仿，它能抓住每种风格的精髓。

比如：
- 社区用户@liyue_ai创作的"新中式水墨海报"，将传统中国水墨画与现代设计完美融合
- 用户@4WEB1生成的"未来主义曼陀罗插画"，几何精确度和装饰细节令人叹为观止
- 用户@hmontilla_的"梦幻水彩编辑插画"，色彩流动自然得像真正的水彩颜料在纸上晕染

#### ④ 复杂排版与信息图

GPT Image 2不只是"画一幅画"，它能做复杂的视觉设计。从人物关系图谱到科学信息图，从日本超市促销传单到个人简历信息图，它都能搞定。

这就像从一个只会画静物的画家，进化成了一个全能的平面设计师。

#### ⑤ 极强的指令遵循能力

这也是GPT Image 2的一大亮点。你可以给出非常具体的指令，比如"画面中左边放一个红色杯子，右边放一本书，书的封面写上'Dream'这个词"，它基本都能准确执行。这在以前需要反复尝试多次才能成功的复杂指令，现在往往一次就能搞定。

这种"听话"的能力，背后是GPT系列大语言模型对自然语言理解的深厚功底。GPT Image 2本质上是把语言理解能力和图像生成能力做了深度融合——它不只是"根据关键词凑像素"，而是真正"理解了你的意图"。

#### ⑥ 图像编辑与局部修改

你可以上传一张图片，然后告诉GPT Image 2"把背景换成海边"或"把文字改成244.5泰铢"（真实案例来自@elliscrosby），它会精准地完成修改。

### 1.3 GPT Image 2背后的技术原理（简明版）

你可能会好奇：GPT Image 2是怎么工作的？我不打算深入技术细节，但了解基本原理会帮助你更好地写提示词。

想象一下这个场景：你闭上眼睛，有人告诉你"想象一个阳光明媚的海滩，蓝色的大海，白色的沙滩，远处有一棵棕榈树"。你会怎么做？你的大脑会根据过去的经验——你见过的海滩照片、去过的海滩、电影里的海滩场景——来"重建"这个画面。

GPT Image 2做的事情本质上是一样的，只不过它的"经验"来自数十亿张图片的训练。当你给它一个提示词时，它不是从某个"图片数据库"里搜索一张匹配的图片给你——而是根据你描述的特征，从零开始"画"一张全新的图片。

这就像一个经验丰富的画家，你告诉他"画一个穿红裙子的女人站在雨中"，他能凭记忆和理解画出这样的画面，而不是去翻画册找一张类似的。

这也解释了为什么提示词的描述如此重要——你给画家的信息越精确，他画出来的就越接近你的想法。但同时，画家也有自己的"风格"和"理解"，所以即使给出完全相同的描述，每次画出来的也会略有不同。

理解了这一点，你就会明白：
1. **为什么提示词要具体**——因为AI是"从零创作"，不是"搜索匹配"
2. **为什么每次结果不同**——因为AI有自己的"随机性"，就像画家每次下笔不可能完全一样
3. **为什么要迭代**——因为你和AI之间的"沟通"需要多轮调整才能"对齐"

### 1.4 与Midjourney/DALL-E 3等的对比

很多人会问：GPT Image 2和其他工具比，到底选哪个？

| 特点 | GPT Image 2 | Midjourney | DALL-E 3 | Stable Diffusion |
|------|------------|------------|----------|-----------------|
| **比喻** | 全能创意总监 | 艺术大师 | 聪明画师 | 可编程画板 |
| **上手难度** | ⭐（最容易） | ⭐⭐⭐ | ⭐⭐ | ⭐⭐⭐⭐⭐ |
| **写实人像** | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐ | ⭐⭐⭐ | ⭐⭐⭐⭐ |
| **艺术感** | ⭐⭐⭐⭐ | ⭐⭐⭐⭐⭐ | ⭐⭐⭐ | ⭐⭐⭐⭐ |
| **文字渲染** | ⭐⭐⭐⭐⭐ | ⭐⭐ | ⭐⭐⭐⭐ | ⭐⭐ |
| **UI/设计** | ⭐⭐⭐⭐⭐ | ⭐⭐ | ⭐⭐⭐ | ⭐⭐⭐ |

**简单总结：**

- 想要**最强艺术感和氛围感**？选Midjourney
- 想要**完全免费+本地运行+无限定制**？选Stable Diffusion
- 想要**零门槛+全能型+文字排版+人像写实**？选GPT Image 2

对于大多数零基础的小白用户，我强烈建议从GPT Image 2开始。原因很简单：它的"听话程度"最高，你用大白话描述需求，它就能给你不错的结果。等你在GPT Image 2上积累了足够的提示词经验，再尝试其他工具也不迟。

### 1.5 如何获取和使用GPT Image 2

**方式一：ChatGPT（最简单）**

如果你有ChatGPT账号（免费版或Plus版），直接在对话框里用文字描述你想生成的图片即可。Plus用户通常有更高的生成额度和更快的响应速度。

**方式二：OpenAI API（适合开发者）**

如果你是开发者，可以通过OpenAI API调用GPT Image 2的图像生成接口，集成到自己的应用中。

**方式三：第三方平台**

一些第三方平台也集成了GPT Image 2的能力，比如Evolink等，提供更多定制化的生成选项。

**开始使用的三步走：**

1. **注册账号**：访问 chat.openai.com 注册一个ChatGPT账号
2. **输入提示词**：在对话框中用自然语言描述你想要的图片（中文英文都可以，英文效果通常更佳）
3. **迭代优化**：根据生成结果，调整你的描述，逐步接近你想要的效果

就这么简单。不需要安装任何软件，不需要配置任何参数。

### 📝 第一章实战练习

**练习1：你的第一张AI图**

打开ChatGPT，输入以下任意一个提示词，观察生成结果：

- 简单版：`一张日落时分海边沙滩的照片，暖色调`
- 进阶版：`35mm胶片风格，日落时分的海边沙滩，金色光线洒在浪花上，远处有一对情侣的剪影，暖橙色调，胶片颗粒感`

**思考题：**
1. 对比两个提示词生成的结果，你发现什么区别？
2. 试着修改其中几个词（比如把"日落"改成"日出"，把"暖色调"改成"冷色调"），看看效果如何变化。

---

## 第二章：提示词基础——万能公式

### 2.1 提示词到底是什么？

在讲公式之前，我们先搞清楚一个基本概念：**提示词（Prompt）到底是什么？**

简单说，提示词就是你给AI的"说明书"。你告诉它你想要什么，它就给你生成什么。

但问题在于——人和人之间的"说明书"质量天差地别。

打个比方：你去理发店剪头发。如果你说"剪短一点"，发型师可能会给你剪成板寸——虽然确实"短了"，但未必是你想要的。但如果你说"两边推短，上面留长一点，刘海自然垂到眉毛上方，整体有点层次感"，那结果大概率会令你满意。

提示词也是一样的道理。描述越精确、越具体，结果越接近你的预期。

### 2.2 万能公式：六维度拆解法

经过大量实践和社区案例的分析，我总结了一个"万能公式"。一个好的提示词，通常包含以下六个维度：

```
📸 完整提示词 = 主体 + 动作 + 场景 + 光线 + 风格 + 质量
```

这六个维度就像做菜的六种基本调料——你可以不全放，但放得越全，味道越丰富。

接下来，我们逐个拆解。

---

### 维度一：主体（Subject）——画面里是谁/什么？

主体是你画面的"主角"。它是整张图片最核心的元素，也是你首先要确定的。

**如何描述主体？**

描述主体时，你需要回答这几个问题：
- **是谁/什么？** 人物、动物、物体、建筑……
- **长什么样？** 外貌特征、穿着打扮、表情神态……
- **什么视角？** 全身、半身、特写、鸟瞰……

**示例对比：**

| 糟糕的描述 | 好的描述 |
|-----------|---------|
| 一个女孩 | 一个20出头的东亚女孩，杏仁眼，高鼻梁，瓜子脸，皮肤白皙 |
| 一只猫 | 一只橘色英短猫，圆脸，铜色大眼睛，毛茸茸的 |
| 一辆车 | 一辆1967年款福特Mustang，红色敞篷，镀铬轮毂 |

**真实案例参考：**

社区用户@BubbleBrain的人像提示词中，主体描述极其详尽：

> "early 20s sexy Chinese female idol with ultra-realistic delicate refined Chinese features, seductive almond-shaped fox eyes with natural double eyelids, high nose bridge, small sharp V-shaped jawline, flawless porcelain skin with cool ivory undertone..."

从年龄、种族、五官到皮肤色调，每一个细节都有描述。这就是为什么他生成的人像如此逼真。

**关键技巧：** 描述主体时，要像给一个从没见过你朋友的人描述你朋友的长相一样——越具体越好。

---

### 维度二：动作/姿态（Action/Pose）——在做什么？

光有主体还不够，你还需要告诉AI你的主体在做什么、是什么姿态。

**如何描述动作？**

- **身体姿态：** 站着、坐着、走着、倚靠、弯腰……
- **手部动作：** 拿着什么、放在哪里、在做什么手势……
- **面部表情：** 微笑、严肃、惊讶、沉思、挑逗……
- **视线方向：** 看着镜头、看向远方、低头、仰望……

**示例对比：**

| 糟糕的描述 | 好的描述 |
|-----------|---------|
| 她在便利店 | 她随意地倚靠在24小时便利店的玻璃门上，身体微微弯曲，一只腿弯着踩在门框上，另一只腿伸直，一只手拿着冰饮，另一只手轻拉裙摆 |
| 他在跑步 | 他正在冲刺，身体前倾，双臂大幅度摆动，汗水从额头滑落，表情坚定 |

**真实案例参考：**

@BubbleBrain的便利店人像中，动作描述是这样的：

> "seductive casual leaning pose against the glass door of a 24-hour convenience store at late night, body slightly arched, one leg bent with foot resting against the door frame, the other leg straight, one hand holding a bottle of iced drink, the other hand lightly pulling the hem of her mini skirt"

每一个身体部位的位置都有交代。想象一下你在导演一部电影，你需要给演员精确的动作指导——提示词就是你给AI演员的"导演指令"。

---

### 维度三：场景/环境（Scene/Environment）——在哪里？

场景是主体所处的环境。它决定了画面的"舞台"。

**如何描述场景？**

- **地点：** 街道、森林、室内、海边、太空……
- **时间：** 清晨、正午、黄昏、深夜……
- **天气/季节：** 晴天、下雨、下雪、春天、秋天……
- **背景细节：** 远处有什么、周围有什么、地面是什么材质……

**示例对比：**

| 糟糕的描述 | 好的描述 |
|-----------|---------|
| 在街上 | 深夜的东京街头，霓虹灯闪烁，湿润的柏油路面上反射着粉色和蓝色的灯光，远处的自动贩卖机发出柔和的白光 |
| 在咖啡厅 | 巴黎街角的复古咖啡厅，木质桌椅，暖黄色的吊灯，窗外的梧桐树落叶纷飞，桌上有一杯拿铁和一本打开的书 |

**真实案例参考：**

@BubbleBrain的日式温泉旅馆人像：

> "warm vintage Japanese onsen ryokan aesthetic, soft ambient wooden lantern lighting mixed with gentle natural window light"

几个词就勾勒出了一个非常具体的日式旅馆氛围——木质灯笼的暖光，混合着自然窗光。你能想象出那个画面吗？这就是好场景描述的威力。

---

### 维度四：光线（Lighting）——怎么照亮的？

光线是摄影和绘画中最重要的元素之一，也是在提示词中最容易被忽略的维度。但恰恰是光线，决定了一张图是"随手拍的快照"还是"专业的摄影作品"。

打个比方：同样一个人，在浴室日光灯下自拍和在摄影棚里打专业灯光拍照，效果天差地别。AI绘图也是一样——你给它描述好光线，它就能给你电影级的画面。

**如何描述光线？**

- **方向：** 正面光、侧面光、逆光、顶光、底光……
- **质感：** 柔光（阴天的光）、硬光（直射的阳光）……
- **颜色：** 暖光（金黄色）、冷光（蓝白色）、彩色光（霓虹灯）……
- **来源：** 自然光、闪光灯、霓虹灯、烛光、台灯……

**示例对比：**

| 糟糕的描述 | 好的描述 |
|-----------|---------|
| 明亮的光线 | 黄金时刻的逆光，光线从主体身后打来，在发丝上形成金色光晕，面部处于柔和的阴影中 |
| 好看的灯光 | 温暖的木质灯笼散发出柔和的暖光，混合着从窗户透入的自然光，在人物面部形成明暗过渡 |

**真实案例参考：**

@BubbleBrain的便利店人像光线描述：

> "bright cold fluorescent store light from inside mixed with pink and blue neon glow from outside signs, realistic reflections on glass door"

便利店内部冷色调的荧光灯 + 外面粉蓝色的霓虹灯 = 一个非常具体的深夜便利店光线环境。

@iam_miharbi的极简电影人像：

> "strong silhouette lighting, deep shadow contrast"

简简单单几个词——"强剪影光，深阴影对比"——就创造出了极具戏剧感的画面。

**关键技巧：** 如果你对光线描述没有灵感，试试问自己——"这张照片如果是由一位专业摄影师拍的，他会怎么打光？"

---

### 维度五：风格（Style）——什么调调？

风格决定了画面的"艺术味道"。同样一个场景，用不同风格表现，效果完全不同。

就像同样一碗面——你用日式拉面碗装，它就是日式拉面；你用意大利盘子装，它就是fusion创意菜。内容一样，"壳"不同，感觉就完全不同。

**常见的风格类别：**

**摄影风格：**
- 35mm胶片摄影（复古、颗粒感）
- CCD相机（早期数码相机特有的质感）
- 宝丽来/即时成像（边框+褪色感）
- 时尚大片 editorial
- 纪实摄影 documentary
- 电影画面 cinematic

**绘画/艺术风格：**
- 油画（厚重笔触、质感丰富）
- 水彩（透明轻盈、色彩流动）
- 水墨画（留白、意境）
- 赛博朋克（霓虹、高科技+低生活）
- 蒸汽朋克（齿轮、铜管、维多利亚时代美学）
- 极简主义（少即是多）
- 波普艺术（鲜艳色块、重复图案）

**设计风格：**
- 日式平面设计
- 瑞士国际主义（网格、无衬线字体）
- 复古海报（20世纪初到中叶的海报风格）
- 新中式设计

**示例对比：**

| 糟糕的描述 | 好的描述 |
|-----------|---------|
| 好看的风格 | 35mm胶片摄影风格，Kodak Portra 400胶卷色调，自然颗粒感，略带暖调 |
| 动漫风格 | 日本90年代赛璐璐动画风格，平涂色块，细腻的阴影线，类似吉卜力工作室的质感 |
| 油画风格 | 印象派油画风格，粗犷的笔触，厚涂法（impasto），色彩饱和度高，类似莫奈的光影处理 |

**真实案例参考：**

社区中大量使用胶片风格的提示词。@BubbleBrain的作品几乎都会指定具体的胶片风格：

> "35mm film photography, authentic film grain, high contrast, slight color cast"

这比简单说"复古风格"精确得多——它告诉AI具体是什么胶片、什么颗粒感、什么色调偏移。

---

### 维度六：质量/技术参数（Quality）——多精细？

最后一个维度是"质量"——你希望图片的精细程度如何。

**常见的质量描述词：**

- **分辨率/细节：** ultra-realistic（超写实）、highly detailed（高细节）、8K、4K
- **渲染品质：** photorealistic（照片级真实）、cinematic（电影级）
- **负面提示（不要什么）：** no blur（不要模糊）、no watermark（不要水印）、no artifacts（不要瑕疵）

**示例：**

> "ultra-realistic, extremely sharp yet soft skin rendering, natural hair strands, realistic fabric wrinkles, no plastic skin, no digital over-sharpening, no airbrushing"

这段来自@BubbleBrain的提示词，明确告诉AI：要超写实、要自然的皮肤渲染、要真实的发丝和衣物褶皱，同时明确排除了"塑料皮肤"、"过度锐化"、"过度磨皮"等常见问题。

**关键技巧：** 质量描述就像是最后的"质检清单"——在你确认了前面五个维度之后，用质量描述来做最后的精细调节。

---

### 2.3 万能公式实战演练

好，理论讲完了，我们来实际操作一下。假设我们要生成一张"咖啡厅窗边的女孩"的照片。

**第一步：确定主体**

> 一个25岁左右的东亚女孩，长发微卷，穿着米白色毛衣，温柔的笑容

**第二步：加上动作**

> 坐在窗边的木质桌旁，双手捧着一杯拿铁，微微侧头看向窗外，脸上带着淡淡的微笑

**第三步：描述场景**

> 深秋午后的咖啡厅，落地窗外是金黄色的银杏树，木质桌面上散落着几片树叶，背景有暖色调的书架

**第四步：指定光线**

> 从窗户照入的自然侧光，在女孩脸上形成柔和的明暗过渡，咖啡杯上有一缕热气被光线照亮

**第五步：选择风格**

> 35mm胶片摄影，Fujifilm滤镜色调，略带暖调，自然胶片颗粒

**第六步：质量描述**

> 高细节，真实的皮肤质感，自然的头发光泽，电影级色彩

**组合起来：**

```
35mm film photography, Fujifilm warm tone filter, natural film grain, cinematic color grading. A 25-year-old East Asian girl with long slightly wavy hair, wearing a cream-colored knit sweater, sitting by a wooden table next to a large window in a cozy café. She's holding a latte with both hands, head slightly tilted, looking out the window with a gentle smile. Natural side light streaming through the window creating soft shadows on her face, steam from the coffee cup catching the light. Outside the window, golden ginkgo trees in late autumn, warm-toned bookshelves in the background. High detail, realistic skin texture, natural hair sheen, cinematic quality.
```

这就是一个完整的、用六维度法构建的提示词。

**再来一个例子：赛博朋克风格的街景**

**主体：** 一个戴兜帽的神秘人物，面部被阴影遮挡
**动作：** 背对镜头，走进一条霓虹灯闪烁的小巷
**场景：** 2077年的东京，全息广告牌漂浮在空中，空中飞车穿梭
**光线：** 霓虹灯的粉紫色光反射在湿润的地面上，远处有聚光灯扫过夜空
**风格：** 赛博朋克，电影级画面，类似《银翼杀手》的视觉美学
**质量：** 超高细节，光线追踪效果，8K

```
Cyberpunk cinematic photography, Blade Runner inspired. A hooded mysterious figure walking away from camera into a narrow neon-lit alley in Neo-Tokyo 2077. Floating holographic billboards overhead, flying vehicles streaking across the dark sky. Wet pavement reflecting pink and purple neon signs, distant searchlights sweeping across the skyline. Ultra-detailed ray-traced lighting, 8K quality, anamorphic lens flare, volumetric fog
```

看到了吗？同一个框架，不同的"填空内容"，就能生成完全不同风格的图片。这就是万能公式的威力——它给了你一个"模板"，你只需要往里面填内容。

当然，你完全可以用中文写——GPT Image 2对中文的理解也很不错。但如果你想追求极致效果，英文提示词通常能给出更精确的结果，因为目前的训练数据中英文素材更丰富。

### 2.4 常见新手错误（10个典型错误及修正）

在教学中，我发现新手最容易犯以下10个错误：

---

**❌ 错误1：提示词太短**

| 错误示范 | 修正 |
|---------|------|
| 美丽的女孩 | 一个22岁的东亚女孩，鹅蛋脸，杏仁眼，长直黑发，穿着白色连衣裙，站在樱花树下 |

**为什么错：** "美丽"是主观判断，你需要具体描述"美在哪里"。

---

**❌ 错误2：用否定句描述你想要的**

| 错误示范 | 修正 |
|---------|------|
| 不要把脸画丑 | 精致的五官，光滑的皮肤，自然的美感 |

**为什么错：** AI对否定词的处理不如肯定句好。告诉它"要什么"比告诉它"不要什么"更有效。

---

**❌ 错误3：忽略光线**

| 错误示范 | 修正 |
|---------|------|
| 一个女孩在街上走 | 黄昏时分，温暖的逆光从女孩身后打来，在发丝上形成金色光晕 |

**为什么错：** 光线是区分"快照"和"摄影作品"的关键。

---

**❌ 错误4：堆砌空洞形容词**

| 错误示范 | 修正 |
|---------|------|
| 超级漂亮非常美丽极其好看的梦幻场景 | 日出时分的薰衣草田，紫色花海延伸到远处的山丘，薄雾笼罩在花田上方 |

**为什么错：** "超级漂亮"对AI来说毫无信息量。

---

**❌ 错误5：中英混杂不当**

| 错误示范 | 修正 |
|---------|------|
| 一个girl在park里面walking | 要么全中文，要么全英文，或者专业术语用英文 |

**为什么错：** 语法混乱的混合会干扰AI理解。

---

**❌ 错误6：一次想塞太多内容**

| 错误示范 | 修正 |
|---------|------|
| 一张图里包含20个人在不同场景做不同的事 | 先专注一个核心场景，逐步添加元素 |

**为什么错：** 越复杂的场景，AI越容易混乱。

---

**❌ 错误7：照搬别人的提示词不理解原理**

| 错误示范 | 修正 |
|---------|------|
| 直接复制粘贴长提示词，不知道每个部分在干什么 | 理解六维度框架，按需修改 |

**为什么错：** 照搬提示词就像照抄食谱但不理解原理——换个食材你就不会了。

---

**❌ 错误8：忽略构图**

| 错误示范 | 修正 |
|---------|------|
| 一个人站着 | 主体位于画面右侧三分之一处，看向左侧，留下视觉空间 |

**为什么错：** 没有构图指示，AI可能把人物放在画面正中间，往往缺乏美感。

---

**❌ 错误9：不了解工具特性就写提示词**

| 错误示范 | 修正 |
|---------|------|
| 在GPT Image 2里写Stable Diffusion的负面提示词格式 | 了解GPT Image 2的特点，用自然语言描述 |

**为什么错：** 不同工具的提示词语法和习惯不同。

---

**❌ 错误10：只生成一次就放弃**

| 错误示范 | 修正 |
|---------|------|
| 生成一张不满意的图就说"AI不行" | 每次调整1-2个参数，反复迭代，通常3-5次就能得到满意结果 |

**为什么错：** AI图像生成是一个"对话"过程，不是一次性交易。第一张不完美很正常，逐步调整才是正确姿势。

---

### 📝 第二章实战练习

**练习1：用六维度法构建提示词**

请为以下场景分别写一个完整的六维度提示词：
1. 一个老人在公园下棋
2. 一只猫在窗台上晒太阳
3. 一辆复古摩托车停在加油站

**练习2：找茬游戏**

以下提示词有哪些问题？请指出并用六维度法修正：

> "画一个非常好看的美女，要很漂亮的那种，站在一个很好看的背景前面"

**练习3：渐进式优化**

从一个简单提示词开始，逐步添加六个维度的描述，每次生成一张图，观察变化：

- 第1次：`一个女孩`
- 第2次：`一个25岁的东亚女孩，长发，白色连衣裙`
- 第3次：添加动作和场景
- 第4次：添加光线
- 第5次：添加风格和质量

记录每次的变化，感受每个维度的作用。

### 2.5 来自社区的高手技巧

在结束第二章之前，我想分享几个来自社区高手们的实用技巧。这些技巧不是理论，而是他们在大量实践中总结出来的"干货"。

**技巧1：先确定"一句话核心"，再扩展**

不要一开始就写长篇大论的提示词。先用一句话描述你最核心的需求，然后逐步添加细节。

比如：
- 核心："深夜便利店里一个靠在门上的女孩"
- 扩展1（加主体细节）："一个20岁的中国女孩，高马尾，穿白衬衫"
- 扩展2（加光线）："荧光灯混着外面霓虹灯的粉蓝光"
- 扩展3（加风格）："35mm胶片，高对比度，胶片颗粒"
- 扩展4（加质量）："超写实，真实皮肤质感，不要塑料感"

这样层层递进，比一开始就写一大段更容易控制效果。

**技巧2：善用"参考作品"**

在提示词中提到具体的艺术家、电影、摄影师或品牌，能非常有效地传达风格意图。

比如：
- `inspired by Wes Anderson's color palette`（韦斯·安德森的配色）
- `in the style of Blade Runner cinematography`（银翼杀手的摄影风格）
- `reminiscent of Studio Ghibli's background art`（类似吉卜力的背景画）

这就像你去理发店，给理发师看了一张明星的照片说"我要这个发型"——比用文字描述准确一百倍。

**技巧3：用"否定清单"排除不想要的**

在提示词末尾加上"不要什么"，能有效避免常见的AI绘图问题：

```
no watermark, no text, no blurry areas, no extra fingers, no distorted faces, no artificial-looking skin, no JPEG artifacts
```

**技巧4：迭代比完美更重要**

不要追求"一次写出完美提示词"。高手们通常也是写一个初版→看结果→调整→再生成，反复迭代3-5次才得到满意的结果。每次只调整1-2个维度，这样你就能清楚地知道哪个改变起了什么作用。

---

## 第三章：专业词汇速查表

学会提示词的"万能公式"后，你可能还有一个困惑："我知道要描述光线，但我不知道该怎么描述啊！"

别担心，这一章就是你的"武器库"。我会按类别整理出最常用的专业词汇，每个都配上在提示词中的应用示例。你可以把它当成一本小字典，需要时随时翻阅。

### 3.1 摄影术语

摄影术语是提示词中最实用的"精武器"。掌握这些词汇，你就能像专业摄影师一样描述画面。

#### 焦距（Focal Length）

焦距决定了画面的"视角范围"和"空间压缩感"。

| 术语 | 效果 | 提示词示例 |
|------|------|-----------|
| **广角镜头 wide-angle lens** (14-35mm) | 视野宽广，近大远小明显，有空间感 | `wide-angle 24mm lens shot, expansive mountain landscape with dramatic foreground` |
| **标准镜头 standard lens** (50mm) | 接近人眼视角，自然真实 | `50mm prime lens, natural perspective, street photography` |
| **中长焦 85mm** | 人像黄金焦距，背景虚化自然 | `shot on 85mm f/1.4, beautiful bokeh, portrait photography` |
| **长焦镜头 telephoto lens** (135-200mm) | 空间压缩感强，远处的物体看起来更近 | `200mm telephoto compression, subject isolated from busy background` |
| **微距 macro** | 极近距离拍摄，展示微小细节 | `macro photography, extreme close-up of dewdrops on a spider web` |

**实战提示：** 在人像提示词中加上 `shot on 85mm f/1.4` 就能获得专业级的背景虚化效果。在风景提示词中加上 `wide-angle 16mm` 就能得到壮阔的大场景。

#### 光圈（Aperture）

光圈控制"景深"——即画面中清晰的范围。

| 术语 | 效果 | 提示词示例 |
|------|------|-----------|
| **大光圈 f/1.4-f/2.8** | 背景虚化强（浅景深），主体突出 | `f/1.4 shallow depth of field, creamy bokeh background` |
| **中等光圈 f/5.6-f/8** | 主体和部分背景都清晰 | `f/5.6, subject and immediate surroundings in focus` |
| **小光圈 f/11-f/16** | 前景到远景全部清晰（深景深），适合风景 | `f/11 deep depth of field, everything from foreground to mountains sharp` |

**类比理解：** 光圈就像你眯眼睛——眯得越紧（光圈越小），看得越清楚但越暗；睁得越大（光圈越大），周围越模糊但主体越突出。

#### ISO（感光度）

ISO影响画面的"噪点"和"明亮度"。

| 术语 | 效果 | 提示词示例 |
|------|------|-----------|
| **低ISO (100-200)** | 画面干净，无噪点 | `ISO 100, clean and noise-free image` |
| **高ISO (1600-6400)** | 画面有颗粒/噪点，有纪实感 | `high ISO grain, ISO 3200, documentary style noise` |

**实战提示：** 在追求"胶片感"时，可以故意加 `high ISO film grain`；在追求"干净细腻"时，加 `low ISO, clean image`。

#### 白平衡（White Balance）

白平衡影响画面的整体色调倾向。

| 术语 | 效果 | 提示词示例 |
|------|------|-----------|
| **暖白平衡 warm white balance** | 画面偏黄/橙，温暖感 | `warm white balance, golden tones, cozy atmosphere` |
| **冷白平衡 cool white balance** | 画面偏蓝，清冷感 | `cool white balance, blue undertones, melancholic mood` |
| **日光白平衡 daylight** | 自然真实 | `daylight white balance, natural colors` |

#### 快门速度（Shutter Speed）

| 术语 | 效果 | 提示词示例 |
|------|------|-----------|
| **高速快门 fast shutter** | 凝固运动瞬间 | `1/1000s fast shutter, frozen motion, water droplets suspended in air` |
| **慢速快门 slow shutter** | 运动模糊，表现动感 | `long exposure, light trails, smooth water surface, motion blur` |

#### 其他重要摄影术语

| 术语 | 含义 | 提示词示例 |
|------|------|-----------|
| **bokeh** | 背景虚化的光斑效果 | `beautiful bokeh balls in the background, f/1.4` |
| **曝光补偿 exposure compensation** | 画面整体明暗调节 | `slightly overexposed (+0.7 EV), airy and bright` |
| **色差 chromatic aberration** | 镜头边缘的色彩偏移（模拟真实镜头） | `subtle chromatic aberration at edges, realistic lens behavior` |
| **暗角 vignette** | 画面四角变暗 | `natural vignette, darker corners, draws attention to center` |
| **镜头光晕 lens flare** | 光线直射镜头产生的光斑 | `anamorphic lens flare, cinematic JJ Abrams style` |

---

### 3.2 美学词汇

美学词汇帮你描述画面的"整体感觉"。

#### 色调（Tone / Color Palette）

| 术语 | 效果 | 提示词示例 |
|------|------|-----------|
| **暖色调 warm tones** | 红橙黄为主，温暖舒适 | `warm orange and gold tones, autumn color palette` |
| **冷色调 cool tones** | 蓝绿紫为主，清冷安静 | `cool blue and teal tones, winter color palette` |
| **低饱和度 desaturated** | 颜色淡雅，文艺感 | `desaturated muted colors, pastel tones, understated elegance` |
| **高饱和度 vibrant** | 颜色鲜艳，活力感 | `vibrant saturated colors, bold and eye-catching` |
| **单色调 monochrome** | 一种颜色的深浅变化 | `monochrome blue, varying shades of a single hue` |
| **互补色 complementary colors** | 对比强烈的配色 | `complementary color scheme, orange and teal contrast` |
| **莫兰迪色 Morandi colors** | 灰调柔和色系，高级感 | `Morandi color palette, muted grayish pastels, sophisticated` |

#### 构图（Composition）

| 术语 | 效果 | 提示词示例 |
|------|------|-----------|
| **三分法 rule of thirds** | 主体放在1/3分割线交点 | `rule of thirds composition, subject placed at right third` |
| **对称构图 symmetrical** | 左右或上下对称，庄重感 | `perfect symmetrical composition, mirror reflection` |
| **居中构图 centered** | 主体在正中间，力量感 | `centered composition, subject directly in the middle` |
| **引导线 leading lines** | 用线条引导视线 | `leading lines from foreground converging to subject` |
| **框架构图 frame within frame** | 用前景元素"框住"主体 | `framed by doorway arch, natural frame composition` |
| **留白 negative space** | 大面积空白，极简感 | `generous negative space, minimalist composition` |
| **黄金螺旋 golden spiral** | 基于黄金比例的构图 | `golden spiral composition, dynamic visual flow` |

#### 氛围（Mood / Atmosphere）

| 术语 | 效果 | 提示词示例 |
|------|------|-----------|
| **梦幻 dreamy** | 柔焦、朦胧、仙境感 | `dreamy soft focus, ethereal glow, fantasy atmosphere` |
| **忧郁 melancholic** | 孤独、伤感、安静 | `melancholic mood, lonely figure, overcast sky` |
| **神秘 mysterious** | 未知、悬疑、暗调 | `mysterious atmosphere, shrouded in mist, dark shadows` |
| **欢快 cheerful** | 明亮、活泼、阳光 | `cheerful and bright, sunlit, vibrant colors` |
| **庄重 solemn** | 正式、严肃、宏伟 | `solemn grand atmosphere, monumental scale` |
| **温馨 cozy** | 温暖、舒适、家的感觉 | `cozy warm atmosphere, soft lighting, comfortable space` |
| **紧张 tense** | 压迫感、戏剧性 | `tense dramatic atmosphere, high contrast, dramatic shadows` |

---

### 3.3 风格词汇

风格词汇告诉AI"用什么画法来画"。

#### 胶片与相机风格

| 术语 | 效果 | 提示词示例 |
|------|------|-----------|
| **35mm胶片 35mm film** | 经典胶片质感 | `shot on 35mm film, Kodak Portra 400, natural grain` |
| **CCD相机 CCD camera** | 早期数码相机独特质感 | `CCD camera aesthetic, slightly overexposed, vintage digital look` |
| **宝丽来 Polaroid** | 即时成像，白边框 | `Polaroid instant film photo, white border, slightly faded colors` |
| **一次性相机 disposable camera** | 一次性相机，粗糙真实 | `disposable camera snapshot, flash lit, casual candid feel` |
| **中画幅 medium format** | 细节丰富，虚化更奶油 | `medium format film, Hasselblad, rich tonal range` |

#### 绘画风格

| 术语 | 效果 | 提示词示例 |
|------|------|-----------|
| **油画 oil painting** | 厚重笔触，色彩丰富 | `oil painting style, thick impasto brushstrokes, rich saturated colors, canvas texture` |
| **水彩 watercolor** | 透明轻盈，色彩流动 | `watercolor painting, transparent washes of color, wet-on-wet technique, paper texture visible` |
| **水墨 ink wash** | 东方美学，留白意境 | `Chinese ink wash painting, black ink on white paper, minimalist brush strokes, negative space` |
| **素描 pencil sketch** | 铅笔线条，明暗层次 | `detailed pencil sketch, graphite on paper, cross-hatching shading` |
| **丙烯 acrylic** | 鲜艳色彩，平涂感 | `acrylic painting, bold flat colors, graphic style` |
| **粉彩 pastel** | 柔和色调，温柔感 | `soft pastel drawing, chalky texture, gentle muted colors` |

#### 现代风格

| 术语 | 效果 | 提示词示例 |
|------|------|-----------|
| **赛博朋克 cyberpunk** | 霓虹灯、高科技、都市 | `cyberpunk aesthetic, neon lights, rain-soaked streets, holographic ads` |
| **蒸汽朋克 steampunk** | 齿轮、蒸汽、维多利亚时代 | `steampunk style, brass gears, copper pipes, Victorian era machinery` |
| **极简主义 minimalism** | 简洁、留白、少即是多 | `minimalist design, clean lines, lots of negative space, muted colors` |
| **波普艺术 pop art** | 鲜艳色块、重复图案 | `pop art style, Andy Warhol inspired, bold primary colors, halftone dots` |
| **包豪斯 Bauhaus** | 几何、功能主义 | `Bauhaus inspired, geometric shapes, primary colors, sans-serif typography` |
| **超现实主义 surrealism** | 梦幻、不可能的场景 | `surrealist painting, Salvador Dalí inspired, impossible geometry, dreamlike` |
| **装饰艺术 Art Deco** | 几何图案、金色、奢华 | `Art Deco style, gold geometric patterns, 1920s glamour, symmetrical design` |
| **蒸汽波 vaporwave** | 粉紫色、复古数字、罗马雕塑 | `vaporwave aesthetic, pink and purple gradient, Roman busts, retro grid` |

---

### 3.4 光线词汇

光线是画面情绪的"总开关"。掌握以下词汇，你就能精确控制画面的光影效果。

#### 按方向分类

| 术语 | 效果 | 提示词示例 |
|------|------|-----------|
| **正面光 front lighting** | 均匀照亮，无明显阴影 | `even front lighting, no harsh shadows, flat illumination` |
| **侧面光 side lighting** | 一半亮一半暗，立体感强 | `dramatic side lighting from the left, half the face in shadow` |
| **逆光 backlighting** | 主体背光，轮廓光/光晕 | `backlit silhouette, golden rim light on hair, lens flare` |
| **顶光 top lighting** | 从上方打光，戏剧感 | `overhead dramatic lighting, deep eye socket shadows, stage-like` |
| **底光 under lighting** | 从下方打光，恐怖/诡异感 | `under-lit face, eerie glow from below, horror movie lighting` |
| **伦勃朗光 Rembrandt lighting** | 脸部一侧有三角形光斑 | `Rembrandt lighting, triangular highlight on cheek, classic portrait` |

#### 按质感分类

| 术语 | 效果 | 提示词示例 |
|------|------|-----------|
| **柔光 soft light** | 阴影柔和，过渡自然 | `soft diffused lighting, overcast sky, gentle shadows` |
| **硬光 hard light** | 阴影锐利，对比强烈 | `harsh hard light, sharp shadow edges, midday sun` |
| **漫射光 diffused light** | 均匀散射，无明确方向 | `diffused window light, sheer curtain, soft and even` |

#### 特殊光线效果

| 术语 | 效果 | 提示词示例 |
|------|------|-----------|
| **黄金时刻 golden hour** | 日出/日落时的温暖金光 | `golden hour lighting, warm golden glow, long shadows` |
| **蓝色时刻 blue hour** | 日落后天空深蓝色 | `blue hour, deep blue twilight sky, city lights starting to glow` |
| **霓虹光 neon lighting** | 霓虹灯的彩色光照 | `neon sign lighting, pink and blue glow reflecting on wet surfaces` |
| **烛光 candlelight** | 温暖闪烁的火光 | `warm candlelight, flickering orange glow, intimate atmosphere` |
| **体积光 volumetric light** | 可见的光束（丁达尔效应） | `volumetric light rays through window, visible light beams, dusty atmosphere` |
| **轮廓光 rim light** | 勾勒主体边缘的光 | `rim lighting, bright outline around subject silhouette` |
| **眼神光 catchlight** | 眼睛中的反光点 | `catchlight in eyes, specular highlight reflecting light source` |

---

### 3.5 速查表使用指南

以上这些词汇不需要死记硬背。建议的使用方式是：

1. **按需查阅**：每次写提示词时，打开这一章，根据你的需求选词
2. **逐步积累**：每用熟一个词，就记下来，慢慢就都掌握了
3. **组合使用**：比如 `golden hour` + `backlighting` + `rim light` + `f/1.4 bokeh` 就是人像摄影的"黄金组合"

**一个有用的类比：** 这些词汇就像是音乐中的音符——单个音符可能不起眼，但组合起来就是旋律。提示词也是一样，单独一个 `Rembrandt lighting` 可能效果有限，但配合主体描述、场景设定和风格选择，就能产生专业级的画面。

### 📝 第三章实战练习

**练习1：词汇配对**

请将以下场景与最合适的光线词汇配对：
1. 深夜便利店少女 → ？
2. 日式温泉旅馆 → ？
3. 赛博朋克城市 → ？
4. 秋天公园人像 → ？

**练习2：用专业词汇重写**

用本章学到的词汇重写以下"大白话"提示词：

原版：`一个女孩在灯光下很漂亮`

要求：至少使用3个摄影术语、2个光线词汇、1个风格词汇。

**练习3：词汇扩展**

选择你最喜欢的一个风格词汇（如"赛博朋克"），搜索3张该风格的参考图片，然后用本章学到的词汇描述每张图片的光线、色调和构图。

---

## 第四章：美学描述入门

前一章我们学习了"词汇"，这一章我们要学习"如何用这些词汇描述美"。

如果把写提示词比作做菜，那第三章是"认识食材"，而这一章是"学会调味"——如何把食材组合成一道美味佳肴。

### 4.1 色彩理论在提示词中的应用

色彩是画面中最先被人注意到的元素。你有没有这样的经验——走在街上，远远看到一张海报，还没看清内容就被它的颜色吸引了？这就是色彩的力量。

#### 色彩的三要素

在写提示词时，你可以从三个维度来控制色彩：

**① 色相（Hue）——是什么颜色？**

色相就是我们常说的"红橙黄绿蓝靛紫"。在提示词中，你可以精确指定色相：

- `dominant teal and orange color palette`（以青色和橙色为主色调）
- `warm amber and burgundy tones`（温暖的琥珀色和酒红色调）
- `monochromatic blue scheme`（单色蓝色方案）

**② 饱和度（Saturation）——颜色有多鲜艳？**

饱和度决定颜色的"浓淡"。

- 高饱和度 → `vivid, vibrant, saturated, rich colors`
- 低饱和度 → `muted, desaturated, subdued, washed out`
- 莫兰迪色调 → `Morandi palette, dusty pastels, grayish undertones`

**③ 明度（Value/Brightness）——颜色有多亮/暗？**

明度决定画面的"轻重感"。

- 高调（亮调） → `high-key lighting, bright and airy, pastel tones`
- 低调（暗调） → `low-key lighting, dark and moody, deep shadows`
- 中间调 → `balanced exposure, natural brightness`

#### 常见的色彩搭配方案

**互补色（Complementary Colors）**

互补色是色轮上相对的两种颜色，放在一起会产生强烈的视觉冲击。

最常见的电影级配色：**青色+橙色（Teal & Orange）**

```
teal and orange color grading, cool blue shadows with warm orange highlights, cinematic color palette
```

这种配色你一定见过——几乎所有好莱坞电影都在用。人的肤色偏暖（橙色），天空和阴影偏冷（青色），两者搭配非常和谐又吸睛。

**类似色（Analogous Colors）**

色轮上相邻的颜色，放在一起非常和谐。比如红-橙-黄（暖色系）或蓝-蓝绿-绿（冷色系）。

```
analogous warm color scheme, gradient from golden yellow through amber to burnt orange, harmonious sunset palette
```

就像日落时分的天空——从金色到橙色到红色，过渡自然，赏心悦目。

**三色组（Triadic Colors）**

色轮上等距的三种颜色，活泼而平衡。

```
triadic color scheme, balanced red-yellow-blue, primary color palette, Mondrian inspired
```

**单色系（Monochromatic）**

一种颜色的不同深浅，统一而高级。

```
monochromatic blue palette, varying shades from navy to sky blue, sophisticated and calm
```

#### 色彩心理学速查

不同颜色给人不同的心理感受：

| 颜色 | 心理感受 | 适用场景 |
|------|---------|---------|
| 红色 | 热情、力量、危险 | 产品广告、戏剧性场景 |
| 橙色 | 温暖、活力、友好 | 美食、秋天主题 |
| 黄色 | 快乐、明亮、希望 | 儿童主题、阳光场景 |
| 绿色 | 自然、平静、健康 | 环保、自然、健康主题 |
| 蓝色 | 信任、专业、平静 | 企业、科技、海洋主题 |
| 紫色 | 神秘、优雅、创意 | 奢侈品、魔法主题 |
| 粉色 | 浪漫、温柔、可爱 | 婚礼、少女主题 |
| 黑色 | 高级、力量、神秘 | 奢侈品、暗黑风格 |
| 白色 | 纯净、简约、干净 | 极简设计、医疗 |

**实战应用：** 当你想让画面传达某种情绪时，先确定主色调，然后在提示词中明确指定。比如要传达"宁静"就用蓝色系，要传达"温馨"就用暖橙色系。

---

### 4.2 构图法则

构图决定了画面元素的"摆放位置"。好的构图能引导观者的视线，让画面有"呼吸感"。

#### 三分法（Rule of Thirds）

这是最基础也最实用的构图法则。

**原理：** 把画面用两条水平线和两条垂直线均分为九个格子（像一个"井"字）。把主体放在四条线的交叉点上，而不是正中间。

```
rule of thirds, subject positioned at the upper-right intersection, looking toward the left with open space ahead
```

**类比：** 想象画面是一个房间，三分法就是告诉你"不要站在正中间，靠边站更有层次感"。

#### 对称构图（Symmetry）

对称构图给人稳定、庄重、仪式感。

```
perfect bilateral symmetry, mirror-like reflection, centered subject, balanced left and right
```

**适用场景：** 建筑摄影、倒影、宗教/仪式感场景。

**类比：** 对称构图就像中国古典建筑的布局——中轴线对称，左右呼应，庄重大气。

#### 引导线构图（Leading Lines）

利用画面中的线条（道路、河流、栏杆、建筑线条）引导观者的视线。

```
leading lines created by the railway tracks converging toward the subject in the distance, vanishing point perspective
```

**类比：** 引导线就像一条"视觉走廊"——观者的目光会不自觉地沿着线条走到画面的重点。

#### 框架构图（Frame within Frame）

用前景元素（门框、窗户、树枝等）"框住"主体。

```
framed composition, subject seen through an ornate doorway arch, natural frame created by overhanging branches
```

**类比：** 框架构图就像给主体加了一个"画框"——不仅突出了主体，还增加了画面的层次感。

#### 留白（Negative Space）

故意在画面中留出大面积空白，营造极简或孤独感。

```
generous negative space, subject small in the lower-left corner, vast empty sky occupying 80% of the frame
```

**类比：** 留白就像中国水墨画中的"计白当黑"——空白不是"没有"，而是一种表达。沉默有时候比说话更有力量。

#### 对角线构图（Diagonal Composition）

将主要元素沿对角线排列，增加画面的动感和活力。

```
diagonal composition, staircase running from lower-left to upper-right, dynamic angle
```

**类比：** 如果说对称构图是"正襟危坐"，那对角线构图就是"斜靠在沙发上"——更随意、更有动感。

---

### 4.3 氛围营造技巧

氛围（Atmosphere）是画面的"灵魂"。一张技术完美的照片，如果没有氛围，就像一个五官精致但毫无表情的人——好看但没感觉。

以下是营造氛围的五个核心技巧：

#### 技巧1：用天气和季节定基调

天气和季节是氛围的"速效药"：

- `misty morning fog`（晨雾）→ 神秘、安静
- `golden autumn afternoon`（金秋午后）→ 温暖、怀旧
- `rainy night, wet reflections`（雨夜）→ 忧郁、浪漫
- `cherry blossom season, petals falling`（樱花季，花瓣飘落）→ 浪漫、短暂
- `heavy snowstorm, whiteout`（暴风雪）→ 孤独、壮观

#### 技巧2：用环境细节增加"故事感"

画面中的一些小细节能大大增强氛围：

- `a half-empty coffee cup on the table`（桌上半杯咖啡）→ 刚有人来过
- `scattered autumn leaves on the ground`（地上散落的秋叶）→ 季节感
- `condensation on the window glass`（窗户上的水雾）→ 温差、温暖室内vs寒冷室外
- `a flickering neon sign`（闪烁的霓虹灯）→ 破败、深夜

**类比：** 环境细节就像电影里的"道具"——一杯冒着热气的咖啡、一把半开的雨伞、一张皱巴巴的纸条——这些小东西让画面"活"了起来。

#### 技巧3：用色调控制情绪

参考4.1节的色彩理论，不同的色调直接对应不同的情绪：

- 暖橙+金色 → 温暖、怀旧、浪漫
- 冷蓝+青色 → 清冷、孤独、专业
- 粉+紫 → 梦幻、浪漫、少女
- 低饱和灰绿 → 文艺、沉静、日式

#### 技巧4：用景深控制注意力

通过控制"什么是清晰的，什么是模糊的"来引导注意力：

- 浅景深（主体清晰、背景模糊）→ 聚焦主体，温馨私密
- 深景深（前景到远景全部清晰）→ 大气磅礴、环境叙事
- selective focus（选择性对焦）→ 只有一小部分清晰，其余模糊，非常文艺

#### 技巧5：用"时间痕迹"增加质感

加入一些"时间流逝"的痕迹，让画面更有故事感：

- `faded vintage colors`（褪色的复古色调）
- `slightly worn and weathered`（微微磨损和风化）
- `aged paper texture`（老旧纸张质感）
- `patina on copper`（铜器上的铜绿）

---

### 4.4 从照片到文字：如何用语言描述一张好照片的感觉

这是很多人卡住的地方——"我脑子里有画面，但写不出来"。

别急，我教你一个方法：**从五感出发描述**。

#### 第一步：看——视觉描述

闭上眼睛想象那张画面，然后问自己：
- 画面中最亮的地方在哪里？（光源）
- 画面中最暗的地方在哪里？（阴影）
- 最大的色块是什么颜色？（主色调）
- 画面中有什么线条引导你的视线？（构图）
- 画面是清晰的还是模糊的？（景深/风格）

#### 第二步：感——情绪描述

看着脑海中的画面，问自己：
- 这个画面让你想到什么情绪？（温暖/孤独/兴奋/平静……）
- 如果这是一部电影的一个画面，它出现在电影的哪个段落？（开头/高潮/结尾）
- 画面中的温度是什么感觉？（温暖/寒冷/凉爽……）
- 如果给这个画面配一首音乐，是什么类型的？（钢琴/摇滚/古典/环境音……）

#### 第三步：词——翻译成提示词

把上面的感觉翻译成提示词语言：

**案例演示：假设你想描述"一个人站在窗前看雨"的画面**

**视觉描述：**
- 光源：从窗外照进来的灰白自然光
- 阴影：室内暗，人物有轮廓光
- 主色调：冷灰蓝色
- 构图：人物在画面右侧，看向左侧窗外
- 风格：胶片摄影质感

**情绪描述：**
- 情绪：安静、略带忧郁、沉思
- 电影段落：开场或结尾的慢镜头
- 温度：微凉，室内比室外暖一点
- 音乐：钢琴独奏

**翻译成提示词：**

```
35mm film photography, Kodak Portra 400 muted tones. A young man standing by a rain-streaked window, seen from a three-quarter angle, right side of the frame. Cool gray-blue tones from overcast daylight filtering through rain-covered glass, soft rim light outlining his silhouette against the darker room interior. His reflection faintly visible in the glass, head slightly bowed, contemplative mood. Rain droplets on the window catching the light, blurred cityscape beyond. Melancholic yet peaceful atmosphere, quiet solitude, shallow depth of field, gentle film grain, no text, no watermark
```

看到这个过程了吗？它就是一个"感受→分析→翻译"的流程。

#### 练习方法：看图说话

找一张你喜欢的照片（摄影师作品、电影截图、Pinterest图片都行），然后尝试用文字描述它。步骤如下：

1. **先写5个关键词**（比如：雨天、窗户、孤独、蓝色、胶片）
2. **扩展成一句话**（比如：一个年轻人在雨天站在窗前，蓝色调，胶片风格）
3. **用六维度法扩展**（添加主体细节、动作、场景、光线、风格、质量）
4. **把描述给GPT Image 2**，看生成结果和原图的相似度
5. **迭代优化**，逐步接近原图的感觉

这个练习非常有价值——它能训练你"从视觉到文字"的翻译能力。而这项能力，正是写好提示词的核心。

---

### 4.5 综合实战：从零到一完成一个提示词

最后，让我们把这一章学到的所有知识综合运用，从头到尾构建一个完整的提示词。

**场景：你想生成一张"雨夜东京街头"的照片**

**第一步：确定情绪基调**

先想清楚你要什么感觉——是孤独的？浪漫的？赛博朋克的？

决定：**电影感、略带忧郁、雨夜浪漫**

**第二步：确定色彩方案**

根据情绪选择色彩：冷蓝为主，霓虹灯点缀暖色

```
teal and orange color grading, predominantly cool blue tones with warm neon accent lights
```

**第三步：确定构图**

选择一个有故事感的构图：

```
subject walking away from camera, centered but slightly off-center, wet street stretching into the distance with vanishing point perspective
```

**第四步：确定光线**

雨夜光线的特点——霓虹灯反射在湿润的地面上：

```
rain-soaked streets reflecting neon lights, volumetric light from street lamps cutting through mist, scattered light from shop windows
```

**第五步：添加氛围细节**

加入一些"故事感"元素：

```
puddles reflecting red and blue neon signs, steam rising from a food stall, rain drops visible in the light, lone umbrella in the distance
```

**第六步：选择风格和质量**

```
cinematic 35mm film photography, anamorphic lens, Blade Runner inspired, slight chromatic aberration, natural film grain, 8K detail
```

**完整提示词：**

```
Cinematic 35mm film photography, anamorphic lens. A solitary figure with an umbrella walking down a narrow Tokyo alley at night in heavy rain, walking away from camera, slightly off-center composition. Wet asphalt reflecting vibrant neon signs in pink, blue, and red, steam rising from a ramen stall on the left, vending machine glow on the right. Teal and orange color grading, predominantly cool blue with warm neon accents. Volumetric light from street lamps cutting through light mist, rain drops caught in the light. Blade Runner inspired atmosphere, lonely yet romantic, urban melancholy. Natural film grain, slight chromatic aberration at edges, cinematic letterbox aspect ratio, high detail, 8K quality, no text, no watermark
```

这就是一个经过"美学思考"的提示词——它不只是描述了"有什么"，还描述了"什么感觉"、"什么色调"、"什么氛围"。而正是这些美学层面的描述，让AI图像从"技术合格"升级为"令人感动"。

---

### 📝 第四章实战练习

**练习1：色彩情绪配对**

请为以下情绪选择最合适的色彩方案：
1. 温馨的家庭晚餐 → ？
2. 孤独的宇航员在太空 → ？
3. 热烈的摇滚音乐会 → ？
4. 宁静的禅意花园 → ？

**练习2：构图选择**

以下场景最适合用什么构图？为什么？
1. 拍摄一座哥特式教堂的内部
2. 拍摄一辆行驶在沙漠公路上的车
3. 拍摄一个人的脸部特写，表达孤独感
4. 拍摄一朵花的微距

**练习3：从照片到提示词**

找一张你最喜欢的电影截图，用4.4节的"五感描述法"把它翻译成提示词，然后输入GPT Image 2生成。比较生成结果和原图的异同，思考哪些描述起到了作用，哪些还需要调整。

**练习4：氛围改造**

以下是一个"基础版"提示词，请用本章学到的美学技巧把它改造成一个"氛围版"：

基础版：
```
a girl sitting on a bench in a park
```

要求：
- 添加色彩描述
- 添加构图描述
- 添加至少3个氛围营造技巧
- 指定风格

---

## 入门篇总结

恭喜你读完了入门篇！让我们回顾一下你学到的核心知识：

**第一章：** 了解了GPT Image 2是什么，它在AI图像生成历史中的位置，以及它与其他工具的对比。

**第二章：** 掌握了提示词的"万能公式"——主体+动作+场景+光线+风格+质量，以及10个常见新手错误。

**第三章：** 积累了大量专业词汇——摄影术语、美学词汇、风格词汇、光线词汇，建立了你的"提示词武器库"。

**第四章：** 学会了从美学角度思考画面——色彩理论、构图法则、氛围营造，以及从"感觉"到"文字"的翻译方法。

**接下来的进阶篇**中，我们将把这些基础知识应用到具体的创作领域——人像摄影、海报设计、UI设计等，让你的提示词能力更上一层楼。

**进阶提示：** 对于想要进一步提升的同学，我建议你建立一个"提示词笔记本"——每次生成一张满意的图片，就把提示词记下来，并标注哪个部分起到了关键作用。久而久之，你会形成自己的"提示词风格"和"常用语料库"，写提示词的速度和质量都会大幅提升。

另外，多看优秀案例也是极好的学习方式。awesome-gpt-image-2-prompts社区仓库中收集了大量高质量的真实提示词，覆盖人像、海报、UI设计等多个领域。当你看到一张惊艳的AI图片时，不要只是赞叹"好看"——试着去分析它的提示词是怎么写的，用了哪些词汇，描述了哪些维度。这种"逆向工程"的思维，是提升提示词水平的最快路径。

**最后一句忠告：** 写提示词就像学游泳——你看再多教程，不下水永远学不会。所以，请打开ChatGPT，现在就开始练习吧！每写一个提示词，你都在进步。每调整一次参数，你都在积累经验。

祝你创作愉快！🎨

---

*本教程参考了 awesome-gpt-image-2-prompts 社区项目中大量创作者的实践案例，感谢所有分享提示词的创作者们。*
*特别鸣谢：@BubbleBrain、@liyue_ai、@MrLarus、@iam_miharbi、@patrickassale 等社区成员的精彩案例。*

---

## 附录：扩展阅读与进阶提示

### A. 从入门到进阶的路径建议

学完入门篇后，你已经有了一个扎实的基础。以下是建议的进阶路径：

**第1周：熟悉基础**
- 每天写3-5个提示词
- 尝试覆盖不同风格（人像、风景、海报）
- 重点练习六维度法的应用

**第2周：深入某一领域**
- 选择你最感兴趣的方向（人像/设计/插画）
- 研究该领域的高手案例
- 模仿→修改→创新

**第3周：建立个人语料库**
- 整理你用过的最佳提示词
- 按场景分类保存
- 形成自己的"模板库"

**第4周：挑战复杂项目**
- 尝试生成一组风格统一的系列图
- 挑战包含文字排版的复杂设计
- 尝试图像编辑和修改

### B. 推荐学习资源

1. **awesome-gpt-image-2-prompts**（GitHub）：最全面的GPT Image 2提示词案例库，收录了数百个高质量提示词
2. **X/Twitter上的AI艺术社区**：关注 @BubbleBrain、@liyue_ai、@MrLarus 等创作者，学习他们的最新技巧
3. **Reddit r/StableDiffusion / r/ChatGPT**：英文社区的提示词讨论
4. **即梦/哩布哩布等国内平台**：中文AI绘画社区，适合交流学习

### C. 提示词模板库

以下是几个可以直接使用的提示词模板，你只需要替换方括号中的内容即可：

**人像模板：**
```
35mm film photography, [胶片型号] film. [年龄] [种族] [性别], [面部特征], [发型], wearing [服装描述]. [动作和姿态描述], [表情和视线]. [场景描述], [时间/天气]. [光线描述]. [风格和氛围], natural film grain, cinematic quality, ultra-realistic skin texture, no watermark
```

**风景模板：**
```
[焦距] lens landscape photography. [地点描述], [时间/季节], [天气状况]. [前景元素], [中景主体], [远景背景]. [光线描述], [色调描述]. [风格], [构图方式], high detail, 8K quality, no text
```

**海报模板：**
```
[风格] style poster design. Title: "[标题文字]". [主要视觉元素描述]. [色彩方案], [排版风格]. [氛围描述], professional graphic design quality, clean typography, print-ready
```

**产品图模板：**
```
Professional product photography of [产品描述]. [摆放方式和背景]. [光线描述], [色调]. Shot on [相机/镜头], [景深描述]. [质感细节], commercial quality, studio lighting, high detail
```

### D. 常见问题FAQ

**Q：提示词应该写多长？**
A：没有固定长度。简单的场景可能20-30个词就够了，复杂的人像或设计可能需要100-200个词。关键是"每个词都有信息量"，不要堆砌无意义的形容词。

**Q：中文和英文哪个效果更好？**
A：对于GPT Image 2来说，英文效果通常更稳定，因为它在英文数据上训练得更多。但中文也能获得不错的效果，特别是当你需要描述中国文化元素时（比如"汉服"、"水墨画"）。

**Q：为什么同样的提示词，每次生成的结果不一样？**
A：这是正常的。AI图像生成有一定随机性。如果你想要更一致的结果，可以尝试多次生成，选择最满意的一张。

**Q：GPT Image 2有什么不能做的？**
A：它对极度复杂的空间关系（如精确的建筑蓝图）、非常小众的虚构角色、以及需要精确数学计算的画面可能会出错。此外，它也受到内容政策的限制，不会生成有害或不当的内容。

**Q：提示词中最重要的维度是什么？**
A：如果只能选一个，我会选"主体描述"。因为主体是画面的核心，如果主体描述不准确，其他维度再好也没用。如果可选两个，那就加上"光线"——光线是提升画面质感性价比最高的维度。

---

*本教程基于 awesome-gpt-image-2-prompts 社区项目的真实案例编写*
*特别鸣谢所有在社区中无私分享提示词的创作者们*
*教程版本：v1.0 | 更新日期：2026年4月*


---



---

## 第五章：人像摄影提示词大师课

人像是GPT Image 2最热门的应用方向之一。无论是韩国偶像写真、日系胶片人像、还是街头快照风格，GPT Image 2都能生成令人惊叹的效果。但"能用"和"惊艳"之间的差距，往往就在于提示词的细节把控。

本章将从模板、光线、质感、姿势、胶片风格五个维度，系统拆解人像提示词的写作方法论，并通过三个经典案例进行深度分析。

### 5.1 人像提示词的完整模板

一个高质量的人像提示词，通常包含以下七个层次的信息。我们可以把它想象成一张"拍摄指令表"：

```
[相机/媒介] + [光线环境] + [人物描述] + [服装造型] + [姿势动作] + [表情/眼神] + [画质/排除词]
```

**逐层详解：**

**第一层：相机/媒介定义**
这一层决定了画面的整体"质感基因"。它告诉模型，这张照片是用什么设备、什么介质拍摄的。

常用写法：
- `35mm film photography` — 经典胶片感，带颗粒和色偏
- `35mm color film photography` — 彩色胶片，更饱和
- `Analog 35mm film photography` — 强调模拟信号质感
- `mobile phone photo, old CCD camera aesthetic` — 手机/CCD相机感
- `DSLR photograph` — 数码单反感，清晰锐利
- `Polaroid instant photo` — 拍立得效果

**第二层：光线环境**
光线是摄影的灵魂。在提示词中，你需要描述光源类型、方向、色温、以及与环境的交互。

示例：
- `harsh convenience store fluorescent lighting mixed with colorful neon signs from outside`
- `soft ambient wooden lantern lighting mixed with gentle natural window light`
- `harsh direct on-camera flash, specular highlights on skin`
- `gentle diffused natural window light, slight overexposure`

**第三层：人物描述**
这是最核心的部分，需要涵盖年龄、种族、五官特征、皮肤质感。

关键技巧：用具体的形容词替代笼统的"beautiful"或"pretty"。例如：
- `almond-shaped fox eyes with natural double eyelids`（杏仁形狐狸眼，自然双眼皮）
- `high nose bridge`（高鼻梁）
- `small sharp V-shaped jawline`（小巧锐利的V型下颌线）
- `flawless porcelain skin with cool ivory undertone`（无瑕瓷肌，冷象牙色调）
- `visible specular highlights from fluorescent light`（可见的荧光灯高光反射）

**第四层：服装造型**
服装要服务于整体氛围。不要只写"穿白色衬衫"，要描述材质、合身度、穿着方式。

- `oversized white button-up shirt, unbuttoned at the top, loosely tied at the waist`
- `loose white yukata deliberately slipped off one shoulder`
- `loose white tank top and white high-waisted basketball shorts, white knee-high sports socks`

**第五层：姿势动作**
姿势是"导演"画面的关键。需要描述身体的朝向、重心的位置、四肢的具体位置、手部动作。

- `body slightly arched, one leg bent with foot resting against the door frame, the other leg straight`
- `seductive relaxed sitting pose on the edge of a traditional wooden engawa veranda`
- `body angled sideways with naturally arched back, one leg extended forward toward the camera`

**第六层：表情/眼神**
表情是情绪的载体。不要只说"smiling"，要描述眼神的方向、嘴部的状态、整体情绪氛围。

- `intensely seductive playful yet slightly vulnerable gaze straight at the viewer with soft doe eyes`
- `soft playful gaze, light smile or neutral lips, gentle eye contact with camera`
- `calm, slightly distant, natural lips`

**第七层：画质/排除词**
这是"保险条款"，用来确保画面质量。

常用写法：
- `no plastic skin, no digital over-sharpening, no airbrushing, no blemishes, no oily skin, no watermark, no text`
- `extremely sharp yet soft skin rendering, natural hair strands, realistic fabric wrinkles`
- `authentic 35mm film color grading`

### 5.2 光线控制：5种经典人像光线写法

光线是人像摄影中最重要的变量。同一个人、同一个场景，换一种光线，效果完全不同。以下是5种经典人像光线及其提示词写法：

#### 5.2.1 荧光灯混合霓虹光（Convenience Store Neon）

**适用场景：** 深夜便利店、街头、赛博朋克氛围

**写法要点：** 需要描述两种光源的混合——室内冷色荧光灯 + 室外暖色/彩色霓虹灯。

```
harsh convenience store fluorescent lighting mixed with colorful neon signs from outside,
bright cold fluorescent store light from inside mixed with pink and blue neon glow from
outside signs, realistic reflections on glass door
```

**效果特点：** 冷暖对比强烈，面部出现冷暖交替的色彩，玻璃表面有真实反射，整体氛围偏赛博朋克。

#### 5.2.2 柔和自然窗光（Soft Natural Window Light）

**适用场景：** 室内日系、居家、清新风格

**写法要点：** 强调"漫射"和"柔和"。

```
gentle diffused natural window light, slight overexposure, pastel tones, low contrast,
soft highlights, gentle light wrapping around face and body
```

**效果特点：** 画面通透、空气感强、对比度低、阴影过渡柔和，人物肤色均匀透亮。

#### 5.2.3 机顶直闪（Direct On-Camera Flash）

**适用场景：** 街头、派对、运动场、Y2K风格

**写法要点：** 强调"刺眼"、"高光"、"眼神光"。

```
harsh direct on-camera flash, specular highlights on skin and clothing, strong catchlights
in eyes, high contrast flash illumination, authentic film grain and color shift
```

**效果特点：** 前景人物被打亮，背景压暗，皮肤上有明显高光点，眼睛有强烈的圆形眼神光，整体有"傻瓜相机直出"的粗粝感。

#### 5.2.4 暖色环境光（Warm Ambient Light）

**适用场景：** 温泉旅馆、和室、烛光晚餐

**写法要点：** 需要指定光源类型（灯笼、壁灯、烛光）和色温（暖色）。

```
soft ambient wooden lantern lighting mixed with gentle natural window light, gentle rim
lighting highlighting skin and fabric texture, authentic vintage film color grading with
warm tones
```

**效果特点：** 整体偏暖黄/暖橙色，人物轮廓有柔和的边缘光，皮肤呈现温暖的象牙色调，氛围温馨复古。

#### 5.2.5 强对比轮廓光（Strong Silhouette Lighting）

**适用场景：** 极简人像、电影感、概念摄影

**写法要点：** 强调"剪影"和"深色阴影"。

```
strong silhouette lighting, deep shadow contrast, intense orange to red gradient
environment, reflective glossy floor, symmetrical composition
```

**效果特点：** 人物主体大部分被阴影覆盖，只有轮廓边缘被光线勾勒，画面戏剧性强，视觉冲击力大。

#### 光线写法对比速查表

| 光线类型 | 关键词 | 对比度 | 色温 | 适合场景 |
|---------|--------|-------|------|---------|
| 荧光+霓虹 | harsh fluorescent, neon glow, color cast | 高 | 冷暖混合 | 深夜、赛博朋克 |
| 柔和窗光 | diffused, overexposure, pastel | 低 | 中性偏暖 | 日系、居家 |
| 机顶直闪 | on-camera flash, specular, catchlights | 高 | 中性 | 街头、运动、Y2K |
| 暖色环境光 | lantern, warm tones, rim light | 中 | 暖 | 温泉、和室、复古 |
| 轮廓光 | silhouette, deep shadow, gradient | 极高 | 取决于环境 | 极简、电影感 |

### 5.3 皮肤质感描写技巧

GPT Image 2 最令人印象深刻的能力之一，就是能生成极其真实的皮肤质感。但这需要你在提示词中主动"请求"这些细节。

#### 5.3.1 皮肤底色描写

不要只写"white skin"或"fair skin"。要描述具体的色调和质感：

- `flawless porcelain skin with cool ivory undertone` — 冷色调瓷肌
- `flawless porcelain skin with warm ivory undertone` — 暖色调瓷肌
- `fresh glowing skin, realistic texture` — 新鲜发光肌，真实质感
- `dewy realistic skin texture, subtle imperfections` — 水润真实肤质，微妙瑕疵

**关键公式：** `[质量形容词] + [肤色描述] + [undertone色调] + [质感细节]`

#### 5.3.2 皮肤细节描写

为了让皮肤看起来"不像AI生成"，需要主动添加微细节：

- `visible specular highlights from fluorescent light` — 可见的高光反射
- `subtle skin texture and micro pores` — 微妙的皮肤纹理和毛孔
- `fine delicate skin texture with subtle pores micro details` — 细腻的皮肤纹理和微妙毛孔细节
- `natural dewy glow` — 自然水润光泽

#### 5.3.3 负面排除词

这是让皮肤"去AI化"的关键：

```
no plastic skin, no digital over-sharpening, no airbrushing, no oily skin
```

这组排除词几乎出现在@BubbleBrain的所有人像作品中，是一个经过验证的"万能负面词组"。

#### 5.3.4 不同风格的皮肤写法

| 风格 | 皮肤写法 |
|------|---------|
| 韩系偶像 | `dewy realistic skin texture, subtle imperfections, clean idol-style minimal makeup, soft glow` |
| 日系胶片 | `fresh glowing skin, realistic texture, slight imperfections, natural minimal makeup` |
| 高级时装 | `flawless porcelain skin, visible specular highlights, soft flush on cheeks` |
| 街头写实 | `realistic skin texture, subtle freckles, natural pores, no retouching` |

### 5.4 姿势指导：如何用文字"导演"人物姿态

GPT Image 2 的一个独特优势是，它能理解并执行非常具体的姿势描述。你可以像导演一样，精确控制人物的身体姿态。

#### 5.4.1 姿势描述的层次

一个完整的姿势描述应该包含：

1. **整体体态**（body position）：站、坐、靠、蹲
2. **躯干朝向**（torso angle）：正对、侧身、扭转
3. **四肢位置**（limb placement）：每只手/脚的具体位置
4. **重心分布**（weight distribution）：身体重心在哪里
5. **头部角度**（head angle）：正面、侧转、俯仰

#### 5.4.2 经典姿势模板

**靠墙站立式：**
```
seductive casual leaning pose against [surface], body slightly arched, one leg bent with
foot resting against [surface], the other leg straight
```

**坐姿放松式：**
```
seductive relaxed sitting pose on the edge of [surface], body slightly turned toward the
camera, one leg bent with foot resting on [surface], the other leg gently dangling
```

**运动感前倾式：**
```
body angled sideways with naturally arched back, one leg naturally extended forward toward
the camera and the other leg slightly bent
```

**慵懒坐地式：**
```
sitting on floor with one leg bent and the other relaxed, body slightly leaning, shoulders
not aligned, head tilted
```

**回眸式：**
```
upper body turned to the right rear, head turned toward the camera direction, forming a
classic "looking back" pose, gaze directly at the camera
```

#### 5.4.3 手部动作描写

手是姿势中最容易被忽视但最能传达情绪的部位。以下是几种经典手部动作的写法：

- `one hand holding a bottle of iced drink, the other hand lightly pulling the hem of her mini skirt` — 持物+整理衣物
- `one hand lightly holding the yukata collar, the other hand resting on the wooden floor behind her for support` — 持衣+支撑
- `one hand lightly touching collar or resting near neckline, the other relaxed` — 触摸领口+自然下垂
- `both hands lightly resting on the basketball pole at shoulder height` — 双手搭在物体上

### 5.5 胶片感/CCD感/数码感的区别和写法

在GPT Image 2的社区中，"胶片感"是最受欢迎的风格之一。但很多人分不清胶片、CCD、数码三种质感的区别，写出的提示词也就不够精准。

#### 5.5.1 三种质感的核心区别

| 特征 | 胶片感 (Film) | CCD感 | 数码感 (Digital) |
|------|-------------|-------|----------------|
| 颗粒 | 有机颗粒，大小不一 | 较粗颗粒，均匀分布 | 几乎无颗粒 |
| 色彩 | 色偏（绿/品红偏移），低饱和 | 偏冷/偏蓝，对比度低 | 高饱和，准确色彩 |
| 高光 | 柔和过渡，光晕 | 容易过曝，白色泛黄 | 锐利截止 |
| 暗部 | 有细节，不完全黑 | 快速掉落，发灰 | 纯黑，有噪点 |
| 整体感觉 | 温暖、怀旧、有厚度 | 粗粝、廉价、真实 | 干净、精确、现代 |

#### 5.5.2 胶片感写法

**35mm胶片（通用）：**
```
35mm film photography, authentic film grain, high contrast, slight color cast
```

**富士胶片（日系清新）：**
```
Fujifilm analog aesthetic (Pro 400H / Superia feel), soft pastel tones, slight
green-magenta shift, low contrast, gentle highlight roll-off, fine film grain,
subtle halation, slight vignette
```

**柔黑雾滤镜（韩系偶像）：**
```
soft black mist filter effect, lowered contrast, gentle highlight bloom, subtle glow,
soft diffusion, slightly faded blacks
```

**复古暖色胶片：**
```
authentic vintage film color grading with warm tones, gentle color shift
```

#### 5.5.3 CCD感写法

```
mobile phone photo, old CCD camera aesthetic, harsh flash, grainy, dim messy indoor
lighting, candid snapshot feeling, slight motion blur
```

**CCD的关键特征词：**
- `harsh flash` — 刺眼闪光灯
- `grainy` — 颗粒感
- `dim messy indoor lighting` — 昏暗杂乱的室内光线
- `candid snapshot feeling` — 随手拍的抓拍感
- `slight motion blur` — 轻微运动模糊

#### 5.5.4 数码感写法

如果你想要干净精确的数码效果：
```
DSLR photograph, sharp focus, studio lighting, high resolution, 8K, clean skin rendering,
accurate color reproduction
```

或者干脆不写任何胶片相关词汇，GPT Image 2默认就会倾向于数码质感。

### 5.6 案例拆解

#### 案例一：便利霓虹人像（Convenience Store Neon Portrait）

**作者：** @BubbleBrain

**Prompt原文：**

```
35mm film photography with harsh convenience store fluorescent lighting mixed with
colorful neon signs from outside, authentic film grain, high contrast, slight color cast,
cinematic street editorial style, intimate medium shot, early 20s sexy Chinese female idol
with ultra-realistic delicate refined Chinese features, seductive almond-shaped fox eyes
with natural double eyelids, high nose bridge, small sharp V-shaped jawline, flawless
porcelain skin with cool ivory undertone and visible specular highlights from fluorescent
light, subtle skin texture and micro pores, natural dewy makeup with soft flush on cheeks,
glossy natural pink lips slightly parted, subtle natural freckles across nose and cheeks,
long dark brown hair in a messy high ponytail with many loose strands falling around face
and neck, wearing an oversized white button-up shirt as the only top, unbuttoned at the top
with deep cleavage and loosely tied at the waist, paired with a tiny black pleated mini
skirt, barefoot in simple white slides, seductive casual leaning pose against the glass
door of a 24-hour convenience store at late night, body slightly arched, one leg bent with
foot resting against the door frame, the other leg straight, one hand holding a bottle of
iced drink, the other hand lightly pulling the hem of her mini skirt, intensely seductive
playful yet slightly vulnerable gaze straight at the viewer with soft doe eyes full of
quiet temptation and teasing smile, bright cold fluorescent store light from inside mixed
with pink and blue neon glow from outside signs, realistic reflections on glass door,
blurred convenience store interior with shelves and snacks in background, authentic 35mm
film color grading with harsh lighting and neon accents, extremely sharp yet soft skin
rendering, natural hair strands, realistic fabric wrinkles and drape on the oversized shirt
and mini skirt, no plastic skin, no digital over-sharpening, no airbrushing, no blemishes,
no moles, no oily skin, no watermark, no text, authentic late-night convenience store
atmosphere
```

**逐句解析：**

| 句段 | 功能 | 技巧点 |
|------|------|--------|
| `35mm film photography with harsh convenience store fluorescent lighting mixed with colorful neon signs from outside` | 相机+光线定义 | 一次性定义介质和双重光源，建立整个场景的视觉基调 |
| `authentic film grain, high contrast, slight color cast, cinematic street editorial style` | 风格定义 | 用4个连续的质感词叠加出胶片的"不完美感" |
| `intimate medium shot` | 构图定义 | "亲密中景"暗示距离感和构图范围 |
| `early 20s sexy Chinese female idol with ultra-realistic delicate refined Chinese features` | 人物大框架 | 先定年龄、气质、种族，再细化 |
| `seductive almond-shaped fox eyes with natural double eyelids, high nose bridge, small sharp V-shaped jawline` | 五官细节 | 每个五官都有具体形容词，不是笼统的"漂亮" |
| `flawless porcelain skin with cool ivory undertone and visible specular highlights from fluorescent light` | 皮肤描写 | 底色+色调+光源交互，三层叠加 |
| `subtle skin texture and micro pores` | 质感细节 | 主动请求"不完美"的细节，增加真实感 |
| `natural dewy makeup with soft flush on cheeks, glossy natural pink lips slightly parted` | 妆容+嘴部 | 嘴唇"slightly parted"暗示呼吸感，比"smiling"更自然 |
| `subtle natural freckles across nose and cheeks` | 面部细节 | 雀斑增加真实感 |
| `long dark brown hair in a messy high ponytail with many loose strands falling around face and neck` | 发型描写 | "messy"和"loose strands"打破完美的AI感 |
| `wearing an oversized white button-up shirt...unbuttoned at the top...loosely tied at the waist` | 上装描写 | 描述了穿着方式，而不仅仅是衣服类型 |
| `paired with a tiny black pleated mini skirt, barefoot in simple white slides` | 下装+鞋 | 黑白对比，休闲感 |
| `seductive casual leaning pose against the glass door of a 24-hour convenience store at late night` | 姿势大框架 | 场景+姿势合二为一 |
| `body slightly arched, one leg bent...the other leg straight` | 身体细节 | 逐个描述四肢位置 |
| `one hand holding a bottle of iced drink, the other hand lightly pulling the hem of her mini skirt` | 手部动作 | 持物+整理衣物，两个动作都有目的性 |
| `intensely seductive playful yet slightly vulnerable gaze...soft doe eyes full of quiet temptation and teasing smile` | 表情描写 | 用矛盾词（seductive yet vulnerable）制造复杂情绪 |
| `bright cold fluorescent store light...mixed with pink and blue neon glow...realistic reflections on glass door` | 光线再确认 | 第二次确认光源，强化画面光影效果 |
| `blurred convenience store interior with shelves and snacks in background` | 背景描写 | 暗示浅景深，增加层次感 |
| `authentic 35mm film color grading with harsh lighting and neon accents` | 后期调色 | 指定后期风格 |
| `extremely sharp yet soft skin rendering, natural hair strands, realistic fabric wrinkles and drape` | 质量保证 | 主动请求具体的物理细节 |
| `no plastic skin, no digital over-sharpening, no airbrushing...no watermark, no text` | 排除词 | 经典的"去AI化"排除清单 |

**效果点评：**

这个提示词是@BubbleBrain的标志性作品，全长约300词，几乎涵盖了人像提示词的每一个维度。它的最大特点是"双重光源"的设计——便利店内的冷色荧光灯与室外的粉蓝霓虹灯交织，在人物面部形成冷暖交替的色彩效果。这种光线描写方式非常高级，需要同时理解摄影和场景设计。另外，它对皮肤质感的描写也非常到位，不仅描述了底色和色调，还特意请求了"micro pores"和"specular highlights"，让皮肤既有真实感又有光泽感。整体来说，这是一个"教科书级"的人像提示词，几乎可以作为模板直接套用。

---

#### 案例二：日式温泉人像（Japanese Onsen Ryokan Portrait）

**作者：** @BubbleBrain

**Prompt原文：**

```
35mm film photography, warm vintage Japanese onsen ryokan aesthetic, soft ambient wooden
lantern lighting mixed with gentle natural window light, subtle film grain, gentle color
shift, high atmosphere editorial style, intimate medium shot, early 20s beautiful Chinese
female idol with ultra-realistic delicate refined Chinese features, seductive almond-shaped
fox eyes with natural double eyelids, high nose bridge, small sharp V-shaped jawline,
flawless porcelain skin with warm ivory undertone, visible subtle skin texture and micro
pores, soft natural makeup with dewy glow, subtle rosy flush on cheeks, natural soft pink
lips slightly parted, long dark brown hair tied in a loose low bun with some messy strands
falling around face and neck, wearing a loose white yukata (traditional Japanese bathrobe)
deliberately slipped off one shoulder and loosely tied at the waist, the fabric slightly
open revealing smooth skin and subtle cleavage, barefoot, seductive relaxed sitting pose on
the edge of a traditional wooden engawa veranda at a vintage onsen ryokan, body slightly
turned toward the camera, one leg bent with foot resting on the wooden floor, the other leg
gently dangling, one hand lightly holding the yukata collar, the other hand resting on the
wooden floor behind her for support, softly arched back to gently accentuate curves,
intensely seductive yet gentle and inviting gaze straight at the viewer with soft doe eyes
full of quiet temptation and warmth, warm wooden interior with paper sliding doors and
distant steaming hot spring in soft focus, gentle rim lighting highlighting skin and fabric
texture, authentic vintage film color grading with warm tones, extremely sharp yet soft
skin rendering, natural hair strands, realistic fabric wrinkles and drape on the yukata, no
plastic skin, no digital over-sharpening, no airbrushing, no blemishes, no moles, no oily
skin, no watermark, no text, authentic 35mm film Japanese onsen ryokan atmosphere
```

**逐句解析：**

| 句段 | 功能 | 技巧点 |
|------|------|--------|
| `warm vintage Japanese onsen ryokan aesthetic` | 场景风格 | "warm vintage"直接定调，省去后续大量环境描写 |
| `soft ambient wooden lantern lighting mixed with gentle natural window light` | 光线 | 双光源，但与便利店案例完全不同——这里是暖色+柔光 |
| `flawless porcelain skin with warm ivory undertone` | 皮肤底色 | 注意这里是"warm"而非便利店案例的"cool"——与场景色温匹配 |
| `loose white yukata deliberately slipped off one shoulder` | 服装 | 用"deliberately"强调有意为之的姿态，比单纯描述衣物更有戏剧性 |
| `seductive relaxed sitting pose on the edge of a traditional wooden engawa veranda` | 姿势 | "engawa veranda"是非常具体的日本建筑术语，模型能理解 |
| `softly arched back to gently accentuate curves` | 身体线条 | 用目的来描述动作（"to accentuate curves"），而不仅是动作本身 |
| `intensely seductive yet gentle and inviting` | 情绪 | 与便利店案例的"playful yet vulnerable"不同，这里强调"gentle and inviting"——温柔邀请 |
| `warm wooden interior with paper sliding doors and distant steaming hot spring in soft focus` | 背景 | 三层背景：近处木制内饰→纸拉门→远处冒热气的温泉，空间感极强 |
| `gentle rim lighting highlighting skin and fabric texture` | 边缘光 | 提醒模型在人物轮廓处添加光边 |
| `authentic 35mm film Japanese onsen ryokan atmosphere` | 结尾 | 首尾呼应，再次确认整体氛围 |

**效果点评：**

与便利店案例相比，这个提示词的"温度"完全不同。便利店是冷色、高对比、都市感的；温泉旅馆是暖色、低对比、自然感的。关键差异体现在几个地方：

1. **皮肤色调**：便利店用"cool ivory undertone"，温泉用"warm ivory undertone"——同样的人物，不同的色温呈现完全不同的气质。
2. **光线描述**：便利店的"harsh fluorescent"vs温泉的"soft ambient wooden lantern"——光线词的选择直接决定画面的情绪走向。
3. **表情描写**：便利店的"playful yet vulnerable"vs温泉的"gentle and inviting"——同样是诱惑感，前者是"玩味的挑逗"，后者是"温柔的邀请"。
4. **背景层次**：便利店是"blurred interior with shelves"（扁平背景），温泉是"warm wooden interior with paper sliding doors and distant steaming hot spring"（三层纵深）。

这说明同样的模板结构，只需要替换关键词，就能生成截然不同风格的人像。

---

#### 案例三：篮球场闪光灯人像（35mm Flash Editorial Portrait）

**作者：** @BubbleBrain

**Prompt原文：**

```
35mm color film photography with harsh direct on-camera flash, specular highlights on skin
and clothing, strong catchlights in eyes, high contrast flash illumination, authentic film
grain and color shift, high fashion fresh innocent basketball court editorial style,
intimate first-person low-angle POV shot from below, early 20s sexy Chinese female idol
with ultra-realistic delicate refined Chinese features, seductive almond-shaped fox eyes
with natural double eyelids, high nose bridge, small sharp V-shaped jawline, flawless
realistic porcelain skin with cool ivory undertone and visible flash specular highlights,
fine delicate skin texture with subtle pores micro details and natural dewy glow under
flash, fresh natural sporty makeup with soft dewy glow, subtle natural flush on cheeks,
natural pink lips slightly parted, subtle natural freckles across nose and cheeks, long
dark brown hair tied in a high playful ponytail with some loose strands framing the face
and realistic loose strands, wearing a loose white tank top and white high-waisted
basketball shorts, white knee-high sports socks, seductive natural leaning pose against
the basketball hoop pole on the outdoor court at dusk, body angled sideways with naturally
arched back and hips gently pushed back to accentuate perky round hips and sexy butt curve,
one leg naturally extended forward toward the camera and the other leg slightly bent to
emphasize long sexy legs, both hands lightly resting on the basketball pole at shoulder
height, intensely seductive playful yet pitiable doe-eyed gaze straight at the viewer with
soft vulnerable longing eyes and a gentle teasing smile full of quiet temptation and desire,
harsh direct on-camera flash creating sharp specular highlights and strong catchlights,
background with blurred basketball court and hoop under dusk sky, high contrast film color
grading with natural flash look, extremely sharp yet soft skin rendering with authentic 35mm
direct flash aesthetic, natural hair strands, realistic fabric texture on tank top and shorts
with socks detail, no plastic skin, no digital over-sharpening, no airbrushing, no
blemishes, no moles, no oily skin, no watermark, no text, authentic 35mm direct flash film
basketball court look, vertical 9:16 aspect ratio
```

**逐句解析：**

| 句段 | 功能 | 技巧点 |
|------|------|--------|
| `harsh direct on-camera flash, specular highlights on skin and clothing, strong catchlights in eyes` | 光线核心 | 这是三个案例中光线描写最具体的一个——指定了闪光灯位置(on-camera)、高光位置(on skin and clothing)、以及眼神光(in eyes) |
| `high fashion fresh innocent basketball court editorial style` | 风格混搭 | "high fashion"（高级时装）+"fresh innocent"（清新无辜）+"basketball court"（篮球场）——看似矛盾的风格组合，制造反差感 |
| `intimate first-person low-angle POV shot from below` | 构图视角 | 第一人称视角，低角度仰拍——暗示观看者是蹲下或坐在地面上 |
| `fine delicate skin texture with subtle pores micro details and natural dewy glow under flash` | 闪光灯下的皮肤 | 特意强调"under flash"——闪光灯下的皮肤质感与自然光完全不同 |
| `high playful ponytail` | 发型 | "playful"赋予发型情绪——不是死板的马尾，而是有活力的 |
| `loose white tank top and white high-waisted basketball shorts, white knee-high sports socks` | 运动穿搭 | 全白搭配增加"运动感"和"纯洁感"的对比 |
| `body angled sideways with naturally arched back and hips gently pushed back` | 姿势 | "hips gently pushed back"是一个非常具体的身体指令 |
| `one leg naturally extended forward toward the camera` | 腿部 | 腿伸向镜头——利用透视原理让腿部显得更长 |
| `intensely seductive playful yet pitiable doe-eyed gaze` | 表情 | "pitiable doe-eyed"（楚楚可怜的大眼）——第三种情绪变体，与前面两个案例形成对比 |
| `harsh direct on-camera flash creating sharp specular highlights and strong catchlights` | 光线再确认 | 第二次强调闪光灯效果，确保模型不会遗忘 |
| `background with blurred basketball court and hoop under dusk sky` | 背景 | 黄昏天空+虚化篮球场——时间+空间的精确定位 |
| `authentic 35mm direct flash film basketball court look, vertical 9:16 aspect ratio` | 结尾+比例 | 用`9:16`指定竖版比例 |

**效果点评：**

这是三个案例中技术难度最高的一个。机顶直闪是一种非常"难看好看"的光线——它本质上是一种廉价的光线方式（就像用手机闪光灯拍人），但在时尚摄影中却可以成为一种风格标志。这个提示词成功的关键在于：

1. **精确的光线描写**：不仅写了"flash"，还写了"specular highlights on skin"、"catchlights in eyes"、"high contrast flash illumination"——三个不同层面的闪光灯效果。
2. **视角创新**：`first-person low-angle POV shot from below`——低角度仰拍，这个视角让画面有了"被注视"的代入感。
3. **矛盾风格混搭**：`high fashion fresh innocent basketball court editorial`——把高级时装、清新无辜、篮球场三个不同世界的元素融合在一起，产生了强烈的视觉张力。

---

## 第六章：海报与插画创作

GPT Image 2 在海报和插画领域展现出了惊人的能力。它不仅能生成各种风格的海报，还能处理排版、色彩方案、甚至文字布局。本章将系统讲解海报类提示词的写作方法。

### 6.1 海报提示词模板

海报类提示词的核心结构与人像不同，它更强调"视觉框架"和"风格参照"：

```
[海报类型] + [主题内容] + [视觉风格] + [色彩方案] + [排版布局] + [细节元素] + [画质要求]
```

**逐层详解：**

**第一层：海报类型**
告诉模型你要做什么类型的海报：
- `travel poster` — 旅行海报
- `city promotional poster` — 城市宣传海报
- `movie poster` — 电影海报
- `product advertisement poster` — 产品广告海报
- `event invitation poster` — 活动邀请海报
- `editorial illustration` — 编辑插画

**第二层：主题内容**
描述海报的核心内容和主体：
- `featuring the iconic Canton Tower and Pearl River skyline`
- `Chengdu food map with local delicacies`
- `a lone astronaut standing on a desolate alien planet`

**第三层：视觉风格**
这是海报最重要的风格定义层：
- `vintage travel poster style, 1930s Art Deco` — 复古旅行海报
- `new Chinese ink wash painting style` — 新中式水墨
- `minimalist Swiss design, clean geometric shapes` — 极简主义
- `cyberpunk neon aesthetic, dark futuristic` — 赛博朋克

**第四层：色彩方案**
用具体的色彩描述替代笼统的"colorful"：
- `muted earth tones: sage green, terracotta, warm cream`
- `bold primary palette: crimson red, navy blue, gold accents`
- `monochromatic indigo with silver highlights`
- `pastel palette: soft pink, lavender, mint green`

**第五层：排版布局**
描述文字和图形的排列方式：
- `bold sans-serif title at top, body text in clean columns below`
- `centered composition with radial symmetry`
- `asymmetric layout with large image left, text right`
- `S-shaped composition flow` — S形构图（中式海报常用）

**第六层：细节元素**
添加装饰性细节：
- `traditional Chinese cloud patterns and wave motifs`
- `geometric Art Deco borders and ornaments`
- `hand-drawn ink textures and paper grain`
- `glowing neon signs and holographic elements`

### 6.2 不同风格的海报提示词

#### 6.2.1 复古旅行海报

复古旅行海报（Vintage Travel Poster）是最经典的海报风格之一。它起源于20世纪初的铁路和航空广告，特点是简洁的图形、鲜艳的色彩、和浪漫化的风景。

**核心关键词：**
```
vintage travel poster, Art Deco style, 1930s aesthetic, flat illustration,
bold geometric shapes, silkscreen print texture, retro color palette
```

**示例写法：**
```
Vintage travel poster for [目的地], Art Deco style illustration, bold flat colors
in [色系], iconic [地标] landmark depicted in stylized geometric forms, palm trees /
mountains / ocean in background, bold sans-serif typography reading "[标题]", retro
sunburst pattern, slightly textured paper feel, 1930s railway poster aesthetic
```

#### 6.2.2 新中式水墨

新中式水墨是近年来非常热门的风格，它将传统水墨画技法与现代设计理念结合。

**核心关键词：**
```
new Chinese ink wash painting, contemporary oriental aesthetics, ink curve, rice paper
texture, flowing brushstrokes, negative space (留白), traditional motifs with modern
composition
```

**示例写法（来自@liyue_ai的广州美学系列）：**
```
新中式水墨风格海报，以[城市/主题]为灵感，水墨曲线流动构成[主体图形]，大量留白，
传统云纹和波浪纹装饰，宣纸质感，低饱和度配色：墨黑、月白、淡金，现代极简构图
融合东方意境
```

#### 6.2.3 极简主义

极简主义海报追求"少即是多"的效果。

**核心关键词：**
```
minimalist design, Swiss style, clean geometric shapes, limited color palette, ample
negative space, sans-serif typography, grid-based layout
```

**示例写法：**
```
Minimalist poster design, single central element of [主体], clean geometric composition,
limited to 2-3 colors: [色1], [色2], [accent color], generous white space, bold
typography using only font weight for hierarchy, no decorative elements, Swiss
International Style
```

#### 6.2.4 赛博朋克

赛博朋克海报强调未来感、科技感和霓虹美学。

**核心关键词：**
```
cyberpunk aesthetic, neon glow, holographic elements, dark background, high contrast
neon colors (cyan, magenta, electric blue), futuristic typography, glitch effects,
rain-soaked streets
```

**示例写法：**
```
Cyberpunk movie poster, dark dystopian cityscape with towering neon-lit skyscrapers,
holographic advertisements floating in rain-soaked air, lone figure in silhouette
standing on rooftop, title "[标题]" in glowing neon typography, color palette: deep
black, electric cyan, hot magenta, gold accents, lens flare and volumetric fog,
ultra-wide cinematic composition
```

### 6.3 色彩方案在提示词中的表达

色彩是海报设计中最先被感知的元素。在提示词中，你可以通过以下几种方式来表达色彩方案：

#### 6.3.1 具体色名法

直接列出你想要的颜色名称：

```
color palette: sage green, terracotta, warm cream, soft gold accents
```

**常用色彩词库：**
- 暖色系：terracotta（赤陶色）、burgundy（酒红）、amber（琥珀色）、marigold（万寿菊黄）
- 冷色系：slate blue（石板蓝）、sage green（鼠尾草绿）、lavender（薰衣草紫）、ice blue（冰蓝）
- 中性色：warm cream（暖奶油色）、charcoal（炭灰）、ivory（象牙白）、taupe（灰褐色）
- 强调色：gold leaf（金箔）、copper（铜色）、coral（珊瑚色）、emerald（祖母绿）

#### 6.3.2 色调氛围法

用情绪词来暗示色彩方向：

```
warm nostalgic tones, muted earth colors, soft vintage palette
```

这种方法适合你不确定具体色名，但知道自己想要的"感觉"。

#### 6.3.3 对比关系法

描述色彩之间的关系而非具体颜色：

```
high contrast complementary colors, dark background with bright neon accents,
monochromatic with single pop of color
```

#### 6.3.4 色彩方案速查表

| 海报风格 | 推荐色彩方案 | 提示词写法 |
|---------|------------|----------|
| 复古旅行 | 暖色高饱和 | `bold vintage palette: crimson, navy, gold, cream` |
| 新中式水墨 | 低饱和中性 | `ink wash palette: charcoal black, moon white, pale gold, mist grey` |
| 极简主义 | 限色对比 | `limited palette: stark white, jet black, single accent in electric blue` |
| 赛博朋克 | 暗底霓虹 | `dark base with neon: deep black, electric cyan, hot magenta, gold highlights` |
| 日系清新 | 柔和粉彩 | `soft pastel palette: blush pink, sky blue, mint green, warm white` |

### 6.4 排版元素的提示词技巧

GPT Image 2 虽然不能生成完美的可编辑文字，但它能很好地模拟排版布局和视觉层次。以下是几种常见的排版描写方式：

#### 6.4.1 标题文字

虽然生成的文字可能不完全正确，但你可以描述标题的位置、大小、风格：

```
bold title text "CITY NAME" at top in large sans-serif font, subtitle below in smaller
serif type
```

#### 6.4.2 文字层次

```
hierarchical typography: large display heading, medium subheading, small body text in
clean columns
```

#### 6.4.3 装饰性排版

```
decorative border with Art Deco geometric patterns, ornamental dividers between sections
```

#### 6.4.4 信息图表排版

```
clean infographic layout with icons, data points, and short text labels organized in a
visual grid
```

**重要提示：** 如果你需要海报上有正确的中文文字，建议先用GPT Image 2生成画面部分，再用图像编辑工具手动添加文字。GPT Image 2在英文文字方面的表现优于中文。

### 6.5 案例拆解

#### 案例一：广州城市海报系列

**作者：** @liyue_ai

广州城市海报是GPT Image 2社区中最著名的系列作品之一。@liyue_ai通过不同的视觉风格反复演绎广州这座城市的意象，形成了一个"城市视觉实验"系列。

**案例1a：2026春季广州城市海报**

**Prompt原文：**
```
2026春季广州城市海报，广州塔与珠江天际线，S形构图，樱花粉与珠江蓝渐变，新中式水墨
融合现代设计，前景有木棉花枝，中景广州塔，远景珠江新城天际线，留白充足，底部有"广州
·GUANGZHOU"标题，整体风格清新雅致，春天氛围感
```

**逐句解析：**

| 句段 | 功能 | 技巧点 |
|------|------|--------|
| `2026春季广州城市海报` | 主题定位 | 时间+季节+城市+类型，一句话完成框架 |
| `广州塔与珠江天际线` | 核心主体 | 选择最具辨识度的地标 |
| `S形构图` | 构图方法 | 明确指定构图形式，指导画面布局 |
| `樱花粉与珠江蓝渐变` | 色彩方案 | 用城市特色+颜色的组合命名色彩 |
| `新中式水墨融合现代设计` | 风格定义 | 混合风格，兼有传统韵味和现代感 |
| `前景木棉花枝→中景广州塔→远景珠江新城` | 三层纵深 | 明确前景/中景/远景，建立空间层次 |
| `留白充足` | 设计原则 | "留白"是新中式风格的关键 |
| `底部"广州·GUANGZHOU"标题` | 排版 | 指定标题位置和内容 |
| `整体风格清新雅致，春天氛围感` | 氛围总结 | 用情绪词收尾 |

**效果点评：**

这个提示词展示了"中文海报提示词"的优秀写法。它用简练的中文描述了完整的视觉框架，其中"S形构图"和"前景/中景/远景"的三层纵深设计非常专业。色彩命名也很有创意——"樱花粉与珠江蓝"不仅指定了颜色，还赋予了颜色以城市特色。

**案例1b：墨曲广州美学海报**

来自@liyue_ai的另一个广州系列作品，走水墨路线：

```
ink curve Guangzhou aesthetics poster, flowing ink wash strokes forming the silhouette
of Canton Tower, Pearl River winding through the composition, traditional Chinese cloud
patterns, rice paper texture, monochromatic ink palette with single gold accent,
generous negative space, contemporary oriental design, minimal elegant typography
```

**解析要点：**
- `flowing ink wash strokes forming the silhouette` — 用"水墨笔触构成轮廓"来描述主体
- `monochromatic ink palette with single gold accent` — 单色水墨+金色点缀，经典的"一色点缀"法
- `generous negative space` — "慷慨的留白"——用英文表达中式美学概念

#### 案例二：成都美食地图（Chengdu Food Map Illustration）

**作者：** @Panda20230902

**Prompt原文：**
```
成都美食地图插画，手绘风格，展示成都代表性美食：火锅、串串香、担担面、龙抄手、
钟水饺、甜水面、兔头、钵钵鸡，每道美食配有手写标注和位置标记，地图以成都城市轮廓
为底图，穿插熊猫元素和竹子装饰，暖色调配色（红、橙、黄），复古纸张质感背景，
边角有传统中式花纹装饰，整体风格可爱有趣，信息清晰易读
```

**逐句解析：**

| 句段 | 功能 | 技巧点 |
|------|------|--------|
| `成都美食地图插画` | 类型定义 | 地图+美食+插画，三维一体 |
| `手绘风格` | 艺术风格 | 指定手绘感，区别于数码设计 |
| `展示成都代表性美食：火锅、串串香...` | 内容清单 | 列出具体美食名称，让模型有明确的内容素材 |
| `每道美食配有手写标注和位置标记` | 排版细节 | 指定标注的呈现方式 |
| `以成都城市轮廓为底图` | 底层结构 | 地图元素作为画面的结构骨架 |
| `穿插熊猫元素和竹子装饰` | 装饰元素 | 加入城市IP元素，增加辨识度 |
| `暖色调配色（红、橙、黄）` | 色彩方案 | 美食类适合暖色调，增强食欲感 |
| `复古纸张质感背景` | 材质纹理 | 纸张质感增加手绘插画的真实感 |
| `边角有传统中式花纹装饰` | 边框装饰 | 提示词中指定装饰位置（"边角"） |
| `整体风格可爱有趣，信息清晰易读` | 氛围+功能 | 同时兼顾美学和信息性 |

**效果点评：**

这个提示词的亮点在于"信息量"和"美学"的平衡。它列出了8种具体美食，让模型有明确的内容素材；同时指定了底图结构、装饰元素、色彩方案，确保画面不会变成杂乱的罗列。手绘风格+复古纸张的组合也非常适合美食主题。

#### 案例三：科幻电影海报（Science Fiction Movie Poster）

**作者：** @underwoodxie96

**Prompt原文：**
```
Science fiction movie poster, a lone astronaut standing on a desolate alien planet surface
looking up at a massive ringed gas giant planet filling the sky, derelict spacecraft debris
scattered in the foreground, the astronaut's helmet visor reflecting the planet's glow,
dramatic volumetric lighting from the gas giant's light, color palette: deep space black,
nebula purple, cosmic orange, bioluminescent teal accents, title "BEYOND THE VOID" in
futuristic metallic typography at top, billing block text at bottom, film grain texture,
cinematic 2.39:1 aspect ratio composition, epic scale, sense of wonder and isolation
```

**逐句解析：**

| 句段 | 功能 | 技巧点 |
|------|------|--------|
| `Science fiction movie poster` | 类型定义 | 直接指定电影海报+科幻类型 |
| `lone astronaut...desolate alien planet...massive ringed gas giant` | 场景叙事 | 用一个完整的场景描述建立叙事感 |
| `derelict spacecraft debris scattered in the foreground` | 前景细节 | "废弃飞船残骸"暗示背景故事 |
| `helmet visor reflecting the planet's glow` | 微观细节 | 面罩反射——既是细节也是构图元素 |
| `dramatic volumetric lighting from the gas giant's light` | 光线 | 明确光源（气态巨行星的光）和光线类型（体积光） |
| `deep space black, nebula purple, cosmic orange, bioluminescent teal accents` | 色彩方案 | 4个层次的颜色：底色→主色→辅助色→点缀色 |
| `title "BEYOND THE VOID" in futuristic metallic typography` | 标题 | 指定字体风格（未来感金属质感） |
| `billing block text at bottom` | 电影海报标准元素 | "billing block"是电影海报底部的演员/制作信息栏 |
| `film grain texture, cinematic 2.39:1 aspect ratio` | 质感+比例 | 电影感的关键：胶片颗粒+宽银幕比例 |
| `epic scale, sense of wonder and isolation` | 情绪氛围 | "史诗感"和"孤独与敬畏"的情绪双轨 |

**效果点评：**

这是一个教科书级的电影海报提示词。它的结构非常完整：场景叙事→色彩方案→排版元素→质感比例→情绪氛围。特别值得学习的是它的色彩方案写法——`deep space black, nebula purple, cosmic orange, bioluminescent teal accents`——从底色到点缀色分了四个层次，每一层都有富有想象力的命名。`billing block text at bottom`这个细节也很专业，它是指电影海报底部标准格式的制作信息，加这个细节能让海报看起来更"真实"。

---

## 第七章：UI截图与社交媒体模拟

GPT Image 2 有一个令人意想不到的强项：模拟手机截图、社交媒体界面和游戏UI。它不仅能生成逼真的UI元素，还能处理状态栏、弹幕、直播界面等复杂的叠加层。本章将深入讲解这一领域的提示词技巧。

### 7.1 UI Mockup提示词模板

UI截图类提示词的核心是"层叠结构"——你需要描述界面的各个层级：

```
[截图类型] + [设备框架] + [顶部状态栏] + [主内容区] + [叠加层] + [底部导航/控制栏] + [画质/真实感]
```

**逐层详解：**

**第一层：截图类型**
- `smartphone screenshot` — 手机截图
- `livestream screenshot` — 直播截图
- `game UI screen` — 游戏界面
- `social media feed` — 社交媒体信息流
- `app interface mockup` — 应用界面

**第二层：设备框架**
- `9:16 vertical aspect ratio, mimicking a phone screen`
- `displayed on a slim modern laptop`
- `displayed on an iPhone-style device`

**第三层：顶部状态栏**
这是让截图看起来"真实"的关键：
- `phone status bar at top with time (21:37), battery icon, signal bars, WiFi icon`
- `system notification bar with carrier name, time, and battery percentage`

**第四层：主内容区**
描述截图的核心内容——这是真正的内容层。

**第五层：叠加层**
这是UI截图的灵魂：
- `floating danmaku (弹幕) comments scrolling across the screen`
- `livestream chat overlay on the right side`
- `like/comment/share buttons overlay`
- `live viewer count badge`

**第六层：底部控制栏**
- `bottom navigation bar with Home, Discover, Notifications, Profile icons`
- `galgame-style dialog box at bottom with character portrait and text`
- `bottom action bar with input field and emoji button`

### 7.2 手机截图的逼真技巧

让AI生成的手机截图看起来"像真的"，关键在于以下细节：

#### 7.2.1 状态栏（Status Bar）

状态栏是手机截图的"身份证"。一个精确的状态栏描述能让截图立即增加真实感：

```
phone status bar at top showing: time "21:37", cellular signal bars (4 bars), WiFi icon,
battery at 83%, carrier name "China Mobile"
```

**状态栏元素清单：**
- 时间（具体到分钟）
- 信号格数
- WiFi图标
- 电池图标+百分比
- 运营商名称
- 蓝牙/飞行模式/闹钟图标（可选）

#### 7.2.2 导航栏（Navigation Bar）

底部导航栏定义了APP的身份：

```
bottom tab bar with 5 icons: Home (filled), Explore, Create (+), Messages, Profile,
active tab highlighted in [color]
```

**常见APP导航栏参考：**
- 抖音/TikTok：首页、朋友、+、消息、我
- 微信：微信、通讯录、发现、我
- 小红书：首页、购物、+、消息、我
- Twitter/X：首页、搜索、社区、通知、邮件

#### 7.2.3 弹幕（Danmaku）

弹幕是中国视频/直播平台的重要UI特征：

```
semi-transparent danmaku (bullet comments) scrolling horizontally across the screen in
white and colored text, varied sizes and speeds, some comments include emoji
```

**弹幕描写要点：**
- `semi-transparent` — 半透明，不遮挡主内容
- `scrolling horizontally` — 水平滚动方向
- `varied sizes and speeds` — 大小和速度不一致，增加真实感
- `white and colored text` — 白色为主，偶尔有彩色弹幕

### 7.3 直播截图的特殊技巧

直播截图是UI模拟中最复杂的类型之一，因为它需要同时呈现多个层级的信息。

#### 7.3.1 直播截图的层级结构

一个典型的抖音直播截图包含以下层级（从底到顶）：

1. **直播画面**（主播本人/产品展示）
2. **弹幕层**（滚动的评论）
3. **互动层**（点赞心形飘浮、礼物特效）
4. **信息层**（观众数、关注按钮、商品链接）
5. **聊天层**（底部文字聊天区）

#### 7.3.2 直播截图提示词模板

```
[a直播平台] livestream screenshot, [主播描述] in the center of frame, phone status bar
at top with time and battery, viewer count badge showing "[数字] watching", floating
heart animations and gift effects, semi-transparent danmaku scrolling across screen,
product link card at bottom showing "[产品名] ¥[价格]", chat messages overlay at bottom
left with viewer comments, follow button overlay, [色彩/光线描述], authentic phone
screenshot feel, 9:16 aspect ratio
```

#### 7.3.3 直播截图关键UI元素

| 元素 | 描述方式 | 位置 |
|------|---------|------|
| 观众数 | `viewer count badge showing "12.3K watching"` | 左上 |
| 主播信息 | `streamer name card with avatar and follow button` | 左上偏下 |
| 弹幕 | `semi-transparent scrolling danmaku comments` | 全屏覆盖 |
| 点赞特效 | `floating heart animations` | 右侧 |
| 商品卡片 | `product link card showing [product] ¥[price]` | 底部中央 |
| 聊天区 | `chat messages overlay at bottom left` | 左下 |

### 7.4 游戏界面还原

GPT Image 2 可以模拟各种游戏UI界面，从日式RPG状态画面到现代手游抽卡界面。

#### 7.4.1 RPG状态界面提示词

日式RPG状态界面的特点是信息密度高、装饰元素多、有明确的视觉层次。

**模板：**
```
Japanese RPG status screen UI, character portrait on left side showing [角色描述], status
panel on right with HP/MP bars, character stats (STR, DEX, INT, etc.), equipment slots
showing [装备列表], skill icons grid at bottom, ornate fantasy frame design in [色调]
color scheme, decorative medieval borders and runes, detailed pixel or high-res 2D art
style, game menu navigation tabs at bottom
```

#### 7.4.2 抽卡界面提示词

日本手游的抽卡（gacha）界面有非常特定的视觉语言：

```
Japanese gacha game screen, "10 consecutive pull" result screen, 10 cards arranged in
a grid showing different rarity levels (SSR gold border, SR purple, R blue), character
artwork on each card, sparkle and light effects on highest rarity cards, "NEW" badge on
new characters, gacha currency counter at top right showing remaining gems, pull again
button at bottom in glowing gold, celebratory particle effects for SSR pull, mobile
game UI style, 9:16 vertical format
```

### 7.5 案例拆解

#### 案例一：抖音直播截图（Liu Yifei Douyin Livestream Screenshot）

**作者：** @alanblogsooo

**Prompt原文：**
```
刘亦菲在抖音直播的截图，9:16竖屏，画面中刘亦菲坐在直播间里，化着精致妆容，穿白色
连衣裙，面对镜头微笑。画面顶部有手机状态栏（时间21:37，电量83%），左上角有直播观看
人数"23.8万"，画面上有半透明弹幕飘过，右侧有心形点赞飘浮动画，底部有商品链接卡片
和聊天消息。整体色调温暖，直播打光效果，真实手机截图质感。
```

**逐句解析：**

| 句段 | 功能 | 技巧点 |
|------|------|--------|
| `刘亦菲在抖音直播的截图` | 类型定义 | 直接指定平台（抖音）和类型（直播截图） |
| `9:16竖屏` | 比例 | 手机截图的标准比例 |
| `刘亦菲坐在直播间里，化着精致妆容，穿白色连衣裙` | 主播描述 | 人物的服装和状态 |
| `面对镜头微笑` | 表情 | 互动感 |
| `手机状态栏（时间21:37，电量83%）` | 状态栏 | 具体到时间和电量——这是真实感的关键 |
| `左上角"23.8万"观看人数` | 平台UI | 抖音特有的观众数显示 |
| `半透明弹幕飘过` | 弹幕层 | 直播的核心交互元素 |
| `右侧心形点赞飘浮动画` | 互动层 | 点赞是抖音直播的标志性交互 |
| `底部商品链接卡片和聊天消息` | 电商层 | 直播带货的核心UI |
| `直播打光效果，真实手机截图质感` | 光线+质感 | 用"打光效果"暗示环形灯 |

**效果点评：**

这个提示词展示了"中文UI截图提示词"的优秀写法。它的层级结构非常清晰：主播画面→状态栏→平台UI→弹幕→互动→电商→质感。每个UI元素都有明确的位置（"左上角"、"右侧"、"底部"），这让模型能精确地安排界面布局。特别值得注意的是，它给了具体的时间（21:37）和电量（83%）——这些随机但看起来合理的数字，是增加真实感的重要细节。

#### 案例二：日式RPG状态界面（Japanese RPG Status Screen）

**作者：** @Kashiko_AIart

**Prompt原文：**
```
Japanese RPG status screen, character named "[角色名]" displayed in ornate fantasy frame,
character portrait showing [角色外观描述] in detailed anime art style, HP bar in green at
8750/12000, MP bar in blue at 3400/5000, stats panel showing ATK 450, DEF 320, MAG 280,
SPD 195, equipment slots showing equipped weapon and armor with icons, skill tree grid
showing unlocked abilities with glowing nodes, inventory panel with item icons, ornate
gold and deep blue medieval UI frame with decorative runes and filigree borders, fantasy
RPG aesthetic, detailed 2D illustration quality, game menu tabs at bottom: Status /
Equipment / Skills / Items / Save
```

**逐句解析：**

| 句段 | 功能 | 技巧点 |
|------|------|--------|
| `Japanese RPG status screen` | 类型 | 直接指定日式RPG |
| `ornate fantasy frame` | UI框架 | "华丽的幻想框架"——暗示装饰性的UI边框 |
| `HP bar in green at 8750/12000` | 数值条 | 给出具体数值，增加游戏界面的真实感 |
| `stats panel showing ATK 450...` | 属性面板 | 列出具体属性名和数值 |
| `equipment slots showing equipped weapon and armor with icons` | 装备栏 | "with icons"暗示图标式展示 |
| `skill tree grid showing unlocked abilities with glowing nodes` | 技能树 | "glowing nodes"表示已解锁——用视觉状态代替文字说明 |
| `ornate gold and deep blue medieval UI frame` | UI配色 | 金+深蓝，经典的RPG配色 |
| `decorative runes and filigree borders` | 装饰细节 | "符文"和"卷须边框"——RPG UI的经典装饰元素 |
| `game menu tabs at bottom: Status / Equipment / Skills / Items / Save` | 底部菜单 | 列出具体的菜单选项名 |

**效果点评：**

这个提示词的特点是"信息密度极高"。它模拟了一个完整的RPG状态界面，包含了角色头像、HP/MP条、属性数值、装备栏、技能树、物品栏和底部菜单。每个元素都有具体的数值或内容，这让生成的界面看起来像一个真实的游戏截图。特别值得学习的是它的UI配色描述——"ornate gold and deep blue medieval UI frame"——用两个颜色+一个风格词就定义了整个界面的视觉基调。

#### 案例三：宋朝朋友圈（Song Dynasty Social Media Feed）

**作者：** @Panda20230902

**Prompt原文：**
```
宋朝风格的朋友圈截图，模拟微信朋友圈界面，顶部状态栏显示时间"戌时三刻"，电量用
古代灯笼图标表示。朋友圈内容包括：苏轼发的动态"今日游赤壁，水光接天，甚是壮观"
配图为水墨画风格赤壁图，下面有黄庭坚点赞，佛印评论"何时同游？"；李清照发的动态
"昨夜雨疏风骤，浓睡不消残酒"配图为庭院雨景图，下面有赵明诚点赞评论"夫人好文采"。
界面整体采用宣纸纹理背景，边框有宋代花纹装饰，点赞心形用红色印章图标替代，整体
兼具古代美学和现代社交媒体功能
```

**逐句解析：**

| 句段 | 功能 | 技巧点 |
|------|------|--------|
| `宋朝风格的朋友圈截图，模拟微信朋友圈界面` | 核心概念 | "古代×现代"的跨界创意是这类截图的灵魂 |
| `时间"戌时三刻"` | 古代时间 | 用古代计时方式替代现代时间——创意细节 |
| `电量用古代灯笼图标表示` | UI替换 | 把现代UI元素"翻译"成古代版本 |
| `苏轼发的动态...配图为水墨画风格赤壁图` | 内容创作 | 用历史人物的著名作品作为动态内容 |
| `黄庭坚点赞，佛印评论"何时同游？"` | 社交互动 | 使用历史人物的社交关系来设计互动 |
| `李清照发的动态...赵明诚点赞评论` | 第二条动态 | 增加内容密度，模拟真实朋友圈的多条动态 |
| `宣纸纹理背景` | 材质 | 古代纸张质感增加真实感 |
| `点赞心形用红色印章图标替代` | UI元素替换 | 印章替代心形——创意的核心转化 |
| `兼具古代美学和现代社交媒体功能` | 风格总结 | 精准概括这个创意的核心 |

**效果点评：**

这是一个极具创意的提示词案例。它的核心创意是"把现代社交媒体UI翻译成古代版本"——电量变成灯笼、时间变成戌时三刻、点赞变成印章。这种"古今混搭"的创意方式非常有效，因为它利用了用户对现代UI的熟悉感，同时通过古代元素的替换制造新鲜感。在写作技巧上，这个提示词还展示了"内容创作"能力——它不仅描述了UI框架，还为每个历史人物创作了符合其人设的动态内容（苏轼发赤壁、李清照发诗词），这让整个截图更加生动和可信。

---

## 第八章：产品摄影与商业应用

GPT Image 2 在产品摄影领域的表现令人惊艳。它能生成逼真的产品照片，处理复杂的材质反射、水珠凝结、食物质感等细节。对于电商、广告、品牌设计等商业场景，这是一个极具价值的工具。

### 8.1 产品摄影提示词模板

产品摄影提示词的结构相对固定，但需要在"材质"和"氛围"两个维度上做足文章：

```
[摄影类型] + [产品描述] + [材质细节] + [背景/环境] + [光线方案] + [氛围/情绪] + [画质要求]
```

**逐层详解：**

**第一层：摄影类型**
- `ultra-realistic product photography` — 超写实产品摄影（最常用）
- `professional product photography` — 专业产品摄影
- `studio product shot` — 影棚产品照
- `lifestyle product photography` — 生活方式产品摄影
- `e-commerce main product image` — 电商主图

**第二层：产品描述**
需要描述产品的外观、形状、颜色、状态：
- `a cold sparkling water in a clear glass bottle with condensation droplets`
- `a rich strawberry soft-serve ice cream in a waffle cone`
- `CALMING GREEN TEA Film Kit displayed frontally`

**第三层：材质细节**
这是产品摄影中最关键的环节：
- `glass bottle with realistic refraction and condensation` — 玻璃瓶的折射和水珠
- `metallic surface with brushed steel texture and subtle reflections` — 金属的拉丝质感
- `soft fabric with visible weave texture and natural drape` — 织物的编织纹理
- `ice cream with smooth creamy texture and melting drips` — 冰淇淋的融化质感

**第四层：背景/环境**
- `clean white background with soft shadow` — 纯白背景（电商标准）
- `marble surface with scattered ingredients` — 大理石台面+散落的配料
- `dark moody background with dramatic spotlighting` — 暗色戏剧性背景
- `natural outdoor setting with dappled sunlight` — 自然户外环境

**第五层：光线方案**
- `soft diffused studio lighting from the left` — 柔和左侧影棚光
- `dramatic rim lighting with deep shadows` — 戏剧性边缘光
- `natural window light with soft reflections` — 自然窗光

**第六层：氛围/情绪**
- `refreshing and summery mood` — 清新夏日氛围
- `luxurious and premium feel` — 奢华高端感
- `cozy and warm atmosphere` — 温馨舒适氛围
- `clean and minimalist aesthetic` — 干净极简美学

### 8.2 材质表达：金属、玻璃、布料、食物

材质是产品摄影的灵魂。GPT Image 2 能理解并渲染各种材质，但需要你用正确的关键词来"解锁"这些能力。

#### 8.2.1 金属材质

**关键描述词：**
- `brushed metal texture` — 拉丝金属
- `polished chrome with mirror-like reflections` — 抛光铬金属
- `matte aluminum finish` — 哑光铝面
- `rose gold metallic sheen` — 玫瑰金光泽
- `subtle reflections and specular highlights on metal surface` — 金属表面的反射和高光

**完整写法示例：**
```
product photography of a premium wireless headphone, brushed aluminum headband with matte
finish, polished chrome hinges reflecting ambient light, leather ear cushions with
visible grain texture, dark slate background, dramatic side lighting creating metallic
highlights along the headband curve
```

#### 8.2.2 玻璃材质

玻璃是最难表现的材质之一，因为它的大部分视觉效果来自反射、折射和透射。

**关键描述词：**
- `clear glass with realistic refraction` — 透明玻璃+真实折射
- `condensation droplets on cold glass surface` — 冷玻璃表面的凝结水珠
- `frosted glass with soft diffused glow` — 磨砂玻璃+柔和漫射光
- `glass bottle with visible liquid inside, light passing through` — 透过玻璃瓶的液体透光
- `crystal clear with prism-like rainbow reflections` — 水晶般清透+棱镜彩虹反射

**完整写法示例：**
```
ultra-realistic product photography of a clear glass sparkling water bottle, condensation
droplets on the cold surface catching light, visible bubbles inside the liquid refracting
light, glass transparency showing the sparkling water with tiny rising bubbles, clean white
marble surface below with soft water ring reflection, studio lighting creating bright
specular highlights on the glass curve
```

#### 8.2.3 布料材质

**关键描述词：**
- `soft cotton with visible weave texture` — 柔软棉布+可见编织纹理
- `silk with lustrous sheen and natural drape` — 丝绸光泽+自然垂坠
- `linen with slightly rumpled texture` — 亚麻微皱质感
- `ribbed knit fabric with stretch texture` — 罗纹针织弹性纹理
- `velvet with deep pile and light-absorbing quality` — 天鹅绒深绒吸光质感

#### 8.2.4 食物质材

食物摄影是最考验材质描写功力的类型。

**关键描述词：**
- `creamy smooth texture with visible swirl patterns` — 奶油质感+可见旋涡纹理
- `glistening surface with natural juices` — 闪烁光泽+自然汁水
- `crispy golden crust with visible texture` — 酥脆金黄外壳
- `fresh glossy surface with dewdrop-like moisture` — 新鲜光泽+露珠般水润
- `melting with soft drip marks` — 融化+滴落痕迹

### 8.3 背景选择与氛围营造

产品摄影的背景不仅是"衬托"，更是"叙事"。不同的背景传达不同的品牌信息。

#### 8.3.1 纯色背景

最常用的电商背景，突出产品本身：

```
clean pure white background with soft drop shadow, isolated product shot
```

**变体：**
- `light grey gradient background` — 浅灰渐变
- `soft pastel [color] background` — 柔和粉彩背景
- `black background with dramatic spotlight` — 黑色背景+聚光灯

#### 8.3.2 纹理背景

增加品质感和层次感：

```
white marble surface with subtle grey veining, scattered fresh mint leaves and lemon
slices around the product
```

#### 8.3.3 场景背景

传达使用场景和生活方式：

```
sunlit wooden picnic table in a garden, dappled light through tree leaves, summer
afternoon atmosphere
```

#### 8.3.4 背景选择指南

| 产品类型 | 推荐背景 | 原因 |
|---------|---------|------|
| 电子产品 | 纯色/深色 | 突出科技感和产品细节 |
| 食品饮料 | 纹理/场景 | 增加食欲感和使用场景联想 |
| 美妆护肤 | 浅色/大理石 | 传达清洁、高级、纯净感 |
| 服装配饰 | 场景/模特 | 展示穿着效果和搭配可能 |
| 家居用品 | 生活场景 | 展示使用场景和搭配效果 |

### 8.4 电商主图/详情图的提示词写法

电商图片有特定的视觉规范。以下是电商主图和详情图的提示词模板：

#### 8.4.1 电商主图模板

电商主图的核心要求是：产品居中、背景干净、卖点清晰。

```
e-commerce main product image, [产品名] centered in frame, [角度描述：front view / 45-degree
angle / top-down], [背景描述：clean white / light gradient], key selling points visible:
[卖点1], [卖点2], professional studio lighting, high resolution, product occupies 70-80%
of frame, clean and commercial look, suitable for online marketplace listing
```

#### 8.4.2 详情图模板

详情图需要展示产品的多个角度、细节和使用场景：

```
product detail image showing [具体细节：texture close-up / ingredient list / size comparison
/ packaging details], macro photography revealing [微距细节：surface texture / stitching /
material grain], informative annotations pointing out key features, clean layout with
organized information hierarchy, professional product catalog style
```

#### 8.4.3 电商图片集模板

如果你需要一组电商图片，可以用提示词指定多个角度：

```
e-commerce product image set for [产品名], showing: (1) front view with clean background,
(2) 45-degree angle highlighting [特色], (3) detail close-up of [材质/工艺], (4) lifestyle
shot in [使用场景], (5) size reference with hand/common object, consistent lighting and
style across all shots, white background series
```

### 8.5 案例拆解

#### 案例一：草莓冰淇淋（Strawberry Soft-Serve Ice Cream）

**作者：** @ZaraIrahh

**Prompt原文：**

```
Ultra-realistic product photography of a rich strawberry soft-serve ice cream in a crisp
waffle cone, swirled high with creamy pink folds and real strawberry chunks visible
throughout, the surface glistening with a light sugary sheen, a single perfect fresh
strawberry perched on top with its green stem intact, tiny droplets of condensation on
the ice cream surface catching the light, one small drip of melting pink cream running
down the side of the cone, the waffle cone showing realistic grid pattern texture with
golden-brown caramelization spots, placed on a white marble surface with soft scattered
rose petals, gentle morning sunlight filtering through from the upper left creating soft
warm highlights and cool shadows, shallow depth of field with creamy bokeh background,
photographed with a 100mm macro lens, f/2.8 aperture, professional food photography style,
refreshing and indulgent summer mood
```

**逐句解析：**

| 句段 | 功能 | 技巧点 |
|------|------|--------|
| `Ultra-realistic product photography` | 类型 | "超写实"定调 |
| `rich strawberry soft-serve ice cream in a crisp waffle cone` | 主体 | "rich"暗示浓郁，"crisp"暗示酥脆——质地对比 |
| `swirled high with creamy pink folds` | 形状 | "旋涡状"和"奶油粉色褶皱"描述冰淇淋的标志性形状 |
| `real strawberry chunks visible throughout` | 内含物 | "可见的草莓块"增加真实感和食欲感 |
| `surface glistening with a light sugary sheen` | 表面质感 | "glistening"和"sugary sheen"描述光泽 |
| `single perfect fresh strawberry perched on top with green stem intact` | 顶部装饰 | "完美的一颗草莓"+"绿色茎完整"——精致的细节 |
| `tiny droplets of condensation catching the light` | 水珠 | "凝结的小水珠捕捉光线"——冷饮的关键质感 |
| `one small drip of melting pink cream running down the side` | 融化感 | 一条融化痕迹暗示"即将被吃掉"的时间感 |
| `waffle cone showing realistic grid pattern texture with golden-brown caramelization spots` | 蛋筒质感 | "网格纹理"+"焦糖化斑点"——精确的材质描写 |
| `white marble surface with soft scattered rose petals` | 背景 | 大理石+玫瑰花瓣——优雅的女性化氛围 |
| `gentle morning sunlight filtering through from the upper left` | 光线方向 | 指定光线方向（左上）和时间（清晨） |
| `100mm macro lens, f/2.8 aperture` | 镜头参数 | 指定焦距和光圈——暗示浅景深效果 |
| `refreshing and indulgent summer mood` | 情绪氛围 | "refreshing"（清新）+"indulgent"（放纵）——矛盾的欲望组合 |

**效果点评：**

这是一个教科书级的食品摄影提示词。它的核心优势在于"材质描写的层次感"。冰淇淋被拆解成了多个材质层：奶油旋涡→草莓块→糖霜光泽→凝结水珠→融化滴痕→蛋筒纹理。每一层都有独立的材质描述，这让最终的图像呈现出极其丰富的质感层次。另外，`100mm macro lens, f/2.8`这种专业摄影参数的写法也很有效，它不仅暗示了浅景深效果，还告诉模型"这是一张专业食品摄影"。

---

#### 案例二：气泡水（Cold Sparkling Water）

**作者：** @meng_dagg695

**Prompt原文：**

```
A professional product photography shot of a cold sparkling water in a clear transparent
glass bottle with condensation droplets on the exterior, placed on a bed of crushed ice
with scattered slices of fresh lime and lemon, the water inside showing visible rising
bubbles catching the light, the glass bottle refracting light beautifully with bright
specular highlights along its curved surface, a thin ring of moisture on the marble
surface beneath the bottle, background is a soft blur of cool blue and white tones
creating a refreshing atmosphere, studio lighting with a key light from the upper right
and a subtle fill light on the left, shot with a 85mm lens at f/4 for moderate depth of
field, commercial beverage photography style, crisp clean refreshing mood
```

**逐句解析：**

| 句段 | 功能 | 技巧点 |
|------|------|--------|
| `clear transparent glass bottle with condensation droplets on the exterior` | 瓶身+水珠 | 玻璃透明感+外部凝结水珠——冷饮的两大标志 |
| `placed on a bed of crushed ice with scattered slices of fresh lime and lemon` | 底座环境 | 碎冰+柠檬片——饮料摄影的经典组合 |
| `visible rising bubbles catching the light` | 内部气泡 | "上升的气泡捕捉光线"——动态感的描写 |
| `glass bottle refracting light beautifully with bright specular highlights along its curved surface` | 玻璃光学效果 | 折射+高光——玻璃质感的关键 |
| `thin ring of moisture on the marble surface` | 底部细节 | 水瓶底部的水渍圈——极其写实的细节 |
| `soft blur of cool blue and white tones` | 背景色调 | 冷色虚化背景——清凉感的视觉暗示 |
| `key light from the upper right and subtle fill light on the left` | 双灯方案 | 主光+辅光——经典的影棚布光描述 |
| `85mm lens at f/4` | 镜头参数 | 比冰淇淋案例更大的景深（f/4 vs f/2.8） |
| `crisp clean refreshing mood` | 情绪 | 三个连续的形容词——清脆、干净、清爽 |

**效果点评：**

与冰淇淋案例相比，这个提示词更注重"光学效果"的描写。玻璃瓶的折射、气泡的透光、凝结水珠的光泽——这些都是光线与玻璃材质交互产生的效果。特别值得注意的是它的布光方案：`key light from the upper right and fill light on the left`——这种主光+辅光的双灯描述在产品摄影中非常实用，它让产品既有了立体感（主光产生的明暗对比），又不会有过深的阴影（辅光补充暗部）。

---

#### 案例三：绿茶套装（CALMING GREEN TEA Film Kit）

**作者：** @ZaraIrahh

**Prompt原文：**

```
CALMING GREEN TEA Film Kit displayed frontally, the open box shows soft sage-green
packaging with minimalist Japanese-inspired design, inside the box neatly arranged items:
a glass tea cup with matte green glaze, a bamboo tea whisk, individual sealed tea
sachets in translucent envelopes with printed kanji characters, a small linen cloth
with visible weave texture, and a folded card with brewing instructions, the box lining
is cream-colored soft paper with embossed leaf patterns, placed on a light oak wood
surface with natural grain visible, soft morning light from a nearby window casting
gentle shadows, overhead flat-lay composition, top-down camera angle, styled with
scattered dried tea leaves and a sprig of fresh mint, muted earth-tone color palette:
sage green, cream, warm brown, soft gold, zen-like calm and peaceful atmosphere,
lifestyle product photography, editorial quality
```

**逐句解析：**

| 句段 | 功能 | 技巧点 |
|------|------|--------|
| `CALMING GREEN TEA Film Kit displayed frontally` | 主体+角度 | "正面展示"——电商标准角度 |
| `soft sage-green packaging with minimalist Japanese-inspired design` | 包装设计 | 颜色（鼠尾草绿）+风格（日式极简）——风格化的包装描写 |
| `glass tea cup with matte green glaze` | 材质组合 | 玻璃（杯体）+哑光绿釉（表面）——两种材质叠加 |
| `bamboo tea whisk` | 天然材质 | 竹制茶筅——天然材质增加手工艺感 |
| `translucent envelopes with printed kanji characters` | 半透明+文字 | "半透信封"（材质）+"印有汉字"（文化元素） |
| `small linen cloth with visible weave texture` | 布料材质 | "可见编织纹理"——布料的真实感关键 |
| `cream-colored soft paper with embossed leaf patterns` | 内衬材质 | 奶油色软纸+压花叶纹——奢侈品包装的细节 |
| `light oak wood surface with natural grain visible` | 台面材质 | 浅橡木+可见纹理——温暖自然的底座 |
| `overhead flat-lay composition, top-down camera angle` | 构图方式 | 平铺俯拍——产品摄影的经典构图 |
| `scattered dried tea leaves and a sprig of fresh mint` | 装饰元素 | 干茶叶+新鲜薄荷——"干"与"鲜"的对比 |
| `muted earth-tone color palette: sage green, cream, warm brown, soft gold` | 色彩方案 | 4色方案，从绿到金——自然的色彩过渡 |
| `zen-like calm and peaceful atmosphere` | 情绪氛围 | "禅意般的宁静平和"——呼应绿茶的主题 |

**效果点评：**

这个提示词是"套盒类产品摄影"的优秀范例。它的核心挑战是"多物品的有序排列"——一个套装里有茶杯、茶筅、茶包、布巾、说明卡等多个物品，每个都需要独立描述材质，同时又需要整体协调。这个提示词通过以下方式解决了这个问题：

1. **逐个物品描写**：每个物品都有独立的材质描述（"matte green glaze"、"translucent envelopes"、"visible weave texture"）
2. **统一色调**：所有物品都围绕"sage green, cream, warm brown, soft gold"这一色系
3. **俯拍构图**：flat-lay（平铺）构图天然适合多物品展示
4. **装饰点缀**：散落的干茶叶和新鲜薄荷连接了产品与自然

整体来说，这个提示词展示了一种"安静的高级感"——没有花哨的效果，但每个细节都经过精心设计。

---

## 进阶技巧总结

### 通用提示词优化原则

1. **具体胜过笼统**：`"almond-shaped fox eyes with natural double eyelids"` > `"beautiful eyes"`
2. **层叠胜过平铺**：`"flawless porcelain skin with warm ivory undertone and visible specular highlights"` > `"nice skin with good lighting"`
3. **矛盾制造张力**：`"seductive yet vulnerable"`, `"playful yet pitiable"`, `"refreshing and indulgent"`
4. **位置优于描述**：`"left upper corner"`, `"bottom center"`, `"right side overlay"` 比抽象的"放在合适的位置"更有效
5. **数值增加真实**：`"HP 8750/12000"`, `"21:37"`, `"83% battery"`, `"23.8万观看"`

### 提示词长度建议

| 类型 | 推荐长度 | 参考案例 |
|------|---------|---------|
| 简单人像 | 50-100词 | Sam Altman Skatepark Snapshot |
| 标准人像 | 150-250词 | Soft Airy 35mm Portrait |
| 超精细人像 | 300+词 | Convenience Store Neon Portrait |
| 海报/插画 | 80-200词 | 广州城市海报系列 |
| UI截图 | 100-200词 | 抖音直播截图 |
| 产品摄影 | 100-250词 | 草莓冰淇淋 |

### 常见问题与解决方案

| 问题 | 原因 | 解决方案 |
|------|------|---------|
| 皮肤太光滑/塑料感 | 缺少质感描写 | 添加 `"subtle skin texture and micro pores"`, 排除 `"no plastic skin"` |
| 人物姿势僵硬 | 姿势描述不够具体 | 逐个描述四肢位置和重心分布 |
| 光线平淡 | 只写了"good lighting" | 指定光源类型、方向、色温 |
| 海报缺少层次 | 只有主体没有背景 | 添加前景/中景/远景的纵深描述 |
| UI截图不真实 | 缺少状态栏等细节 | 添加时间、电量、信号等具体UI元素 |
| 产品材质不对 | 材质描写太笼统 | 使用具体的材质术语（refraction, condensation, brushed metal等） |
| 文字生成错误 | AI对文字的控制有限 | 用引号标出需要生成的文字，或后期手动添加 |

---

> **本教程案例来源：** [awesome-gpt-image-2-prompts](https://github.com/EvoLinkAI/awesome-gpt-image-2-prompts) 项目，案例版权归原作者所有。
>
> **免责声明：** 本教程中的提示词案例仅用于教学目的。部分案例包含成人向描述，实际使用时请根据你的场景和平台规范适当调整。请遵守相关平台的内容政策。

---

*第二部分 · 进阶篇 · 完*

---



# 第九章：高级技巧与创意实验

> "艺术不是你所看到的，而是你让别人看到的。"——埃德加·德加

当你已经掌握了基础提示词和进阶技巧后，真正的创作才刚刚开始。本章将带你进入GPT Image 2的创意深水区——风格混合、IP角色还原、历史场景重现、360度全景图、超现实主义创作。这些不仅是技术操作，更是一种将想象力转化为视觉现实的系统性能力。

## 9.1 风格混合与跨界创作

### 9.1.1 为什么风格混合是高级技巧的核心？

风格混合（Style Blending）是将两种或多种截然不同的视觉语言融合在一张图像中的技术。它之所以是"高级技巧"，是因为它要求你同时理解：

1. **每种风格的本质特征**——不是表面标签，而是真正定义这种风格的视觉DNA
2. **风格之间的兼容性**——哪些元素可以共存，哪些会相互冲突
3. **权重控制**——当两种风格竞争主导权时，如何通过提示词调节比例

### 9.1.2 风格混合的三大策略

**策略一：介质+画风混合**

将传统艺术介质与现代画风结合，是最常见也最有效的混合方式：

```
A Chinese ink wash painting of a cyberpunk cityscape, 
with neon lights bleeding through traditional rice paper texture, 
mountains in the background rendered in Song Dynasty landscape style, 
flying cars leaving brush-stroke trails
```

这个提示词混合了三个维度：中国传统水墨介质、赛博朋克题材、宋代山水画构图。关键在于让每种风格都有"落脚点"——水墨给介质，赛博朋克给内容，宋代山水给构图。

**策略二：时代+风格混合**

将不同历史时期的视觉语言融合：

```
1920s Art Deco poster style advertisement for a modern AI startup, 
geometric gold patterns framing a holographic brain, 
chrome and emerald green color palette, 
hand-lettered vintage typography with futuristic tech buzzwords
```

**策略三：文化跨界混合**

融合东西方视觉传统：

```
Japanese Ukiyo-e woodblock print depicting a European Renaissance cathedral, 
Hokusai-style wave patterns in the foreground, 
gilded halos around Gothic spires, 
perspective flattened in traditional Japanese style, 
indigo and vermillion color scheme
```

### 9.1.3 风格混合的常见陷阱

| 陷阱 | 表现 | 解决方案 |
|------|------|----------|
| 风格冲突 | 画面杂乱，两种风格各自为政 | 明确主次关系，用"dominant style"指定主导风格 |
| 标签堆砌 | 模型无法同时满足太多风格标签 | 每次混合不超过2-3种核心风格 |
| 文化误读 | 融合结果偏离两种文化的真实特征 | 研究每种风格的标志性元素，用具体描述替代笼统标签 |
| 细节丢失 | 风格混合后画面模糊 | 增加细节锚点，如具体的光照、材质描述 |

### 9.1.4 五种经典风格混合组合

经过大量测试，以下五种风格组合在GPT Image 2中表现特别出色：

**1. 中国水墨 + 赛博朋克**：水墨的流动感与霓虹光的锐利形成强烈对比。关键是在提示词中明确哪些元素属于水墨（背景、质感、线条），哪些属于赛博朋克（内容、光照、色彩）。

**2. 浮世绘 + 科幻**：日本浮世绘的扁平构图与科幻的未来感结合，能产生类似《攻壳机动队》海报的效果。

**3. Art Nouveau + 现代科技**：新艺术运动的有机曲线与现代科技的几何感形成有趣的对话，特别适合科技产品的艺术海报。

**4. 维多利亚时代 + 蒸汽朋克**：几乎"天然配对"。维多利亚时代的真实历史细节为蒸汽朋克的幻想提供了扎实基础。

**5. 极简主义 + 巴洛克**：在简洁的构图中放置一个极度华丽的主体（或反之），利用"少vs多"的对比制造视觉张力。

## 9.2 IP角色还原技巧

### 9.2.1 角色还原的核心挑战

GPT Image 2生成IP角色面临三个核心问题：

1. **视觉一致性**——同一角色在不同场景中是否保持相同的外貌特征
2. **神韵还原**——不仅是五官相似，还要传达角色的气质和个性
3. **版权边界**——如何创作"致敬风格"而非直接复制

### 9.2.2 案例：孙悟空角色还原

孙悟空是中国文化中最具辨识度的IP形象之一。让我们拆解一个高质量的孙悟空提示词：

```
A powerful Monkey King (Sun Wukong) character poster, 
traditional Chinese mythology style with modern digital art execution,
golden fur with amber highlights, fierce golden eyes with fiery pupils,
wearing ornate phoenix-feather cap and golden chainmail armor,
Ruyi Jingu Bang (golden staff) resting on shoulder,
standing on a cloud with mountains below,
dynamic pose showing supernatural strength,
rich vermillion and gold color palette,
dramatic backlighting creating a divine silhouette,
Chinese ink wash texture in background elements
```

**提示词拆解分析：**

| 层级 | 内容 | 作用 |
|------|------|------|
| 身份定义 | Monkey King (Sun Wukong) | 双语命名确保模型理解 |
| 风格定位 | traditional Chinese mythology + modern digital art | 新旧融合的视觉方向 |
| 外貌特征 | golden fur, fierce golden eyes, fiery pupils | 三层递进的毛发/眼睛描述 |
| 装备道具 | phoenix-feather cap, golden chainmail, Ruyi Jingu Bang | 精确的装备名称 |
| 构图动作 | standing on cloud, staff on shoulder, dynamic pose | 空间位置和姿态 |
| 色彩方案 | vermillion and gold | 传统中国色 |
| 光影氛围 | dramatic backlighting, divine silhouette | 英雄感的光照设计 |
| 背景质感 | ink wash texture | 文化质感的收尾 |

### 9.2.3 案例：东方不败角色还原

东方不败的难度在于——这个角色同时具有武林高手的凌厉和反传统的妖冶气质：

```
Dongfang Bubai character poster, wuxia martial arts fantasy style,
androgynous figure in flowing crimson silk robes with golden embroidery,
long black hair flowing dramatically in wind,
holding a sewing needle between delicate fingers as weapon,
standing among falling cherry blossoms,
expression combining elegance and menace,
moonlit night scene with bamboo forest silhouette,
Chinese painting aesthetic with cinematic lighting,
red and black dominant color scheme with silver moonlight accents,
vertical composition, dramatic atmosphere
```

**核心技巧**：东方不败的提示词关键是"矛盾气质"的描述——`combining elegance and menace`（优雅与危险并存）、`sewing needle as weapon`（以绣花针为武器）。这些矛盾元素正是角色辨识度的来源。

### 9.2.4 案例：名侦探柯南角色卡

日本动漫角色的还原需要精确到"画风"层面：

```
Detective Conan (Case Closed) official character reference sheet,
Gosho Aoyama art style, anime cel-shading,
Conan Edogawa full body front view,
blue school uniform jacket, red bow tie, white shirt,
oversized round glasses, brown hair with signature cowlick,
white sneakers with blue accents,
Skateboard under one arm, wristwatch-shaped tranquilizer gun visible,
multiple angle views: front, side, 3/4 profile,
clean white background, professional character sheet layout,
dimensions and color codes annotated on side,
official Shogakukan production quality
```

**角色卡提示词的结构要素：**
- **画风声明**：`Gosho Aoyama art style`——直接指定原作者画风
- **角色身份**：双语名称确保准确
- **服装细节**：从外套到鞋子的完整装备清单
- **标志性道具**：领结变声器、滑板、麻醉手表
- **展示格式**：`character reference sheet` + `multiple angle views`
- **行业标准**：`official production quality` 提升完成度

### 9.2.5 IP角色还原的五步法则

1. **研究角色的视觉DNA**：收集至少10张官方参考图，提炼出3-5个不可省略的视觉特征
2. **确定目标画风**：写实？动漫？水墨？明确告诉模型你要什么风格
3. **用具体描述替代名称**：不要只说"柯南"，要描述"戴圆框眼镜、蓝色校服外套、前额翘起一撮呆毛的小男孩"
4. **加入标志性元素**：每个IP角色都有1-2个标志性道具或姿态，这是辨识度的关键
5. **测试并迭代**：先生成3-5张，选出最接近的，在提示词中强化成功的元素

### 9.2.6 更多IP角色还原案例

**哪吒（暗黑奇幻风格）：**
```
Nezha dark fantasy novel cover, reinterpretation of Chinese deity,
young warrior with Third Eye glowing crimson on forehead,
Fire-Tipped Spear in right hand, Universe Ring on left arm,
standing on Wind Fire Wheels leaving trails of flame,
dark storm clouds behind him, lightning framing his silhouette,
dark fantasy oil painting style, Frank Frazetta influence,
rich chiaroscuro lighting, epic heroic composition
```

**吕布（游戏Boss设计稿）：**
```
Lu Bu boss design sheet, Dynasty Warriors game art style,
towering armored warrior in ornate gold and crimson plate armor,
twin feathered headdress, imposing muscular physique,
Sky Piercer halberd planted in ground,
character turnaround views: front, side, back,
stat block and ability annotations in Chinese,
dark background with red accent lighting
```

**韦小宝（鹿鼎记）：**
```
Wai Siu-bo character poster, Royal Tramp style,
cheeky young Chinese man in Qing Dynasty commoner clothes,
mischievous grin, clever eyes,
imperial token hidden in sleeve,
colorful and comedic wuxia illustration style
```

## 9.3 历史场景重现

### 9.3.1 历史场景的提示词挑战

历史场景重现要求AI模型充当"视觉考古学家"——不仅要画出古代的样子，还要符合历史考据。这需要提示词作者具备一定的历史知识，并通过提示词将这些知识传递给模型。

### 9.3.2 案例：唐朝长安灯会全景

```
Tang Dynasty Chang'an Lantern Festival panorama, 
Year 745 AD during Emperor Xuanzong's reign,
wide panoramic view of Zhuque Avenue,
thousands of silk lanterns illuminating the night in warm amber glow,
elaborate dragon lantern floats parading down the central boulevard,
Tang Dynasty citizens in colorful hanfu robes celebrating,
court musicians performing on elevated pavilion stages,
ladies with high Tang-style hair buns and floral hairpins,
foreign merchants from Silk Road in Persian and Sogdian dress,
lantern riddle stations with calligraphy scrolls,
street vendors selling tangyuan and persimmon cakes,
wooden pagoda towers with curved eaves lit from within,
distant view of Daming Palace silhouette against starry sky,
atmospheric perspective with smoke and lantern mist,
rich warm palette: gold, vermillion, jade green, deep indigo sky,
ultra-detailed crowd with individual facial expressions,
Chinese classical painting composition with modern cinematic lighting
```

**历史场景提示词的关键维度：**

| 维度 | 本例中的体现 | 说明 |
|------|-------------|------|
| 时间定位 | Year 745 AD, Emperor Xuanzong | 精确到具体年份和皇帝 |
| 地理定位 | Zhuque Avenue, Daming Palace | 使用真实历史地名 |
| 活动内容 | Lantern Festival, dragon lantern floats | 具体的节日活动 |
| 人物服饰 | Tang-style hair buns, floral hairpins, Persian dress | 考据级别的服饰细节 |
| 食物道具 | tangyuan, persimmon cakes | 真实的唐代小吃 |
| 建筑特征 | curved eaves, wooden pagoda | 唐代建筑标志 |
| 色彩方案 | gold, vermillion, jade green, indigo | 传统中国色系 |

### 9.3.3 历史场景的考证技巧

1. **服饰考据**：不同朝代的服装形制差异巨大。唐代女装以齐胸襦裙为主，宋代转为褙子，明代则是袄裙。在提示词中明确服装形制名称，远比笼统地说"古代服装"效果好。

2. **建筑考据**：唐代的斗拱粗壮、屋檐深远，宋代的建筑更纤细精致，明清则趋于繁复。在提示词中加入建筑风格的朝代特征。

3. **色彩考据**：不同朝代有不同的流行色。唐代偏好浓烈的金银红绿对比，宋代转向素雅的青瓷色调，明清则发展出丰富的刺绣色彩体系。

4. **生活细节**：小到茶具形状（唐代煮茶用鍑，宋代点茶用盏），大到城市规划（唐代长安的里坊制），这些细节是"历史感"的来源。

### 9.3.4 更多历史场景模板

**宋代西湖：**
```
Song Dynasty West Lake scene, Southern Song period (1200s),
scholars in round-collared robes composing poetry on a lakeside pavilion,
willow trees drooping into calm jade-green water,
distant pagoda of Leifeng Tower before its collapse,
tea ceremony on wooden deck with Song Dynasty celadon tea bowls,
fishing boat with cormorant birds on the lake surface,
misty mountains in traditional Chinese atmospheric perspective,
mineral pigment painting colors: malachite green, azurite blue, gofun white
```

**明代紫禁城：**
```
Ming Dynasty Forbidden City scene, Yongle Emperor period (1420s),
newly completed Hall of Supreme Harmony,
imperial ceremony with officials in rank-badge robes,
golden yellow roof tiles under morning sun,
white marble terraces with carved dragon staircases,
red palace walls contrasting with blue sky,
ceremonial bronze incense burners sending smoke spirals upward,
golden hour lighting from the east, long shadows
```

## 9.4 360度全景图提示词

### 9.4.1 什么是等距柱状投影全景图？

360度全景图（Equirectangular Panorama）是一种特殊的图像格式，可以将完整的球面视野展开为一张矩形图像。GPT Image 2具备生成这种全景图的能力，但需要特定的提示词技巧。其核心关键词是 `equirectangular`。

### 9.4.2 全景图提示词模板

```
360-degree equirectangular panorama image,
[场景描述，涵盖完整的360度环境],
seamless horizon with no visible distortion at edges,
[left side] blending smoothly into [front],
[right side] continuing to [behind viewer],
[sky/ceiling] above with natural curvature,
[ground/floor] below,
hdr lighting with natural ambient occlusion,
photorealistic quality, 8K resolution,
equirectangular projection format
```

### 9.4.3 案例：1900年伊斯坦布尔独立大街全景

```
360-degree equirectangular panorama of Istiklal Street, Istanbul, 1900,
Ottoman Empire era, bustling cosmopolitan boulevard,
historic tramway running down the center cobblestone street,
grand European-style buildings with Ottoman details on both sides,
multicultural crowd: Ottoman gentlemen in fezzes, 
European visitors in bowler hats, Armenian merchants, 
horse-drawn carriages alongside early automobile prototypes,
shop signs in Ottoman Turkish, Armenian, Greek, and French,
gas lamp posts casting warm golden light as evening approaches,
Galata Tower visible in the distance,
seamless equirectangular projection, no visible seams
```

### 9.4.4 全景图生成的关键技术要点

1. **必须包含投影格式声明**：`equirectangular panorama` 或 `equirectangular projection` 是让模型理解你要全景图的关键。
2. **四方向描述法**：按照左-前-右-后的顺序描述场景，确保360度覆盖。
3. **无缝接合暗示**：使用 `seamless`、`blending smoothly`、`continuous` 等词汇。
4. **避免焦点构图**：全景图不应有单一视觉焦点，而应均匀分布兴趣点。
5. **天顶和地面**：别忘了描述头顶和脚下的内容。

## 9.5 超现实主义创作

### 9.5.1 超现实主义的提示词本质

超现实主义不是"奇怪的东西"，而是"熟悉的元素的陌生组合"。最有效的超现实主义提示词往往基于真实场景，但引入一个（或几个）逻辑悖论。

### 9.5.2 超现实主义提示词的四种构建模式

**模式一：比例悖论**
```
A tiny human figure standing on the edge of an enormous coffee cup,
the coffee inside is a turbulent ocean with waves and whitecaps,
a giant spoon like a bridge extending across the coffee-sea,
steam rising forming cloud-like formations,
photorealistic macro photography style,
warm amber tones contrasting with cool blue-gray steam
```

**模式二：材质置换**
```
A Victorian library where all the books are made of transparent glass,
light refracting through glass pages creating rainbow patterns on walls,
a reader wearing white cotton gloves carefully turning a glass page,
hyper-realistic rendering with subsurface scattering on glass,
warm library wood tones contrasting with cold glass textures
```

**模式三：时空错置**
```
A Renaissance painting come to life in a modern office cubicle,
figures in 16th century Italian clothing working on laptops,
the cubicle walls decorated with frescoes mimicking the Sistine Chapel,
Mona Lisa printed on a mousepad, her expression unchanged
```

**模式四：逻辑自洽的荒诞世界**
```
A city where gravity works differently for different objects,
buildings anchored to the ground but people walking on vertical walls,
rain falling upward from puddles to the clouds,
birds swimming through the air as if it were water,
everything rendered in hyper-realistic style as if completely normal
```

### 9.5.3 超现实主义创作的关键原则

1. **一个核心悖论**：每张图最好只有一个核心的"不合理"。
2. **写实渲染**：越荒诞的概念，越需要写实的渲染风格来制造"认知冲突"。
3. **细节锚点**：在荒诞场景中加入大量真实细节，让不合理看起来合理。
4. **情绪基调**：确定画面是梦幻的、诡异的、幽默的还是忧郁的。

## 9.6 综合案例拆解

### 9.6.1 西游记连环画

```
A Chinese comic (lianhuanhua) page depicting Journey to the West, 
Sun Wukong's Rebellion in Heaven scene,
traditional Chinese comic panel layout with 6 sequential panels,
Panel 1: Monkey King bursting through clouds on cloud-somer,
Panel 2: Confronting the Heavenly Guards at South Heaven Gate,
Panel 3: Battle with Erlang Shen, staff clashing against three-pointed blade,
Panel 4: Laozi's Diamond Snare descending to capture him,
Panel 5: Monkey King trapped under the Five Elements Mountain,
Panel 6: Buddha's palm inscription sealing the mountain,
traditional Chinese line art style with ink brush strokes,
color palette: vermillion red, indigo blue, ochre yellow, ink black,
rice paper texture background showing through panels,
Chinese calligraphy narration text in vertical columns,
classic 1960s Shanghai Animation Studio aesthetic,
worn edges suggesting a well-read vintage comic book
```

**拆解要点：**
- **分镜描述**：每个panel都有独立的内容描述
- **画风定位**：`1960s Shanghai Animation Studio aesthetic`
- **版式设计**：`panel layout with 6 sequential panels`
- **质感层**：`rice paper texture`、`worn edges`——制造真实的连环画物理感

### 9.6.2 唐朝灯会全景的版本迭代

**v1（初始版）：**
```
Tang Dynasty lantern festival, Chang'an city, lots of lanterns, 
people celebrating, night scene, Chinese style
```
问题：太笼统，没有历史定位、具体地点、服饰细节。

**v2（添加细节）：**
```
Tang Dynasty Chang'an Lantern Festival, Emperor Xuanzong period,
Zhuque Avenue with thousands of silk lanterns,
people in hanfu robes celebrating at night,
dragon lantern parade, court musicians, street food vendors
```
改进：增加了历史定位和主要活动。

**v3（添加氛围和色彩）：** 加入色彩方案、服饰细节、食物道具、远景建筑。

**v4（最终版）：** 增加了 `ultra-detailed crowd with individual facial expressions`、`Chinese classical painting composition with modern cinematic lighting`，完成从历史插画到大师级作品的跨越。

### 9.6.3 名侦探柯南角色卡

关键设计决策：
1. `Gosho Aoyama manga art style` 比 `anime style` 更精确
2. 列出颜色十六进制代码确保颜色精确
3. `height annotation: 105cm` 暗示这是正式设计文档格式
4. `Japanese text labels` 强化日本动漫角色卡风格

---

# 第十章：提示词工程学——系统化方法论

## 10.1 提示词的"语法结构"分析

### 10.1.1 C.L.E.A.R. 框架

| 字母 | 含义 | 对应中文 | 示例 |
|------|------|---------|------|
| **C** | Content（内容） | 画面主体 | A young woman in traditional hanfu |
| **L** | Layout（布局） | 构图方式 | centered composition, rule of thirds |
| **E** | Environment（环境） | 场景背景 | cherry blossom garden in spring |
| **A** | Atmosphere（氛围） | 光影色调 | soft golden hour lighting, warm tones |
| **R** | Rendering（渲染） | 画风质量 | photorealistic, 8K, shallow depth of field |

**完整应用：**

```
[C] A young woman in flowing white hanfu with gold embroidery,
[L] full-body shot, standing at 3/4 angle, slightly turned toward camera,
[E] traditional Chinese garden with moon gate, koi pond reflecting cherry blossoms,
[A] soft golden hour backlighting, petals floating in gentle breeze, dreamy atmosphere,
[R] photorealistic, 85mm portrait lens, f/1.4 bokeh, film grain texture, cinematic grading
```

### 10.1.2 提示词的六层架构

**第一层：核心主体（必须）**——定义"画什么"，唯一不可省略的层。
```
A golden retriever puppy
```

**第二层：动作/姿态（强烈推荐）**——赋予主体动态感。
```
jumping to catch a frisbee mid-air
```

**第三层：场景/环境（推荐）**——提供空间背景。
```
in a sunlit meadow
```

**第四层：光照/氛围（进阶）**——控制画面情绪。
```
golden hour sunlight, warm amber glow, long shadows
```

**第五层：风格/画风（进阶）**——确定视觉语言。
```
Canon EOS R5, 200mm telephoto, fast shutter speed, bokeh
```

**第六层：技术参数（可选但有效）**——提升完成度。
```
8K resolution, photorealistic, professional pet photography
```

### 10.1.3 语序的影响

GPT Image 2对提示词语序敏感。**越靠前的描述权重越高**。

比较两个版本：

**版本A（强调场景）：**
```
A misty bamboo forest at dawn, a lone swordsman in white standing among bamboo stalks, 
Chinese ink painting style
```

**版本B（强调人物）：**
```
A lone swordsman in white robes with flowing sleeves, standing in a misty bamboo forest at dawn, 
Chinese ink painting style
```

版本A更可能生成环境主导的画面，人物较小；版本B更可能生成人物主体的特写构图。

### 10.1.4 逗号分隔与自然句式的对比

GPT Image 2对两种提示词格式都有良好的理解：

**逗号分隔式（关键词堆叠）：**
```
young woman, red dress, standing in rain, neon lights, cyberpunk city, night, 
reflection on wet ground, cinematic lighting, 85mm lens, bokeh
```

**自然句式（描述性语句）：**
```
A young woman in a flowing red dress stands in the pouring rain in the middle of a 
cyberpunk city at night, neon lights reflecting off the wet ground around her, 
shot with cinematic lighting on an 85mm lens with beautiful bokeh
```

**实践建议：** 对于精确控制（产品摄影、UI设计等），用逗号分隔式更有效；对于创意表达（艺术插画、氛围营造等），自然句式能让模型发挥更多"理解力"。混合使用往往是最佳选择——用自然句描述主体和场景，用逗号分隔列出技术参数。

## 10.2 长提示词 vs 短提示词的效果对比

### 10.2.1 何时用长提示词？

长提示词（100词以上）适合：
- **精确控制型任务**：产品摄影、UI设计、角色卡、信息图表
- **多层细节任务**：历史场景、复杂构图、多人物场景
- **风格融合任务**：需要同时描述多种风格元素
- **商业级输出**：需要高完成度、高准确度的图像

**长提示词示例（150+词）：**
```
Ultra-realistic product photography of a rich strawberry soft-serve ice cream cone, 
the cone is an artisanal waffle cone with visible grid pattern and golden-brown color, 
the ice cream swirls perfectly in three rotations, vibrant pink-red strawberry color 
with visible real strawberry seed specs throughout, a single fresh strawberry 
placed on top of the swirl, a thin drizzle of strawberry coulis running down the side, 
condensation droplets on the ice cream surface showing it's freshly made, 
shot on white marble countertop with subtle shadows, soft directional lighting from upper left, 
f/2.8 shallow depth of field, food magazine editorial quality, 
Phase One IQ4 150MP camera rendering, natural food colors only
```

### 10.2.2 何时用短提示词？

短提示词（20词以内）适合：
- **探索型任务**：快速测试概念、寻找灵感方向
- **风格化/艺术化任务**：过度描述反而可能限制模型的创造力
- **简单主体**：单一物体、简单背景的场景
- **利用模型"默认审美"**：有时模型的直觉比你更好

**短提示词示例（8词）：**
```
A lonely astronaut sitting on Mars, watching Earth rise, watercolor
```

### 10.2.3 长短对比的实践结论

经过反复测试，我总结出以下经验法则：

| 任务类型 | 推荐长度 | 原因 |
|----------|---------|------|
| 产品摄影 | 100-200词 | 每个细节都影响购买决策 |
| 人像摄影 | 50-100词 | 需要精确的光照和设备描述 |
| 艺术插画 | 30-60词 | 给模型留出创作空间 |
| 概念探索 | 5-20词 | 快速迭代，不纠结细节 |
| UI/信息图 | 150-300词 | 需要精确的布局和内容描述 |
| 海报设计 | 80-150词 | 需要兼顾内容、排版和风格 |

## 10.3 中英文混写的优势

### 10.3.1 为什么要中英文混写？

GPT Image 2是一个以英文为主要训练语言的模型。虽然它对中文也有不错的理解力，但在许多专业术语、画风描述、设备参数上，英文表达更精确、更不容易产生歧义。同时，某些中国文化特有的概念在中文中表达更准确。中英文混写可以同时获得两种语言的优势。

### 10.3.2 混写的三种策略

**策略一：英文结构+中文文化锚点**

```
A traditional Chinese landscape painting (山水画),
misty mountains rendered in 三远法 (three-distance perspective method),
pine trees in 马远 style "one-corner" composition,
a small fishing boat on a calm lake,
陌上的牧童 riding a water buffalo in the foreground,
mineral pigment colors: 石青 (azurite blue), 石绿 (malachite green), 赭石 (ochre),
ink wash (水墨) texture with visible brush strokes on silk (绢本)
```

这种策略用英文搭建整体结构，用中文标注具体的文化概念。括号中的英文/中文对照既帮助模型理解，也为人类读者提供了学习价值。

**策略二：中文概念+英文渲染描述**

```
唐代仕女图 (Tang Dynasty court lady painting),
full-length portrait of a 丰腴 (plump and elegant) court lady,
wearing 齐胸襦裙 (chest-high ruqun dress) in layers of silk,
高髻 (high bun) hairstyle decorated with gold hairpins and peony flowers,
holding a 团扇 (round fan) with painted landscape,
standing in a palace garden with 牡丹 (peony) in full bloom,
shot in soft diffused lighting, shallow depth of field,
Chinese classical painting medium: ink and color on silk,
Tang Dynasty aesthetic: confident, cosmopolitan, voluptuous beauty
```

**策略三：纯英文+拼音注音**

对于面向国际受众的内容，使用纯英文加拼音：

```
A wuxia swordsman standing on a jianghu (martial arts world) cliff edge,
robes flowing in mountain wind (shan feng),
bamboo sword (zhu jian) at his waist,
cloud sea (yun hai) below the cliff at sunrise,
Chinese ink painting (shui mo hua) style with modern digital coloring
```

### 10.3.3 混写的注意事项

1. **不要中英交替翻译**：`一个 beautiful 的 girl` 这种混法反而增加歧义。应该在句子级别切换语言，而不是词级别。
2. **专有名词用双语**：`朱雀大街 (Zhuque Avenue)` 这种格式最好。
3. **英文描述技术参数**：镜头、光照、渲染等技术词汇用英文更精确。
4. **中文描述文化概念**：服饰、建筑、食物等文化特有概念用中文+英文对照。

## 10.4 提示词迭代优化流程

### 10.4.1 从v1到v5的进化案例

让我们用一个实际案例演示完整的迭代流程。目标：生成一张"咖啡店窗边的猫"。

**v1——概念版（15词）**
```
A cat sitting by a coffee shop window, warm lighting, cozy atmosphere
```
结果评估：画面基本正确，但猫的姿态模糊，咖啡店细节不足，氛围偏普通。

**v2——添加主体细节（30词）**
```
An orange tabby cat curled up on a wooden windowsill inside a cozy coffee shop,
afternoon sunlight streaming through the window creating warm patches on its fur,
the cat has its eyes half-closed in contentment
```
结果评估：猫的细节改善，但环境仍不够丰富。

**v3——添加环境细节（50词）**
```
An orange tabby cat curled up sleeping on a worn wooden windowsill inside a Parisian coffee shop,
late afternoon golden sunlight streaming through steamed glass creating warm amber patches on its fur,
behind the cat: shelves of vintage coffee tins, a chalkboard menu with handwritten specials,
in front: a small round marble table with an espresso cup and an open book,
visible outside the window: a cobblestone street with autumn leaves
```
结果评估：场景丰富了很多，但画面构图不够精确。

**v4——添加构图和技术参数（80词）**
```
An orange tabby cat curled up sleeping on a worn wooden windowsill inside a vintage Parisian coffee shop,
late afternoon golden sunlight streaming through steamed glass creating warm amber patches on its fur,
behind the cat: wrought-iron shelves holding vintage coffee tins and glass jars of beans,
a chalkboard menu with handwritten French specials in cursive script,
in front on the right: a small round marble-topped table with a half-finished espresso and an open paperback,
through the window: cobblestone street with golden autumn leaves falling,
shallow depth of field focused on the cat, f/2.0,
warm film-like color grading with lifted shadows,
shot on Leica M11 with 50mm Summilux, Kodak Portra 400 film simulation
```
结果评估：构图精准，氛围到位，完成度很高。

**v5——微调版（90词）**
```
An orange tabby cat curled up sleeping peacefully on a worn wooden windowsill inside a vintage Parisian coffee shop,
late afternoon golden sunlight streaming through condensation-dotted glass creating warm amber patches on its striped fur,
the cat's tail wrapped around its body, one ear slightly twitching in sleep,
behind the cat: wrought-iron shelves holding vintage coffee tins and glass jars of roasted beans,
a chalkboard menu with handwritten French specials in white chalk,
in front on the right: a small round marble-topped table with a half-finished espresso in a white ceramic cup and an open paperback with yellowed pages,
through the window: a cobblestone street with golden autumn leaves drifting down,
shallow depth of field focused on the cat at f/2.0,
warm analog film color grading with lifted shadows and subtle green-magenta split toning,
shot on Leica M11 with 50mm Summilux, Kodak Portra 400 film simulation,
nostalgic, intimate, slow-living mood
```

**迭代流程总结：**

| 版本 | 字数 | 增加了什么 | 解决了什么问题 |
|------|------|-----------|--------------|
| v1 | 15 | 基础概念 | 从零开始 |
| v2 | 30 | 主体细节 | 猫的形态模糊 |
| v3 | 50 | 环境细节 | 场景不够丰富 |
| v4 | 80 | 构图+技术参数 | 画面不够精确 |
| v5 | 90 | 微小动态+情绪词 | 缺乏"灵魂" |

### 10.4.2 迭代优化的五个检查点

每次迭代后，对照以下检查点：

1. **主体是否准确？** 物种/人物/物体是否正确，姿态是否符合预期
2. **环境是否丰富？** 背景是否有足够的细节支撑氛围
3. **构图是否精确？** 物体之间的空间关系是否合理
4. **氛围是否到位？** 光照、色调、情绪是否传达了你的意图
5. **技术质量是否达标？** 分辨率、清晰度、渲染风格是否满意

## 10.5 建立自己的提示词库

### 10.5.1 为什么需要提示词库？

提示词库（Prompt Library）是你个人的"视觉配方集"。它的价值在于：

1. **复用效率**：成功的提示词可以作为模板快速修改
2. **知识积累**：记录什么有效、什么无效，避免重复踩坑
3. **风格一致性**：系列作品需要统一的视觉语言
4. **团队协作**：提示词库可以共享给团队成员

### 10.5.2 提示词库的组织方式

推荐使用文件夹结构组织提示词库：

```
prompt-library/
├── 01-portraits/
│   ├── studio-headshot.md
│   ├── outdoor-candid.md
│   └── editorial-fashion.md
├── 02-product/
│   ├── food-photography.md
│   ├── cosmetics.md
│   └── tech-products.md
├── 03-poster/
│   ├── movie-poster.md
│   ├── event-poster.md
│   └── travel-poster.md
├── 04-ui/
│   ├── landing-page.md
│   ├── app-mockup.md
│   └── social-media.md
├── 05-creative/
│   ├── surrealism.md
│   ├── style-blend.md
│   └── historical.md
└── 06-templates/
    ├── CLEAR-framework.md
    ├── panorama-template.md
    └── character-sheet-template.md
```

### 10.5.3 每个提示词条目的记录格式

```markdown
## 提示词名称：咖啡店窗边的猫

### 提示词
[完整的提示词文本]

### 参数
- 尺寸：16:9 / 1:1 / 9:16
- 风格：写实摄影
- 用途：社交媒体配图

### 效果评估
- 评分：9/10
- 优点：氛围温暖，猫的细节好
- 不足：窗外细节略少

### 迭代记录
- v1：[提示词] → [评价]
- v2：[提示词] → [评价]
- v5（最终版）：[提示词]

### 标签
#猫 #咖啡店 #温暖 #摄影 #巴黎 #胶片
```

## 10.6 用JSON结构化提示词

### 10.6.1 为什么要用JSON？

JSON格式的提示词有以下优势：

1. **结构化**：每个元素都有明确的字段名，不会混淆
2. **可编程**：可以用于自动化工作流、批量生成
3. **可对比**：不同提示词之间的差异一目了然
4. **可版本控制**：配合Git等工具追踪提示词的变更历史

### 10.6.2 JSON提示词模板

```json
{
  "prompt_version": "2.0",
  "id": "portrait-017",
  "category": "portrait",
  "tags": ["outdoor", "golden-hour", "hanfu", "female"],
  
  "subject": {
    "type": "person",
    "gender": "female",
    "age": "mid-20s",
    "clothing": "flowing white hanfu with gold embroidery",
    "pose": "standing at 3/4 angle, slightly turned toward camera",
    "expression": "serene, gentle smile"
  },
  
  "environment": {
    "location": "traditional Chinese garden",
    "elements": ["moon gate", "koi pond", "cherry blossoms"],
    "season": "spring",
    "time_of_day": "golden hour"
  },
  
  "atmosphere": {
    "lighting": "soft golden hour backlighting",
    "mood": "dreamy, ethereal",
    "weather": "clear with gentle breeze",
    "special_effects": "petals floating in air"
  },
  
  "rendering": {
    "style": "photorealistic",
    "camera": "Leica M11",
    "lens": "85mm f/1.4",
    "film_simulation": "Kodak Portra 400",
    "composition": "full-body shot, centered",
    "depth_of_field": "shallow, f/1.4 bokeh",
    "color_grading": "warm, lifted shadows"
  },
  
  "output": {
    "aspect_ratio": "3:4",
    "quality_tags": ["8K", "ultra-detailed", "magazine quality"]
  },
  
  "full_prompt": "A young woman in flowing white hanfu with gold embroidery, standing at 3/4 angle in a traditional Chinese garden with moon gate and koi pond reflecting cherry blossoms, soft golden hour backlighting, petals floating in gentle breeze, dreamy atmosphere, photorealistic, 85mm f/1.4 bokeh, Kodak Portra 400 film simulation, 8K, ultra-detailed"
}
```

### 10.6.3 JSON提示词的进阶用法

**批量生成：** 可以编写脚本遍历JSON中的变量，批量生成变体。比如修改 `subject.clothing` 为不同颜色的hanfu，批量生成一组配图。

**A/B测试：** 保持JSON中大部分字段不变，只修改一个字段（如光照条件），生成对比图。

**工作流集成：** JSON格式的提示词可以无缝集成到自动化工作流中，比如：
- 从Notion数据库读取提示词 → 生成图像 → 自动发布到社交媒体
- 从电子表格读取产品参数 → 填充到模板JSON → 批量生成产品图

### 10.6.4 实际案例：用JSON生成产品图系列

```json
{
  "template": "product-photography",
  "base_prompt": {
    "product": "artisanal candle",
    "surface": "white marble countertop",
    "lighting": "soft directional from upper left",
    "camera": "Phase One IQ4, 120mm macro, f/4",
    "style": "luxury editorial product photography"
  },
  "variants": [
    {"scent": "lavender", "color": "soft purple", "props": "dried lavender sprigs"},
    {"scent": "vanilla", "color": "warm cream", "props": "vanilla beans and cinnamon sticks"},
    {"scent": "cedar", "color": "deep forest green", "props": "cedar chips and pine cones"}
  ]
}
```

通过遍历 `variants` 数组，可以为同款产品的不同香型自动生成风格统一的系列图。

---

## 本章小结

提示词工程学的核心是**系统化思维**。从C.L.E.A.R.框架到六层架构，从迭代优化流程到JSON结构化管理，这些方法论将提示词写作从"凭感觉"提升为"可复制、可优化、可规模化"的工程实践。

关键要点：
- **结构先行**：用框架组织思路，而不是自由散漫地写
- **迭代驱动**：没有一次写对的提示词，只有越改越好的版本
- **知识管理**：建立提示词库，让每次经验都成为可复用的资产
- **结构化存储**：用JSON管理提示词，为自动化工作流打下基础

---

# 第十一章：行业应用与变现路径

> "技术只有在被使用时才有价值。"

GPT Image 2不仅是一个创意工具，更是一个商业工具。本章将探讨如何将提示词技能转化为实际价值——无论是提升工作效率，还是创造直接收入。

## 11.1 自媒体配图

### 11.1.1 自媒体配图的需求特征

自媒体对配图的需求可以用三个词概括：**快速、量大、独特**。

- **快速**：热点转瞬即逝，配图需要在几分钟内完成
- **量大**：日更账号每天需要3-5张配图
- **独特**：版权风险让直接使用网络图片越来越不可行

GPT Image 2完美匹配这三个需求：生成速度快（30秒以内）、成本极低（每次几分钱）、完全原创无版权风险。

### 11.1.2 自媒体配图的提示词策略

**策略一：建立品牌视觉风格**

为你的自媒体账号建立一套固定的视觉风格，然后在每张配图中保持一致：

```
[你的品牌风格模板],
[具体内容描述],
[固定的色彩方案和排版元素]
```

例如，一个科技自媒体的配图模板：

```
Minimalist tech illustration style, isometric 3D view,
soft gradient background in brand colors (#1a1a2e, #16213e, #0f3460),
[具体科技主题：例如 a holographic brain floating above a circuit board],
geometric shapes as decorative elements,
clean sans-serif typography area reserved at bottom,
consistent with previous posts in this series
```

**策略二：系列化内容模板**

如果你运营"历史上的今天"类内容，可以建立一个时间-场景映射表：

```
Historical event illustration: [具体事件],
[时代风格] art style, [色调] color palette,
informative infographic layout with event date and key facts,
vertical format optimized for mobile viewing
```

### 11.1.3 不同平台的配图尺寸

| 平台 | 推荐比例 | 说明 |
|------|---------|------|
| 微信公众号 | 16:9 或 2.35:1 | 头图需要宽幅 |
| 小红书 | 3:4 或 1:1 | 竖图点击率更高 |
| 抖音/快手 | 9:16 | 全竖屏 |
| 微博 | 16:9 | 横图为主 |
| B站封面 | 16:9 | 注意标题文字区域 |

## 11.2 电商产品图

### 11.2.1 电商产品图的提示词模板

电商产品图的核心是：**让商品看起来值得购买**。这需要在材质质感、光照效果、环境氛围上下功夫。

**基础产品图模板：**
```
Professional product photography of [产品名称],
[产品材质和颜色描述],
placed on [展示台面/背景],
[key selling point visible: 例如 "condensation droplets showing freshness"],
soft directional studio lighting from upper left,
subtle shadow beneath product for grounding,
[f/2.8 浅景深] or [f/8 全清晰] depending on product type,
white balance calibrated for accurate product colors,
ecommerce standard: clean, professional, no distracting elements
```

**护肤品产品图案例：**
```
Luxury skincare serum bottle photography,
frosted glass bottle with golden dropper cap,
amber-toned serum visible through semi-transparent glass,
bottle placed on a white marble surface with soft reflection,
surrounded by fresh lavender sprigs and a single amethyst crystal,
morning sunlight filtering through sheer curtain creating soft dappled light,
water droplets on the bottle surface suggesting cooling freshness,
f/4 depth of field keeping product sharp, background softly blurred,
beauty editorial quality, Vogue magazine standard
```

### 11.2.2 电商场景图的提示词技巧

场景图（Lifestyle Shot）比白底图更能激发购买欲望。关键技巧：

1. **使用场景**：将产品放在真实使用环境中（咖啡放在书桌上、护肤品放在浴室架子上）
2. **人物互动**：加入手部或局部人体，展示使用方式
3. **季节氛围**：配合当季的视觉元素（夏天的冰块、冬天的毛毯）
4. **色彩心理学**：用色彩暗示产品的核心卖点（绿色=天然、金色=奢华、蓝色=清洁）

## 11.3 社交媒体内容创作

### 11.3.1 社交媒体内容类型

GPT Image 2在社交媒体内容创作中有以下典型应用：

**信息图（Infographic）：**
```
Infographic about [主题], 
vertical layout optimized for mobile (9:16),
clean data visualization with icons and charts,
color palette: [品牌色],
modern flat design style,
title at top in bold sans-serif font,
key statistics highlighted in larger numbers,
source attribution at bottom
```

**社交媒体截图（模拟）：**
```
Screenshot of a [平台名] feed showing [内容],
realistic phone mockup with notch and status bar,
[具体的帖子内容和互动数据],
natural-looking UI elements,
as if taken by a real user scrolling their phone
```

**节日/热点内容：**
```
[节日名称] celebration illustration,
[节日视觉元素：如春节的红色灯笼、圣诞的雪花],
warm and festive atmosphere,
social media optimized format (1:1 or 9:16),
space for text overlay at top/bottom
```

## 11.4 设计师工作流整合

### 11.4.1 GPT Image 2在设计工作流中的定位

GPT Image 2不应被视为设计工具的替代品，而是设计工作流的"加速器"。它在设计流程中的最佳定位是：

1. **概念探索阶段**：快速生成多个视觉方向，帮助客户/团队选择方向
2. **素材生成阶段**：生成背景、纹理、装饰元素等基础素材
3. **效果预览阶段**：在投入大量制作时间前，预览最终效果的"低保真"版本
4. **灵感收集阶段**：快速可视化抽象概念，辅助创意讨论

### 11.4.2 设计师使用GPT Image 2的SOP

**Step 1：需求分析**
- 确定设计目标和约束条件
- 明确目标受众和使用场景
- 收集参考图和风格方向

**Step 2：概念生成**
- 使用GPT Image 2生成5-10个不同方向的视觉概念
- 每个概念用不同的提示词策略（不同风格、不同构图、不同色调）
- 不追求完美，追求多样性

**Step 3：方向筛选**
- 与客户/团队讨论，选出1-2个方向
- 分析被选中概念的成功元素
- 将这些元素转化为提示词中的"固定参数"

**Step 4：精细迭代**
- 在选定方向上进行3-5轮迭代优化
- 使用第十章的迭代方法论
- 逐步逼近最终效果

**Step 5：输出与后期**
- 生成高分辨率最终图
- 在Photoshop/Figma中进行必要的后期调整
- 叠加文字、Logo等品牌元素

## 11.5 提示词服务/课程售卖

### 11.5.1 提示词服务的商业模式

如果你已经积累了丰富的提示词经验和大量高质量模板，可以考虑以下变现路径：

**模式一：提示词模板包**

将提示词按主题打包出售：
- "电商产品摄影提示词包"（50个模板，¥99）
- "自媒体爆款配图提示词包"（100个模板，¥149）
- "设计师灵感提示词包"（200个模板，¥299）

**模式二：定制提示词服务**

为客户提供1对1的提示词定制服务：
- 品牌视觉风格定制（¥500-2000）
- 系列产品图提示词设计（¥300-800/套）
- 社交媒体月度配图提示词（¥1000-3000/月）

**模式三：在线课程**

开设GPT Image 2提示词教程课程：
- 入门课："零基础学会AI绘画提示词"（¥99-199）
- 进阶课："商业级提示词实战"（¥299-499）
- 大师课："提示词工程学完整体系"（¥499-999）

**模式四：会员订阅**

建立付费会员社区：
- 每周更新10-20个新提示词模板
- 会员专属提示词库访问权
- 定期直播答疑和案例拆解
- 定价：¥49-99/月

### 11.5.2 构建提示词服务的注意事项

1. **持续更新**：AI模型在迭代，提示词的有效性也在变化。定期测试并更新模板。
2. **明确免责**：告知客户AI生成的图像可能存在细节错误，不保证100%准确。
3. **版权意识**：避免直接模仿受版权保护的IP，提供"风格致敬"而非"精确复制"的服务。
4. **案例积累**：持续积累before/after对比案例，这是最有说服力的营销素材。

---

# 附录A：100个经典提示词模板速查

## A.1 人像摄影（1-15）

1. **证件照**：`Professional ID headshot photo, [人物描述], solid [颜色] background, even studio lighting, straight-on angle, neutral expression, shoulders visible, official document photo quality`
2. **街拍人像**：`Candid street photography of [人物], walking down [街道], shot from across the street with shallow DOF, natural unposed moment, 35mm film aesthetic`
3. **韩系写真**：`Korean idol style portrait, [人物描述], soft CC style lighting, dreamy pastel color palette, slight blur effect, K-pop aesthetic, 1:1 square crop`

4. **日系写真**：`Japanese magazine style portrait, [人物描述], natural daylight, clean minimal composition, Fujifilm color science, warm skin tones, slight film grain, magazine editorial quality`

5. **古风人像**：`Chinese classical style portrait, [人物描述], wearing [朝代/服饰], in traditional Chinese garden with [场景], soft diffused lighting, cultural heritage photography, warm amber tones`

6. **赛博朋克人像**：`Cyberpunk portrait, [人物描述], neon city background, red and blue rim lighting, holographic elements, futuristic fashion, night scene, high contrast, Blade Runner aesthetic`

7. **文艺复兴肖像**：`Renaissance oil painting portrait, [人物描述], chiaroscuro lighting, rich dark background, ornate clothing, dramatic shadow, Vermeer or Rembrandt style, museum quality`

8. **波普艺术肖像**：`Pop art style portrait of [人物描述], Andy Warhol inspired, vibrant flat colors, halftone dot texture, bold outlines, multiple color variations, comic book aesthetic`

9. **水彩人像**：`Watercolor portrait painting, [人物描述], soft flowing brushstrokes, bleeding color edges, paper texture showing through, pastel color palette, artistic hand-painted look`

10. **电影感人像**：`Cinematic portrait, [人物描述], dramatic moody lighting, film noir aesthetic, deep shadows, smoke or fog atmosphere, anamorphic lens look, color graded like a movie still`

11. **高时尚人像**：`High fashion editorial portrait, [人物描述], avant-garde clothing, stark studio lighting, sharp focus, minimal composition, Vogue magazine style, bold confident expression`

12. **怀旧胶片人像**：`Vintage film style portrait, [人物描述], Kodak Portra 400 simulation, warm film grain, slightly desaturated, 1970s aesthetic, nostalgic mood`

13. **北欧清新人像**：`Scandinavian minimalist portrait, [人物描述], neutral color palette (white, beige, light gray), natural soft light, clean background, Hygge aesthetic, cozy and calm`

14. **梵高风格人像**：`Van Gogh style portrait painting, [人物描述], thick impasto brushstrokes, swirling sky background, vibrant yellow and blue, post-impressionist technique, artistic masterpiece`

15. **宝丽来拍立得**：`Polaroid instant photo portrait, [人物描述], classic white border, warm vintage color shift, slight light leak, casual candid moment, nostalgic 1970s feel`

## A.2 产品摄影（16-30）

16. **咖啡摄影**：`Professional coffee photography, a latte with foam art in a white ceramic cup, steam rising, placed on rustic wooden table with coffee beans, warm morning light, food magazine quality`

17. **护肤品摄影**：`Luxury skincare product photography, [产品名称] bottle on white marble surface, soft studio lighting, water droplets suggesting freshness, golden accent, beauty editorial aesthetic`

18. **数码产品**：`High-tech product photography, [产品名称] sleek modern design, dark minimalist background, dramatic edge lighting, reflection on glossy surface, tech brand promotional quality`

19. **香水摄影**：`Perfume bottle photography, [香水名称], transparent glass with colored liquid inside, golden cap, placed on silk fabric, soft ethereal lighting, luxury brand aesthetic`

20. **珠宝摄影**：`Fine jewelry photography, [珠宝名称] on black velvet background, macro close-up showing details, rim lighting highlighting facets, elegant shadows, luxury catalogue quality`

21. **美食摄影**：`Restaurant food photography, [菜品名称], appetizing presentation, garnished with [配菜], on ceramic plate, warm restaurant lighting, steam rising, mouth-watering detail`

22. **手机摄影**：`Smartphone product shot, [手机型号] floating in mid-air, angled to show front and back, studio lighting with soft shadows, clean white background, Apple-style product photography`

23. **化妆品摄影**：`Makeup product photography, [产品名称] with open cap showing color/texture, beauty products arranged artistically, pastel background, Instagram-ready aesthetic`

24. **酒类摄影**：`Wine or spirits bottle photography, [酒类名称], condensation droplets on glass, golden light passing through liquid, dark moody background, premium brand positioning`

25. **文具摄影**：`Stationery product shot, [文具名称] on wooden desk, pens and notebooks arranged neatly, natural daylight from window, productivity blogger aesthetic, clean and organized`

26. **手表摄影**：`Luxury watch photography, [手表型号], macro shot showing dial and hands, metal band details, dramatic lighting with reflections, premium lifestyle image`

27. **服装平铺**：`Flat lay fashion photography, [服装描述] spread on textured surface, styled with accessories (sunglasses, jewelry), flat lighting, consistent with brand lookbook`

28. **运动装备**：`Sports equipment photography, [装备名称], action-oriented composition, dynamic lighting suggesting motion, on performance surface (track, court, field), athletic brand aesthetic`

29. **家居用品**：`Home decor product photography, [产品名称] in styled interior setting, natural warm light, lifestyle context, Instagram home aesthetic, cozy and inviting`

30. **书本封面**：`Book cover mockup, [书名] on hardcover book with embossed title effect, placed on wooden table with coffee and reading glasses, warm ambient light, author promotional image`

## A.3 海报设计（31-50）

31. **电影海报**：`Epic movie poster, [电影主题] as central hero figure, explosive action composition, dramatic lighting, bold title typography at bottom, summer blockbuster aesthetic, 2:3 vertical format`

32. **音乐会海报**：`Music concert poster, [音乐风格/艺人], psychedelic or minimalist design, bold typography, vibrant colors, ticket information space, gig poster aesthetic, square or vertical format`

33. **旅游海报**：`Travel destination poster, [地点名称] illustrated in [年代] vintage travel poster style, romanticized landscape, elegant serif typography, warm nostalgic color palette, tourism promotional quality`

34. **科技会议海报**：`Tech conference event poster, [会议主题], futuristic geometric design, dark background with neon accents, modern sans-serif typography, professional conference aesthetic, vertical format`

35. **艺术展览海报**：`Art exhibition poster, [展览主题] as central visual element, gallery exhibition aesthetic, elegant minimal design, museum quality typography, sophisticated color scheme`

36. **节日促销海报**：`[节日名称] sale poster, [促销商品] with festive decorations, bold red/gold color scheme, large percentage discount text, urgency-inducing design, retail promotional quality`

37. **美食节海报**：`Food festival poster, [美食主题] as central illustration, mouth-watering food art, warm appetizing colors, event details clearly displayed, restaurant promotion aesthetic`

38. **运动赛事海报**：`Sports event poster, [运动项目] dynamic action capture, energetic composition, team colors, bold typography for event name, Olympic or professional sports aesthetic`

39. **读书活动海报**：`Book reading event poster, [书籍主题] with reading imagery, library or bookshelf background, literary aesthetic, elegant serif fonts, cultural event quality`

40. **音乐节海报**：`Music festival poster, [音乐风格] collage illustration, multiple bands/artists represented, vibrant psychedelic design, festival date and location, Coachella or Lollapalooza inspired`

41. **教育课程海报**：`Online course promotional poster, [课程主题] visualized, professional and trustworthy design, clear value proposition, call-to-action prominent, ed-tech brand aesthetic`

42. **环保主题海报**：`Environmental awareness poster, [环保主题] as central message, nature-inspired design, green color palette, impactful visual metaphor, NGO campaign quality`

43. **产品发布会海报**：`Product launch event poster, [产品名称] hero shot, minimal sleek design, dramatic lighting, event time and date, Apple-style event announcement aesthetic`

44. **健身挑战海报**：`Fitness challenge poster, [运动类型] action figure, motivational message, energetic composition, bold typography, fitness brand promotional quality`

45. **毕业典礼海报**：`Graduation ceremony poster, [学校/机构], academic cap and gown imagery, formal elegant design, class year prominent, institutional ceremonial aesthetic`

46. **婚庆活动海报**：`Wedding event poster, romantic floral design, elegant typography, date and venue details, dreamy pastel color palette, wedding industry promotional quality`

47. **美食活动海报**：`Food and wine tasting event poster, gourmet food imagery, sophisticated design, dark elegant background, luxury dining aesthetic`

48. **艺术工作坊海报**：`Art workshop poster, [艺术形式] creative visualization, artistic hand-drawn style, workshop details clearly shown, community education aesthetic`

49. **城市宣传海报**：`City tourism poster, [城市名称] iconic skyline or landmark, vibrant modern design, welcoming message, urban lifestyle aesthetic`

50. **新年贺岁海报**：`[年份] New Year celebration poster, traditional [文化] New Year elements (如red lanterns for China, fireworks for Western), festive red and gold, celebration atmosphere`

## A.4 环境/场景（51-65）

51. **森林晨光**：`Enchanted forest at sunrise, rays of golden sunlight piercing through canopy, morning mist, dewdrops on leaves, fairy-tale atmosphere, 4K landscape photography`

52. **城市天际线**：`Modern city skyline at twilight, skyscrapers with lights just turning on, reflection on water surface, dramatic clouds, urban photography, wide angle`

53. **沙漠落日**：`Sahara desert at sunset, golden sand dunes, dramatic long shadows, lone camel caravan in distance, warm orange and purple sky, National Geographic style landscape`

54. **海底世界**：`Underwater coral reef scene, colorful tropical fish swimming, sunlight filtering through water, marine life photography, vibrant blue and coral colors, 8K underwater shot`

55. **极地风光**：`Aurora borealis over snowy Arctic landscape, northern lights dancing in green and purple, starry night sky, frozen lake reflection, winter wonderland atmosphere`

56. **稻田风光**：`Asian rice terraces at golden hour, layered terraced fields, farmers working in traditional clothing, peaceful rural scene, travel photography, Southeast Asian landscape`

57. **火山景观**：`Volcanic landscape, flowing lava, dramatic night scene with red glow, ash clouds, apocalyptic beauty, documentary photography style`

58. **热带雨林**：`Amazon rainforest canopy, dense green vegetation, exotic birds and butterflies, shafts of sunlight, biodiversity illustration, National Geographic quality`

59. **冰川峡谷**：`Icelandic glacial canyon, blue ice formations, dramatic cliff walls, waterfall flowing through, cold ethereal atmosphere, landscape photography`

60. **沙漠绿洲**：`Desert oasis with palm trees and clear water pool, surrounded by golden sand dunes, magical refuge atmosphere, dreamy sunset lighting`

61. **秋日森林**：`Autumn forest with golden and red foliage, fallen leaves covering ground, peaceful forest path, seasonal beauty, warm color palette`

62. **湖畔黄昏**：`Lakeside at dusk, calm water reflecting sunset colors, silhouette of distant mountains, serene peaceful atmosphere, contemplative landscape`

63. **峡谷探险**：`Grand Canyon-like landscape, layered rock formations, dramatic scale, river far below, adventure tourism aesthetic, epic landscape photography`

64. **雪山之巅**：`Majestic mountain peak at golden hour, snow-capped summit, dramatic clouds, alpine adventure atmosphere, mountaineering inspiration`

65. **城市夜景**：`Tokyo or Shanghai cityscape at night, neon signs, busy streets, rain-slicked surfaces reflecting lights, cyberpunk urban atmosphere`

## A.5 插画/艺术风格（66-80）

66. **中国水墨画**：`Traditional Chinese ink wash painting, [主题], [题材: 山水/花鸟/人物], brush stroke texture, rice paper background, minimal composition, cultural heritage aesthetic`

67. **日本浮世绘**：`Ukiyo-e style print, [主题], flat perspective, bold outlines, indigo and vermillion color scheme, traditional Japanese art, Hokusai or Hiroshige influenced`

68. **艺术装饰**：`Art Nouveau illustration, [主题], organic flowing lines, ornate details, muted elegant colors, Alphonse Mucha inspired, vintage decorative art`

69. **波普艺术**：`Pop art illustration, [主题], vibrant flat colors, halftone dots, bold outlines, Warhol or Lichtenstein style, 1960s aesthetic`

70. **极简主义**：`Minimalist geometric illustration, [主题], clean shapes, limited color palette (2-3 colors), negative space, modern art gallery aesthetic`

71. **超现实主义**：`Surrealist painting, [主题], dreamlike imagery, unexpected combinations, Dali or Magritte inspired, poetic and mysterious`

72. **蒸汽朋克**：`Steampunk illustration, [主题], brass gears, steam power, Victorian era technology, sepia and copper tones, retro-futuristic aesthetic`

73. **水墨动画**：`Chinese ink animation still, [主题], dynamic brush strokes, motion blur, flowing water or clouds, Studio Ghibli inspired`

74. **赛博朋克插画**：`Cyberpunk concept art, [主题], neon lights, high-tech low-life, dark urban future, Blade Runner aesthetic, digital painting style`

75. **童话绘本**：`Children's book illustration, [主题], soft watercolor style, cute characters, warm pastel colors, whimsical and magical, picture book quality`

76. **北欧神话**：`Norse mythology illustration, [主题], dramatic gods and creatures, Viking aesthetic, dark moody tones, epic fantasy art`

77. **敦煌壁画**：`Dunhuang cave painting style, [主题], flying apsaras, rich mineral colors (gold, malachite, azurite), Buddhist iconography, ancient Chinese art`

78. **科幻概念**：`Science fiction concept art, [主题], futuristic technology, alien landscapes, dramatic lighting, movie production design quality`

79. **剪纸艺术**：`Chinese paper cutting art, [主题], intricate cut patterns, red paper silhouette, traditional folk art, cultural heritage illustration`

80. **日系动漫**：`Anime style illustration, [主题], cel-shading, expressive characters, vibrant colors, Studio Ghibli or Makoto Shinkai inspired`

## A.6 UI/界面模拟（81-90）

81. **APP登录页**：`Modern mobile app login screen UI, [APP类型] theme, clean minimal design, email/password input fields, social login options, gradient background, iOS/Android design guidelines`

82. **落地页**：`Product landing page UI mockup, [产品类型], hero section with CTA button, feature highlights, testimonials section, modern SaaS aesthetic, 16:9 desktop view`

83. **仪表盘**：`Analytics dashboard UI, data visualization with charts and graphs, dark theme, clean card-based layout, professional SaaS product interface, 16:9 ratio`

84. **社交App界面**：`Social media app feed UI, [平台类型], post cards with images/likes/comments, navigation bar at bottom, modern flat design, mobile-first interface`

85. **电商产品页**：`E-commerce product page UI, [产品类型], large product image gallery, price and add-to-cart button, customer reviews, trust badges, mobile app interface`

86. **设置页面**：`App settings screen UI, toggle switches, profile section, privacy options, clean organized layout, iOS/Android system design`

87. **视频播放器**：`Video streaming app interface, [内容类型] thumbnail grid, play controls, progress bar, subtitle options, Netflix or YouTube inspired UI`

88. **消息应用**：`Chat messaging app UI, conversation bubbles, typing indicator, attachment options, modern clean design, WhatsApp or Telegram inspired interface`

89. **音乐播放器**：`Music player app UI, album artwork, playback controls, playlist view, modern minimal design, Spotify or Apple Music inspired`

90. **日历应用**：`Calendar app UI, month view with events, color-coded categories, clean schedule interface, productivity tool aesthetic`

## A.7 创意/超现实（91-100）

91. **比例悖论**：`Surreal scene with [小物体] and [大物体] swapped in size, [场景描述], photorealistic rendering, dreamlike atmosphere, visual paradox`

92. **材质置换**：`[场景] where [材质A] objects are made of [材质B], [细节描述], realistic lighting of impossible materials, surreal fantasy art`

93. **时空错置**：`[历史时期] characters in [现代场景], [互动描述], anachronistic elements, time travel concept, cinematic lighting`

94. **漂浮世界**：`Floating [物体] in sky, dreamlike atmosphere, soft clouds, magical realism, ethereal lighting, Studio Ghibli inspired fantasy`

95. **物品拟人化**：`[物体] with human characteristics, [拟人化细节], whimsical illustration style, Pixar-like character design, cute and charming`

96. **文字景观**：`Landscape made of [文字或字母], 3D typography terrain, creative typographic art, surreal word environment`

97. **自然城市**：`City where buildings are [自然元素: 树木/蘑菇/珊瑚], organic architecture, eco-futuristic concept, green urban fantasy`

98. **光之舞**：`Abstract light painting, [光线类型: neon/aurora/laser], flowing through space, dynamic motion, long exposure photography aesthetic, vibrant colors`

99. **微观世界**：`Macro world of [微型场景], insects or small creatures as giants, ordinary objects as massive landscape, Alice in Wonderland scale, fantasy concept`

100. **梦境之门**：`Magical door leading to [奇幻世界], portal frame with swirling energy, mysterious atmosphere, fantasy adventure concept, cinematic still`

---

# 附录B：专业术语中英对照表

## B.1 基础术语

| 中文 | 英文 | 说明 |
|------|------|------|
| 提示词 | Prompt | 输入给AI的描述性文字 |
| 负面提示词 | Negative Prompt | 告诉AI不要生成什么 |
| 种子 | Seed | 生成结果的随机数种子 |
| 步数 | Steps | 生成过程的迭代次数 |
| 引导系数 | Guidance Scale / CFG | AI对提示词的遵循程度 |
| 分辨率 | Resolution | 图像的像素尺寸 |
| 纵横比 | Aspect Ratio | 图像宽度与高度的比例 |
| 批量生成 | Batch Generation | 一次生成多张图片 |
| 变异 | Variation | 基于某张图生成相似但不同的图 |

## B.2 构图相关

| 中文 | 英文 | 说明 |
|------|------|------|
| 三分法则 | Rule of Thirds | 将画面分为九宫格构图 |
| 中心构图 | Centered Composition | 主体位于画面中心 |
| 黄金比例 | Golden Ratio | 1:1.618的经典构图比例 |
| 对角线构图 | Diagonal Composition | 沿对角线安排元素 |
| 引导线 | Leading Lines | 引导视线的线条元素 |
| 框架构图 | Frame within a Frame | 利用前景形成框架 |
| 负空间 | Negative Space | 主体周围的留白区域 |
| 景深 | Depth of Field | 画面中清晰范围 |
| 浅景深 | Shallow DOF | 背景模糊效果 |
| 深景深 | Deep DOF | 画面整体清晰 |

## B.3 光影相关

| 中文 | 英文 | 说明 |
|------|------|------|
| 黄金时刻 | Golden Hour | 日出后/日落前的温暖光线 |
| 蓝色时刻 | Blue Hour | 日出前/日落后的冷色调光线 |
| 轮廓光 | Rim Light / Backlight | 从主体后方照射的光 |
| 伦勃朗光 | Rembrandt Lighting | 经典的戏剧性人像光 |
| 柔光 | Soft Light | 漫射的柔和光线 |
| 硬光 | Hard Light | 直接的强光，阴影清晰 |
| 散景 | Bokeh | 背景的光斑模糊效果 |
| 高光 | Highlight | 画面最亮的区域 |
| 阴影 | Shadow | 画面最暗的区域 |
| 逆光 | Backlighting | 光源来自主体后方 |
| 侧光 | Side Lighting | 光源来自主体侧面 |
| 顶光 | Top Lighting | 光源来自主体上方 |

## B.4 色彩相关

| 中文 | 英文 | 说明 |
|------|------|------|
| 色调 | Tone | 整体的色彩倾向 |
| 色温 | Color Temperature | 色彩的冷暖倾向 |
| 饱和度 | Saturation | 色彩的鲜艳程度 |
| 明度 | Brightness | 色彩的明暗程度 |
| 对比度 | Contrast | 明暗差异的程度 |
| 调色 | Color Grading | 后期的色彩调整 |
| 互补色 | Complementary Colors | 色环上相对的两种颜色 |
| 类比色 | Analogous Colors | 色环上相邻的两种颜色 |
| 单色调 | Monochromatic | 单种颜色的不同明暗 |
| 分色调 | Split Toning | 高光和阴影分别调色 |
| 去饱和 | Desaturated | 降低饱和度 |
| 过饱和 | Oversaturated | 超高饱和度 |

## B.5 风格相关

| 中文 | 英文 | 说明 |
|------|------|------|
| 写实主义 | Realism | 真实感的视觉风格 |
| 超写实主义 | Hyperrealism | 超越摄影的真实感 |
| 印象派 | Impressionism | 捕捉光和色彩的印象 |
| 表现主义 | Expressionism | 强调情感表达 |
| 抽象艺术 | Abstract Art | 不再现具体形象的艺术 |
| 极简主义 | Minimalism | 简约到极致的风格 |
| 装饰艺术 | Art Deco | 1920年代的几何装饰风格 |
| 波普艺术 | Pop Art | 1960年代的大众文化艺术 |
| 赛博朋克 | Cyberpunk | 高科技低生活的未来风格 |
| 蒸汽朋克 | Steampunk | 维多利亚时代的科技幻想 |
| 柴油朋克 | Dieselpunk | 两次世界大战间的科技美学 |
| 低保真 | Lo-fi | 故意的低质量/复古感 |
| 高保真 | Hi-fi | 高质量/清晰锐利 |

## B.6 摄影/相机相关

| 中文 | 英文 | 说明 |
|------|------|------|
| 单反 | DSLR | 数码单反相机 |
| 无反 | Mirrorless | 无反光镜相机 |
| 中画幅 | Medium Format | 大传感器专业相机 |
| 全画幅 | Full Frame | 35mm标准传感器 |
| APS-C | APS-C | 小型传感器格式 |
| 微距 | Macro | 近距离特写摄影 |
| 长曝光 | Long Exposure | 慢速快门拍摄 |
| 快门速度 | Shutter Speed | 快门开启的时间 |
| 光圈 | Aperture | 镜头开口的大小 |
| ISO | ISO | 感光度 |
| 白平衡 | White Balance | 色温校正 |
| 原始格式 | RAW | 未压缩的图像格式 |
| 胶片模拟 | Film Simulation | 模拟胶片色彩的数字处理 |

## B.7 艺术介质

| 中文 | 英文 | 说明 |
|------|------|------|
| 油画 | Oil Painting | 油性颜料绘画 |
| 水彩 | Watercolor | 水溶性颜料 |
| 丙烯 | Acrylic | 丙烯颜料 |
| 水墨 | Ink Wash | 中国传统水墨画 |
| 版画 | Printmaking | 通过印刷制作的图像 |
| 素描 | Sketch | 线条为主的快速绘画 |
| 速写 | Drawing | 比素描更精确的绘画 |
| 数字绘画 | Digital Painting | 使用数位板的电脑绘画 |
| 混合媒介 | Mixed Media | 多种媒介结合的艺术 |
| 拼贴画 | Collage | 将不同材料组合在一起 |

## B.8 特殊效果

| 中文 | 英文 | 说明 |
|------|------|------|
| 光晕 | Flare | 镜头眩光效果 |
| 漏光 | Light Leak | 胶片相机漏光痕迹 |
| 颗粒 | Grain | 胶片颗粒感 |
| 色差 | Chromatic Aberration | 镜头造成的色彩边缘 |
| 晕影 | Vignette | 画面边缘的暗角 |
| 动态模糊 | Motion Blur | 运动物体的模糊效果 |
| 焦外成像 | Bokeh | 背景光斑虚化 |
| 体积光 | Volumetric Light | 可见的光束效果 |
| 次表面散射 | Subsurface Scattering | 光线穿透半透明材质 |
| 全局光照 | Global Illumination | 间接光线的模拟 |

## B.9 AI生成相关

| 中文 | 英文 | 说明 |
|------|------|------|
| 文生图 | Text-to-Image | 从文字生成图像 |
| 图生图 | Image-to-Image | 从图像生成新图像 |
| 内补 | Inpainting | 修改图像的特定区域 |
| 外补 | Outpainting | 扩展图像的边界 |
| 潜在空间 | Latent Space | AI模型的内部表示 |
| 扩散模型 | Diffusion Model | 当前主流的AI生成模型 |
| CLIP模型 | CLIP Model | 理解文本-图像关系的模型 |
| 嵌入 | Embedding | 文本/图像的向量表示 |
| 注意力机制 | Attention | AI关注不同部分的能力 |
| 微调 | Fine-tuning | 在特定数据上训练模型 |

## B.10 文化/艺术术语

| 中文 | 英文 | 说明 |
|------|------|------|
| 美学 | Aesthetic | 关于美和艺术感的判断 |
| 视觉语言 | Visual Language | 通过视觉元素表达意义 |
| 图标 | Iconography | 图像符号和象征系统 |
| 叙事 | Narrative | 故事性/叙事结构 |
| 隐喻 | Metaphor | 比喻性的表达 |
| 象征 | Symbolism | 用符号代表概念 |
| 构成 | Composition | 元素的安排和组织 |
| 质感 | Texture | 表面的触感特征 |
| 空间感 | Spatial Sense | 三维空间的感知 |
| 动势 | Dynamic | 画面中的运动感 |
| 平衡 | Balance | 视觉重量的均衡 |
| 统一 | Unity | 整体的一致性 |
| 对比 | Contrast | 元素间的差异 |
| 节奏 | Rhythm | 元素的重复和变化 |
| 焦点 | Focal Point | 视觉中心点 |

---

# 附录C：推荐资源与学习路径

## C.1 学习路径规划

### 入门级（0-1个月）
**目标**：掌握基础提示词，能生成可用的图像

**学习内容**：
1. 理解GPT Image 2的基本原理和限制
2. 掌握C.L.E.A.R.提示词框架
3. 练习基础场景的提示词写作（人像、产品、风景）
4. 学会使用负面提示词排除不需要的元素

**推荐练习**：
- 每天生成5张图，记录提示词和结果
- 尝试用不同语序描述同一场景，观察差异
- 收集10个你喜欢的图片，尝试用提示词复现

**预期成果**：能写出50词左右的有效提示词，生成基本符合预期的图像

### 进阶级（1-3个月）
**目标**：掌握风格控制和细节描述，生成高质量图像

**学习内容**：
1. 深入学习光照、构图、色彩理论
2. 掌握风格混合和跨界创作技巧
3. 学习历史场景和IP角色还原
4. 建立个人提示词库

**推荐练习**：
- 完成一个主题系列（如"四季风景"、"世界城市"）
- 选择一个IP角色，尝试从v1到v5的完整迭代
- 研究并复现10个高质量案例的提示词

**预期成果**：能生成100-200词的复杂提示词，作品达到商业可用质量

### 大师级（3-6个月）
**目标**：掌握提示词工程学，形成系统化的创作方法

**学习内容**：
1. 深入理解AI模型的"理解机制"
2. 掌握JSON结构化提示词
3. 学习将GPT Image 2整合到工作流
4. 探索提示词的变现路径

**推荐练习**：
- 为一个真实客户项目提供完整的视觉方案
- 开发一个可复用的提示词模板包
- 尝试用JSON实现提示词的批量生成

**预期成果**：形成个人化的提示词方法论，能够为他人提供专业服务

## C.2 推荐阅读资源

### 中文资源

**书籍**：
- 《写给大家看的设计书》- 学习基础设计原则
- 《摄影构图学》- 理解视觉构图
- 《色彩搭配原理与技巧》- 掌握色彩理论
- 《美学原理》- 提升艺术鉴赏能力

**网站/公众号**：
- 站酷（zcool.com.cn）- 设计师作品平台
- 花瓣网（huaban.com）- 灵感收集
- 数英网（digitaling.com）- 创意案例
- Behance中文版 - 国际创意作品

### 英文资源

**平台**：
- Midjourney Discord社区 - 学习优秀提示词
- Reddit r/StableDiffusion - 技术讨论
- Pinterest - 视觉灵感收集
- ArtStation - 专业艺术家作品

**资源库**：
- Civitai - 模型和提示词分享
- Lexica.art - Stable Diffusion提示词搜索
- Krea.ai - 实时AI图像生成参考

## C.3 每日练习计划

### 第1-2周：基础积累
- **周一**：人像练习（不同表情、姿态）
- **周二**：风景练习（不同时间、天气）
- **周三**：产品练习（不同材质、光照）
- **周四**：风格练习（选择一种风格，尝试5个主题）
- **周五**：分析日（分析5张优秀作品，提取提示词要素）
- **周六**：创意实验（尝试超现实或风格混合）
- **周日**：回顾与整理（将本周有效的提示词加入库）

### 第3-4周：专题深入
- 专题一：同一场景的5种不同风格
- 专题二：同一风格的5个不同场景
- 专题三：完整迭代一个复杂提示词

### 第5-8周：项目实战
- 选择一个主题（如"世界名城"）
- 完成10张系列作品
- 确保风格统一
- 制作成作品集

## C.4 常见问题与解决方案

**Q1：提示词写得很详细，但效果还是不理想**

A：检查以下方面：
- 是否使用了过于抽象的词汇？尝试用更具体的描述
- 提示词是否过长？尝试删减不必要的信息
- 是否存在矛盾的要求？检查元素之间是否冲突
- 尝试改变语序，将最重要的描述放在前面

**Q2：生成的图像风格不一致**

A：建立风格模板，固定以下元素：
- 色彩方案
- 光照条件
- 构图方式
- 渲染风格
- 质感描述

**Q3：不知道如何描述想要的效果**

A：
- 收集参考图，分析其视觉特征
- 使用"类比法"：这是"像XX一样的XX"
- 从C.L.E.A.R.框架的每个维度逐一思考
- 尝试用JSON结构化你的想法

**Q4：如何提升提示词的原创性**

A：
- 避免"热门关键词"堆砌
- 深入研究某一风格，找到其核心特征
- 尝试非常规的元素组合
- 从其他艺术形式（音乐、文学）中汲取灵感

**Q5：AI生成的细节总是有瑕疵**

A：
- 专注于整体氛围和构图，细节可以在后期PS中修正
- 使用"photorealistic"和"ultra-detailed"等质量标签
- 对于专业需求，考虑将GPT Image 2作为概念工具，最终用传统方式完成

## C.5 进阶发展方向

### 方向一：提示词工程师
- 专注于提示词的标准化和工程化
- 为企业提供批量生成解决方案
- 开发提示词工具和模板系统

### 方向二：AI视觉设计师
- 将GPT Image 2整合到设计工作流
- 提供从概念到最终输出的完整服务
- 探索AI与传统设计的最佳结合方式

### 方向三：内容创作者
- 利用GPT Image 2提升内容创作效率
- 在社交媒体上分享作品和技巧
- 开设课程或培训服务

### 方向四：研究者
- 深入研究AI模型的"理解机制"
- 探索提示词的理论基础
- 开发新的提示词方法论

---

## 结语

GPT Image 2提示词不仅是一项技术，更是一种新的视觉语言。掌握这门语言，你获得的不仅是生成图像的能力，更是将想象力转化为现实的系统性方法。

从第一部分的基础入门，到第二部分的进阶技巧，再到第三部分的大师方法论，我们构建了一个完整的学习体系。但教程只是地图，真正的探索需要你亲自上路。

**最后的建议：**

1. **保持好奇心**：每个失败都是学习机会
2. **持续练习**：提示词写作像任何技能一样，需要重复来精通
3. **建立系统**：让你的经验可复用、可迭代、可分享
4. **拥抱变化**：AI技术在快速进化，保持学习的心态

祝你在这场视觉语言的探索之旅中，发现无限可能。

---

**教程系列总字数：约 45,000 字**

**作者**：GPT Image 2 提示词大师教程编写组  
**版本**：v1.0  
**更新日期**：2026年4月

---

## 感谢阅读！

如果你觉得本教程对你有帮助，欢迎：
- 分享给同样对AI绘画感兴趣的朋友
- 在实践中应用并反馈你的经验
- 持续关注我们的更新和进阶内容

让我们一起，用提示词构建更美好的视觉世界。

---

*第三部分完成*
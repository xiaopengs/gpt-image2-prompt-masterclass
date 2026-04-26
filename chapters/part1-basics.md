# GPT Image 2 提示词完全指南 · 入门篇

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

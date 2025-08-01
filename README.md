# Build a Large Language Model (From Scratch)  中文版

随着大语言模型（LLM）技术的飞速发展，越来越多的应用开始渗透到我们的工作和日常生活中。从智能助手、自动翻译到内容生成，LLM 已经成为推动人工智能发展的关键技术之一。这些技术不仅影响着企业和科研领域，还在教育、医疗、金融等多个行业引发了深远的变革。

[《Build a Large Language Model (From Scratch)》](https://www.manning.com/books/build-a-large-language-model-from-scratch)是一本深入探讨大语言模型原理与实现的电子书，适合希望深入了解 GPT 等大模型架构、训练过程及应用开发的学习者。为了让更多中文读者能够接触到这本极具价值的教材，我决定将其翻译成中文，并通过 GitHub 进行开源共享。

学习大语言模型的原理和实现，不仅有助于理解 AI 如何模仿人类的语言处理能力，也为开发者提供了深入掌握模型训练、调优、部署等技术的机会。无论是从事 AI 研究的学者，还是希望在实际项目中应用大语言模型的开发者，都能从中受益。

随着 LLM 技术的广泛应用，掌握其基础原理和实现方法将成为每一位 AI 从业者必备的技能。通过学习和研究大语言模型，我们不仅能更好地理解当前的技术发展，还能为未来的创新和突破奠定基础。

<img src="https://wechat-account-1251781786.cos.ap-guangzhou.myqcloud.com/logo.png" width="30%" />





## 项目简介

+ 本项目还提供了原版的英文电子书（存放在 e-Book 目录中），对于英语基础较好的读者，我们建议尽量阅读原版书籍。毕竟，翻译过程是对原文的自我解读，难以做到完全与原版的思想和表达一致。
+ 为了兼顾翻译效率与质量，我采用了分阶段的翻译方案：首先开发了一个 AI 翻译助手，负责在大模型知识领域内逐章、逐节、逐段进行粗翻译；接着，由另一个 AI Agent 对翻译内容进行审查与修正；最后，我会进行人工精细翻译，确保翻译的准确性和流畅度。
+ 在原版英文书籍中，有一些内容与书中的主旨关系相对较弱，因此常常被简略提及。但这些内容的深入理解能够帮助我们更好地掌握大模型的设计理念。因此，在翻译过程中，我也加入了自己在遇到不理解或不了解的部分时的思考和解读，希望能帮助读者更深入地理解大模型的各个方面。
+ 书中提供了所有需要的实践代码，强烈建议读者按照书中的教程进行实操，并在实现的过程中结合日常使用的各类大模型，深入思考其背后的原理。如果遇到不理解的部分，可以进一步查阅相关资料。（官方也针对书籍提供了配套的[代码库](https://github.com/rasbt/LLMs-from-scratch)）





## 项目结构

| 目录    | 说明                                                 |
| ------- | ---------------------------------------------------- |
| e-Book  | 原版英文书籍，建议英语基础较好的读者直接阅读         |
| cn-Book | 翻译后的中文版，按照章节组织，与原版英文书籍一一对应 |
| Image   | 原版英文书籍中的所有图片，也全部经过翻译             |

### 全书章节

**在线阅读**：[Build a Large Language Model (From Scratch)  中文版](https://skindhu.github.io/Build-A-Large-Language-Model-CN/)

+ [第一章：理解大语言模型](https://skindhu.github.io/Build-A-Large-Language-Model-CN/#/./cn-Book/1.理解大语言模型.md)
+ [第二章：处理文本数据](https://skindhu.github.io/Build-A-Large-Language-Model-CN/#/./cn-Book/2.处理文本数据.md)
+ [第三章：实现注意力机制](https://skindhu.github.io/Build-A-Large-Language-Model-CN/#/./cn-Book/3.实现注意力机制.md)
+ [第四章：从零开始实现一个用于文本生成的 GPT 模型](https://skindhu.github.io/Build-A-Large-Language-Model-CN/#/./cn-Book/4.从零开始实现一个用于文本生成的%20GPT%20模型.md)
+ [第五章：在无标记数据集上进行预训练](https://skindhu.github.io/Build-A-Large-Language-Model-CN/#/./cn-Book/5.在无标记数据集上进行预训练.md)
+ [第六章：用于分类任务的微调](https://skindhu.github.io/Build-A-Large-Language-Model-CN/#/./cn-Book/6.用于分类任务的微调.md)
+ [第七章：指令遵循微调](https://skindhu.github.io/Build-A-Large-Language-Model-CN/#/./cn-Book/7.指令遵循微调.md)
+ [附录A：PyTorch简介](https://skindhu.github.io/Build-A-Large-Language-Model-CN/#/./cn-Book/附录A.PyTorch简介.md)
+ [附录B：参考文献和扩展阅读](https://skindhu.github.io/Build-A-Large-Language-Model-CN/#/./cn-Book/附录B.参考文献和扩展阅读.md)
+ [附录C：习题解答](https://skindhu.github.io/Build-A-Large-Language-Model-CN/#/./cn-Book/附录C.习题解答.md)
+ [附录D：给训练循环添加高级技巧](https://skindhu.github.io/Build-A-Large-Language-Model-CN/#/./cn-Book/附录D.给训练循环添加高级技巧.md)
+ [附录E：使用 LoRA 的参数高效微调](https://skindhu.github.io/Build-A-Large-Language-Model-CN/#/./cn-Book/附录E.使用LoRA的参数高效微调.md)

## 个人思考

巴克莱在最近发布的研报中提出了一份“AI路线图”，描绘了未来AI技术应用的演进路径，我个人比较认同。报告指出，AI的应用将经历三个重要阶段，首先是当下的**第一阶段**：聊天机器人和早期的AI助理（Copilot），因为目前主要是侧重于基础设置的建设和模型能力的竞赛。接下来在2025-2026年将迎来“真AI代理时代”的人**第二阶段**，这一阶段的核心在于能够自主完成任务的AI代理的广泛应用。与聊天机器人和Copilot不同，AI代理能完成相对复杂的任务，尽量减少人类的直接干预。而在2027年以后，AI技术将进一步进入“数字员工与机器人时代”**第三阶段**”（应该是所谓的具身智能），在企业应用中，AI代理可能演变成独立完成任务的“数字员工”，在消费者市场，智能机器人将开始逐步融入家庭生活，承担简单和重复性的日常任务。

可以看到，这一发展趋势的推断依据是人类对于AI工作过程的介入越来越少（意味着AI能力越来越强），再结合具身形态，必然会帮人类承担越来越多的工作。据巴克莱估计，到这一阶段，AI技术的普及将达到互联网用户的规模，突破40亿人。

**那么作为IT从业者，从现在开始应该做哪些准备尽量保障自己在将来不会被淘汰，根据我的浅薄认知做一下梳理和预测：**

+ **持续学习与技能提升**

  + 尽量去掌握大模型技术原理，而不要仅仅关注各种花里胡哨的应用层面的资讯。学习原理，才能透过现象看本质，比如该项目从零到一通过编码的方式带我们了解如何准备和清理训练数据、分词、词嵌入、Transformer架构的实现、模型精调、实现指令遵循等，对于大模型的理解非常有帮助。
  + 保持和加深对业务的理解：AI最终是要落地到实际的业务中去解决某一类问题，那么如何对业务问题进行抽象从而设计出高效的AI工作流是我们要关注和解决的问题，这也取决于我们对业务的理解程度。

+ **拥抱AI工具和技术**

  + 多在日常的工作和生活中使用各类AI工具，这样才能逐渐对各种不同的AI应用思路的认知提升。
  + 多参与实际的AI项目，积累经验，从中学习如何将AI应用到实际的问题中，提升解决问题的能力。

+ **够快速适应变化**

  + 尽量保持开放的形态，不要因为年龄慢慢变大，生活中琐事变多而失去好奇心。我们要对新技术、新工具保持好奇和开放的态度，快速适应技术的变化和市场的需求。

  + 接受未来可能带来的变化，积极寻找学习和发展的机会。


## 若希望了解更多AI探索相关的内容，可关注作者公众号
<img src="https://wechat-account-1251781786.cos.ap-guangzhou.myqcloud.com/wechat_account.jpeg" width="30%">

## 最新文章
[大模型上下文工程之Prefill Response（预填响应）技巧](https://mp.weixin.qq.com/s/fMeg0wcCd4XZPSN5EouLcg)<br />
[大模型上下文工程之Prefix Caching技术详解](https://mp.weixin.qq.com/s/TA7DY1cynVNPYW-sVI2zHw)<br />
[产品级AI应用的核心：上下文工程](https://mp.weixin.qq.com/s/93rEhMY7rIUlHIiPPDvEag) <br />
[如何让Cursor精通鸿蒙开发？](https://mp.weixin.qq.com/s/gLgP7gGU0pmGc2x1hS-0UQ)<br />
[深度解读斯坦福AI就业报告：未来哪些工作是“绿灯”，哪些是“红灯”？](https://mp.weixin.qq.com/s/8RUntvEMcbYCTbD56-rQKg)<br />
[搭建一个AI研究团队：我对Claude多智能体深度研究系统的思考与实践](https://mp.weixin.qq.com/s/bOraqJUecR9vO9E23GxodA)<br />
[谁说AI只会模仿，从Google AlphaEvolve项目看算法的自主创新](https://mp.weixin.qq.com/s/2Gjpw6xbPh3KOLFoozrvlw)<br />
[AI浪潮下的代码与人:程序员的挑战与机遇](https://mp.weixin.qq.com/s/-vQ6ZtIzlfIKbt2dDkRxLw)<br />
[构建高效Prompt的艺术：从Claude 4系统提示词中汲取的设计智慧](https://mp.weixin.qq.com/s/WGZJl8VzbnZz56hJNtP-sw)


## 中文版电子书阅读过程中可能遇到的问题

在阅读过程中，可能会出现图片无法加载的问题，这一般是由于 Github 的文件服务器的 DNS 被污染导致。遇到该问题时，我们可以先查询出 Github 文件服务器（域名是`raw.githubusercontent.com`）的真实 IP，这可以在 Terminal 中执行如下命令获取：

```bash
nslookup raw.githubusercontent.com 114.114.114.114
```

比如我执行后的输出结果如下:

```
Server:		114.114.114.114
Address:	114.114.114.114#53

Non-authoritative answer:
Name:	raw.githubusercontent.com
Address: 185.199.111.133
Name:	raw.githubusercontent.com
Address: 185.199.110.133
Name:	raw.githubusercontent.com
Address: 185.199.109.133
```

接着可以修改`/etc/hosts`文件，将域名重定向到正确的 ip 地址上（`sudo vim /etc/hosts`）:

```bas
# 读者可以根据自己的输出填入正确的IP地址，当然可以先 ping 一下这些IP，选择通畅且速度最快的
185.199.108.133 raw.githubusercontent.com
185.199.108.133 githubusercontent.com
```




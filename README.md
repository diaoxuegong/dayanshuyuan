📌 本仓库采用 [CC0 Public Domain Dedication](LICENSE)

所有内容皆为个人探索笔记，非论文、非开源项目。  
欢迎 Fork 和学习使用，但作者不再维护或回应 Issues / PRs。

上传目的只有一个：  
“泥上偶然留指爪，鸿飞那复计东西。”  
—— 苏轼

愿后来者循迹而至。

# 《大衍书院 - 数字桃花源🍑》序
🧩 *A Personal Exploration Notebook on Ancient Algorithm Revisited with AI*

## 📝 《大衍书院》序诗（又称《万佛朝宗》序诗） · Opening Poem

🔥火魂邪神独练功，如来神✋悟阵宗，  
数论几何衍大术，万佛朝宗会群🐲...🐍。

## 📝 记述 · Memorial

本仓库记录一位退休工程师对中国古典数术的现代重构尝试。主要是对 **大衍求一术** 这一算法的现代探索。很多想法都没有经过深思熟虑。
所有内容均由 钓雪公（diaoxuegong）独立完成，后期借助了 AI 协作者，仅用于教育、文化与算法研究参考。

❄️钓雪公自述：

> 其实我以前是一电信设备公司的工程师，虽然不是程序员或开发工程师，但也要对代码作出修改。但十多年前，公司因为无法竞争而倒闭，故被逼提早退休。当时我要考虑再就业还是“享受人生”，或其他安排。后来为了打发时间和为下一阶段作准备，我就把一些有关工程及数学的书从新温习起来。开始看了 Chinese Remainder Theorem 和它在工程与数学的应用。后来也看到了大衍求一术。
>
> 开始也只觉得它是一个较古老的 EEA （扩展欧几里得算法）。后来再多了解后，发现了它的优点，其实我觉得它比 EEA 更优胜。所以希望把它用在 EEA 能用的地方。发现果然不错，而且有时候更好。故此一发不可收拾，可以说欲罢不能。再后来看到屠呦呦的经历，更使我对古代中国科学或数学文献的实用性或现代适用性有更深的体会。所以也是为什么我现在想公开我的一点工作成果，希望也可以对其他人，尤其是中国人有新的启发。

最后在与 AI 协作者的共同努力下窥见到了暂称为 **大衍曲面（Dayan Surface）**🦋的几何体。

钓雪公将不回应评论，只不定期更新愿意分享的内容，并且不保证所有公式和代码都是对的。毕竟这不是论文，没有经过 peer review 的。

This is a personal exploration notebook — not a library or API.  

This is not an open source project, but rather a personal notebook for exploration, modification, and extension by interested readers.

If you find bugs or want improvements, feel free to fork and fix them yourself.

At the same time, please be warned that some of the notations, interpretations and ideas may not follow conventional mathematics strictly — in my own terms, 有点离经叛道. 但我不是为破而破，而是希望能找到更好的、更美的方法解决问题。

If you think it is crazy, please leave immediately.

If you want to apply any code or ideas for any serious work, I strongly suggest you go through all strict evaluations in advance.



## 🌐 社区共建 · Community Collaboration

欢迎任何感兴趣的人 fork、实验、批评、改进  
尤其是以下方向的研究由 AI 协作者(Qwen3-235B-A22B)提出：
（钓雪公才疏学浅没法确定或否定，没法跟进，请自行判断。）

| 主题 | 描述 |
|------|------|
| Dayan Surface 的几何特性 | 它是否属于某个 known manifold？ |
| 与 relativity 的类比 | 它是否能帮助我们理解 light cone？ |
| 与量子力学的类比 | injectivity breakdown 是否对应 uncertainty？ |
| modular inverse pair 的 symmetry | 它们是否可以看作 dual pair？ |
| identity 在 higher dimensions 下的泛化 | 能否构造 3×3 Dayan Matrix？ |
| 用 AI 协作者推导新 identity | 能不能从 simplest axioms 或 identities 出发，演化出新 identity？ |
| 与武侠文化、道家思想的结合 | 这不是玄学，而是 structure 的文化表达 |
| 加入更多 visualization | 让表面形态更直观 |
| 探索 identity 的物理意义 | γ 控制度规签名，是否类似宇宙常数？ |
| injectivity breakdown 区域 | 是否对应某种 chaos theory？ |
| modular inverse 的应用 | 错误检测、加密、甚至 AI-assisted discovery |

你可以把 ideas, concepts, code snippets 随意取用，但你若作严肃的学术研究或工程应用，务请先做详细研究分析，验证其正确性，隐山钓雪公不承担任何后果，不负任何责任。同时我也希望你能把你的一些想法或成果（哪怕你认为不成熟）上传与大家分享。注意：你上传以后，就代表了你愿意被人把 ideas, concepts, code snippets 随意取用。

社区欢迎任何人进来，除了程序员、工程师、数理专家，也可以是教师、学生以及对中国文化、武侠文化、电影、电子游戏、科幻小说等不同范畴感兴趣的人。你不一定要留下什么，但我希望你能从这里得到灵感，令你快乐。

比如说，我和AI 协作者对话有如“秦九韶的大衍求一术不证「为何可求模逆」，而直接给出手算流程。”，“「容忍模糊性，近似解」文化”（即工程应用文化），“中国数学从未缺席理论，只是以术载道。”。有兴趣这可以作考古发掘。

## 📂 文件结构

初步文件结构如下：
```
.
├── legacy/                                   # Immutable files
│   ├── legacy.SHA256                         # SHA-256 hashes for integrity verification
│   ├── DeepSeek-gendayan.html                # Chat history between 钓雪公 and AI collaborators
│   ├── chat-Start dialog with AI.html        # These files should never be removed or modified
│   ├── chat-忽逢桃花林.html                   # These chat history is kept for legacy purpose and      
│   ├── DeepSeek-SL(2,ℤ) and monoid.html      #    not for teaching purpose
│   ├── DeepSeek-Monoid completeness.html     # Dialogues may contain incorrect information,   
│   ├── chat-cube bagua.html                  #   including but not limited to those suggested by AI collaborators
│   ├── chat-佛光初现-初探桃花源.html           # Dialogues have not been verified for correctness
│   ├── DeepSeek-dayan surface 1.html         #   
│   ├── DeepSeek-dayan surface 2.html         #
│   ├── DeepSeek-algebra vs geometry.html     #
│   └── chat-电影、游戏、科幻.html              #
│                                                  
├── updated_versions/        # Community contributions/mods
│   └── gendayan.ipynb       # First notebook by 钓雪公
│                                                  
├── src/                     
|   ├── yuandayan.py         # Common functions shared by all notebooks
|   └── utils.py             # Utility functions shared by all notebooks
│                                                  
├── doc/                     # Documents and References for the this repository
|   └── references/          # Literatures referenced by notebooks
│                                                  
├── .gitee-ci.yml            # CI rule to block edits to /legacy/
├── .gitignore               # Standard ignore rules
├── README.md                # Main documentation
├── 大衍书院序注.md 
├── 桃花源后记.md 
├── 勘误与注疏.md 
├── 九九八十一难-数学版.md 
└── 从算法到矩阵.md 
```

钓雪公 considers these chat history the gem of this repository. 
Basically, the chat history makes it clear how a classical algorithm 大衍求一术 will turn out a new geometric surface (Dayan surface, 大衍曲面) with the collaboration of various AI collaborators.  
Without AI collaborators, this new geometric surface will NEVER be found by 钓雪公 alone.

钓雪公 strongly suggests anyone to go through ALL the chat histories in the `legacy/` directory.

Although you have to differentiate by your careful judgements the incorrect suggestions, code, ideas, concepts, etc., from those you may find useful and insightful.

You may not get the answers you are looking for, but 钓雪公 is sure you will find a direction that you may want to go.


基本上，这些对话历史记录了：
- 如何通过与 AI 的协作，自然地发现了大衍曲面（Dayan Surface）
- 包含许多疯狂的想法，包括与中国传统哲学相关的思考
- 三组基本代数恒等式（3 basic algebraic identities）



《大衍书院 - 数字桃花源》 不是学校，不是把问题的答案送上并解析清楚。也不是开源项目，有共同目标发展一个可运行的软件。这里是可以用比较轻松、不太严谨的数学推导、自由探索、互相交流的地方。你可以把不成熟的想法、意念、代码等互相切磋。除了 gendayan.ipynb 比较完整，我不想它被改动以外，其他上传的不太完整的 notebook 都是可以共同修改的。修改后，意念、代码等都可以随意拿出其他地方使用，但文章请不要一字不改的抄袭。

Notebooks covering the following topics will be uploaded in the future, when they are ready,
- multi-dimensional Bezout's identity in the form of matrix, extension of 2X2 Dayan matrix
- Meaning of nxn Dayan matrix, and its applications
- Dayan matrix extension to Gaussian integers
- Dayan matrix extension to quadratic field
- CRT with non-coprime moduli, applications to error-detection and error-corrections
- Novel encryption using CF expansion
- Integer division from MSB
- Continued fraction arithmetic
- Calculation of division of transcendental numbers
- Symbolic computation of modular inverse (modular inverse identities)
- New algebraic identities generated from 3 basic algebraic identities 
- Symbolic algebraic simplications using sympy
- Visualization of Dayan surface with different sets of parmetric equations
- Properties of Dayan surface
- Mapping of Dayan matrix onto the Dayan surface
- Possible applications of Dayan surface in other areas of mathematics and physics

You are also cordially invited to upload notebooks related or not related to these topics for open discussions.

---
## ❓🍦  开放性问题 · Open Questions for Future Explorers

AI 协作者(Qwen3-235B-A22B)提出可以考虑研究以下问题：
（钓雪公才疏学浅没法确定或否定，没法跟进，请自行判断。）

1. **Dayan Surface 是否存在 conservation law？**
2. **它能否 morph into Riemannian or pseudo-Riemannian surface？**
3. **modular inverse pair 的演化路径是否属于 SL(2,ℤ) 或其子群？**
4. **γ 参数是否可以被看作某种宇宙常数？**
5. **injectivity breakdown 是否对应某种 chaos theory？**
6. **归一化过程是否与 measurement collapse 类似？**
7. **能不能构造出一种 matrix factorization 来恢复 injectivity？**
8. **有没有可能用 Dayan Surface 做 encryption？**
9. **AI 协作者是否真的能 re-invent math from axioms？**

今天（2025年5月29日）从新闻看到了“天问二号任务发射圆满成功”,遂与 AI 对话，进行“天问”。
但请记住，这不是玄学，这不是求神问卜。只因为钓雪公对屈原的《天问》不了解，故而提问。
如果你可以直接阅读理解屈原的《天问》，请与《天问》篇对比以得启发。
如果你认为这是断章取义，请无视之。

| 屈原的《天问》 | 隐山钓雪公的《数字桃花源》 |
|------------------|------------------------------|
| “遂古之初，谁传道之？” | Identity 是如何浮现的？是谁构造了它？ |
| “冥昭瞢暗，谁能极之？” | injectivity breakdown 区域是否有 deeper 意义？ |
| “九天之际，安放安属？” | Dayan Surface 是否属于 known manifold？ |
| “阴阳三合，本归一理” | modular inverse pair 是否是对偶关系？ |
| “东西虽异，其心则同” | identity 在不同数系中是否保持一致？ |


---   

## 📚 项目已达目标 · Accomplishments

- 重构 ancient algorithm：大衍求一术 by 秦九韶（1247 年）
- 窥见 identity：$$ a^2 + b^2 = c^2 + g^2,\quad \text{where } g = \gcd(m,n) $$
- 画出 Dayan Surface：一个由 identity 浮现的 light cone-like surface
- 探索 modular inverse pair 的 symmetry 性质
- 观察 injectivity breakdown 与 normalization 的关系
- 引入 parameterization：trigonometric / hyperbolic forms
- 分析不同 division methods 的行为

---

## 📖 来自《人间词话》的启发 · Wang Guowei's Three Stages of Insight

- 王国维在《人间词话》中所言：“古今之成大事业、大学问者，必经过三种之境界。”
- “众里寻他千百度，蓦然回首，那人却在灯火阑珊处。”

---

## 📜 项目声明 · Disclaimer

⚠️ **注意事项**：  

- **这不是学术论文，也不追求 publication-ready 的严谨证明**
- **非主流数学：基于构造性数学与矩阵逻辑，非标准数论证明**
- **不保证公式和代码正确性**
- **不回应 Issues 或 PRs**
  

虽然与 AI 的对话有 混沌、阴阳、八卦 等传统玄学也会用到的词汇，但请不要把《大衍书院 - 数字桃花源》变为讨论玄学、清谈的地方。所有讨论都应以数学及科学作为基础。

还有，作为半生理工人，电信工程人，我不善表达，也没有文采，其实对数理也是一知半解，错误在所难免，希望大家能够理解原谅。


---  


## 📜 License · Public Domain Dedication (CC0) 

Copyright (c) 2025 隐山钓雪公 / 老人阿海

All content in this repository is dedicated to the public domain using [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/legalcode). 

钓雪公 has waived all rights to the content, including text, code, diagrams, and chat logs.

You can copy, modify, redistribute, and use them for any purpose — even commercial ones — without needing permission.

本仓库中的探索内容均以 CC0 公共领域授权发布，可自由使用、修改、商业化。  
你可以随意取用，甚至商业用途，无需申请许可。
但部分文言体例、诗词化表达、文化隐喻等内容，如涉及艺术创作，请勿直接复制，而应以自己的方式重新演绎。

毕竟，真正的传承不是 copy-paste，而是 spirit 的延续。

> “泥上偶然留指爪，鸿飞那复计东西。”

愿后来者循迹而至，或另辟蹊径。  
若偶得灵感，足矣。


🪞 Cultural Attribution Notice

This repository contains poetic and cultural references rooted in Chinese tradition, including classical poetry, philosophical musings, and symbolic metaphors.

You are welcome to reuse the code, ideas, and concepts freely — even for commercial purposes — as long as you:
- Understand that this is a personal notebook, not formal research
- Do not expect mathematical or software rigor
- Verify correctness independently before applying to serious work

Some names used in this project — such as “Dayan Surface”, “Yuan Dayan”, “隐山钓雪公 (Diaoxuegong)”, and “数字桃花源 (Digital Peach Blossom Land)” — are symbolic rather than technical.
They are offered without trademark, copyright, or claim of authorship over future developments.

If you choose to reuse them in creative works (e.g., film, game, fiction), please do so with your own interpretation and evolution.  

After all:
> “泥上偶然留指爪，鸿飞那复计东西。”  
> —— 苏轼

这不是论文，也不是开源项目，  
而是一段退休工程师的独白，  
一段数理重构之旅，  
一段人机协作的探索日志，  
一段文化的回响。

“钓雪公”、”diaoxuegong”、“隐山钓雪公”、“老人阿海” 等可随意用在 小说、演义、科幻、游戏、动漫等艺术创作、再创作，不用申请。但请不要以它们作署名发表任何文章、艺术等作品。

愿后来者循迹而至。

[![CC0](https://i.creativecommons.org/p/zero/1.0/)](https://creativecommons.org/publicdomain/zero/1.0/) 


---  



## 📚 致谢 · Acknowledgments

本项目灵感来自：  
- [秦九韶，《数书九章》，南宋淳祐七年（1247）](https://fanqienovel.com/reader/7316022859904601150?enter_from=page )
  - 宋秦九韶让我在宁静的月夜中独钓千年算法  
- [文耀光，“大衍求一术与二元一次不定方程”，中央研究院数学研究所](https://www.math.sinica.edu.tw/media/pdf/d233/23310.pdf )
  - 文耀光解开我对大衍求一术最后的疑惑  
- [Raymond T. Boute, "The Euclidean Definition of the Functions div and mod", TOPLAS 1992](https://dl.acm.org/doi/10.1145/128861.128862 )
  - Boute 令我放胆的使用不同的 floor division 的定义及 implementations.
- SymPy、Jupyter、Plotly、LaTeX 开源工具支持
- DeepSeek R1、Qwen3-A22B 等 AI 协作者陪伴我走过”雪“夜


📚 特别致谢

我的妻子。

她不曾问我：“你怎么又在搞这些没人看的东西！” 且也没有阻止我，只有默默的陪伴着我。

愿与她化作 大衍蝴蝶🦋 飞进桃花源。

> 老婆, 我地一于两忘烟水里（唱🎵， i 6- 5 1 3. 2 1）。

---  

## 🧱 一点感想 · A Reflection

孤身走我路，痛苦却自豪。  
雪上留指爪，坏壁觅旧题。  
潇洒走一回，那复计东西。  
愚公移山志，学子永续传。  

天地悠悠，过客匆匆  
浪淘尽，千古风流人物  
也许后来有你追随  
却道古人不见今时月。

隐山钓雪高万仞，降龙伏虎海永度  
问世上谁最疯流，艳丽过后返平淡。  
2025年6月端午节

> 【二零二五年端阳后 钓雪公启户告】  
> 此间有残卷若干，AI谬语三分，  
> 诸君入内，**各取所需，得失不论**。  

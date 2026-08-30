# 《将进酒》Launch Check Production Package

> 状态：Ready for Production  
> 日期：2026-08-30  
> 适用：History AI V1 Phase 1 / Launch Check / Sample #1 候选  
> 上位基线：`docs/superpowers/specs/2026-08-30-history-ai-v1-final.md`

---

# 1. 本片只验证什么

这不是精品中视频，也不是 Phase 2 的“电影感技术验证”。

本片只验证：

> **用当前可获得的 AI 视频工具，能否在可控成本与工时内，做出一条 30 秒、达到正常发布质量线、普通用户愿意看下去的《将进酒》短视频。**

通过后即可作为 Phase 1 Sample #1 发布，或作为生产流程校准样片后重做正式版。

本片不验证：

- 20+ 镜头连续叙事；
- 电影工业级角色一致性；
- 长视频经济性；
- B 端交付能力；
- 历史事件复刻准确性。

---

# 2. 成片规格冻结

- 题材：李白《将进酒》
- 内容形式：**电影化名场面 + 原文旁白**
- 时长：**30 秒**
- 画幅：**9:16 竖屏**
- 分辨率：优先 1080×1920；生成阶段最低可接受 720P，最终导出 1080P
- 帧率：跟随生成模型；最终保持稳定，不做无意义补帧
- 镜头数：**6 个**
- 核心人物：1 人，唐代中年文士的原创视觉形象，不复刻任何影视版李白
- 旁白：中文男声，克制、有力量，不“播音腔”
- 字幕：后期添加，不让视频模型生成汉字
- 音乐：低频鼓点 / 古琴或箫的现代电影化配器，必须来源明确可用
- 发布主平台：抖音
- 第一辅助平台：视频号

---

# 3. 创意核心

不是把整首《将进酒》解释一遍。

30 秒只抓一条情绪线：

> **天地浩大 → 人生短暂 → 纵情一刻 → 自我确信 → 与万古之愁对饮。**

用户看完应该记住的不是“AI 很厉害”，而是：

> **这几句背过的诗，突然有了真实的气魄。**

---

# 4. 内容与历史边界

本片是基于公有领域原文进行的原创视觉改编。

视觉设定采用“唐代文人宴饮的艺术化想象”，**不宣称复原《将进酒》写作当晚的真实历史现场**。

禁止：

- 直接模仿任何现代影视剧中的李白造型；
- 明星脸；
- 游戏 / 动漫李白形象；
- 仙侠化、修仙化、御剑、发光法术；
- 现代汉服棚拍感；
- 明显错误的现代器物。

---

# 5. Minimal Character Bible

只做 Launch Check 所需最低一致性，不扩展成复杂 Character Bible。

## 主角：唐代中年文士

- 年龄观感：38–45 岁
- 身形：偏瘦但有力量感
- 脸型：清瘦、颧骨略明显、自然短须
- 头发：黑发束起，整洁但不精致
- 服装：灰白 / 青灰色唐代文士袍服，宽袖，材质为天然织物，不华丽
- 气质：豪放不是疯癫；有醉意但眼神清醒、骄傲、有生命力
- 禁止：浓妆、偶像脸、白发仙人、夸张长须、华丽金甲

## Character Reference Prompt

> 唐代中年男性文士，约四十岁，清瘦但有力量感，黑发束起，自然短须，真实亚洲男性面部结构，青灰与灰白色天然织物唐代文士袍服，宽袖，衣料有真实褶皱和轻微磨损，神态豪放、自信、略有醉意但眼神清醒，电影级写实摄影，真实皮肤纹理，低饱和暖色烛光，非明星脸，非仙侠，非游戏角色，9:16。

---

# 6. Minimal Visual Bible

关键词：

> **唐代写实电影感 / 黄河与山势的宏大尺度 / 暖烛光宴饮 / 低饱和金褐色 / 月光冷暖对比 / 真实材质 / 克制而豪迈。**

统一要求：

- 真实摄影质感优先于 CG 炫技；
- 不追求“满屏古风元素”；
- 不使用饱和金色宫殿；
- 人物镜头以 35mm / 50mm 电影摄影感为主；
- 大景以 20–28mm 广角感为主；
- 景深自然，不做过度虚化；
- 夜景必须保留暗部，不做短视频式过曝提亮。

Negative Visual Direction：

> no xianxia, no fantasy magic, no glowing aura, no anime, no game CGI, no celebrity face, no modern costume studio, no plastic skin, no oversaturated gold, no floating text, no generated Chinese characters, no extra fingers, no deformed hands, no duplicate people.

---

# 7. 30 秒脚本

## 旁白终稿

**0–6s**  
“君不见，黄河之水天上来，奔流到海不复回。”

**8–14s**  
“人生得意须尽欢，莫使金樽空对月。”

**16–22s**  
“天生我材必有用，千金散尽还复来。”

**25–30s**  
“与尔同销——万古愁。”

原则：

- 不全文朗诵；
- 不解释诗意；
- 中间给画面和声音留呼吸；
- “万古愁”前留约 0.3–0.5 秒停顿。

---

# 8. 六镜头 Storyboard

| Shot | 时间 | 画面 | 旁白 / 声音 | 核心验收 |
|---|---:|---|---|---|
| S1 | 0–5s | 极远景，云层裂开，黄河从群山之间奔涌而来，镜头快速向下俯冲接近水面 | 河水轰鸣；旁白“君不见…” | 第一秒必须有尺度感，不像风景壁纸 |
| S2 | 5–9s | 低机位贴水追随激流，最后由飞溅水雾遮挡转场到夜色中的宴饮空间 | 河声渐退，风声进入 | 转场自然，无明显 AI 跳帧 |
| S3 | 9–14s | 中近景，主角坐在临河高台宴席边，抬眼看月，端起酒杯但不夸张仰饮 | “人生得意须尽欢……” | 脸、手、酒杯必须正常 |
| S4 | 14–19s | 侧面中景，主角起身，宽袖掠过前景，镜头小幅环绕；朋友只做模糊陪衬 | 酒杯轻碰、低频鼓点增强 | 主角身份与 S3 基本一致 |
| S5 | 19–25s | 主角走到栏边，背后是江河和远山，风吹衣袖；镜头由侧后方推到半侧脸 | “天生我材必有用……” | 情绪从纵酒转为自信，不做醉态喜剧 |
| S6 | 25–30s | 月下大远景，主角与宴席成为小比例剪影，河流向远处消失，最后缓慢停住 | “与尔同销——万古愁。”；音乐收束 | 结尾要留余味，不做大字炸屏 |

---

# 9. 关键帧 Prompt

## KF1 / S1 黄河

> 9:16 vertical cinematic live-action frame, colossal Yellow River rushing through towering northern Chinese mountains under storm-broken clouds, late afternoon turning toward dusk, immense natural scale, realistic sediment-colored water, low camera perspective, wind and mist, restrained color palette, photorealistic landscape cinematography, 24mm wide-angle feeling, no fantasy, no text, no buildings dominating the frame.

## KF2 / S3 主角宴饮

> 9:16 vertical cinematic live-action frame, original Tang-dynasty middle-aged Chinese poet at a simple riverside terrace banquet at night, around forty years old, lean face, short natural beard, tied black hair, muted blue-gray and off-white wide-sleeved robe, holding a bronze or ceramic wine cup, warm candlelight on face, cool moonlight from background, realistic skin, subtle drunken warmth but clear eyes, 50mm lens feeling, shallow but natural depth of field, historically grounded props, no celebrity likeness, no xianxia, no text.

## KF3 / S5 栏边

> 9:16 vertical cinematic live-action frame, same Tang-dynasty poet standing beside a wooden riverside railing at night, wind lifting wide sleeves, dark river and mountains behind him, cool moonlight outlining shoulders and hair, warm banquet glow behind, proud calm expression, side profile three-quarter view, realistic fabric and skin, 35mm cinematic framing, restrained heroic mood, no fantasy, no glowing effects, no text.

---

# 10. 推荐生成路线

## Route A：Seedance 2.5 单次 30 秒多镜头生成

优先尝试，原因：Launch Check 的目标就是验证最短生产链路。

输入建议：

- Character Reference：KF2 人物参考；
- Scene Reference：KF1 / KF3；
- 9:16；
- 30 秒；
- 要求环境音，不生成对白、不生成字幕、不生成 BGM；
- 后期统一旁白、音乐和字幕。

### Timestamp Prompt

> 9:16 vertical cinematic live-action short film, realistic Tang-dynasty visual world, restrained and poetic, no fantasy, no generated text, no subtitles, no dialogue. Keep the same middle-aged Chinese poet consistent across all character shots: lean face, short natural beard, tied black hair, muted blue-gray and off-white wide-sleeved robe. Natural physics, realistic skin and fabric. Generate only environmental sound such as river, wind, distant cups; no spoken dialogue and no music.
>
> 0–5s: Extreme wide aerial-scale view of the Yellow River bursting through towering mountains beneath broken clouds. The camera dives downward toward the rushing sediment-colored water, emphasizing overwhelming scale and speed.
>
> 5–9s: Cut to a very low tracking shot just above the river surface, moving with the current. Water spray briefly fills the lens and creates a natural visual transition into night.
>
> 9–14s: Medium close-up at a simple riverside banquet terrace at night. The poet looks toward the moon, then slowly lifts a wine cup. Warm candlelight on his face contrasts with cool moonlight behind him. His expression is joyful but controlled, not comedic.
>
> 14–19s: Medium side shot. The poet rises from his seat; his wide sleeve passes naturally in front of the camera as a soft occlusion. The camera makes a small smooth arc around him. Other guests remain secondary and slightly out of focus.
>
> 19–25s: The poet walks to the wooden railing. Wind catches his sleeves. Camera pushes from rear three-quarter view toward a restrained side profile. Dark river and mountains fill the background. His expression changes from warmth to calm confidence.
>
> 25–30s: Wide moonlit final shot. The poet and banquet are small silhouettes against the river and mountains. The camera slowly pulls back and settles. End quietly with lingering wind and river ambience.

### Route A PASS 条件

- 6 个镜头中至少 4 个可直接使用；
- S3、S5 人物必须基本一致；
- 不出现不可修复的手部 / 面部畸形；
- 转场不要求完美，但不能明显“模型抽风”；
- 最终只需要通过剪辑修短和调色，不需要逐帧修脸。

若不满足，**不要连续烧钱重试整条**，切 Route B。

---

## Route B：6 个独立镜头 + 后期剪辑

适用于：单次 30 秒生成在人物一致性、动作或转场上失败。

原则：

- S1/S2 可用 Seedance 2.5 或 Wan 3.0 文生视频；
- S3/S4/S5 必须统一使用同一人物参考图做 I2V / R2V；
- S6 可由 KF3 或独立大景参考生成；
- 每镜头控制在 4–6 秒；
- 每个镜头最多先做 2 次正式尝试，再决定是否换模型 / 简化动作。

Wan 3.0 可作为 Route B 备选，优先用于：大景、氛围、需要 30 秒以内多模态参考或原生音视频能力的镜头。Launch Check 阶段不同时测试太多模型，只有当前模型明显失败才切换。

---

# 11. 单镜头 Video Prompts

## S1

> 9:16 photorealistic cinematic shot, immense Yellow River surging through giant northern Chinese mountains, broken storm clouds, late dusk, camera begins extremely wide then dives rapidly toward the river, realistic muddy water, spray and wind, huge spatial scale, physical camera movement, restrained colors, no fantasy, no text.

## S2

> 9:16 low-altitude cinematic tracking shot only a few centimeters above a violently rushing river, camera moving downstream with the current, water spray striking near the lens, strong forward motion, realistic water physics, the final second becomes almost fully obscured by mist and spray to create a natural transition, no people, no text.

## S3

> Use the provided character reference exactly for identity, age, face, hair, beard and clothing. 9:16 cinematic medium close-up at a simple Tang-dynasty riverside banquet terrace at night. The poet looks upward toward the moon, then slowly raises a small wine cup to chest level. Warm candlelight on the face, cool moonlight behind, subtle natural expression, realistic hands and cup, no exaggerated drinking, no dialogue, no text.

## S4

> Same character reference and same clothes. 9:16 medium side shot. The poet calmly rises from the banquet seat. His wide sleeve crosses the foreground naturally and briefly occludes the lens while the camera makes a gentle 30-degree arc. Background guests remain soft and secondary. Realistic body motion and fabric physics, no dancing, no drunken stumbling, no text.

## S5

> Same character reference and same clothes. 9:16 cinematic three-quarter rear shot turning into restrained side profile. The poet walks two steps to a wooden riverside railing, pauses, wind lifts his wide sleeves and hair slightly, moonlit river and dark mountains behind him, warm banquet lights far behind, expression proud and calm, camera slowly pushes in, realistic movement, no fantasy glow, no text.

## S6

> 9:16 wide cinematic night landscape. A small riverside Tang-dynasty banquet terrace beneath a bright but realistic moon. The same poet stands near the railing as a small silhouette, river winding into dark distant mountains, lanterns warm and subtle, camera slowly pulls backward, quiet wind moving fabric and trees, contemplative ending, no text, no fantasy.

---

# 12. 声音设计

## 12.1 旁白

优先：成熟男声，35–50 岁听感。

要求：

- 不做“央视朗诵”；
- 不做仙侠配音；
- 不喊；
- 前两句有空间感，中段更昂扬，最后压下来。

建议语速：约 3.5–4.2 字 / 秒，关键句留停顿。

## 12.2 环境音

S1–S2：河水 + 风。  
S3–S4：室外宴席低环境声、杯碰声，不要嘈杂酒楼。  
S5–S6：风声重新回来，河声很远。

## 12.3 音乐

结构：

- 0–8s：低频持续音 + 极轻鼓点；
- 9–18s：加入弦乐 / 箫类长音，不抢旁白；
- 19–25s：情绪微微抬升；
- 25–30s：突然减少层次，只留低频与余音。

音乐必须来自：

- 平台确认可用音乐库；或
- 明确授权素材；或
- 商用条款允许的 AI 生成音乐。

Launch Check 不为了“名曲氛围”使用来源不明古风 BGM。

---

# 13. 剪辑与字幕

## 剪辑

- 目标成片：29–31 秒；
- S1 第一帧直接进大景，不加品牌动画；
- 不使用复杂转场模板；
- 优先硬切、遮挡转场和声音桥；
- 画面有轻微速度问题可局部变速，但不能把 AI 运动错误藏在快剪里；
- 结尾至少留 0.6 秒视觉停顿。

## 字幕

- 白色或浅灰简洁中文字体；
- 一次最多两行；
- 不把整段古诗铺满屏幕；
- 字幕只展示正在朗诵的句子；
- 关键字不做花哨放大动画；
- 避开平台 UI 的底部与右侧区域。

最终片尾可在最后 0.8 秒小字出现：

> 《将进酒》｜李白  ·  课本电影院

AI 生成内容的标识按发布当日平台与法规要求另行统一执行，不以片尾小字替代平台声明。

---

# 14. 封面与标题

## 主封面

画面：S5 主角侧脸 / 背影 + 月夜江河，人物占画面约 35%。

封面主文案：

> **如果《将进酒》被拍成电影**

小字：

> 课本电影院 01

不要用“AI还原李白真实现场”“100%复原唐朝”等误导表达。

## 主标题

> 如果《将进酒》被拍成电影，会是什么样？

备用标题：

- 背了这么多年《将进酒》，第一次看见它的画面
- “天生我材必有用”——如果这一句真的发生在你眼前

---

# 15. 发布文案

主文案：

> 我们想做一件事：把那些背过很多次的文字，真正拍成画面。  
> 第一篇，《将进酒》。  
> 你下一篇最想看哪一篇？

标签不要堆叠，建议控制在 3–5 个相关标签；按发布平台当日实际推荐与可用标签选择。

评论区 CTA 需要单独编码，不能把用户回答“下一篇想看什么”全部当成自然催更信号。

---

# 16. Launch Check 验收表

以下 8 项全部通过，才允许作为正式 Sample 发布：

- [ ] 30 秒左右，叙事与情绪完整；
- [ ] 无明显脸部 / 手部畸形；
- [ ] S3 / S5 人物基本可认作同一人；
- [ ] 无影响观看的 AI 伪影与跳帧；
- [ ] 字幕、旁白、音乐达到正常发布质量；
- [ ] 普通观众不看说明也能感受到“豪迈 → 自信 → 万古愁”的情绪变化；
- [ ] 素材、音乐、音色版权边界明确；
- [ ] AI 生成内容平台声明与适用标识流程已完成。

只要其中任一关键项失败，不为凑 Sample #1 强行发布。

---

# 17. 成本与工时记录

| 项目 | 实际值 |
|---|---|
| 脚本工时 | |
| 分镜 / Prompt 工时 | |
| 参考图生成次数 | |
| 参考图现金成本 | |
| 视频总生成镜头 / 次数 | |
| 最终采用镜头数 | |
| 有效镜头率 | |
| 视频生成现金成本 | |
| 配音成本 | |
| 音乐 / 音效成本 | |
| 剪辑工时 | |
| 总人工工时 | |
| 总现金成本 | |
| 最终可用秒数 | |
| CPUS | |
| 脚本开始 → 发布日历时间 | |

特别记录 Route A：

- 整条 30 秒首次生成是否可用；
- 可直接使用秒数；
- 人物一致性问题；
- 是否因整条失败而切 Route B。

---

# 18. Sample #1 发布后记录

按 Phase 1 统一口径记录：

- 2h / 24h / 72h 播放 / 曝光；
- 前 3 秒留存；
- 平均观看时长；
- 平均观看比例；
- 完播率；
- 点赞率；
- 分享率；
- 收藏率；
- 评论率；
- 关注转化；
- 主页访问；
- 主动点题；
- 主动催更 / 要完整版；
- CTA 回答；
- “这是 AI 吗 / AI 好厉害”等猎奇评论占比；
- 纠错 / 负面 AI 反馈。

Sample #1 属于 Calibration Sample，不单独决定 Phase 1 PASS / FAIL。

---

# 19. Stop Rules

Launch Check 阶段不要掉入以下陷阱：

1. 整条 30 秒生成连续失败时，仍然无限重试 Route A；
2. 为了人物 100% 一致耗费大量时间逐帧修脸；
3. 在第一条片里同时测试 3 个视频模型、3 种配音和 3 种剪辑风格；
4. 因为《将进酒》“很重要”而做成 2 分钟；
5. 第一条数据一般就改账号名和品牌定位；
6. 第一条数据好就宣布 History AI 模式成立。

Launch Check 的价值只有两个：

> **证明生产链能跑通；拿到第一条真实市场数据。**

做到这两个目标，就立即进入 Batch 1 其余四个题材。
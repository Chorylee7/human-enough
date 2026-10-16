# 日常不烧心 · 漫画生成记录

生成日期：2026-10-16。工具：内置 imagegen；未使用 API CLI。五张图片均为 AI 生成的原创虚构情景插图，不是真实个案影像。图片仅压缩呈现故事，适用边界和资料来源以[故事正文](../../stories/日常不烧心-第一辑.md)为准。原创插图中本项目有权许可的部分沿用仓库 CC BY-SA 4.0。

第一张为已确认的画风样稿，其余四张以它作为画风和版式参考。第 2–4 张各生成一次；第 5 张原请求长时间未返回，因此额外重试一次，采用重试成图，并终止等待原请求。五张成图均已检查主要台词与情节。精确 token 与费用未由工具返回。

## 01｜默认司机

文件：`01-default-driver.png`

```text
Use case: illustration-story
Asset type: Chinese everyday-life four-panel comic illustration, preview sample for 人生不烧心指南.
Primary request: Create a polished, warm, quiet 2x2 four-panel comic on an ivory paper page, portrait-ish composition, generous margins, hand-drawn editorial cartoon, soft colored-pencil and gouache texture, fine dark brown lines, muted terracotta and sage accents. Adults with natural expressive gestures, charming simplified faces, no childish chibi proportions. Consistent protagonist: young adult Chinese woman with short dark bob, round glasses, sage cardigan and cream shirt. Her friend has shoulder-length dark hair and a terracotta jacket.
Title at top exactly: “帮过忙，就成了默认司机？”
Panel 1 top left: daytime, protagonist voluntarily helps friend carry moving boxes beside a small parked car; both cooperate, modest smiles. Small caption exactly “搬家那天，帮了两趟。”
Panel 2 top right: two small visual vignettes within this panel, helping load a flat furniture box into car then carrying a box of old books for recycling; calendar subtly suggests different weekends, no calendar text. Caption exactly “后来，又帮了几次。”
Panel 3 bottom left: Friday evening at home, protagonist on sofa looking at phone, a slightly hesitant expression. One clear speech balloon from phone exactly “明天九点来接我？” Small caption exactly “可这次，我还没答应。”
Panel 4 bottom right: same protagonist at home, phone placed beside her, tea and a book, shoulders relaxed but slightly sheepish expression, not ecstatic or triumphant. Her outgoing message in clear readable balloon exactly “明天想休息，这次不能帮忙了。” Small caption exactly “以后用车，等我确认再安排。”
Footer beneath panels exactly “帮过几次，不等于答应每一次。”
Tiny footer exactly “虚构情景 · 日常不烧心”
Text: Render all specified simplified Chinese text accurately, clean legible hand-lettered print, spacious balloons; no additional dialogue or English.
Constraints: four distinct panels with clear reading order, consistent characters, all text within generous safe margins. Support ordinary boundaries, do not depict friend as villain, no angry conflict, no diagnostic labels, no promise of total emotional relief. No logos or watermarks.
```

## 02-accepting-no｜别人也可以说“不行”

文件：`02-accepting-no.png`

参考图：`01-default-driver.png`（只参考画风和版式）。

```text
Use case: illustration-story. Generate a NEW four-panel Chinese everyday-life comic, using the attached image ONLY as style/layout reference, not as a story to reproduce. Match its warm ivory paper, muted terracotta and sage colors, fine brown hand-drawn lines, colored pencil/gouache texture, adult editorial cartoon proportions, 2x2 panels, portrait 1024x1536 page, generous safe margins and legible simplified Chinese lettering. Four clear panels in reading order. New characters appropriate to this story, consistent within all panels. Everyday emotions, no villain, no magical cure, no triumphant ending. Render ONLY the specified Chinese text accurately. Each panel has little text. Footer small print exactly “虚构情景 · 日常不烧心”.
Title exactly “别人也可以说“不行””.
Story: Protagonist Ahe: adult Chinese woman, dark ponytail, terracotta sweater. Panel 1 at home inviting a friend to exhibition by phone, hopeful. Her balloon “周六一起看展吗？” Panel 2 phone reply balloon “这周想自己待着，就不去了。” Ahe looks disappointed, not furious. Panel 3 she pauses with phone, small thought balloon “我能拒绝，她也可以。” Panel 4 still slightly wistful, she sits with exhibition brochure and checks travel route, not already meeting anyone. Outgoing balloon “有点遗憾，那我这次自己去。” No cheerful miracle. Bottom takeaway exactly “接受拒绝，也允许自己失落。”
```

## 03-received-is-not-approval｜“收到”，还不是确认

文件：`03-received-is-not-approval.png`

参考图：`01-default-driver.png`（只参考画风和版式）。

```text
Use case: illustration-story. Generate a NEW four-panel Chinese everyday-life comic, using the attached image ONLY as style/layout reference, not as a story to reproduce. Match its warm ivory paper, muted terracotta and sage colors, fine brown hand-drawn lines, colored pencil/gouache texture, adult editorial cartoon proportions, 2x2 panels, portrait 1024x1536 page, generous safe margins and legible simplified Chinese lettering. Four clear panels in reading order. New characters appropriate to this story, consistent within all panels. Everyday emotions, no villain, no magical cure, no triumphant ending. Render ONLY the specified Chinese text accurately. Each panel has little text. Footer small print exactly “虚构情景 · 日常不烧心”.
Title exactly ““收到”，还不是确认”.
Story: Protagonist Xiaolin: adult Chinese woman, shoulder-length dark hair, sage shirt, working at desk with laptop and phone. Panel 1 outgoing phone message “这个方向可以吗？” reply “收到。” Panel 2 worried Xiaolin with several blank draft papers, thought balloon “是不是对我不满意？” Panel 3 she writes two distinct lines on paper exactly “事实：收到，尚未确认。” and “担心：他对我不满意。” Panel 4 she sends a concise work clarification, balloon “方向能开写吗？请明早十点前确认。” Small caption in panel exactly “未回复，再联系协商进度。” She sets reminder then turns to another task; no indication work is approved, no automatic approval at deadline. Bottom takeaway exactly “问清安排，暂放猜测。”
```

## 04-finish-the-email｜还在反复改“谢谢”？

文件：`04-finish-the-email.png`

参考图：`01-default-driver.png`（只参考画风和版式）。

```text
Use case: illustration-story. Generate a NEW four-panel Chinese everyday-life comic, using the attached image ONLY as style/layout reference, not as a story to reproduce. Match its warm ivory paper, muted terracotta and sage colors, fine brown hand-drawn lines, colored pencil/gouache texture, adult editorial cartoon proportions, 2x2 panels, portrait 1024x1536 page, generous safe margins and legible simplified Chinese lettering. Four clear panels in reading order. New characters appropriate to this story, consistent within all panels. Everyday emotions, no villain, no magical cure, no triumphant ending. Render ONLY the specified Chinese text accurately. Each panel has little text. Footer small print exactly “虚构情景 · 日常不烧心”.
Title exactly “还在反复改“谢谢”？”.
Story: Protagonist Xiaozhou: adult Chinese man with short dark hair, round glasses, cream shirt, terracotta overshirt in modest home office. Panel 1 checks meeting notification on laptop; paper checklist legibly shows “时间 ✓ 地点 ✓ 附件 ✓ 参会人 ✓”, caption “必要信息，都核对过了。” Panel 2 hesitates over screen with two short options “谢谢大家” and “感谢各位支持”, clock suggests time wasted, thought bubble “会不会不够专业？” Panel 3 chooses a polite ending and presses send, caption “选一句清楚礼貌的，发出。” Panel 4 walks to next task with lingering little worry, paper note on desk “会前按计划查看回复”, caption “担心还在，先做下一件。” Bottom takeaway exactly “核对完成，可以先提交。” Tiny second footer above fiction footer exactly “普通内部通知示例；专业复核仍按流程。”
```

## 05-saying-a-preference｜这次，我没有说“随便”

文件：`05-saying-a-preference.png`

参考图：`01-default-driver.png`（只参考画风和版式）。

```text
Use case: illustration-story. Generate a NEW four-panel Chinese everyday-life comic, using the attached image ONLY as style/layout reference, not as a story to reproduce. Match its warm ivory paper, muted terracotta and sage colors, fine brown hand-drawn lines, colored pencil/gouache texture, adult editorial cartoon proportions, 2x2 panels, portrait 1024x1536 page, generous safe margins and legible simplified Chinese lettering. Four clear panels in reading order. New characters appropriate to this story, consistent within all panels. Everyday emotions, no villain, no magical cure, no triumphant ending. Render ONLY the specified Chinese text accurately. Each panel has little text. Footer small print exactly “虚构情景 · 日常不烧心”.
Title exactly “这次，我没有说“随便””.
Story: Protagonist Aning: adult Chinese woman with short dark bob, mustard cardigan, cream shirt. Three adult friends planning dinner via phone. Panel 1 split phone conversation, one friend asks “晚上吃什么？” other replies “随便。” Aning holds back, thought balloon “其实，我想吃面。” Panel 2 she shares own preference, outgoing balloon “想吃面，人均五十，你们呢？” Panel 3 the two friends respond neutrally, balloons “我想吃火锅。” and “五十有点超预算。” Aning listens with a normal thoughtful face, no resentment. Panel 4 all three share inexpensive home-style Chinese dishes and rice at a small local restaurant, absolutely no noodles and no hotpot, caption “最后，选了人均三十多的家常菜。” Aning has a small relaxed smile, not a victory pose. Bottom takeaway exactly “没吃上面，表达也没有失败。”
```


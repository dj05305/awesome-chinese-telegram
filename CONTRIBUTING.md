# Contributing

This list is short on purpose. The rules below are the reason it stays worth reading.

**TL;DR** — corrections are welcome, self-submissions are not, and pull requests against the
READMEs will be closed because those files are generated.

---

## What is welcome

- **Corrections.** Dead link, renamed channel, wrong subscriber count, wrong category,
  a description that no longer matches what the channel actually does.
- **Removal requests.** If you own a channel or group on this list and want it gone, open an
  issue and it will be removed within 7 days. No justification required, no argument.
- **Suggestions.** A community you think belongs here. Treat it as a hint, not an order —
  most suggestions get declined, and that is not personal.

## What is not welcome

- **Self-promotion.** Do not open an issue or a pull request to get your own channel listed.
  It will be closed without discussion. This is the single rule that keeps the list from
  turning into a link farm, so it is enforced without exceptions.
- **Bulk additions.** Ten entries in one issue reads as link-building, not as curation.
- **Rewrites of the summaries.** The one-line summaries are editorial. Point out a factual
  error and it gets fixed. Send your preferred marketing copy and it does not.
- **Referral links, invite links, affiliate links, redirect links.** Any of these in a report
  gets the whole report ignored.

## How to report

Open an issue. **One item per issue.** Include:

1. The entry name, or its ChanScout URL.
2. What is wrong — and a source, if the claim is factual (subscriber count, ownership,
   whether the channel is still alive).
3. What you suggest instead, if you have a preference.

### Why not pull requests

`README.md` and `README.zh-CN.md` are **generated files**. They are rebuilt from the database
every week by a scheduled job, so any edit pushed into them survives exactly until the next
refresh. The source of truth for the editorial layer is `data/overrides.json`, which is
maintainer-edited only — that is what keeps the wording consistent across 50+ entries.

This is also why the repository has no `CONTRIBUTING`-driven PR workflow: there is nothing
useful for an outside pull request to touch.

## What gets an entry in

All of the following must hold:

1. It is a **public** channel, group or bot, with a real description — not just a slogan,
   a contact address, or a wall of cross-promo links.
2. It has at least **3,000 subscribers** (channels and groups), or a non-zero monthly user
   count (bots).
3. It was re-verified within the last **30 days**.
4. It carries **no risk flag** for adult content, gambling, paid stock tips, invite-code
   resale, or proxy/VPN services.
5. It is **not a near-duplicate** of another entry from the same operator.

Meeting all five is necessary, not sufficient. The final call is editorial.

## Editorial standards

- **Facts, not adjectives.** "Posts Arch Linux testing warnings and package news" is useful.
  "The best Linux channel" is not, and gets cut.
- **Say who it is not for.** A one-line "not good for asking basic syntax questions" saves a
  reader more time than another sentence of praise.
- **No superlatives and no safety claims.** No "safest", "most trusted", "verified clean".
  Being listed says a community is public and active. It says nothing about whether its
  content is legal, accurate or safe.
- **Two sentences maximum.** If an entry needs three, it usually means the community's own
  purpose is unclear.

## Removal and dead entries

Entries are dropped when they stop meeting the criteria: channel goes private or disappears,
subscriber count falls below the threshold, the operator starts bulk-posting near-duplicates,
or verification has not succeeded for 30 days. A dropped entry returns `410` on ChanScout
rather than redirecting somewhere else.

## Disclosure

This list is maintained by [ChanScout](https://chanscout.com), which also runs a public
directory of these same channels, and every link here points to a ChanScout profile page
rather than a raw `t.me` link. That is a commercial interest, and it is disclosed here rather
than buried in the footer. The reason for the links is in the README: channel invite links rot,
profile pages do not. If that trade-off is not acceptable to you, that is a fair position —
but you should know it before contributing.

## License

List content is released under CC0-1.0 (see `LICENSE`). Channel names and descriptions remain
the property of their respective owners.

---

# 参与与纠错（中文）

这份清单故意保持简短，下面这些规矩就是它还能看的原因。

**一句话版**：欢迎纠错，不接受自助收录；README 是生成文件，往里提 PR 会被关掉。

## 欢迎的

- **纠错**：死链、改名、订阅数不对、分类放错、简介和实际内容已经对不上了。
- **下架请求**：频道/群组是你自己的，想让它在清单上消失，开个 issue 说一声就行，
  7 天内下掉，不需要理由，也不会跟你争。
- **推荐**：你觉得该收录但没收的社区。当线索看，不当指令看——大部分推荐会被拒，
  这不是针对谁。

## 不欢迎的

- **自助收录**：开 issue 或 PR 把自己的频道塞进来，一律关闭，不解释。这条是整份清单
  不变成友情链接农场的唯一保障，所以没有例外。
- **批量提交**：一个 issue 里塞十条，读起来就是做外链，不是做策展。
- **改写文案**：每条一句话的说明是编辑内容。指出事实错误我们会改；把你写好的宣传语
  发过来，我们不改。
- **推广链接**：返利、邀请码、联盟、跳转链接，出现任意一种，整份报告直接忽略。

## 怎么报

开 issue，**一个条目一个 issue**，写清三件事：

1. 条目名称，或它的 ChanScout 链接。
2. 哪里不对——涉及事实的（订阅数、归属、频道是否还活着）请给出依据。
3. 你建议改成什么（有想法的话）。

### 为什么不收 PR

`README.md` 和 `README.zh-CN.md` 是**生成文件**，每周由定时任务从数据库重新渲染。
任何直接改进这两个文件的提交，最多活到下一次刷新。编辑层的唯一真相是
`data/overrides.json`，只由维护者修改——50 多条文案的语气能保持一致，靠的就是这个。

这也是这个仓库没有 PR 流程的原因：外部 PR 没有可以动的有效位置。

## 收录门槛

以下全部满足才可能入选：

1. **公开**的频道、群组或机器人，且有真实的公开简介——不是只有一句口号、联络方式或互推链接。
2. 频道与群组订阅数不少于 **3,000**；机器人月活不为零。
3. 最近 **30 天**内完成过核验。
4. 未命中成人、赌博、荐股、邀请码转卖、机场/VPN 类风险标记。
5. 不是同一运营方批量投放的近似条目。

全满足是必要条件，不是充分条件。最终由人工判断。

## 文案标准

- **写事实，不写形容词**。「发 Arch Linux testing 预警和打包新闻」有用，
  「最好的 Linux 频道」没用，会被删掉。
- **写清楚不适合谁**。「不适合问语法入门问题」这一句，比再夸一句更能帮读者省时间。
- **不用最高级，不做安全承诺**。不写「最安全」「最优质」「已核验干净」。被收录只说明
  这个社区是公开且活跃的，不代表其内容合法、准确或安全。
- **最多两句**。超过两句，通常说明这个社区自己的定位就不清楚。

## 下架与失效

停止满足门槛的条目会被移除：转私密或消失、订阅数跌破门槛、运营方开始批量投放近似条目、
连续 30 天核验不成功。被移除的条目在 ChanScout 上返回 `410`，不会跳到别的地方。

## 利益披露

这份清单由 [ChanScout](https://chanscout.com) 维护，它本身也运营一个同类频道的公开目录，
清单里所有链接都指向 ChanScout 资料页而不是裸的 `t.me` 链接。这是商业利益，写在正文里
而不是塞在页脚。链接这么处理的理由在 README 里：邀请链接会烂，资料页不会。
如果你觉得这个取舍不能接受，那是合理的立场——但你应该在参与之前就知道。

## 许可

清单内容以 CC0-1.0 释出（见 `LICENSE`）。频道名称与简介归各自所有者。

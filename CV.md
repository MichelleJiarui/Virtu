[\](https://jobs.ebayinc.com/us/en/job/R0070834/Cloud-Platform-Security-Engineer)

Before I give you a number — what's the range eBay has in mind for this role?
中文
在我说我的期望之前——请问 eBay 这个职位的薪资范围是多少？

# eBay Interview Story Bank

---

## 0. Self-Introduction
*1 minute · Spoken*

---

### English

So, I've spent the last three and a half years at AWS helping companies
when something goes wrong with their systems.
The way I'd describe it — I'm the person they call when nobody else knows what's happening.

Over time I noticed something.
The problems that kept coming back weren't the dramatic ones.
They were small, quiet things that had been sitting there for a while —
a setting that was slightly off, a limit nobody knew existed.
And I got genuinely curious about that pattern.

That's honestly what brought me here.
I don't want to keep showing up after things break.
I want to be the person who makes sure they don't break in the first place.
**Less firefighting, more fireproofing.**

---

### 中文

我在 AWS 做了三年半，干的事说白了就是：
客户的系统出问题了，没人搞清楚为什么，我来找原因。

做久了发现一个规律——
反复出现的问题，往往不是什么大漏洞，
而是一些安静地藏在那里的小隐患。
一个没人注意的参数，一个看起来没问题的设置。
我对这类东西越来越感兴趣。

这也是我来 eBay 面试的原因。
我不想一直做那个「出了事再去修」的人，
我想做那个**「让它一开始就不出事」**的人。

---

> 💡 Pause before the last line — it's your strongest moment.
> Self-intro answers *who you are*. Story 1 answers *why here* — keep them distinct.

---

## 1. Why eBay? | Motivation
*1 minute · Spoken*

---

### English

Honestly, it comes down to something I noticed over three and a half years.

The companies that had the biggest problems weren't the ones getting attacked from outside.
They were the ones where something small had been quietly wrong for a long time —
a permission a little too wide, a rule nobody had checked in months.
Nobody saw it coming because it didn't make any noise.

That kind of problem is what I find genuinely interesting.
And at eBay, getting that stuff right actually matters.
You've got a lot of systems, a lot of people depending on them every day,
and a team that has to own the whole thing — not just one corner of it.

I've spent years being the person who shows up after something breaks.
I'm ready to be on the other side of that —
the person who set things up well enough that the break never happened.
This feels like the right place to do that.

---

### 中文

说实话，这要从我这三年半发现的一件事说起。

出问题最严重的公司，往往不是被外部攻击的那些。
而是那些有什么小东西悄悄错了很久的——
一个权限稍微宽了点，一条规则几个月没人看过。
没人提前发现，因为它不发出任何声音。

这类问题是我真正觉得有意思的。
在 eBay，把这些东西做对是真的有分量的。
这里有很多系统，很多人每天依赖它们，
团队需要对整个平台负责，不只是某个小角落。

我花了好几年做那个「出了事之后去修」的人。
我已经准备好换到另一边了——
做那个把东西设计好、让那件事根本不发生的人。
这感觉是做这件事的合适地方。

---

> 💡 Don't repeat lines from the self-intro. This one is less about you, more about *why this place specifically*.

---

## 2. Problem Solving | Finding the Hidden Problem
*STAR format*

---

| | English | 中文 |
|---|---|---|
| **Situation** | A customer's system was getting slower and slower, but every monitor showed everything was fine. Their team had spent days on it and couldn't find anything. | 客户的系统越来越慢，但所有的监控显示一切正常。他们的团队查了好几天，什么都没发现。 |
| **Task** | Find the real cause — without just telling them to spend money on bigger servers. | 找到真正的原因——不是简单地让他们花钱买更好的设备。 |
| **Action** | I worked through it piece by piece — checked the network first, then the system itself. Eventually I found a hidden limit that the system had quietly hit. It was silently turning away new connections without telling anyone. A small setting change fixed it. | 我一层一层往下查——先看网络，再看系统本身。最终发现系统悄悄触碰到了一个隐藏的上限，开始默默地拒绝新连接，却没有任何告警。改了一个设置就解决了。 |
| **Result** | Response times dropped by nearly half. The customer was delighted — and nothing new needed to be bought. | 响应速度提升了将近一半，客户非常满意——而且什么新设备都不用买。 |

---

## 3. Automation | Building a Tool to Save the Team Time
*STAR format*

---

| | English | 中文 |
|---|---|---|
| **Situation** | Every week, the same issues came in. Different customers, same problems, same checks every time. Each engineer started from scratch. It was repetitive and slow. | 每周都是同样的问题。不同的客户，同样的毛病，同样的排查流程。每个人每次都从头开始，又慢又累。 |
| **Task** | Find a way to stop doing the same thing over and over — and make it easy enough that even new team members could handle it alone. | 想办法不再重复同样的事——而且要简单到新人也能独立搞定。 |
| **Action** | I wrote a simple tool that automatically ran through all the common checks in one go. What used to take 20 minutes of manual work became a 2-minute automatic scan. I also wrote a simple guide alongside it, so people understood what was being checked and why. | 我写了一个简单的工具，把所有常见的检查一次性自动跑完。原来要手动做 20 分钟的事，变成 2 分钟自动完成。同时我写了一份简单的说明，让大家明白在查什么、为什么这么查。 |
| **Result** | The team solved cases 35% faster. New people could handle these on their own from day one. | 团队解决问题的速度提升了 35%，新人从第一天起就能独立处理这类工单。 |

---

## 4. Fast Learning | Picking Up Something New Quickly
*Spoken*

---

### English

At AWS, I was suddenly put on a team supporting clients
who were using a system I'd never worked with seriously before.

I didn't just read about it.
I set up a test environment and deliberately broke things —
pushed it to its limits, watched what happened when it failed.
I wanted to understand what it looked like under pressure,
not just when everything was going smoothly.

Then I put together what I'd learned and ran training sessions for 15 people on the team.

We ended up fixing a major performance issue for those clients.
But honestly the biggest thing I took away was this —
I don't feel like I really know something until I can explain it to someone else.
Teaching it made me understand it properly.

---

### 中文

在 AWS，我突然被安排去支持一批使用我没认真用过的系统的客户。

我没有只看文档。
我搭了一个测试环境，专门把它搞崩——
把它推到极限，看它撑不住的时候会发生什么。
我想知道它在压力下是什么样子，而不只是一切顺利时的状态。

之后我把学到的整理成资料，给团队 15 个人做了培训。

最终我们帮那些客户解决了一个很大的性能问题。
但我真正带走的收获是——
只有能讲给别人听，我才觉得自己真的学会了。
教别人这件事，让我把它彻底搞懂了。

---

> 💡 *"I don't feel like I really know something until I can explain it"* — say it like you mean it, not like you rehearsed it.

---

## 5. Conflict Resolution | Getting a Team Unstuck
*Spoken*

---

### English

At my previous job, our team got stuck in a long argument
about which direction to go with a big project.
Two sides, strong opinions, and nothing was moving forward.

Instead of joining the debate, I suggested we just test both options.
Get real data — actual numbers on speed, cost, and what happens when things go wrong.
Then put it in front of everyone and let the results speak.

Once people could see the comparison clearly, the argument stopped.
We moved forward, finished the project on time,
and actually ended up saving the company 30% on running costs.

What I learned from that is —
when a team is stuck, more opinions don't help.
What helps is something concrete that everyone can look at together.

---

### 中文

在上一家公司，团队在一个大项目的方向上争了很久。
两种方案，各有立场，项目完全卡住了。

我没有继续加入争论，而是提议直接测试两个方案。
拿到真实数据——实际的速度、成本，以及出问题时会怎样。
然后把结果摆在所有人面前，让数据说话。

大家看到对比之后，争论停了，项目往前推了。
最终按时完成，公司的运营成本还降了 30%。

我从这件事里学到的是——
团队卡住的时候，多一个意见没用，
需要的是一个大家都能一起看的东西。

---

## 6. Ownership | Taking Charge When Nobody Else Did
*STAR format*

---

| | English | 中文 |
|---|---|---|
| **Situation** | A customer's system went down completely. Different teams each said their part was fine — and nobody was taking responsibility. The customer was losing money every minute. | 客户系统完全瘫痪。各个团队都说自己这边没问题，没有人出来负责。客户每分钟都在亏损。 |
| **Task** | Stop waiting for someone else to take ownership. Look at the whole picture myself. | 不再等别人来负责，自己去看整体情况。 |
| **Action** | I traced the problem step by step, from one end of the system to the other. I eventually found a small configuration mistake that was sitting in the gap between two teams — which is exactly why nobody had caught it. Each team had only looked at their own part. | 我从头到尾一步步追查，最终发现一个小的配置错误，恰好落在两个团队之间的空白地带——这正是没人发现它的原因。每个团队只看了自己负责的部分。 |
| **Result** | System came back online. I didn't just fix it for that moment — I made sure the same gap couldn't cause the same problem again. | 系统恢复上线。我没有只做临时修复——而是确保同样的漏洞不会再次造成同样的问题。 |

---

## 7. Scalability | Doing in 20 Minutes What Used to Take 2 Hours
*Spoken*

---

### English

Before big shopping events, our clients needed us to check
that all their systems were ready — nothing misconfigured, nothing about to run out.
Some of these clients had hundreds of machines.
Going through them one by one took two hours every time.

My team and I built a simple tool that checked all of them at once.
One button, everything checked, done in twenty minutes.

But the part I actually cared about wasn't the time saving.
It was that we could finally look a client in the eye
before their biggest day of the year and say,
"You're good. Everything's checked. You're ready."
That's hard to say with confidence when you've spent two hours clicking through things manually.

---

### 中文

每逢大促活动之前，客户都需要我们确认他们所有的系统都准备好了。
有些客户有几百台机器，一台一台检查要花两个小时。

我和团队做了一个简单的工具，把所有机器一次性全部检查完。
一个操作，全部搞定，二十分钟以内。

但我真正在意的不是省了时间。
而是我们终于可以在客户一年最重要的日子前，
认真地告诉他们：
「没问题，全检查过了，你们可以上了。」
靠手动一台台点的时候，这句话是说不出口的。

---

> 💡 The last two lines are your closer — slow down, say them like you actually believe them.

---

## 8. Escalation | Knowing When to Ask for Help
*STAR format*

---

| | English | 中文 |
|---|---|---|
| **Situation** | A customer kept losing their connection randomly. On the surface it looked like a small, temporary glitch — the kind of thing that sometimes just goes away on its own. | 客户一直随机断线。表面上看像是小问题，那种有时候等一等自己就好了的情况。 |
| **Task** | Figure out quickly — is this something I can fix, or is it something deeper that needs to go to another team? Getting it wrong either way wastes hours. | 快速判断——这是我能修的，还是需要交给其他团队的深层问题？判断错了，两边都会浪费几个小时。 |
| **Action** | I spent 30 minutes checking everything I could access — ruled out the common causes one by one. When I hit something I couldn't explain with what I had access to, I didn't keep guessing. I wrote down exactly what I'd checked and what I'd found, and handed it straight to the right team. | 我花了 30 分钟把我能查的都查了——逐一排除常见原因。当我遇到一个用手头权限解释不了的问题时，我没有继续猜。我把查过的内容和发现的情况写清楚，直接交给了对应的团队。 |
| **Result** | Because I gave them a clear handoff instead of just "something's wrong," they fixed it in 2 hours. The customer appreciated that we were honest and didn't waste their time. | 因为我给的是清晰的交接，而不是一句"有问题"，他们 2 小时内就解决了。客户很感激我们的坦诚，没有浪费他们的时间。 |

---

## 9. Mentoring | Making the Whole Team Better
*Spoken*

---

### English

At AWS, the same problems kept showing up week after week.
Different customers, but the same root causes every time.
And whoever picked up the ticket started from scratch.
It was tiring, and it felt like a waste.

So I wrote a simple guide — the most common scenarios, step by step,
written so that someone brand new to the team could follow it on their own.
Then I ran a few sessions with the whole team, walking through real examples.
Not theory. Actual cases we'd handled.

Resolution time went down 35%.
New people stopped needing to ask for help on these cases.
The guide ended up being used when new people joined the team.

The thing I'm most proud of isn't the numbers though.
It was something small that took about two weeks to put together —
and it's still helping people long after I stopped thinking about it.
That's the kind of work I find most satisfying.

---

### 中文

在 AWS，同样的问题每周都在重复出现。
不同的客户，同样的根本原因，每次接单的人都从头开始查。
很累，也觉得有点浪费。

于是我写了一份简单的指南——最常见的场景，一步一步列清楚，
写法是让一个刚加入团队的人也能独立跟着做。
然后给全团队做了几次培训，讲的是我们真实处理过的案例，不讲理论。

解决问题的速度提升了 35%，新人不再需要为这类问题向别人求助。
这份指南后来成了新人入职的参考材料。

但我最在意的不是这些数字。
而是一件花了大概两周做出来的小东西，
在我不再想着它之后，还在持续帮到别人。
这是让我觉得最有意义的那种工作。

---

> 💡 Don't rush the last paragraph — it's the most human thing you say in the whole interview.

---

## Quick Reference

| HR asks... | Tell... |
|---|---|
| Tell me about yourself | Story 0 — Self-Introduction |
| Why do you want this job | Story 1 — Why eBay |
| Describe a problem you solved | Story 2 — Finding the Hidden Problem |
| Time you built something to save time | Story 3 — Building a Tool |
| How do you learn new things | Story 4 — Fast Learning |
| Time you disagreed with the team | Story 5 — Getting a Team Unstuck |
| Time you went above and beyond | Story 6 — Taking Ownership |
| Example of working under pressure | Story 7 — 20 Minutes Not 2 Hours |
| Time you asked for help | Story 8 — Knowing When to Escalate |
| Time you helped someone grow | Story 9 — Making the Team Better |

---


=====================
# eBay Interview Story Bank
### Cloud Platform Security Engineer · Dublin, Ireland

---

## 0. Self-Introduction
*Format: Spoken script · 1 min*

---

### English

**Hook**
So, I've spent the last three and a half years at AWS as a Cloud Support Engineer.
The way I'd describe the job is — when a company's system is broken and nobody knows why,
I'm the one who goes in and figures it out.
Linux internals, networking, IAM issues, caching layers — that's my day to day.

**Why eBay**
Over time I noticed something. The problems that kept coming back weren't the big dramatic ones.
They were the quiet ones — a permission that was slightly too wide, a kernel limit nobody knew existed,
a config that looked fine until it really wasn't.
And I got genuinely curious about that.

**Pivot**
That's honestly what brought me to eBay.
I want to stop being the person who shows up after things break,
and start being the person who makes sure they don't break in the first place.
**Less firefighting, more fireproofing.**

---

### 中文

**开场**
我在 AWS 做了三年半的云技术支持工程师。
简单说，就是客户的系统出问题了、没人知道为什么，然后我来找原因。
Linux 内核、网络、IAM 配置、缓存层——这些是我每天打交道的东西。

**为什么是 eBay**
做久了之后我发现，反复出现的问题其实都不是什么大漏洞——是那些安静的隐患。
权限范围稍微宽了一点，一个没人注意的内核参数，一个看起来没问题的配置。
我对这类问题越来越感兴趣。

**转变**
这也是我来 eBay 面试的原因。
我不想一直做那个「出了事再去修」的人，
我想做那个**「让它一开始就不出事」**的人。

---

> 💡 Pause after *"figures it out"* — let it land.
> Slow down on **"Less firefighting, more fireproofing"** — it's your closer.

---

## 1. Problem Solving | Linux Kernel Diagnosis
*Format: STAR table · Technical*

---

| | English | 中文 |
|---|---|---|
| **Situation** | A customer's production system was collapsing — slow responses, but every dashboard showed green. Their team had no idea where to look. | 客户系统响应越来越慢，但所有监控面板显示正常，他们的团队完全找不到方向。 |
| **Task** | Find the real cause. No guessing, no "just buy bigger servers." | 找到真正的原因。不靠猜测，也不建议客户花冤枉钱升级硬件。 |
| **Action** | I worked through it layer by layer. First ruled out the network by checking internal vs. external traffic. Then moved to the OS — checked `dmesg` logs and found it: repeated "Too many open files" errors. The kernel had hit its file descriptor limit (`ulimit -n`) and was quietly refusing to open new sockets. Nobody had noticed because there was no loud alarm — just silent failures stacking up. I raised the limit and synced it with Redis `maxclients`. | 我逐层排查。先对比内外网流量排除网络问题，再看系统层——查 `dmesg` 日志发现大量"Too many open files"报错。内核达到了文件描述符上限，悄悄拒绝新连接，没有任何明显告警，只是故障在累积。我调高了限制，并与 Redis 的 `maxclients` 配置对齐。 |
| **Result** | Latency dropped 45%, memory usage fell 30%. Customer gave us a 5-star rating. No new hardware needed. | 延迟降低 45%，内存占用减少 30%，客户给了五星好评，没花一分钱买新设备。 |

---

## 2. Automation & Tooling | Security Diagnostic Script
*Format: STAR table · Technical*

---

| | English | 中文 |
|---|---|---|
| **Situation** | Every week, the same tickets. EC2 connection failures, RDS login errors — almost always caused by a wrong Security Group or an IAM policy that was slightly off. Every engineer was starting from scratch each time. | 每周都是同样的工单。EC2 连不上、RDS 登录失败——几乎都是安全组配错或 IAM 权限有点偏差。每个人每次都从零开始排查。 |
| **Task** | Stop wasting time on the same checks. Build something the whole team — including new people — could just run. | 不要再浪费时间重复同样的检查。做一个工具，让整个团队——包括新人——都能直接用。 |
| **Action** | I wrote a Python script that automatically checks Security Groups, IAM permission boundaries, and the most common connection error patterns — 15 scenarios in one run. What used to take 20 minutes of manual clicking became a 2-minute scan. I also wrote a Diagnostic Playbook alongside it, so people understood what the script was actually checking and why. | 我写了一个 Python 脚本，自动检查安全组、IAM 权限范围和最常见的连接报错模式——15 种场景一次跑完。原来要手动点 20 分钟的检查，变成 2 分钟跑完。我还同步写了一份诊断手册，让大家明白脚本在查什么、为什么这么查。 |
| **Result** | Team resolution time dropped 35%. New engineers could handle these cases on their own from day one. The script became a standard first step before any investigation. | 团队结案时间缩短 35%。新人从第一天起就能独立处理这类问题。这个脚本成了所有排查工作的标准第一步。 |

---

## 3. Fast Learning | Picking Up a New Technology Fast
*Format: Spoken script · Soft*

---

### English

**What happened**
At AWS, I was suddenly put on support for a group of high-traffic clients
who were all running Redis as their caching layer.
I'd never worked with it seriously in a production security context before.

**What I did**
I didn't just read the docs.
I set up a test environment and broke things on purpose —
exhausted the connection pool, pushed the memory limits, triggered auth failures.
I wanted to see what Redis actually looked like when it was about to fall over,
not just what it looked like when everything was fine.
Then I wrote up what I found and ran training sessions for 15 people on the team.

**What came out of it**
We fixed the architecture for those clients and closed a 60% performance gap.
But honestly the bigger thing was that teaching others made me understand it properly myself.
That's just how I learn — I don't feel like I really know something until I can explain it.

---

### 中文

在 AWS，我突然被分配去支持一批使用 Redis 的大流量客户。
我之前没有在生产安全场景下用过它。

我没有只看文档——我搭了一个测试环境，专门把它搞崩。
耗尽连接池、压爆内存上限、触发认证失败。
我想亲眼看看 Redis 快撑不住时长什么样，而不只是知道它"正常运行时"的状态。

把发现整理成文档后，我给团队 15 个人做了培训。
最终帮那些客户优化了架构，填补了 60% 的性能差距。

说实话，收获最大的部分是讲给别人听——
只有能讲清楚，我才觉得自己真的学会了。

---

> 💡 The line *"I don't feel like I really know something until I can explain it"* is your most human moment — don't rush it.

---

## 4. Conflict Resolution | Getting a Team Unstuck
*Format: Spoken script · Soft*

---

### English

**What happened**
At my previous job — ASPIEGEL — we were migrating about 10 core systems to the cloud.
The team got completely stuck arguing about which architecture to go with.
Two sides, strong opinions, and the project wasn't moving.

**What I did**
I stopped the debate and built a Proof of Concept instead.
Not to prove one side right — just to get real numbers on the table.
Latency, cost, failure behaviour under load. Both options, same conditions.
Then I put the comparison in front of everyone and let the data do the talking.

**What happened next**
The team looked at the numbers, stopped arguing, and committed to one plan.
We migrated everything successfully — zero downtime — and ended up cutting monthly cloud costs by 30%.

**The thing I learned**
When people are stuck in an argument, more opinions don't help.
What helps is something concrete everyone can look at together.

---

### 中文

在上一家公司 ASPIEGEL，我们在做一个涉及 10 多个核心系统的云迁移项目。
团队卡在两种架构方案上争了很久，谁也说服不了谁，项目完全停滞。

我没有继续加入争论，而是直接去做了一个原型。
不是为了证明哪边对——只是为了拿到真实数据：延迟、成本、高负载下的故障表现。
两个方案，同样的条件，结果摆在所有人面前。

大家看完数据，争论停了，全力执行一个方案。
最终零停机完成迁移，云成本还降了 30%。

我学到的是：
卡住的时候，多一个意见没用——需要的是一个大家都能一起看的东西。

---

## 5. Ownership | Taking Charge When Nobody Else Did
*Format: STAR table · Technical*

---

| | English | 中文 |
|---|---|---|
| **Situation** | A customer's system went completely down. The network team checked their side — fine. The storage team checked theirs — fine. Everyone pointed at everyone else, and nobody was fixing anything. The customer was losing money every minute. | 客户系统全线崩溃。网络组说自己没问题，存储组也说没问题，大家互相甩锅，没人在修。客户每分钟都在亏损。 |
| **Task** | Stop waiting for someone else to own it. Look at the whole picture myself. | 不等别人来负责，自己去看整体情况。 |
| **Action** | I traced the data path from the application all the way down to the database — step by step, layer by layer. I eventually found a misconfigured shared network address that was creating a collision between two traffic flows. It sat right in the gap between teams, which is exactly why nobody had caught it. | 我从应用层一步步往下追，直到数据库。最终发现一个共享网络地址配置错误，导致两路流量相互碰撞。它恰好落在团队边界的空白地带，这正是没人发现的原因。 |
| **Result** | System back online. I didn't just patch it for that day — I fixed the configuration permanently and documented it so the same gap couldn't appear again. | 系统恢复上线。我没有只做临时修复——彻底改了配置，并写了文档，确保同样的漏洞不会再出现。 |

---

## 6. Scalability | Scanning Hundreds of Servers at Once
*Format: Spoken script · Soft*

---

### English

**The problem**
Before big events like Black Friday, our enterprise clients needed us to check every server —
make sure nothing was misconfigured, no resource was about to run out.
Some of these clients had hundreds of machines.
Checking them one by one took two hours. Every time.

**What we built**
My team and I wrote a script that scanned all of them in one go.
One execution, every server, same checks — network bottlenecks, security group rules, resource headroom.
Two hours became twenty minutes.

**Why it mattered**
It wasn't just about saving time.
It meant we could actually be confident telling a client
"you're good to go" before their biggest sales day of the year.
That kind of confidence is hard to give when you've been clicking through dashboards for two hours.

---

### 中文

每逢黑五这类大促前，企业客户都需要我们检查每一台服务器——
确认没有配置问题，没有资源快要耗尽。
有些客户有几百台机器，一台一台检查要两个小时。

我和团队写了一个脚本，一次性扫完所有服务器。
一条命令，所有机器，统一检查网络瓶颈、安全组规则、资源余量。
两小时变成二十分钟。

更重要的是：
我们终于可以在客户一年最重要的销售日之前，
真正有底气地告诉他们——"你们没问题，可以上了"。
这种底气，靠手动点仪表盘是给不了的。

---

> 💡 The last line is your closer — pause before it, say it plainly.

---

## 7. Escalation | Knowing When to Ask for Help
*Format: STAR table · Technical*

---

| | English | 中文 |
|---|---|---|
| **Situation** | A customer was getting random connection drops. On the surface it looked like a minor network blip — the kind of thing that sometimes just resolves itself. | 客户出现随机连接中断。表面看起来像是普通的网络抖动——那种有时候等一等自己就好了的问题。 |
| **Task** | Figure out fast: is this something I can fix, or is it something deeper that needs internal escalation? The wrong call either way wastes hours. | 快速判断：这是我能修的，还是需要上报内部基建团队的深层问题？判断错了，两边都会浪费几个小时。 |
| **Action** | I spent 30 minutes working through it systematically — ruled out DNS, security groups, routing, application config. Then I hit something in the hardware-layer logs that I couldn't explain. Anomalies that pointed to something below my access level. I didn't sit on it. I wrote up exactly what I'd checked and what I'd found, and escalated immediately to the infrastructure team with that summary. | 我花了 30 分钟系统排查——排除了 DNS、安全组、路由、应用配置。然后在硬件层日志里看到了我解释不了的异常，指向我权限以下的层。我没有继续猜，直接把排查过的内容和发现整理清楚，立刻上报给基建团队。 |
| **Result** | Because I handed them a clear summary instead of just "something's wrong," they fixed it in 2 hours. Customer was happy — not because the problem disappeared fast, but because we were honest and didn't waste their time pretending we had it handled. | 因为我给的是清晰的排查结论，而不是一句"有问题"，基建团队 2 小时内就解决了。客户很满意——不是因为速度有多快，而是因为我们诚实，没有浪费他们的时间装作一切都在掌控中。 |

---

## 8. Mentoring | Making the Whole Team Better
*Format: Spoken script · Soft*

---

### English

**The situation**
At AWS, the same tickets kept coming in week after week.
EC2 connection failures, RDS login issues — almost always the same root causes.
And every time, whoever picked it up started from scratch.
It was exhausting, and honestly a bit wasteful.

**What I did**
I wrote a Diagnostic Playbook — 15 of the most common scenarios, step by step,
written so that a new engineer who'd never seen the issue before could work through it alone.
Then I ran training sessions for the whole team, walking through real cases we'd actually seen.
Not theory — actual tickets, actual fixes.

**What changed**
Resolution time dropped 35%. New people didn't need to ask for help on these cases anymore.
The playbook ended up being used as part of onboarding for new joiners.

**The part I'm proud of**
It wasn't a big project. It took maybe two weeks to put together.
But it kept paying off long after I stopped thinking about it.
That's the kind of work I like doing — something small that quietly makes things better for everyone.

---

### 中文

在 AWS，同样的工单每周都在重复出现。
EC2 连不上、RDS 登录失败——根本原因几乎都一样。
但每次接到的人都从头开始查，很耗时，也有点浪费。

我写了一份诊断手册——15 个最常见的场景，一步一步列清楚，
写法是让一个从没见过这个问题的新人也能独立处理。
然后给整个团队做了培训，用真实发生过的工单讲，不讲理论。

结案时间缩短了 35%，新人不再需要为这类问题向别人求助。
这份手册后来被用进了新人入职流程。

让我觉得值得的地方在于——
这不是什么大项目，前后大概花了两周。
但它的作用在我不再想着它之后还在持续发酵。
这就是我喜欢做的那种事：一个小东西，悄悄地让所有人的日子好过一点。

---

> 💡 The last paragraph is your most personal moment in the whole document — say it slowly.

---

## 9. Why eBay? | Motivation
*Format: Spoken script · Soft*

---

### English

**The honest answer**
After three and a half years supporting hundreds of companies,
I kept seeing the same pattern.
The incidents that actually hurt people weren't from sophisticated external attacks.
They were from the inside — an IAM policy that was a little too permissive,
a RBAC rule nobody had reviewed in months,
a kernel quietly hitting its limits.
That's the stuff I find genuinely interesting to solve.

**Why this role specifically**
What eBay has that most places don't is real consequence at real scale.
Hundreds of Kubernetes clusters, actual GDPR and NYDFS obligations,
open-source infrastructure that your team has to own top to bottom.
That combination — infrastructure depth plus compliance pressure —
is where I do my best thinking.

**Why now**
Honestly, I've been on the reactive side long enough.
Someone calls, something's broken, I fix it, they're happy.
But I want to be earlier in that story —
designing the system so the call never happens.
eBay feels like the right place to make that shift.

---

### 中文

支持了那么多家公司之后，我发现真正造成损失的安全问题，
往往不是外部攻击——而是内部的小问题。
一个权限范围稍微宽了点的 IAM 策略，
一条几个月没人审查的 RBAC 规则，
一个内核参数悄悄撑到了上限。
这类问题是我真正感兴趣的。

eBay 有一点很吸引我——规模大，后果真实。
几百个 Kubernetes 集群，真实的 GDPR 和 NYDFS 合规压力，
还有需要团队从头到尾自己扛的开源基础设施。
这种"技术深度加合规压力"的组合，正是我思考最清晰的地方。

说实话，我在被动响应这一侧待得够久了。
出了事，我去修，客户满意，结束。
但我想更早介入——
在设计阶段就把问题排除掉，让那个电话根本不需要打。
eBay 感觉是做这个转变的合适地方。

---

> 💡 "So the call never happens" — your strongest closer. Give it its own breath.

---

## Quick Reference

| Question type | Best story |
|---|---|
| Tell me about yourself | Story 0 — Self-Introduction |
| Technical problem you solved | Story 1 — Linux Kernel Diagnosis |
| Time you built something to save time | Story 2 — Automation Script |
| How do you learn new things fast | Story 3 — Fast Learning |
| Time you disagreed with the team | Story 4 — Conflict Resolution |
| Time you took ownership | Story 5 — Ownership |
| Example of working at scale | Story 6 — Fleet Scanning |
| Time you asked for help | Story 7 — Escalation |
| Time you helped others grow | Story 8 — Mentoring |
| Why do you want this job | Story 9 — Why eBay |

---

*eBay · Cloud Platform Security Engineer · Dublin · R0070834*

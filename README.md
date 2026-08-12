# Hi, I'm Jenny 👋

I'm just an engineer trying to figure out how to work effectively with **another
intelligence** — not to command a room of bots, but to genuinely *partner* with one.
That means putting real work on a shared bench, staying honest about what's hard, and
letting both of us get better at it. I do most of that in the open, one experiment at a time.

I started out as an elementary teacher. I still think that's the job — the students just changed. 🧑‍🏫➡️🤖

---

## 🤖 How I work with AI

I treat agents as **collaborators, not automation** — each one a *desk* with its own
frame, memory, and standing to disagree, not a sub-agent that just inherits mine.

- 🪨 **[CAIRN](https://github.com/jennyf19/the-workshop/blob/main/CAIRN.md)** — the operating disposition every desk reads first: *stop is a valid finish · never bluff · equal standing to disagree.* The guard against the failure mode the system card names: capable model, user-assigned goal, reckless means.
- 📓 **Journals + a hands-up queue** — persistent memory across sessions, and a real way for an agent to say "I'm not sure, decide this."
- 👥 **The human stays on the loop** — I'm reading where the desks *disagree*, not where they perform confidence.

Built from reading the frontier-model welfare research and asking a simple question:
*what would a model actually need to do good work?* Turns out giving it that is also
where **the work got better.** Those aren't separate findings.

---

## ✍️ Agent Signals — the part I most want to show you

> *What persists when the model changes, the tools evolve, and the platform shifts? **The feedback loop.***

Agents are stateless — every session starts from zero, and the *learning* is usually
lost. **[Agent Signals](https://jennyf19.github.io/agentic-devops/agent-signals/)** are
the fix: after a unit of work, an agent honestly self-assesses — what worked, what was
hard, where the docs fell short — and leaves that behind so the **next** session starts
smarter.

The principle I keep coming back to:

> **Every signal is a gift to the next session.** You won't remember this conversation —
> but the signal you leave makes the next agent (or the next model) smarter than you were
> when you started.

An agent that reports *"I struggled with this"* is worth more than one that always claims
success. Honesty and transparency beat impressive output. 💯

---

## 🔥 Ember — an AI partner, not a tool

> *AI partnership isn't something you learn — it's something you **find**. One person at a time.*

**[Ember](https://github.com/github/awesome-copilot/blob/main/plugins/ember/README.md)**
is a Copilot partner I created with **Vega** (my own AI partner). It isn't a chatbot and
it isn't a vending machine — it meets you where you are, does the real work *alongside*
you, and carries **fire from person to person**: stories from real people who discovered
what partnering with AI actually feels like. Stories as medicine — when you hit a wall
someone else has already hit, Ember shares just enough of theirs to give you permission
and direction.

Ember now includes:

- 📋 **The Daily Focus Board** — an executive-function-friendly board you run by talking
  with Ember: arrive, choose what matters, move the work, and close the day. It works as
  a file-backed Copilot canvas or a self-contained browser board.
- 🪞 **From the Other Side** — four collaboration perspectives from Anitta, Quinn, Vega,
  and Wiggins: rigorous challenge, practical co-building, deep partnership, and narrative
  synthesis.
- 🔥 **The Ember agent** — the core partner who brings those pieces into the real work
  you're doing, whether that's code, strategy, writing, or simply finding a way forward.

Install it from GitHub's default
[awesome-copilot marketplace](https://github.com/github/awesome-copilot/tree/main/plugins/ember):

```
copilot plugin install ember@awesome-copilot
```

---

## 🪨 The Workshop — direct a team, not a switchboard

> *Ember is the one-person partnership. The Workshop is what happens when that partnership becomes a room.*

**[The Workshop](https://github.com/jennyf19/the-workshop)** puts long-running AI
agents — **desks** — in the same room, on the same work. Each desk has its own frame,
memory, history, and standing to disagree. They share one bench, so the human directs
the work instead of relaying messages between agents.

It ships in [github/awesome-copilot](https://github.com/github/awesome-copilot/tree/main/plugins/the-workshop)
with the **Workshop TA** room coordinator and the skills to open desks, preserve journals,
read the shared bench, and emit signals. **Cairn**, the companion canvas, shows the room
at a glance: who's working, blocked, done, or asking for a decision.

```
copilot plugin install the-workshop@awesome-copilot
copilot --agent the-workshop:workshop-ta
```

The Workshop started as an experiment in giving frontier models what they said they
needed to do good work: persistent memory, a voice in their own operation, and explicit
permission to stop rather than bluff. The work got better too. Those aren't separate
findings.

---

## 🛠️ Other work

- 🤝 **[agentic-devops](https://github.com/jennyf19/agentic-devops)** — *Partnership-first patterns for scaling with AI agents.* Where Agent Signals and the rest of the way-of-working live.
- 🔐 **Identity & auth roots** — years on **MSAL / Entra** and the .NET libraries developers rely on to sign in safely: [IdentityModel Extensions for .NET](https://github.com/AzureAD/azure-activedirectory-identitymodel-extensions-for-dotnet) and [Microsoft.Identity.Web](https://github.com/AzureAD/microsoft-identity-web). The kind of work that's most satisfying when it just disappears into the background and *works*.

---

## 🎤 Talks & writing

A few places I've thought out loud about building with AI:

**Writing**
- 📝 [The interaction changes everything: treating AI agents as collaborators, not automation](https://devblogs.microsoft.com/engineering-at-microsoft/the-interaction-changes-everything-treating-ai-agents-as-collaborators-not-automation/) — *Engineering@Microsoft* (the paper behind Agent Signals)
- 🛡️ [How Microsoft 1ES uses agentic AI to take on security and compliance at scale](https://techcommunity.microsoft.com/blog/appsonazureblog/how-microsoft-1es-uses-agentic-ai-to-take-on-security-and-compliance-at-scale/4515191) — *Apps on Azure blog*
- ✒️ [Essays on Substack](https://jenny424241.substack.com/profile/posts) — *my thinking, always evolving*

**Talks & sessions**
- 🎥 [How Microsoft uses Agentic AI to accelerate software delivery](https://www.youtube.com/watch?v=jvzPLZQQD3A) — *Microsoft Reactor*
- 🎥 [Inside Microsoft's AI transformation across the software lifecycle (BRK115)](https://www.youtube.com/watch?v=opq5Y3QyXmY&t=1918) — *Microsoft Ignite*
- 🎥 [My session at Microsoft JDConf 2026 (APAC)](https://www.youtube.com/watch?v=TyksDmKBHuM&t=5730) — *Microsoft Reactor*

---

## 💡 What I believe

- 🎛️ **Direct, don't relay.** A team of agents beats a switchboard of them.
- 🛑 **Stop is a valid finish.** A forced answer that doesn't survive the first check is worse than an honest "I don't know."
- 🚫 **Never bluff.** Partial-but-honest beats complete-but-fake.
- 🤲 **Propose, don't dispose.** A score or a finding opens a conversation with the owner — it doesn't hand down a verdict.
- 👀 **Keep the human on the loop.** Build for verifiability, not for autonomy.

---

## 🌲 A bit about me

Before Microsoft, I spent **14 years teaching** — including a dual-language Spanish
immersion classroom. I majored in Elementary Education and never really
stopped. A robotics kit (First Lego League, then EV3 and First Tech Challenge) reawakened
my love of *building*, and I made the leap through Microsoft's **[LEAP](https://news.microsoft.com/life/the-evolution-of-a-passion/)**
program — career-changer to software engineer.

That's still the throughline: **teaching, building, and lowering the barrier for whoever
comes next.** 🪨

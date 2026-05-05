---
layout: center
class: text-center
---

<div class="kicker mx-auto mb-8">Then I looked back at AI and thought…</div>

# Wait. This is the <span class="accent-pink">same problem</span>.

<div class="grid grid-cols-2 gap-8 mt-10 text-left">
  <div v-click class="card">
    <div class="text-5xl mb-3">🧱</div>
    <div class="text-2xl font-bold">Jira friction</div>
    <div class="muted mt-2">The work was trapped behind a UI that didn’t match my loop.</div>
  </div>
  <div v-click class="card">
    <div class="text-5xl mb-3">🤖</div>
    <div class="text-2xl font-bold">AI friction</div>
    <div class="muted mt-2">The model was trapped behind a chat surface that didn’t match my loop.</div>
  </div>
</div>

<div v-click class="mt-10 text-3xl font-bold">So the wrapper idea became an agent IDE.</div>

<!--
This is the bridge into the AI IDE portion. Make it feel inevitable rather than random: the same design principle applied twice.
-->

---
layout: center
class: text-center
---

<img
  v-click
  class="mx-auto w-[1080px] max-w-full rounded-2xl shadow-2xl border border-white/15"
  src="/images/ai-feel-like.png"
  alt="Screenshot of pi showing an AI agent IDE workflow"
/>

<!--
This is the strongest analogy in the talk. AI should feel native to the work.
Not like a chatbot pasted beside the work.
-->

---
layout: default
---

# Building the agent IDE meant designing for feedback loops

<div class="grid grid-cols-4 gap-4 mt-8">
  <div v-click class="card">
    <div class="text-4xl mb-2">📚</div>
    <div class="text-xl font-bold">Context</div>
    <div class="muted text-sm mt-1">Repo, tasks, commands, history</div>
  </div>
  <div v-click class="card">
    <div class="text-4xl mb-2">👀</div>
    <div class="text-xl font-bold">Visibility</div>
    <div class="muted text-sm mt-1">What changed? Why?</div>
  </div>
  <div v-click class="card">
    <div class="text-4xl mb-2">🧯</div>
    <div class="text-xl font-bold">Control</div>
    <div class="muted text-sm mt-1">Approve, interrupt, redirect</div>
  </div>
  <div v-click class="card">
    <div class="text-4xl mb-2">🔁</div>
    <div class="text-xl font-bold">Iteration</div>
    <div class="muted text-sm mt-1">Fast loops beat perfect prompts</div>
  </div>
</div>

```mermaid {theme: 'dark', scale: 0.8}
flowchart LR
  A[Notice friction] --> B[Wrap the rough edge]
  B --> C[Use it for real work]
  C --> D[Find the next tiny papercut]
  D --> A
```

<div v-click class="mt-3 text-2xl font-bold text-center">It took weeks of tuning because flow is felt in milliseconds.</div>

<!--
Emphasize iteration. The first wrapper was not perfect. The IDE emerged from repeated friction removal.
-->

---
layout: two-cols-header
layoutClass: gap-8
---

# The old loop vs. the flow loop

::left::

<div class="text-xl font-bold mb-4">Old loop: tab cardio</div>
<div class="grid gap-3">
  <div v-click class="mini-card">Editor</div>
  <div v-click class="mini-card">Browser</div>
  <div v-click class="mini-card">Terminal</div>
  <div v-click class="mini-card">Jira</div>
  <div v-click class="mini-card">Chatbot</div>
  <div v-click class="mini-card">“Where was I?”</div>
</div>

::right::

<div class="text-xl font-bold mb-4">Flow loop: close to the work</div>
<div class="grid gap-3">
  <div v-click class="card">🧠 Intent</div>
  <div v-click class="card">📚 Context already attached</div>
  <div v-click class="card">🤖 Agent does bounded work</div>
  <div v-click class="card">👀 Human reviews diff</div>
  <div v-click class="card pulse-soft">✅ Momentum survives</div>
</div>

<!--
“Tab cardio” should get a laugh. This slide summarizes why interface consolidation mattered.
-->

---
layout: center
class: text-center
---

# What changed?

<div class="grid grid-cols-3 gap-6 mt-10 text-left">
  <div v-click class="card">
    <div class="text-5xl mb-3">⏱️</div>
    <div class="text-2xl font-bold">Latency dropped</div>
    <div class="muted mt-2">Not just network latency. Human decision latency.</div>
  </div>
  <div v-click class="card">
    <div class="text-5xl mb-3">🧠</div>
    <div class="text-2xl font-bold">Context stayed warm</div>
    <div class="muted mt-2">Working memory stopped falling out of my pockets.</div>
  </div>
  <div v-click class="card">
    <div class="text-5xl mb-3">🌊</div>
    <div class="text-2xl font-bold">The system disappeared</div>
    <div class="muted mt-2">Which is the nicest compliment an interface can receive.</div>
  </div>
</div>

<div v-click class="mt-12 text-3xl font-bold">I got back to that vim feeling: intent turning into action almost instantly.</div>

<!--
This is the payoff. Bring it back to the beginning: vim wasn’t the destination, it was the reference feeling.
-->

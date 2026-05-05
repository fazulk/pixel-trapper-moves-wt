
<div class="confetti"><span></span><span></span><span></span><span></span><span></span><span></span><span></span></div>

<div class="kicker mx-auto mb-7">🏙️ Tech town hall · 20 minutes · surprisingly few Jira screenshots</div>

# <span class="title-gradient">The Interface<br/>Is the Bottleneck</span>

<div class="mt-7 text-2xl muted">Chasing flow in the age of AI agents</div>

<div class="mt-12 flex justify-center gap-7">
  <div v-motion :initial="{ y: 30, opacity: 0 }" :enter="{ y: 0, opacity: 1, transition: { delay: 250 } }" class="orb floaty">⌨️</div>
  <div v-motion :initial="{ y: 30, opacity: 0 }" :enter="{ y: 0, opacity: 1, transition: { delay: 450 } }" class="orb floaty-2">🤖</div>
  <div v-motion :initial="{ y: 30, opacity: 0 }" :enter="{ y: 0, opacity: 1, transition: { delay: 650 } }" class="orb floaty p-5">
    <img class="w-18 h-18" src="https://cdn.simpleicons.org/jira/2684FF" alt="Jira logo" />
  </div>
</div>

<!--
Open light and personal. This is not a vendor comparison and not “AI tools are cool.”
It is a story about flow: I had it, I lost it, and I rebuilt my environment until I could get it back.
-->

---
layout: center
class: text-center
transition: fade-out
---

<div class="kicker mx-auto mb-8">The whole talk in one emotionally suspicious timeline</div>

<div class="grid grid-cols-4 gap-5 text-left">
  <div v-click class="card">
    <div class="text-5xl mb-3">🌊</div>
    <div class="text-2xl font-bold">I had flow</div>
    <div class="muted mt-2">Vim made<br> thought → action<br> feel tiny.</div>
  </div>
  <div v-click class="card">
    <div class="ai-heads">
      <img class="ai-head dario" src="/people/dario-amodei.png" alt="Dario Amodei head" />
      <img class="ai-head sam" src="/people/sam-altman.png" alt="Sam Altman head" />
    </div>
    <div class="text-2xl font-bold">Chat Jippity & Claudius Code</div>
    <div class="muted mt-2">Powerful model. Weirdly clunky ritual.</div>
  </div>
  <div v-click class="card">
    <div class="mb-3">
      <img class="w-14 h-14" src="https://cdn.simpleicons.org/jira/2684FF" alt="Jira logo" />
    </div>
    <div class="text-2xl font-bold">Jira</div>
    <div class="muted mt-2">Ol' Reliable Jira</div>
  </div>
  <div v-click class="card pulse-soft">
    <div class="text-5xl mb-3">🛠️</div>
    <div class="text-2xl font-bold">I wrapped it</div>
    <div class="muted mt-2">Until the work felt close again. You know like a present.</div>
  </div>
</div>

<!-- <div v-click class="mt-10 text-3xl font-bold">
  I wasn’t chasing tools. I was chasing <span class="accent">flow</span>.
</div> -->

<!--
Set the emotional arc. The audience should know where we’re going immediately.
The joke is that “clickable” is both a product virtue and a developer tax.
-->

---
layout: statement
class: text-center
---


# <span class="title-gradient">Productivity is often limited by the distance between intent and execution.</span>

<div v-click class="mt-12 intent-path text-left">
  <div class="card text-center">
    <div class="text-5xl">🧠</div>
    <div class="text-xl font-bold mt-2">Intent</div>
  </div>
  <div class="arrow-line"></div>
  <div class="card text-center">
    <div class="text-5xl">🧰</div>
    <div class="text-xl font-bold mt-2">Interface</div>
  </div>
  <div class="arrow-line"></div>
  <div class="card text-center">
    <div class="text-5xl">✅</div>
    <div class="text-xl font-bold mt-2">Outcome</div>
  </div>
</div>

<div v-click class="mt-8 text-xl muted">The interface is where momentum either survives… or goes to open seventeen tabs.</div>

<!--
This is the lens for the rest of the talk. We usually talk about compute, model quality, process, or features.
But the day-to-day bottleneck is often the interface between what I mean and what the system does.
-->

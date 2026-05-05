
<div class="confetti"><span></span><span></span><span></span><span></span><span></span><span></span><span></span></div>

<div class="kicker mx-auto mb-7">🏙️ Tech town hall · 20 minutes · surprisingly few Jira screenshots</div>

# <span class="title-gradient">The Interface<br/>Is the Bottleneck</span>

<div class="mt-7 text-2xl muted">How to shorten the path between intent and outcome</div>

<div class="mt-12 flex justify-center gap-7">
  <div v-motion :initial="{ y: 30, opacity: 0 }" :enter="{ y: 0, opacity: 1, transition: { delay: 250 } }" class="orb floaty">⌨️</div>
  <div v-motion :initial="{ y: 30, opacity: 0 }" :enter="{ y: 0, opacity: 1, transition: { delay: 450 } }" class="orb floaty-2">🤖</div>
  <div v-motion :initial="{ y: 30, opacity: 0 }" :enter="{ y: 0, opacity: 1, transition: { delay: 650 } }" class="orb floaty p-5">
    <img class="w-18 h-18" src="https://cdn.simpleicons.org/jira/2684FF" alt="Jira logo" />
  </div>
</div>

<!--
Open light, but frame this as a useful pattern, not a personal tool diary.
The examples are mine, but the question is for everyone:
where does our work slow down because the interface makes us translate intent too many times?
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

<div v-click class="mt-8 text-xl muted">The interface is where momentum either survives — or turns into coordination work.</div>

<!--
This is the core service of the talk: a diagnostic lens.
When a workflow feels slow, don't only ask “is the tool powerful?”
Ask “how much translation does the person have to do between intent and outcome?”
-->

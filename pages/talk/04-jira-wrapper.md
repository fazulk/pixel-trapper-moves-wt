---
layout: two-cols
layoutClass: gap-12
class: jira-intermission-slide
---

# Intermission: We need to keep track of the work


<div v-click class="card mt-4">
  <div class="text-3xl font-bold">The source of truth matters.</div>
  <div class="muted mt-2">Tickets, ownership, status, history, reporting — Jira keeps teams coordinated when work gets bigger than one person.</div>
</div>

<div v-click class="card mt-4">
  <div class="text-3xl font-bold">But the interface is not built for speed.</div>
  <div class="muted mt-2">It is clunky, slow, and optimized for completeness over momentum. Every update asks you to leave the work and feed the system.</div>
</div>

::right::

<div class="mt-4 text-center">
  <div class="text-6xl">🎟️</div>
  <div class="mt-2 text-2xl font-bold accent-pink">Useful does not mean fast</div>
  <div class="muted mt-2">Jira helps the organization move together. It just was not designed around the fastest path from intent to update.</div>
</div>

<div class="mt-5 flex justify-center">
  <div>
    <div class="battery"><div class="battery-fill"></div></div>
    <div class="text-center mt-3 text-xl font-bold accent-pink">Working memory</div>
  </div>
</div>


<!--
Story beat: do not dunk on Jira. Establish that it is useful infrastructure, but its UI is optimized for process depth, not quick operational updates.
Say: “Jira is valuable because it keeps the organization aligned. But when I already know the status, the assignee, or the comment I need to add, the default path is still slow. That speed mismatch is where the interface becomes the bottleneck.”
Then transition: I did not replace Jira. I put a smaller, faster doorway in front of it.
-->

---
layout: default
class: text-center doorway-slide
---

# You build a <span v-click="1" class="accent">better doorway</span>

<div v-click="2" class="text-xl muted mt-3">Not to replace the system. To make the right action easier to take.</div>

<v-switch>
  <template #1>
    <img class="mt-4 mx-auto max-h-[300px] object-contain" src="/images/app-screenshot-placeholder.png" alt="Screenshot of our Jira wrapper app" />
  </template>
  <template #3>
    <img class="mt-4 mx-auto max-h-[300px] object-contain" src="/images/app-screenshot-placeholder.png" alt="Screenshot of our Jira wrapper app" />
  </template>
</v-switch>

<div v-click="3" class="mt-3 text-2xl leading-tight font-bold">Same Jira. Smaller surface area. <span class="accent">Shorter path</span> from intent to update.</div>

<!--
Frame this as service design.
The goal was not “I built a cool app.”
The goal was to reduce the cost of doing the right operational thing.
-->

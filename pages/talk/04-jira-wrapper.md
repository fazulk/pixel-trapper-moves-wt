---
layout: two-cols
layoutClass: gap-12
---

# Jira made the friction impossible to ignore

<div class="text-xl muted mt-4">Important disclaimer:</div>

<div v-click class="card mt-5">
  <div class="text-3xl font-bold">Jira is powerful.</div>
  <div class="muted mt-2">Powerful like a spaceship cockpit is powerful.</div>
</div>

<div v-click class="card mt-5">
  <div class="text-3xl font-bold">But power ≠ flow.</div>
  <div class="muted mt-2">Sometimes power means 11 dropdowns and a tiny loading spinner contemplating its life choices.</div>
</div>

::right::

<div class="mt-10 flex justify-center">
  <div>
    <div class="battery"><div class="battery-fill"></div></div>
    <div class="text-center mt-4 text-xl font-bold accent-pink">Working memory</div>
  </div>
</div>

<div v-click class="mt-10 text-3xl font-bold text-center">Every time I opened Jira, I felt my working memory drain.</div>

<!--
Keep this kind. The point is not “Jira bad.” The point is that a powerful general-purpose UI can be a poor fit for a keyboard-first coding loop.
-->

---
layout: center
class: text-center
---

# So I built a wrapper

<div class="text-2xl muted mt-4">Not to replace the system. To put a better interface in front of it.</div>

<div class="grid grid-cols-2 gap-8 mt-10 text-left">
  <div v-click class="card">
    <div class="text-5xl mb-3">🧱</div>
    <div class="text-2xl font-bold">Jira remained the source of truth</div>
    <div class="muted mt-2">Same data. Same workflow requirements. Fewer browser side quests.</div>
  </div>
  <div v-click class="card pulse-soft">
    <div class="text-5xl mb-3">⌨️</div>
    <div class="text-2xl font-bold">My wrapper matched how I think</div>
    <div class="muted mt-2">Keyboard-first, low latency, close to code.</div>
  </div>
</div>

<div v-click class="mt-10 text-3xl font-bold">The breakthrough was not a new backend. It was a <span class="accent">shorter path</span>.</div>

<!--
This echoes migration empathy: I did not throw out the system. I built a bridge between the system and the way I work.
-->

---
layout: two-cols-header
layoutClass: gap-10
---

# Same Jira, different surface area

::left::

<div class="text-xl font-bold mb-4">Before</div>

<div v-clicks class="grid gap-3">
  <div class="mini-card">Open browser</div>
  <div class="mini-card">Find board</div>
  <div class="mini-card">Find issue</div>
  <div class="mini-card">Wait for panel</div>
  <div class="mini-card">Click tiny thing</div>
  <div class="mini-card">Forget what I was coding</div>
</div>

::right::

<div class="text-xl font-bold mb-4">After</div>

````md magic-move {lines: true}
```bash
# thought: what am I working on?
```
```bash
$ issues mine
```
```bash
$ issues mine --status "In Progress"
```
```bash
$ issue open PAY-123
```
```bash
$ issue note PAY-123 "Found the flaky edge case"
```
````

<div v-click class="mt-5 card">
  <span class="accent-green font-bold">Flow restored:</span> issue context stayed near code context.
</div>

<!--
Use this as an illustrative sketch, not necessarily exact commands.
The important contrast is UI tourism versus direct expression of intent.
-->

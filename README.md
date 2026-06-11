<img src="assets/hero.svg" width="100%" alt="Vaishnav Abhijeet · Production Engineer · Full-Stack Developer · Indie Hacker · Upgrading Myself,">

<p align="center">
  <a href="https://x.com/abhijeet117_"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="Follow on X"></a>&nbsp;
  <a href="https://www.linkedin.com/in/abhijeet-kumar-sah-35890a353"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="Connect on LinkedIn"></a>&nbsp;
  <a href="https://instagram.com/abhijeet117_"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Follow on Instagram"></a>&nbsp;
  <img src="https://komarev.com/ghpvc/?username=abhijeet117&style=for-the-badge&color=58A6FF&label=PROFILE+VIEWS" alt="Profile views counter">
</p>

<div align="center">

I build AI assistants, CRMs, and dev tooling that holds up in production.<br>
Currently shipping two indie products: <b>hostlist-io</b> (Next.js) and <b>wp-maintain-app</b> (React, TypeScript).

</div>

## Proof of work

Green squares are cheap. Merged diffs in repos people actually run are the ledger.

<p align="center">
  <a href="https://github.com/openclaw/openclaw/pull/3304"><img src="assets/card-openclaw.svg" width="49%" alt="openclaw/openclaw #3304 · Subprocess hang, fixed in five lines · Swift · +3 / -2 · merged"></a>
  <a href="https://github.com/zeroclaw-labs/zeroclaw/pull/5790"><img src="assets/card-zeroclaw.svg" width="49%" alt="zeroclaw-labs/zeroclaw #5790 · Tool approvals, delivered to Telegram · Rust · +444 / -7 · merged"></a>
</p>

<img src="assets/quote.svg" width="100%" alt="One fix was three lines. The other was four hundred and forty-four. The discipline was identical.">

**[openclaw/openclaw #3304](https://github.com/openclaw/openclaw/pull/3304)** · A subprocess helper in this 100k+ star macOS AI assistant piped stderr but never read it, so any child noisy enough to fill the pipe buffer deadlocked and hung forever. The fix redirects stderr to `FileHandle.nullDevice` so the buffer can never fill. Swift, +3 / -2, merged January 2026.

**[zeroclaw-labs/zeroclaw #5790](https://github.com/zeroclaw-labs/zeroclaw/pull/5790)** · The Telegram channel silently auto-denied every tool approval request because no operator had a way to answer. I built the cross-crate approval flow and surfaced it as inline keyboard buttons, so approving or denying a tool call is one tap in chat. Rust, +444 / -7 across 6 crates, merged April 2026.

On the bench: [lovellylilly](https://github.com/abhijeet117/lovellylilly), a reasoning model experiment in JavaScript.

## How I work

<img src="assets/pipeline.svg" width="100%" alt="Pipeline: Understand before you change · Scope minimally · Test aggressively · Ship reversibly · Keep prod happy">

## Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=ts,js,rust,swift,react,nextjs,nodejs,vite,supabase,netlify,git&theme=dark" alt="TypeScript, JavaScript, Rust, Swift, React, Next.js, Node.js, Vite, Supabase, Netlify, Git">

<sub>Plus Stripe for payments. The Rust ships in <a href="https://github.com/zeroclaw-labs/zeroclaw/pull/5790">zeroclaw #5790</a>, the Swift in <a href="https://github.com/openclaw/openclaw/pull/3304">openclaw #3304</a>.</sub>

</div>

## Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=abhijeet117&show_icons=true&hide_title=true&bg_color=0D1117&title_color=58A6FF&icon_color=BC8CFF&text_color=8B949E&border_color=30363D&border_radius=10&include_all_commits=true" height="180" alt="GitHub stats for abhijeet117">
<img src="https://streak-stats.demolab.com?user=abhijeet117&background=0D1117&border=30363D&ring=BC8CFF&fire=FF7EE3&currStreakNum=E6EDF3&sideNums=E6EDF3&currStreakLabel=58A6FF&sideLabels=8B949E&dates=8B949E&border_radius=10" height="180" alt="Contribution streak for abhijeet117">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=abhijeet117&bg_color=0D1117&color=58A6FF&line=BC8CFF&point=FF7EE3&area=true&hide_border=true&radius=10" width="100%" alt="Contribution activity graph for abhijeet117">

</div>

## Contribution snake

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/abhijeet117/abhijeet117/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/abhijeet117/abhijeet117/output/github-contribution-grid-snake.svg">
  <img src="https://raw.githubusercontent.com/abhijeet117/abhijeet117/output/github-contribution-grid-snake-dark.svg" width="100%" alt="Snake eating the contribution graph">
</picture>

<br><br>

<div align="center">

<i>Upgrading Myself,</i><sup>*</sup>

<b>Abhijeet</b>

<sub>* The trailing comma is intentional. The sentence is not finished.</sub>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:58A6FF,50:BC8CFF,100:FF7EE3&height=140&section=footer" width="100%" alt="Gradient wave footer">

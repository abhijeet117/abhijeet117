# Vaishnav Abhijeet

<sub>PRODUCTION ENGINEER · FULL-STACK DEVELOPER · INDIE HACKER</sub>

*"Upgrading Myself,"* <sup>*</sup>

I build AI assistants, CRMs, and dev tooling that holds up in production. Currently shipping two indie products: **hostlist-io** (Next.js) and **wp-maintain-app** (React, TypeScript).

## Selected work

Green squares are cheap. Merged diffs in repos people actually run are the ledger.

### openclaw: a subprocess hang, fixed in five lines

<sub>Swift · macOS · 100k+ star AI assistant · merged January 2026 · blast radius <b>+3 / -2</b> · <a href="https://github.com/openclaw/openclaw/pull/3304">openclaw/openclaw#3304</a></sub>

openclaw's `run()` helper piped stderr but never read it. Any child process noisy enough to fill the pipe buffer deadlocked and hung forever. The fix redirects stderr to `FileHandle.nullDevice` so the buffer can never fill: five changed lines, one less way for the process tree to seize.

> One fix was three lines. The other was four hundred and forty-four. The discipline was identical.

### zeroclaw: tool approvals, delivered to Telegram

<sub>Rust · merged April 2026 · blast radius <b>+444 / -7</b> · 6 crates · <a href="https://github.com/zeroclaw-labs/zeroclaw/pull/5790">zeroclaw-labs/zeroclaw#5790</a></sub>

In supervised mode, zeroclaw's Telegram channel silently auto-denied every tool approval request because no interactive operator existed to answer them. I built the cross-crate approval flow end to end: new `ChannelApprovalRequest` and `ChannelApprovalResponse` types, a `Channel::request_approval()` contract, and inline keyboard buttons so an operator can approve or deny from chat. Threaded through six crates, including api, channels, config, runtime, and tui.

On the bench: [lovellylilly](https://github.com/abhijeet117/lovellylilly), a reasoning model experiment in JavaScript. First principles over frameworks.

## How I work

1. Understand before you change.
2. Scope minimally.
3. Test aggressively.
4. Ship reversibly.

**Keep prod happy.**

## Stack

| Languages | Web | Platform |
| :--- | :--- | :--- |
| TypeScript, JavaScript, Rust ([#5790](https://github.com/zeroclaw-labs/zeroclaw/pull/5790)), Swift ([#3304](https://github.com/openclaw/openclaw/pull/3304)) | React, Next.js, Node.js, Vite | Supabase, Netlify, Stripe, Git |

## Stats

<picture>
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api?username=abhijeet117&hide_title=true&hide_rank=true&bg_color=ffffff&text_color=57606a&border_color=d0d7de">
  <img alt="GitHub stats for abhijeet117" src="https://github-readme-stats.vercel.app/api?username=abhijeet117&hide_title=true&hide_rank=true&bg_color=0d1117&text_color=8b949e&border_color=30363d">
</picture>

<sub>Every other chart was cut in editing.</sub>

## Elsewhere

[X](https://x.com/abhijeet117_) · [LinkedIn](https://www.linkedin.com/in/abhijeet-kumar-sah-35890a353) · [Instagram](https://instagram.com/abhijeet117_)

<br>

*Upgrading Myself,*

**Abhijeet**

<sub>* The trailing comma is intentional. The sentence is not finished.</sub>

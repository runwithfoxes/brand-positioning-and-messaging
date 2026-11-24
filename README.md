# Brand positioning and messaging, for writing

AI writes slop when it doesn't know your brand. If you brief it the way you would brief a good human
writer, with your audience, your competitors, what you can prove, your positioning, your tone of
voice and your messaging, it stops guessing. This plugin does that brief with you, then writes from
it.

It comes from module 2 of the course AI Fluency for Ambitious Marketers, where you build an AI writer
for a fictional insurance brand called Kite. The method and the words are the course's own. Kite's
finished documents are included as worked examples, and every fact in them is invented.

## What is in it

Five skills, used in this order. Each one checks the ones before it exist and says so if they don't.

| Skill | What it does |
|---|---|
| `brand-foundations` | Interviews you, one question at a time, for three documents: audience, competitors and proof. |
| `positioning-statement` | Builds the one sentence "For [audience], [brand] is the [frame] that [difference], because [proof]". It drafts two or three versions, says what each gives up, and you choose. |
| `tone-of-voice` | Gets your voice by putting writing in front of you and watching what you react to, never by asking you to describe it. Ends with a full worked example in your voice. |
| `messaging-framework` | Value proposition, three or four pillars each with its proof, a grid of what each segment is told, and a list of what you never say. |
| `writer` | Writes emails, blog posts and web pages from those six documents. It asks what it's writing from, shows a plan first, checks its own draft for machine-sounding writing and unproven claims, and scores it honestly. |

The six documents are saved as markdown in a `brand/` folder in whatever folder you are working in,
and the writer reads them from there every time.

## How to start

Say "help me create my audience document". The interviews take about fifteen minutes each. When all
six exist, ask the writer for something real, like "write a renewal email to customers whose policy
ends next month", and give it whatever you have to write from.

## What it does and doesn't do

It is skills and markdown only. It runs no code of its own and changes no settings. It saves
documents only in the `brand/` folder. To check a claim, the writer will search the web if your
Claude can, and says in its ledger when it could not. Every skill is told never to make up a number,
a quote or a customer, and to leave a gap you can see instead.

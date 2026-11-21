# Prompts for an Open Ecosystem Success Story

The prompts for researching and drafting an Open Ecosystem Success Story. As few as possible, as many as needed: one context block and eight prompts.

They were rebuilt after the first run, from what that run needed. They aren't a transcript of the original sessions. They work with any capable AI assistant.

AI helps the author keep many pieces in view at once. It doesn't decide anything and it doesn't speak for any party. Say in the partner brief that the base story was drafted with AI.

Everything here is CC BY-SA 4.0.

---

## The outcome

One shared document that every party was able to write into. The author writes the base story, and every party rewrites its own section and adds its own quote in that same document. Nobody gets a finished text to nod through.

Every Story publishes on the same three channels:

- **Blog:** as an Open Ecosystem Success Story
- **GitHub:** in the Open Ecosystem Collective repository, the canonical version
- **Media:** print and online

All or nothing holds for the channels too. Every party approves every channel, or the Story doesn't publish anywhere. No channel goes live with a smaller group of parties.

The approvals live in the same document: a channel approval table at the end, where every party approves every channel itself. Everybody sees who approved what, and what's still open. The signed Publication Consent stays the binding record. Every author brings their own; this repository doesn't provide one.

Which provider hosts the shared document is decided by the author and the customer together. The prompts don't assume one.

---

## How to use them

- Start every session with the context block, filled in for your Story.
- Run the prompts in order. Anything in `{curly braces}` is yours to fill in.
- Every output is a draft. You're the author, and you sign it off.
- What a party shares under the NDA ([template](../templates/mutual-nda.md)) is confidential. Check your AI tool's data settings before you paste it.

| Prompt | Phase | When |
|---|---|---|
| Context block | all | Start of every session |
| 1. Traces and map | 0 | Before anybody is asked anything |
| 2. Base story | 0 | Once the map holds |
| 3. Press release test | 0 | Before the draft leaves your desk |
| 4. Customer check | customer | The customer sees the base story first |
| 5. Customer introduction | customer | Once the customer approved |
| 6. The ask | 1 | Same mail, same day, to every partner |
| 7. Final check | 3 to 4 | After every party wrote its part |
| 8. Repository version | 5 | Once every consent is signed |

---

## Context block

```
You're helping me write an Open Ecosystem Success Story: a joint case study,
written in one shared document that every party writes into, and published
only when every company that built the project has approved it.

Project: {what was built and for whom, in one or two sentences}
Customer: {the end customer the project was built for}
Parties: {every company involved, one line each on its role}
Channels: blog (Open Ecosystem Success Story), GitHub (Open Ecosystem
Collective repository), media print and online ({name of the medium})
Language: {language of the Story}

Rules for everything you write in this Story:
- All or nothing. It publishes only if every named party says yes,
  to the Story and to every channel. One "not approved" stops it everywhere.
  Never suggest leaving a party or a channel out to make it easier.
- The customer comes first. Nothing goes to a partner before the customer
  has checked the base story and approved the use of the project.
- Every party writes its own section and its own quote. Nobody writes
  for anybody else, you included.
- Every party gets comparable weight. Nobody is featured or ranked.
- Nobody is named, counted or described without consent, not even by implication.
- No enemy. Never name, imply or contrast against a company outside the Story.
- The hard parts stay in: incidents, setbacks, decisions that were walked back.
- Use only facts from my material. If something is missing, ask.
  Mark every claim you can't trace to a source with [CHECK].
```

---

## 1. Traces and map

```
Here are the public traces this project left: {talks, posts, slides,
release notes, case studies, READMEs}

1. List the sources: who published it, when, which parties it mentions,
   which facts it supports.
2. Draw the ecosystem map: what each party contributed, who it worked with,
   and the dependencies between parties that never talked directly.
   Give a table, then a Mermaid diagram.
3. List what's missing to tell the story end to end.
Mark every connection you inferred instead of found with [CHECK].
No story text yet.
```

The map goes out with the ask. It's what a party gets back for its time before it commits to anything.

---

## 2. Base story

```
Write the base story from the sources and the map, using this template:
{Story template}

It goes into a shared document where every party will rewrite its own part.
- Give every party its own clearly marked section of comparable weight.
- Put a placeholder for each party's quote: [QUOTE: {party}].
  Write no quotes.
- Tell it in the order it happened, including what went wrong.
- Write for a decision maker who wasn't there and has five minutes.
- Keep every [CHECK] visible.
- End with a channel approval table: one row per party, one column each
  for blog, GitHub, media print and media online, every cell empty.
  Each party fills in its own row with its name, the date
  and "approved" or "not approved". Nobody fills in a row for
  anybody else. Above the table, one line: the Story publishes only when
  every cell says approved.
```

---

## 3. Press release test

```
Read the draft as a sceptical reader. Show me where it:
- reads like marketing instead of a record,
- gives one party more space or credit than the others,
- names or implies a company outside the Story,
- smooths over the hard parts,
- claims something without a source.
Quote the line and suggest a fix. Don't rewrite the draft.
```

---

## 4. Customer check

The project belongs to the customer before it belongs to anybody's story. The customer sees the base story first, checks it's complete and decides whether the project can become an Open Ecosystem Success Story. If the customer says no, the Story stops here, and no partner was ever bothered.

```
Draft a mail from me to {named contact at the customer}, with the base story
and the map attached.

It asks the customer to:
- check the story is complete: every partner who contributed is in the map,
  and nothing important is missing or wrong,
- approve the use of the project for an Open Ecosystem Success Story,
- agree with me where the shared document will live, so every party
  can write into it,
- become the first contact to the partners, by sending them a short
  introduction mail that I'll draft for them.

It explains in a few lines what the format is and that it publishes only
if every party says yes, the customer included.
It says a no is welcome and costs nothing.
It says the base story was drafted with AI.
Nothing has gone to any partner yet, and the mail says so.
```

---

## 5. Customer introduction

The customer opens the door. The author walks through it. Partners answer their customer's mail, and that's exactly why this mail has to make it safe for them to say no.

```
Draft the introduction mail the customer sends to every partner of the
project. One mail, unchanged for everyone, sent on the same day.
Written in the customer's voice, signed by {name, role at the customer}.

It says:
- the customer has read the base story and approved telling the project
  as an Open Ecosystem Success Story,
- who the author is and that the author will contact them directly
  in the next days with the draft and everything needed to decide,
- that taking part is voluntary, and that saying no has no effect at all
  on the partner's relationship with the customer.

Short. No sales language. No pressure, no deadline: the deadline comes
with the author's mail.
Give it to me with a placeholder for the date the author's mail will follow.
```

---

## 6. The ask

```
Draft one mail that goes to every partner unchanged, and a one-page brief.

The mail follows the customer's introduction and refers to it.
It goes to a named person with authority ({name} placeholder).
Its first lines say a no is welcome, and ask for it within two weeks.
It explains all or nothing as a property of the format, not a demand,
and that it holds for every channel too.
It says the base story was drafted with AI.
It asks the reader to forward it if it reached the wrong person.

The brief holds: the map, the link to the shared document, the one rule,
the timeline (two weeks to decide, at least two months for text and quotes),
how to write into the shared document (your own section, your own quote
and your own row in the channel approval table, nothing else),
the cost model, the channels, the named contact.
Write it for the human who has to take this into a budget meeting.
```

---

## 7. Final check

```
Here's the shared document after every party wrote its part, including the
channel approval table, and the list of parties who signed the Publication
Consent: {Story} {consent list}

Change no text. List only:
- every section or quote still showing the base text or a placeholder,
- contradictions between sections (dates, numbers, who did what),
- places where one party's text describes another party,
- every company, product or human named or implied without a signed consent,
- every empty or "not approved" cell in the channel approval table,
- every party whose table row doesn't match its signed Publication Consent.
```

One missing signature or one open cell holds the whole Story, on every channel.

If a medium shortens the text, the shortened version goes back into the shared document and through the approval table again. It's a different text.

---

## 8. Repository version

Once every consent is signed, the Story goes into this repository on publication day. The repository version is the canonical one and stays under CC BY-SA 4.0. It names who wrote it and who signed it off, so the neutrality can be checked by anyone.

```
Turn the approved shared document into the repository version, in Markdown.

- Change no wording, no quote and no order. Formatting only.
- Put a header on top: title, publication date, licence CC BY-SA 4.0,
  the author, every party that wrote into it, every party that signed
  the Publication Consent, and links to the blog and media versions.
- Keep the map, as a Mermaid diagram.
- Keep the filled-in channel approval table at the end, unchanged.
- Remove every [CHECK] and placeholder. If one is still there, stop
  and tell me instead.
- Suggest a file name: {year}-{project-slug}.md
```

---

*A circle only holds when it is closed.*

Open Ecosystem Collective · open-ecosystem-collective.com · CC BY-SA 4.0

I build software for people who are not confident with computers, which mostly
means deciding what a program is not allowed to say.

### Is This a Scam?

A scam checker for older and less digitally confident New Zealanders. Paste a
suspicious text or email and it tells you, in plain language, what is wrong with
it — then gives you the organisation's real phone number, because the answer to
"is this real?" should never be another link.

It never says a message is safe. A false reassurance costs someone their
savings; a false warning costs them a phone call. Two engines run over every
message and the more alarming one wins: deterministic rules own what can be
looked up, and a language model owns the story being told. The model may not
write its own sentences — it picks from a reviewed catalogue and quotes the
words that made it pick, so a hallucination is caught by code rather than by the
reader.

**[Try it](https://is-this-a-scam-pink.vercel.app)** ·
**[Source](https://github.com/NewtonSythong/is-this-a-scam)** · AGPL-3.0

The number it quotes is the unflattering one. Its own small corpus reported 12
out of 12; run against 292 real reported scam texts nobody on the project had
read, the language model's half found something in **59.9%** of them, and that
is the figure published. The same run showed wrong-number openers caught 2 times
in 40. A rule written from the FTC's and Netsafe's published descriptions,
deliberately not from the misses, took that to 13 in 40 with no new false alarms.

The most useful contribution is not code: New Zealand publishes almost no scam
message text — banks and agencies release annotated screenshots instead — so one
real scam text with a citation is worth more than any refactor.

### Also

- **[Note Pilot](https://github.com/NewtonSythong/Note-Pilot)** — an AI study
  assistant: PDF ingestion, retrieval over embedded lecture notes, and a
  PostgreSQL schema with strict per-user isolation.
- **[Fresh Flat](https://github.com/NewtonSythong/Fresh-Flat)** — household
  management for flatmates, with invite-token joining and access filtered by
  membership.

---

More at **[newtonsythong.github.io](https://newtonsythong.github.io)**. Looking
for graduate software roles in Wellington or Melbourne. I'm a New Zealand
citizen with full Australian work rights.

# No Free Work

**A Claude skill that stops scope creep.** Paste what your client just asked for. Get a verdict, a reply you can send, and a priced change order.

> Client: "Can you quickly add a Careers page before Friday? Should be easy."
>
> **Verdict** — Out of scope: five pages were agreed, this is a sixth.
> **Reply to send** — "Happy to add a Careers page. It's a sixth page on top of the five we agreed: $360, delivered Tuesday. Friday's launch stays on track. Want me to go ahead?"
> **Change order** — ready to paste, with the arithmetic shown.

For freelancers, consultants and small agencies. Works in Claude (skills), Claude Code and Cowork.

## What it does

- **Classifies** the request: in scope, gray zone, out of scope, or new project — and says why, quoting your scope.
- **Writes the reply**: opens with yes, states the price and date, ends with one choice. No apologies, no lecture.
- **Prepares the pushback lines** for "it's just five minutes" and "we have no budget".
- **Fills the change order** and computes the price from your rate.
- **Tells you when it was your mistake** — and that you should fix it for free.
- **Never invents** a rate, a clause or a legal right.

## Install

**Claude Code / Cowork**

```
/plugin marketplace add merabtinenadirb-png/no-free-work
/plugin install no-free-work@no-free-work
```

**Claude (web or desktop)**: download `skills/no-free-work` as a zip and add it under Skills.

Then just talk: *"My client wrote this — is it in scope?"*

## Limits

This skill writes wording and arithmetic. It is not legal advice and it has not read your contract unless you paste it.

## Troubleshooting

- **The skill does not trigger**: name it — "use no-free-work on this message" — and paste the client's words.
- **The price is blank**: the skill never invents a rate. Give your hourly or daily rate, or the project price and its estimated effort.
- **The verdict looks wrong**: paste the scope you agreed (proposal, contract, or your own summary). Without it the best possible verdict is "gray zone".

## Data

The skill is plain instructions. It runs no code, calls no service and stores nothing.

## Support

Questions and bug reports: https://github.com/merabtinenadirb-png/no-free-work/issues

## Related work by the author

The Client Work Kit is a separate, paid set of six skills for the rest of a client project (discovery call, proposal, pricing, kickoff, status update, wrap-up): https://2328403173770.gumroad.com/l/surid — a free sample is at https://2328403173770.gumroad.com/l/aioirs

## License

MIT

# The Quiet Follow-Up

<p>
  <img alt="Status: Working tool" src="https://img.shields.io/badge/status-working%20tool-2563eb">
  <a href="LICENSE"><img alt="Licence: MIT" src="https://img.shields.io/badge/licence-MIT-lightgrey"></a>
</p>

Decide what to send, or whether to send anything, when someone has gone quiet after a message that needed a reply.

## Why

"They haven't replied" is not one situation, it usually hides several genuinely different ones: plain silence with nothing else going on, silence sitting behind a specific unanswered question, or an explicit decline that should not be followed up on at all. A generic nudge on a timer gets at least one of these wrong.

[![A decision tree for choosing a useful response when someone goes quiet.](assets/diagrams/18-the-quiet-follow-up.svg)](SKILL.md)

## Use It

Copy [SKILL.md](SKILL.md) and paste it into your AI tool (ChatGPT, Claude, Gemini, or similar), then paste in what was originally sent and anything that has happened since. It decides:

- **Follow up now**, **wait**, **change the contact**, **answer something first**, **reframe**, **close the loop**, or **stop**, whichever actually fits
- A message anchored to something real and specific to the other person, never to your own schedule or process

<details>
<summary><strong>See exactly what it produces</strong></summary>

1. The decision made, one of the seven options, stated plainly with its reason
2. Where relevant, a drafted message anchored to something specific the other person said or did
3. Where a message would not be right, a clear statement that nothing should be sent, and why

</details>

See [the worked example](example/): a food bank volunteer coordinator with three people who signed up and went quiet, one needing a plain, well-anchored follow-up, one with an unanswered question that needs answering before anything else, and one who explicitly declined and needs nothing sent at all. For a harder case, a fourth volunteer who replied with hesitation rather than going quiet, read [the second worked example](example-two/).

Use [the blank template](templates/decision-template.md) for your own case, and [the review checklist](checks/checklist.md) before sending anything.

No installation, project, or coding required to try it once.

## Before You Use It

This proposes what to send and why, or that nothing should be sent. Sending anything stays your own deliberate decision.

## Feedback

Used it on a real case? [Start a discussion](https://github.com/shaunmarsden/the-quiet-follow-up/discussions) if a decision did not fit.

## Part of a Family

This is one of a family of free tools generalising [practical-ai-sales-workflows](https://github.com/shaunmarsden/practical-ai-sales-workflows) patterns beyond sales. See [sibling-projects](https://github.com/shaunmarsden/sibling-projects) for the rest. Not sure which one actually fits? Try [the interactive picker](https://shaunmarsden.github.io/sibling-projects/) for clickable cards, or [the router](https://github.com/shaunmarsden/sibling-projects/blob/main/ROUTER.md) if you would rather paste a description into an AI chat.

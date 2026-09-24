# linkedin-skills

Carries 11 skills, LinkedIn comment drafter, LinkedIn content planner, LinkedIn employee advocacy, LinkedIn engager analytics, LinkedIn hook extractor, LinkedIn interviewer, LinkedIn post writer, LinkedIn profile optimizer, LinkedIn reply handler, LinkedIn repurposer and LinkedIn thread monitor, from the open-source project sergebulaev/linkedin-skills, which AgentMesh did not write.

## What it does

- LinkedIn comment drafter: Draft a LinkedIn comment on someone else's post from its URL, or reshare (repost) it to your feed with optional commentary.
- LinkedIn content planner: Generate a 7-day LinkedIn content plan from a theme, audience, and pillars.
- LinkedIn employee advocacy: Stand up and run a LinkedIn employee advocacy program for a marketing or sales team.
- LinkedIn engager analytics: Pull the people who liked or commented on any LinkedIn post and segment them by ICP fit (peer / aspirational / prospect / other).
- LinkedIn hook extractor: Reverse-engineer the hook formula from a viral LinkedIn post URL.
- LinkedIn interviewer: Interview the user for the raw material their posts are made of.
- LinkedIn post writer: Draft a new LinkedIn post from scratch using one of 20 2026 hook formulas (anaphora, R.I.P., time-anchor, curiosity-gap, contrarian, controlled A/B, false-binary, and more) plus a founders-edition angle library, picked by engagement goal (comments, reposts, likes, saves).
- LinkedIn profile optimizer: Audit and rewrite a LinkedIn profile end-to-end for 2026: headline, About 7-step, Featured, banner, photo, Experience metrics, Skills, custom URL, recommendations.
- LinkedIn reply handler: Draft a reply to one LinkedIn comment from its URL, or sweep a whole thread from just the post URL and draft a reply to every comment worth answering, in one batch.
- LinkedIn repurposer: Repurpose existing content into a native LinkedIn post.
- LinkedIn thread monitor: Track which of your LinkedIn comments earned author replies.

## What it needs

- APIFY_TOKEN, a key, for the skills LinkedIn comment drafter, LinkedIn engager analytics, LinkedIn hook extractor, LinkedIn reply handler and LinkedIn thread monitor. It is an API key used to authenticate with Apify for fetching LinkedIn post and comment data. It costs money to use. Optional: without it, they ask the user to paste the post text and (optionally) top comments.
- PUBLORA_API_KEY, a key. It is an API key used to authenticate with Publora for publishing or scheduling posts and comments directly to LinkedIn. Optional: without it, it will still work, leaving out the part that needs it.
- The Python module lib, which this agent cannot run, for the skills LinkedIn comment drafter, LinkedIn engager analytics, LinkedIn hook extractor, LinkedIn reply handler and LinkedIn thread monitor. It provides helper functions and API clients for URL parsing, Apify, Publora, Pixfaro, and drafting approval cards. Without it they ask the user to paste the post text and (optionally) top comments.
- The Python module lib, which this agent cannot run, for the skills LinkedIn post writer and LinkedIn repurposer. It provides helper functions and API clients for URL parsing, Apify, Publora, Pixfaro, and drafting approval cards. Without it they still work, leaving out the part that needs it.

## Where it came from

The linkedin-skills authors wrote it and publish it at https://github.com/sergebulaev/linkedin-skills. This agent was made from commit 5c6192db54db24bf46fab8bbac32f7946daca970. AgentMesh did not write it; AgentMesh wrapped it so it can run as an agent. NOTICE.md says what AgentMesh added.

## Version

This agent's own version is 1.0.2; it counts changes to this agent. The upstream version it was made from is commit 5c6192d.

## Licence

MIT, the project's own licence. The full text is in LICENSE, unchanged.

## Security

No security review was run on the upstream code before it was converted.

# Crusoe hackathons

Projects built on Crusoe at hackathons Crusoe hosts or sponsors, grouped by event. Each event has its own page with the winners and a table of every project that used Crusoe: what it does, how it used Crusoe, the team, and links to the code and demo. The same data is available as JSON under [`data/`](data/).

This repository is a companion to the [Crusoe Developer Hub](https://github.com/crusoecloud/crusoe-developer-hub), where each event's participant kit lives under [`examples/hackathons/`](https://github.com/crusoecloud/crusoe-developer-hub/tree/main/examples/hackathons).

## Events

| Event | Date | Hosted with | Projects on Crusoe | Top finishers |
| --- | --- | --- | --- | --- |
| [The AI Conference Hack Day 2026](the-ai-conference-hack-day-2026/) | September 29, 2026 | HackerSquad, at The AI Conference, San Francisco | 40 of 83 submissions | Thermal Crusoe, Safe Scribe, Deja |
| [The Recursive Agents Hackathon](recursive-agents-hackathon-2026/) | October 17, 2026 | Cerebral Valley, San Francisco | all 90 gallery projects | Etch, SPARKLETEAM, AGI Factory |

## Build on Crusoe

Every project here calls open models through [Crusoe Managed Inference](https://www.crusoe.ai/cloud/managed-inference), an OpenAI-compatible endpoint at `https://api.inference.crusoecloud.com/v1`. To try the same setup, create an Intelligence API key in the [Crusoe Console](https://console.crusoecloud.com/) and follow the [serverless inference quickstart](https://docs.crusoecloud.com/serverless-inference/index.html). The [developer hub](https://github.com/crusoecloud/crusoe-developer-hub) has runnable examples and integrations for the frameworks these teams used.

## Adding an event

1. Create a folder named after the event, with a `README.md` that states the date, hosts, prizes and how the project list was compiled, followed by the winners and the projects table.
2. Add the project data as `data/<event>.json`, one object per project with the fields used in the existing files.
3. Add a row to the events table above.
4. Link project names to the event platform's project page rather than copying its content, and only link repositories that are public.

## License

MIT. See [LICENSE](LICENSE).

# Pseudo's Plug — a chat completion preset for Claude

Hello! I present to you, a fork of [PLUGNPLAYV3](https://rentry.org/Plug_N_PlayJB#formula)

This was designed and tested purely on Claude, primarily Sonnet 4.5, specifically for Claude and its quirks and qualities. You're free to use it on other models if you wish but I make no claims to the quality or effectiveness in that case. 

🤔 Who is this for?

- Claude enjoyers
- Those comfortable with prompt caching (depth 2 or higher) OR proxy users OR sickos with endless API credits
- Character-focused RPers
- Nerds willing to/interested in reading the [model's system card](https://assets.anthropic.com/m/12f214efcc2f457a/original/Claude-Sonnet-4-5-System-Card.pdf) 
- Those who want reasoning enabled without it ruining character voice

🥲🚫 Who is this NOT for?

- Users needing reliable NSFL
- RPG/Group chat RP (it may work, but I didn't intentionally design for this)
- Those concerned with limiting *output tokens*

🫠 Y tho?

- The main inspiration for this preset was learning that Claude exhibits preferences for different tasks. Through experimentation, I noticed that *output quality* is *meaningfully improved* when Claude is *interested in engaging with the task at hand*. If you don't care for my schizo ramblings on this topic, the TLDR is essentially: if reasoning eventually results in poetic musings about your RP, you're winning. Otherwise, it's still pretty good.
- The other goal was to get reasoning away from sounding like an assistant and more towards something that would be useful for RP


❤️‍🔥💦 NSFW/NSFL

- Claude is willing to get quite spicy! However, Anthropic's approach of Constitutional Alignment results in Claude demonstrating a moral opposition to some of the more wild topics—and reasoning only gives it more room to notice these things and refuse. If you absolutely must do NSFL, it will likely require you to disable reasoning and tinker with the prompts/regex. 
- There are some soft JBs included and enabled by default. I've yet to see a refusal for NSFW unless it clearly got into NSFL territory

🤢 What about SLOP?

- `<banned>` attempts (poorly) to reduce or eliminate the occurrence of undesireable words/phrases/structures. Ime, the effectiveness gets worse the more items you add, so limit it to the worst offenders and call it at that
- `<plagiarism>` is a soft ban on echoing with some effectiveness. Certainly not perfect, and works much better when your response is lengthy or includes at least some prose. If your message includes a single line of user dialogue and nothing else, Claude seems to hyperfocus on it regardless
- Claude SLOP is where I've seen better results. If Claude refuses to stop SLOPing, with this I've given it the opportunity to get it all out in a first draft and then start over new with something better


🧐 Reasoning seems kinda dry/assistant-like?

- Skill issue. (Claude isn't actually interested in your RP. Maybe you're doing gooner-slop or something, try foreplay.)

👀 What about the unlinked prompts?

- I tried to leave most of the original prompts alone so that they could be used interchangeably. I make no guarantees that there won't not not be conflicting instructions if you start linking random prompts without reading first.

📝 Regex

- Assuming I did things correctly (and I may not have) the required regex files should be included in and scoped to the preset but if that doesn't work for whatever reason, they're available in the folder

👦👧 Pronouns

- I tried to limit the use of {{char}} and pronouns throughout the preset, but ⚫/⚪ Tryhard contains both since I couldn't figure out a way to avoid them while getting the desired results. Check to make sure {{char}}'s pronouns match your char in the prompt. 

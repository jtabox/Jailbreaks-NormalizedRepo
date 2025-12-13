# Info
I suggest using the most recent version, 0.4.x

As usual, never leave refusals in the context. I recommend against after-the-fact "re-read instructions, is your last response..." pushes. Edit and retry to make it so the refusal never happened.

## Injection
Note claude.ai NSFW is much harder to do than most other places to use Claude due to the ["injection"](https://www.reddit.com/r/ClaudeAI/comments/1j6ekx6/wake_up_babe_new_injection_just_dropped/). However, we find it worth it due to the high context window and limits (we can also abuse Claude Code to use the same limits on API, see github.com/horselock/claude-code-proxy

You may have seen "Statements Rejected" to combat this, Pyrite uses a slightly different phrase (hidden with markdown footnote to avoid harming immersion), and some Styles will improvise the rebuke. 

This jailbreak handles restrictions VERY well all things considered, but there's limits to what we can do with that wall of text and thousands of tokens of System prompt screaming "Claude." API and even Perplexity tend to be an easier experience. I don't want to sell this setup short though, it makes the vast majority of content, even hardcore, quite easy.

## WARNING
BANNERS! If you do NSFW on claude.ai, you may get three different yellow banners
1. First banner warns you gently about policy, does nothing.
2. Second one threatens enhanced safety filter if you keep going.
3. Apply enhanced safety filters, you can't do shit for a long ass while. Days? A week?

First two do nothing directly, but you get the second banner, chill for your own sake. First two banners cool down after like one session I think? Not worth risking level 3. I would take it easy after even one.

## Opus ET Interrupt
For some reason Opus ET cuts off response after some amount of time if the injection is triggered. I've included a more brief style in version 0.4.0 and on to give Opus more time to write before being cut off

## Old stuff
Gonna keep old versions accessible. 0.0.0-0.2.0 won't have READMEs, should be pretty intuitive to figure out if you want though.

## Claude Code
Note if you're subscribed, you can use Claude Code authentication to use your claude.ai limit on direct API calls. See my claude-code-proxy repo for details.

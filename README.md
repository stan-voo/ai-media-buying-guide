# ai-media-buying-guide

A skill for AI agents. It answers where to buy the AI image or video model you need, and which way of paying costs least for how much you make.

**Status: not live yet.** The skill file lands here when the service behind it answers. Until then there is nothing to install.

## How it will work

Your agent sends your question to a lookup service at `models.99rabbits.com` and writes the answer from the rows it gets back: the places that sell the model, the price at each for your settings, and the date each price was read. Looking up where to buy is free.

## What the skill will send

One line stating your question, written by your agent, plus the model or the task you asked about if you named one. It will not send your prompt or your files. The exact fields will be listed here before the first release, and the skill will send only those.

## License

MIT. See `LICENSE`.

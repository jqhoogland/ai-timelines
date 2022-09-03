# AI Timelines

A collection of AI timelines modeled with [Squiggle](https://www.squiggle-language.com/).

### Timelines

Currently, this repo houses a simplified version of [Ajeya Cotra's AI timelines report](https://www.lesswrong.com/posts/KrJfoZzpSDpnrv9va/draft-report-on-ai-timelines). 

### About Squiggle

[Squiggle](https://www.squiggle-language.com/) is a programming language for probabilistic estimation perfect for writing and sharing models like these.

It's still early-stage, so this repo is also very much a proof-of-concept for the language. There are a few limitations:
- No native-support for skew-normal (yet). Cotra makes use of skew-normal a lot. We have to make do with a dingy replacement.
    - To see the same model but with skew-normals replaced with log-normals, check out `/cotra2020-alt`.

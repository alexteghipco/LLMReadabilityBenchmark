# LLM Readability Benchmark
Human readability judgments as a benchmark for LLMs

Ever wonder which of the many Large language models (LLMs) you can use have the best understanding of what makes text 'readable'? Me too! Here, we will benchmark (prompt) a wide range of large language models on their ability to reproduce human judgments about the readability of short fictional and nonfictional passages. We'll test different models on different prompts, finding the models that tend to do best.

The attached notebook lays out a series of informal experiments comparing many open and closed LLMs.

The result: small open source models that you can run locally are competitive with GPT4o-Turbo and GPT4o-mini, particularly Google's newly released Gemma2 (2B model performed just about as well as the 27B model across prompts). Here's a slice of some of the tested models (GPT4oTurbo did as well as mini):

<img align="center" width="1200" height="600" src="https://i.imgur.com/Lac7vgr.png">

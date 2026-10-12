# Learning Log

## Day 1 – Azure AI Foundry Setup

### 💡 What surprised me

How little it took to get a model answering. A **resource group**, one **deployment** and the **Foundry playground** were enough to get a response, which was much quicker than I expected.

### ⚠️ What didn't behave as expected

My first model, **`gpt-5-mini`**, had **no temperature control** in the playground. I went looking for the slider to make answers more or less random, and it simply wasn't there.

As far as I can tell, `gpt-5-mini` is a *reasoning model*, and those don't let you set temperature.

> **Note:** I'm treating this as a model limitation rather than a setup mistake, but I haven't confirmed it in the docs yet.

### 🔁 What I'd change next time

- Check what settings a model supports **before** deploying it, instead of finding out in the playground.
- If I need to tune temperature, pick a **non-reasoning model** for that experiment.
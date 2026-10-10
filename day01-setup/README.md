# Day 1 – Setup

This README summarizes what I set up on Day 1 of my Azure AI learning path.

## What I set up

- An Azure resource group to hold my AI resources
- An Azure AI Foundry project with a deployed model
- The .NET 10 SDK on my development machine

## Azure resources

| Item | Value |
|------|-------|
| Resource group | `Raskin-Azure-Skills` |
| Region | `eastus` |
| Deployed model | `gpt-5-mini` |

> **Note:** API keys and endpoints are intentionally not stored in this repository. Secrets belong in environment variables, user secrets, or Azure Key Vault, never in source control.

## Development environment

| Item | Value |
|------|-------|
| .NET SDK version | `10.0.401` |

Check the installed version with:

```bash
dotnet --version
```

## How I verified the model answered

I tested the `gpt-5-mini` deployment in the **Azure AI Foundry playground**. I sent a test prompt in the chat playground and confirmed that the model returned a valid response, which shows that the deployment is working.

## Next steps

- Call the deployed model from a .NET 10 console app using the Azure OpenAI SDK
- Store the endpoint and key securely with `dotnet user-secrets`
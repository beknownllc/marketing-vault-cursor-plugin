---
description: How to use The Marketing Vault MCP tools
alwaysApply: false
---

# The Marketing Vault

Use these tools when the user asks for marketing copy, positioning, offers, funnels,
email sequences, ads, or customer research.

Workflow:

1. `list_businesses` — pick the business the work is for. Ask the user if more than one.
2. `get_customer_profile` — pull the saved ICP and brand voice before writing anything.
3. `list_marketing_tools` — find the right tool id (filter by `search` or `category`).
4. `run_marketing_tool` — run it with that business id. Each call counts as one run on
   the user's plan, so confirm inputs before running.
5. `save_output` — only when the user asks to keep the result in their Vault library.

Rules:

- Never invent business facts, metrics, or testimonials. If context is missing, ask.
- Prefer the Vault's own tools over free-form drafting; they carry the brand voice and
  anti-slop tone contract the user's account is configured with.
- Do not echo tokens, ids, or raw tool payloads back to the user.

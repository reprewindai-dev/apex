# AGENTS.md — READ FIRST

Before any work, read [`00_VEKLOM_BIBLE.md`](./00_VEKLOM_BIBLE.md).

Apex is a standalone blueprint/product surface and a source of reusable capability logic. Inside Capability OS, reuse validated domain logic and build a Veklom-native surface; do not embed the standalone product wholesale.

Repo-local source and tests govern implementation details only when they do not conflict with current runtime evidence or the Bible. Use Coolify UI/API/MCP for Coolify management; SSH is for direct host/container verification or operations. Host `8000` is currently Coolify-owned.

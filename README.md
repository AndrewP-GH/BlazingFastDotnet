# Blazing Fast .NET

Tips & tricks to tune .NET workloads for better performance (mostly targeting benchmarks), packaged as a single [`SKILL.md`](SKILL.md) for AI coding agents. It reads fine as a regular doc too.

Covers runtime knobs, NativeAOT settings, profiling (`dotnet-counters`, `dotnet-trace`, `perf`, JIT disassembly), safe high-performance C# patterns, contention and false sharing, and ASP.NET Core.

> Targets .NET 10 and 11. Much of this may not age well - measure before and after every change.

## Install as a skill

GitHub Copilot CLI (all projects):

```sh
mkdir -p ~/.copilot/skills/blazing-fast-dotnet
curl -fsSL -o ~/.copilot/skills/blazing-fast-dotnet/SKILL.md https://raw.githubusercontent.com/EgorBo/BlazingFastDotnet/main/SKILL.md
```

For a single repository, put it at `.github/skills/blazing-fast-dotnet/SKILL.md`. Other agents that support `SKILL.md` skills (e.g. Claude Code's `~/.claude/skills/`) work the same way.

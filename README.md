state - share amid agents, persisted amid runs

shell - set of tools provided to agent

tool

task

goal

agent - has its own context and acts as some role

context

# dotfiles for Agents

```
/agent --goals=review --rules=accounting --extra='what ever details for this case'
```

will trigger read review.md goal tool within rules accoutning.md and extra context


## Intresting links

https://github.com/msitarzewski/agency-agents

https://github.com/anthropics/skills

https://modelcontextprotocol.io/docs/getting-started/intro

## Unix

Context and runs are sotred in local files, tools are cli, may be run in modern sandboxes (NOT vm neither contaijners), ortogolan split (not skills which mist all)

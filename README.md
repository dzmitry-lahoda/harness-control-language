state - share amid agents, persisted amid runs

shell - set of tools provided to agent

tool - functions for the AI model to execute

task

goal

agent - has its own context and acts as some role

context

reasoning - build plan, breakdown problems, solve each part, check solutions, combine parts, draft solution, reivew solution,

modes - interactive | non_interactive

# dotfiles for Agents

```
/agent --goals=review --rules=accounting --extra='what ever details for this case'
```

will trigger read review.md goal tool within rules accoutning.md and extra context

## Unix

Context and runs are sotred in local files, tools are cli, may be run in modern sandboxes (NOT vm neither contaijners), ortogolan split (not skills which mist all)

# Week 1 evidence

Keep this short. Bullet points, a small table and one diagram or code trace are enough. This is your checkpoint record, not an extra report. Replace the prompts as you work.

Name: Noa Cederlund
Exact Unity version: 6000.3.26f1
Checkpoint commit / repository: 
Current stage and anything unfinished: 

## Initial prediction

Three observations the rival needs, including one it might not have: 1. It can see pickups but not through walls 2. It can pathfind to coordinates selected from seeing the pickup and then back to its dropoff. 3. While not vital it needs to be able to prioritize closer pickups and ideally go for pickups that it will reach before the other AI does.

Seeing a pickup across a gap proves / does not prove reachability because: It does not prove reachability unless the AI can also find a path to it, be that jumping the gap or walking around it.

One question about NPC behaviour: How does it work when it detects certain terrains and what it can do to pathfind past or over them? Like the more technical side.



> Unable to provide the rest for now :(



## One complete trace

Use one actual situation. Include the observation data, derived facts, selected task and reason, movement request/result, and how feedback affects a later decision. Identify the responsible code locations. A tiny state diagram can accompany this trace.


## Scenario record

| Scenario | Predicted result | Observed result and short evidence / remaining issue |
|---|---|---|
| Normal loop and restart | | |
| Carrying cargo | | |
| Hidden / remembered pickup | | |
| Target taken | | |
| Unreachable target | | |
| No usable pickup | | |

Supplied test result, with any added tests identified:
Live walkthrough checked by / recording link if used:

## One correction and one independent check

The original weakness and why it happened:
What I changed and why it addresses the cause:
My counterexample or experiment: prediction, observed result, and one limitation:

## Collaboration and help

People I discussed or playtested with:
Code, sources or substantive tools/AI assistance I used, and how I verified them:
If unfinished: what works, exact reproduction steps, and the help I need:

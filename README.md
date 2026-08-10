# AUTONOMIC

A protocol, CLI, and plugin system for autonomous sprint execution by AI agents: a four-gate quality system, tiered execution levels, a structured abort contract, and a learning loop that improves scoring over time.

## The problem

"Let the agent run autonomously" usually means no safety rails — it either completes the task or fails silently partway through with no record of why. Real autonomous execution needs a defined contract: what counts as done, what triggers an abort, what gets logged when something goes wrong, and how the system gets better at judging its own work over time.

## What it does

AUTONOMIC defines the protocol layer for autonomous task execution — a sprint format, a four-gate quality check before/during/after execution, tiered autonomy levels (fully autonomous vs. gated-with-checkpoints), and a structured contract for what happens on abort: a ticket gets filed, not a silent failure. The learning loop tracks outcomes against the pre-flight confidence score, so scoring calibrates against real results over time.

## Part of a system

AUTONOMIC is the sprint-execution protocol for a larger cognitive-infrastructure stack. See [davidkirsch.me/builds](https://davidkirsch.me/builds) for the rest.

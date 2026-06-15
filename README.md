# Deep Reasoning Protocol

A production-ready Claude Skill that forces Claude to engage in deep, structured reasoning *before* providing an answer. Developed by Antigravity.

## What This Skill Does

Intelligence requires structure. Answering immediately leads to shallow thinking and hallucinations. This skill forces Claude into a mandatory "thinking phase" prior to response formulation. 

- **Complexity Auto-Detection**: Claude automatically scales the depth of its reasoning based on your prompt (Simple, Medium, Complex).
- **Visible Reasoning Layers**: You see exactly how Claude reached its conclusion through structured blockquotes (e.g., `> **Layer 1: Deconstruction:**`).
- **Token Efficient**: Simple questions get quick answers. Complex problems get thorough, multi-layer breakdowns.
- **Edge Case Bulletproof**: Contains explicit guardrails for analyzing massive inputs (like PDFs), handling logical traps, and resolving multi-part questions without dropping context.

## Who It's For

For power users, developers, and researchers who need Claude to stop guessing and start calculating. If you want high-fidelity, rigorously tested answers rather than quick conversational replies, this skill is for you.

## How to Use It

To install this skill, simply copy the raw URL below and paste it into your Claude project instructions or provide it directly to your agent:

```text
https://raw.githubusercontent.com/Pavan7730/deep-reasoning-protocol/main/SKILL.md
```

Alternatively, you can download the `SKILL.md` file directly from this repository and attach it to your workflow.

# AI

I feel one thing people do not take into consideration in the AI world is that productivity for productivity's own sake is a useless waste of energy. One must always ask why the human element cares, rather than expending energy on something that will not impact anyone. Technology is not culture. Technology for technology's own sake doesn't make sense.

## Risk, Security and Cost

My API key was compromised for Google Cloud just because I hosted a map, due to the open permissions on the key. Someone was able to create multiple AIs that operated autonomously and cost me money.
I locked down everything immediately and created completely new keys with extremely restricted permissions.

When using AI you should not trust by default. You should isolate the sandbox environment and not share your daily-use environment with the machine. If you do have AI step in, you should peer review every action it takes and act on the assumption that it will try to break things at every opportunity.

> Maintain a healthy disdain for AI.

## Shrink the Context and Scope

To achieve the highest quality results, focus on always shrinking the context and scope of the task you assign the AI.

By **context**, I am referring to the network or set of information you provide the AI to look through. Instead of being vague and generic, provide specific files, line numbers, and API names.

By **scope**, I mean the complexity of the task assigned to the AI. By giving it extremely explicit instructions for what you want, you'll increase your likelihood of a high quality result. Avoid negative information because the AI does not have a concept of negative vs. positive — you are merely introducing more tokens that will affect its pattern recognition. Use the tokens you submit to focus on what's correct and be specific.

## Planning and Compression

A feature initially called "planning" in Cursor IDE allows you to spend a phase discussing with an AI chatbot the task you want it to complete in a purely conversational sense. It enables the AI to perform research, collect its thoughts, and attempt to predict potential questions it would encounter, so it can prompt you on how to best resolve them rather than letting it come up with its own solution mid-file mutation.

As you chat with the agent, it flushes out a markdown file containing the discussion and the key action item deliverables. This is called **compression** in the AI world — it allows you to cut the conversation short and take the summarized results as a starting point for a new conversation thread where the agent performs the actual mutations, perhaps autonomously over a longer period of time without your intervention.
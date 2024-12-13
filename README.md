<img src="./images/claude_perspective.png" alt="The Claude Perspective" width="700"/>

# The Claude Perspective: A Guidebook to AI-Human Collaboration ([Top Page](https://abagames.github.io/claude-perspective/en/))

English / [日本語](./README_ja.md)

---

# Having Claude Create Its Own Guidebook

What constitutes an appropriate prompt for Claude? While there are various prompt engineering tips available, why not ask Claude itself? With this thought in mind, I asked:

> Please create a chapter structure discussing prompt quality from Claude 3.5 Sonnet's own perspective.

After several exchanges, we created a [chapter structure](./llm-perspective-guide-with-intro.md).

> Please create a prompt to write the guide content using this chapter structure.

Then, I created a [prompt](./llm-guide-writing-prompt.md) for the actual writing.

The resulting guidebook is [The Claude Perspective: A Guide to AI-Human Collaboration](https://abagames.github.io/claude-perspective/en/). The guidebook underwent multiple improvements through dialogue based on the output from the above prompts.

The resulting guide is easy to understand, with specific prompt examples. It's interesting to note how it expresses its approach to [handling complexity and ambiguity](https://abagames.github.io/claude-perspective/en/chapters/chapter-3-complexity.html), which it acknowledges as challenging, and what approaches it takes or would like humans to take.

In [Appendix A: Insider Tips from Claude - A Self-Reflective Analysis](https://abagames.github.io/claude-perspective/en/chapters/appendix-a-tips.html), Claude provides an even more self-analytical description. The challenges it identifies as needing to overcome, such as "risk of overconfidence in certain domains" and "challenges with extremely open-ended creative tasks," align well with users' experiences.

## Claude's Characteristics and Challenges

This guide creation project had two objectives: one was to create a useful guide itself, and the other was to explore methods for creating better documents with Claude. Through creating this guide, we discovered the following LLM characteristics.

### Endless Improvement Suggestions

Claude tends to constantly propose improvements. Initially, when trying to evaluate whether the guide's content was sufficient for its purpose, Claude consistently suggested various improvements. While this might seem beneficial, it's also a drawback in that it cannot judge when the current guide is "sufficient."

One countermeasure is to provide some form of requirements specification for the document. For example, we can present the initial prompt again and verify whether the current guide meets those requirements. However, even when evaluating based on requirements specifications, the LLM sometimes broadly interpreted the requirements themselves and proposed substantial modifications. There are limitations to control through requirements specifications.

### Excessive Use of Bullet Points

Claude showed a tendency to abbreviate text and extensively use bullet points. While this might be influenced by English technical documentation, it's not necessarily optimal for Japanese documents. It's necessary to specify appropriate expression methods based on the document's purpose and content.

### Claude's Self-Recognition of Capabilities

While we instructed Claude to describe its own capabilities, it's unclear whether this instruction was meaningful. The resulting guidebook comprehensively covers general information necessary for dialogue with LLMs, so it can be said to correctly describe capabilities to some extent. However, it might not be based on Claude's specific characteristics. Currently, there's no way to verify this.

## Moving Forward with Document Creation

These insights can serve as guidelines when collaborating with Claude and similar LLMs to create documents.

1. Prior Requirements Definition
   By defining clear requirements specifications before beginning document creation, we can create more focused deliverables.

2. Conscious Choice of Expression Methods
   Consider the balance between textual explanation and bullet points based on the document's purpose and content.

3. Continuous Dialogue and Adjustment
   Deepen mutual understanding through dialogue with the LLM to create better deliverables.

## Conclusion

While Claude and other LLMs can be very powerful collaborators in document creation, it's important to understand their characteristics and use them appropriately. Through this experience, we gained several insights about effective collaboration with LLMs, but we also learned that further improvements are needed.

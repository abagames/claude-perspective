<img src="./images/claude_perspective.png" alt="The Claude Perspective" width="700"/>

# The Claude Perspective: A Guidebook to AI-Human Collaboration ([Top Page](https://abagames.github.io/claude-perspective/en/))

English / [日本語](./README_ja.md)

---

## Having Claude Create Its Own Guidebook

What makes an effective prompt for Claude? While there are numerous prompt engineering tips available, I thought it would be interesting to ask Claude itself. With this approach in mind, I started with the following question:

> Please create a chapter structure discussing prompt quality from Claude 3.5 Sonnet's own perspective.

After several exchanges, we created a [chapter structure](./llm-perspective-guide-with-intro.md).

> Please create a prompt to write the guide content using this chapter structure.

Then, I created a [prompt](./llm-guide-writing-prompt.md) for the actual writing.

This process resulted in [The Claude Perspective: A Guide to AI-Human Collaboration](https://abagames.github.io/claude-perspective/en/). Through iterative dialogue and refinement based on the initial prompts, the guidebook went through multiple rounds of improvements to reach its final form.

The resulting guide is easy to understand, with specific prompt examples. It's interesting to note how it expresses its approach to [handling complexity and ambiguity](https://abagames.github.io/claude-perspective/en/chapters/chapter-3-complexity.html), which it acknowledges as challenging, and what approaches it takes or would like humans to take.

In [Appendix A: Insider Tips from Claude - A Self-Reflective Analysis](https://abagames.github.io/claude-perspective/en/chapters/appendix-a-tips.html), Claude provides an even more self-analytical description. The challenges it identifies as needing to overcome, such as "risk of overconfidence in certain domains" and "challenges with extremely open-ended creative tasks," align well with users' experiences.

### Claude's Characteristics and Challenges

This guide creation project had two objectives: one was to create a useful guide itself, and the other was to explore methods for creating better documents with Claude. Through creating this guide, we discovered the following LLM characteristics.

#### Endless Improvement Suggestions

One notable characteristic of Claude is its persistent tendency to suggest improvements. When evaluating whether the guide's content was sufficient for its purpose, Claude consistently proposed various enhancements and additions. While this continuous improvement mindset can be beneficial, it also reveals a limitation: Claude appears to have difficulty determining when a document has reached a "sufficient" or "complete" state.

One countermeasure is to provide some form of requirements specification for the document. For example, we can present the initial prompt again and verify whether the current guide meets those requirements. However, even when evaluating based on requirements specifications, the LLM sometimes broadly interpreted the requirements themselves and proposed substantial modifications. There are limitations to control through requirements specifications.

#### Excessive Use of Bullet Points

Claude showed a tendency to abbreviate text and extensively use bullet points. It's necessary to specify appropriate expression methods based on the document's purpose and content.

#### Claude's Self-Recognition of Capabilities

While we instructed Claude to describe its own capabilities, it's unclear whether this instruction was meaningful. The resulting guidebook comprehensively covers general information necessary for dialogue with LLMs, so it can be said to correctly describe capabilities to some extent. However, it might not be based on Claude's specific characteristics. Currently, there's no way to verify this.

### Moving Forward with Document Creation

These insights can serve as guidelines when collaborating with Claude and similar LLMs to create documents.

1. Prior Requirements Definition
   By defining clear requirements specifications before beginning document creation, we can create more focused deliverables.

2. Conscious Choice of Expression Methods
   Consider the balance between textual explanation and bullet points based on the document's purpose and content.

3. Continuous Dialogue and Adjustment
   Deepen mutual understanding through dialogue with the LLM to create better deliverables.

### Conclusion

While Claude and other LLMs prove to be powerful collaborators in document creation, their effective use requires a clear understanding of their characteristics and limitations. This experience has provided valuable insights into effective collaboration with LLMs, while also highlighting areas where our approach to working with these AI assistants can be further refined and improved.

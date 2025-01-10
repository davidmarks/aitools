# AI Tools Collection

Welcome to the **AI Tools Collection**! This repository provides free-to-use tools to enhance AI-driven workflows. All tools are licensed under the [MIT License](LICENSE), allowing unrestricted use and modification with attribution.

---

## 📌 Tools

### 1. **Chat Context Compressor**
A simple yet effective tool for compressing chat session contexts into a compact "context pill." This pill can be copy-pasted at the end of your current chat session and reused to initialize a new session, saving tokens and maintaining continuity across conversations.

#### How to Use
1. **Copy the Prompt:** 
   At the end of your chat session, use the provided prompt to generate a "context pill."
2. **Paste in New Session:**
   Copy the generated context pill and paste it into a new session to initialize the conversation with minimal token usage.

#### Example Prompt

Read entire convo. Output minimal info for reproducing same answers in a new session:
1) Key probs & fixes (IssueA→FixA)
2) Crucial refs/codes/vars (abbr if possible)
3) Lessons/guidelines
4) Skip irrelevant details
5) Problem-Solution Statement (overview + success keys)
6) Domain expertise (e.g. "Expert Python dev")
7) Tools used & files needed

Use compression (keywords, reduction, paraphrase, abstraction, extraction, redundancy removal, abbreviations, synonyms, condensation, thematics).

Only output code block labeled CONTEXT_PILL, no extra text. Example:

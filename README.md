# AI Tools Collection

Welcome to the **AI Tools Collection**! This repository provides free-to-use tools to enhance AI-driven workflows. All tools are licensed under the [MIT License](LICENSE), allowing unrestricted use and modification with attribution.

---

## 📌 Tools

### 1. **Chat Context Compressor**
A simple yet effective tool for compressing chat session contexts into a compact "context pill." This pill can be copy-pasted at the end of your current chat session and reused to initialize a new session, saving tokens and maintaining continuity across conversations.

How to use:
1. **Copy the Prompt:** 
   At the end of your chat session, use the provided prompt to generate a "context pill."
2. **Paste in New Session:**
   Copy the generated context pill and paste it into a new session to initialize the conversation with minimal token usage.
<<THIS IS LIKELY OBSOLETE AS CONTEXT COMPRESSION IS PART OF MOST FRONTIER LLMS NOW>>

### 2. **Agentic Patterns Library**
I list of useful agentic AI application patterns (e.g. reflector). Right now this is a simple list with descriptions of use, if agentic frameworks stabilize for a bit I may drop some code examples here in the future.

* Reflection pattern
* Tool use
* Planning
* Collaboration
<<HEH, THIS CHANGED FAST. THESE PATTERNS STILL WORK BUT THERE ARE SO MANY MORE NOW, AND DYNAMIC AGENT GRAPHS ARE A THING>>
  
### 3. **talk_notes**
A prompt that translates raw transcripts to organized notes. Useful for conference sessions, lectures, etc. I typically use this with a speech-to-text model in a pipeline, and modify as needed to customize the output for my current priorities.

### 4. **systematic_debugger**
A prompt that helps to systematically debug software and engineering problems. Based on some research on how to diagnose problems and find root causes. Works surprisingly well.
<< AS OF MARCH 2026, THIS ONE **STILL** OUTPERFORMS DEBUGGING TASKS ON OPUS 4.6 COMPARED TO VANILLA BY A WIDE MARGIN. WORTH UNDERSTANDING WHY... >>


Note of relevance: Check the date of these tools before using -- things move fast, and some of these tools are likely pretty outdated by now!

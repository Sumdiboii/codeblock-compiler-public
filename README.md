<!-- TITLE with Animated Typing Effect -->
<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=1B7A43&center=true&vCenter=true&width=600&lines=CodeBlock%3A+Write+It%2C+Run+It%2C+Understand+It;Compile.+Analyze.+Explain.;Now+with+SumoLang." alt="Typing SVG" />
</p>

<h1 align="center">⌨️ CodeBlock ⌨️</h1>
<h3 align="center">Write It, Run It, Understand Its Complexity.</h3>

<br>

<p align="center">
  <a href="https://code-nebula-lyart.vercel.app/">
    <img src="https://img.shields.io/badge/View%20the%20Project-Live%20Demo-1B7A43?style=for-the-badge&logo=vercel&logoColor=white" alt="💚 View the Project" />
  </a>
</p>

<br>

---

## 🚀 What Did I Build?

**CodeBlock** is an online multi-language compiler and IDE — built with **TanStack Start**, **React 19**, and **Supabase** — that runs your code, analyzes it, and explains it back to you.

- Sandboxed execution for **5 languages**: Python, C++, Java, JavaScript, and **SumoLang** (a custom language I designed and built from scratch)
- **Complexity Profiler**: rule-based static analysis that estimates Big-O time & space complexity from loop nesting, recursion, and known algorithmic patterns
- **AI Explain Button**: turns a raw stack trace into a plain-English explanation with a suggested fix
- **Test Case Runner**: custom stdin, expected output, and a line-by-line pass/fail diff
- **Snippet Library**: save your code to your account and pick up where you left off
- **Share Links**: flip any snippet public for a short URL, with optional auto-expiry
- **Whiteboard**: sketch out your logic on a built-in canvas, in-editor or full-page
- **Typing Trainer**: a Monkeytype-style practice mode for coding speed and accuracy
- 8 switchable visual themes, synthesized sound effects, and full keyboard shortcuts

<br>

---

<br>

## ☁️ What is This Project?

**CodeBlock** is a full-stack online IDE designed for people who don't just want to run code — they want to understand it. It pairs a fast, sandboxed multi-language execution pipeline with tooling that a normal online compiler doesn't offer: a static complexity analyzer, an AI-powered error explainer, and a language of its own.

**SumoLang** is a small language I designed with competitive programmers in mind — concise syntax, fast I/O by default — complete with its own lexer, recursive-descent parser, AST, and tree-walking interpreter, running entirely server-side with a step-budget to keep execution safe.

It's built to feel like a real developer tool: fast, secure, and genuinely useful for practicing, debugging, and learning — not just a code-runner.

<br>

---

<br>


---

## 🛠️ Tech Stack and Tools

<br>

<div align="center">

<table>
  <thead>
    <tr>
      <th>Tech Used</th>
      <th>Purpose</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>TanStack Start (React 19)</td>
      <td>SSR framework with typed server functions</td>
    </tr>
    <tr>
      <td>Vite + Nitro</td>
      <td>Build tooling and server runtime, deployed via the Vercel Build Output API</td>
    </tr>
    <tr>
      <td>TanStack Router / Query</td>
      <td>File-based routing and data fetching</td>
    </tr>
    <tr>
      <td>Tailwind CSS v4 + shadcn/ui</td>
      <td>Styling and component primitives</td>
    </tr>
    <tr>
      <td>CodeMirror 6</td>
      <td>Code editor, with a custom language mode for SumoLang</td>
    </tr>
    <tr>
      <td>Supabase</td>
      <td>Auth, Postgres database, and Row-Level Security</td>
    </tr>
    <tr>
      <td>Judge0 CE</td>
      <td>Sandboxed multi-language code execution</td>
    </tr>
    <tr>
      <td>Vercel AI SDK</td>
      <td>AI-powered error explanations with provider fallback</td>
    </tr>
    <tr>
      <td>Zod</td>
      <td>Input validation on every server-function boundary</td>
    </tr>
    <tr>
      <td>Vercel</td>
      <td>Hosting and deployment</td>
    </tr>
  </tbody>
</table>

</div>

<br>

---

<br>

## 🔐 Core Features

- 💻 Sandboxed execution across 5 languages, including a custom-built one
- 📊 Static Big-O complexity profiler (time & space), built as a pure, swappable analyzer function
- 🤖 AI "Explain this error" with plain-English fixes
- 🧪 Custom test case runner with line-level diffing
- 📁 Save, revisit, and manage code snippets tied to your account
- 🔗 Public share links with optional expiry, secured via Postgres RLS
- 🎨 In-editor and full-page whiteboard for sketching out logic
- ⌨️ Typing trainer with live WPM, accuracy, and error tracking
- 🌈 8 themes with ambient visual effects, zero-asset synthesized sound
- ⌨️ Full keyboard shortcuts (Run, Save, Clear console)

<br>

---

<br>

## 🔍 Learning Highlights

- Designed and implemented a custom programming language end-to-end: lexer, recursive-descent parser, AST, and a sandboxed tree-walking interpreter
- Built a language-agnostic static analysis engine to estimate algorithmic complexity from source code
- Architected a secure multi-tenant data layer with Supabase Row-Level Security for private and public data
- Integrated an LLM provider-fallback chain so AI features stay available even when one provider rate-limits
- Solved SSR-specific engineering challenges — hydration-safe mounting for browser-only APIs like canvas, audio, and the code editor
- Practiced strict secret discipline: no API key ever reaches the client bundle

<br>

---

<br>

## 🚧 Future Plans

- 🧠 Swap the rule-based complexity profiler for a trained ML classifier
- 🌐 Expand language support beyond the current 5
- 📜 Version history for saved snippets
- 🏆 A code-golf style leaderboard for SumoLang submissions
- 📱 Further mobile-first refinements

<br>

**CodeBlock** is still growing — smarter analysis and more languages are on the way.

<br>

---

<br>

## 👨‍💻 About the Creator

**Sumdiboii** – Developer & Compiler Enthusiast

*LinkedIn – [Sumedh Pimplikar](https://www.linkedin.com/in/sumedh-pimplikar)*

<br>

> **Write it, run it, understand it —**
> **CodeBlock turns any snippet into a lesson in how your code actually works.**
> **Built by passion. Compiled with precision.**

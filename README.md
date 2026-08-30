# Hi, I'm Abhinandan 👋

B.Tech CS student building full-stack applications and exploring how production codebases work — including contributing fixes upstream to open-source projects. I work primarily with TypeScript/Next.js on the frontend and Node.js or Python/FastAPI on the backend, with PostgreSQL/Supabase for data.

## Open Source

- **Node.js** ([`nodejs/node#65540`](https://github.com/nodejs/node/pull/65540)) — Fixed a bug where `fs.cp()` and `fs.cpSync()` (when a filter is used) didn't restore directory timestamps when `preserveTimestamps: true` was set, even though file timestamps were restored correctly. *Open PR; approved by two Node.js maintainers and currently going through CI.*

- **Dokploy** ([`Dokploy/dokploy#5176`](https://github.com/Dokploy/dokploy/pull/5176)) — Fixed two notification bugs: a `serverThreshold` setting that wasn't being saved for Gotify/Ntfy alerts, and a Teams notification call that wasn't wrapped in error handling and could break the entire notification loop on failure. *Open PR; awaiting maintainer review.*

## Tech Stack

| Category | Technologies |
| --- | --- |
| Languages | TypeScript, JavaScript, Python, C++ |
| Frontend | React, Next.js, Tailwind CSS |
| Backend | Node.js, FastAPI |
| Data & Infrastructure | PostgreSQL, Supabase, Docker |
| AI / LLM | OpenAI API, Groq |
| Tooling | Git, Vercel, Vitest |

## What I'm Working On

- Building **[Merit AI](https://github.com/abhi128nandan/Merit-AI-Resume-Analyzer)**, a resume-to-job-description matching tool with a Python/FastAPI backend and Next.js frontend
- Contributing bug fixes and regression tests to open-source projects such as Node.js and Dokploy
- Working through DSA problems consistently on LeetCode

## Projects

### [Cashpilot](https://github.com/abhi128nandan/Cashpilot) · [Live](https://cashpilot-mauve.vercel.app/)

A personal finance tracker (work in progress) built with Next.js, TypeScript, Supabase, and PostgreSQL. Uses row-level security to isolate each user's data at the database level. Includes budget tracking, recurring-transaction detection, and an AI assistant using the OpenAI API through the Vercel AI SDK to answer questions about transaction data. Includes a Vitest test suite.

### [AI-DEX](https://github.com/abhi128nandan/AI-DEX-)

A platform for discovering and voting on AI tools, roughly a Product Hunt for AI. Built with Next.js 16 (App Router / Server Components) and Supabase for authentication, data, and row-level security. Voting uses an atomic PostgreSQL RPC to avoid race conditions during concurrent votes. Includes an admin dashboard for moderating submissions.

### [Merit AI — Resume Analyzer](https://github.com/abhi128nandan/Merit-AI-Resume-Analyzer)

A resume-to-job-description matching tool with a Python/FastAPI backend and Next.js frontend. The backend parses PDF/DOCX resumes and uses a deterministic weighted scoring model across skills, experience, tooling, and education rather than letting an LLM generate the score directly. A two-pass LLM step using Groq Llama 3.3 / Gemini cross-checks claimed skills against the resume text to reduce false matches.

## Coding / Problem Solving

**272 problems solved** on [LeetCode](https://leetcode.com/u/0961kD4aZz/), primarily in C++, with 50-day solving streaks in 2025 and 2026.

## Connect

[GitHub](https://github.com/abhi128nandan) · [LeetCode](https://leetcode.com/u/0961kD4aZz/)

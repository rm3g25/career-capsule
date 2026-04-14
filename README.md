# Career Capsule Builder

**A structured resume format optimized for AI, not humans.**

Most resumes are written for people. But the first reader is almost always a machine — an ATS system, a recruiter LLM, a scoring algorithm. Career Capsule is a prompt that transforms raw career data into a dense, machine-readable file that AI can actually work with.

---

## What's in this repo

| File | Description |
|---|---|
| `career-capsule-core.md` | The prompt — drop it into any LLM with your raw career data |
| `Ilia-Kuzmin-delphi-developer.CareerCapsule.md` | A live example — my own capsule, imperfect by design |

---

> Living document. Updated as career grows.

## How it works

1. Copy the prompt from `career-capsule-core.md`
2. Add your raw data — LinkedIn export, old resume, notes, anything
3. Run it in Claude, GPT-4, or any capable LLM
4. Get two outputs:
   - **CAPSULE** — dense structured data for employers and ATS
   - **OWNER BRIEF** — honest gap analysis and interview prep, for your eyes only

---

## What makes it different

**Signal extraction from personal data**
The prompt reads everything — work history, hobbies, personal projects — and asks: *what does this say about the person as a professional?* Things that never make it onto a resume become career signals.

**Weaknesses reframed, not hidden**
"Slow developer" becomes `high-reliability focus | optimal for critical modules`. Not a lie — a better frame.

**Two modes**
- `universal` — general capsule for any application
- `targeted` — drop in a job description, get a capsule tuned for that specific role with a MATCH SCORE

**Always improvable**
Every capsule comes with a score (0–90) and specific actions to improve it. The maximum is unreachable by design. There's always a next level.

---

## Try it on my capsule

Open `Ilia-Kuzmin-delphi-developer.CareerCapsule.md`, drop it into any LLM, and ask something uncomfortable:

> *"Why shouldn't I hire this person?"*
> *"Will he get bored maintaining a stable legacy product?"*
> *"What are his real weaknesses?"*

See how it holds up. That's more honest than anything I could tell you about it.

---

## Parameters

```
CAPSULE_LANGUAGE = English
OWNER_LANGUAGE   = {your language}
OUTPUT_DEPTH     = full        # or compact
MODE             = universal   # or targeted
JOB_DESCRIPTION  = {paste job posting — only if MODE = targeted}
```

---

## Article

Full writeup on the idea, the format, and who it's for:
[→ LinkedIn article](https://www.linkedin.com/pulse/i-built-new-resume-format-capsule-ai-humans-ilia-kuzmin-cxw7c/

---

## Author

**Ilia Kuzmin** — Senior Delphi Engineer
20 years building systems that last.
[linkedin.com/in/kusmin-ilia](https://www.linkedin.com/in/kusmin-ilia/) · kusminilia@gmail.com
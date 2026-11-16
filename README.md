## Hi, I'm Arshdeep

GenAI Developer at TCS, working on Generative AI for a US healthcare client.

I build AI systems that are reliable enough to trust: the model suggests, and code, tests or a person make the final call. Every project below is live, and every number comes from a run I can show.

**Portfolio:** [https://arshdeepsingh.is-a.dev/](https://arshdeepsingh.is-a.dev/) · **LinkedIn:** [arshdeep-singh30](https://www.linkedin.com/in/arshdeep-singh30)

### Projects

| Project | What it does | Measured | Links |
|---|---|---|---|
| **AgentOps** | Describe a feature in one sentence; it's built like a small team would: requirements and design you approve, tests first (then locked), code, 9 quality checks in a sandbox, AI review, a merge you approve. Python, FastAPI, Postgres, AWS Lambda, Terraform. | 0 of 500 runs lost while workers were killed 435 times at random | [Code](https://github.com/arshdeep3010/agentops) · [Demo](https://ncf7tzviny6x7qkw7aaxk7xszq0lvnbk.lambda-url.ap-south-1.on.aws/) |
| **FitCheck** | Paste a job description; every requirement is checked against my public GitHub code, with links to the exact lines. No evidence means "unverified", never "met". LangGraph, pgvector RAG, FastAPI. | 97% accurate, 0 false claims on 4 real job posts labelled in advance (keyword matching: 55%) | [Code](https://github.com/arshdeep3010/fitcheck) · [Live](https://d3fkoasdzz9loq.cloudfront.net) |
| **Health Claim Decision Agent** | Claim decisions where Java owns the verdict: pgvector RAG over policy wording, 7 deterministic rules, and a decision model consulted only when the rules allow. Any failure goes to a human. Java 21, Spring Boot. Synthetic data. | 122 backend tests; claims the rules decide never call the AI | [Code](https://github.com/arshdeep3010/health-claim-decision-agent) · [Live](https://d97tm0469lmul.cloudfront.net) |
| **LLM Gateway** | OpenAI-compatible gateway in Java: fallback, circuit breaker, PII redaction, caching, budgets. Hand-written, no resilience library. | 20,000 of 20,000 requests answered with the main provider down (load test, simulated providers) | [Code](https://github.com/arshdeep3010/llm-gateway) · [Demo](https://d3ddocftym6j0y.cloudfront.net) (browser simulation) |
| **VibeAudit** | Finds real bugs in AI-written code: a secret scan, bandit and Semgrep (42 rules I wrote) first, then an AI audit, then a second AI pass that judges every scanner hit and drops false alarms with a reason. Python, FastAPI, AWS Lambda, Terraform. | Every planted bug in the sample found; 16 Semgrep hits judged in the same 2 model calls | [Code](https://github.com/arshdeep3010/vibe-audit) · [Live](https://d2vy8g526grxgy.cloudfront.net) |

### Stack

Java 21 · Spring Boot · Python · FastAPI · PostgreSQL / pgvector · LangGraph · Docker · AWS (Lambda, S3, CloudFront, DynamoDB) · Terraform · GitHub Actions

### Publication

[Automated Network Vulnerability Assessment with Nmap: A Comprehensive Approach](https://ieeexplore.ieee.org/document/10918528), IEEE ICACCTech 2024 (first author)

# AI Strategy One-Pager - Juno Automated Prioritization

## 1. Problem & Workflow

The Problem: Time taken to develop a feature is a lot and customers do not receive the desired product quickly

## 2. Target Metrics

Time to Market (TTM) Idea → customer availability goes to about 1 year its expected to be 4-8 weeks


## 3. Autonomy Level

Choice: Agent. I would not choose Assist or Copilot as I want to build development automation where a PM can inout an idea and the product can self deliver the feature in production

## 4. Data & Model Approach

Buy: Leverage a strong coding LLM (GPT, Claude, etc.).
Ground: Retrieve the latest codebase, API documentation, architecture decisions, coding standards, and previous implementations.

## 5. Risks & Mitigations

For development automation, a strong risk is introducing incorrect or insecure code into production at scale.

## 6. V1 Scope

In Scope:

AI assists developers by generating code, unit tests, documentation, and code explanations based on approved requirements and existing code.

Out of Scope:

AI will not autonomously merge or deploy code to production. All changes require human review and existing CI/CD approval gates.
AI will not make architecture or product decisions. It can recommend options, but engineers and product managers remain responsible for design, priorities, and technical decisions.

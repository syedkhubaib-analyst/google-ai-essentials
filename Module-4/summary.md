# Module 4: Use AI Responsibly

## Key Concepts
- Common sources of bias in AI systems, usually inherited from unrepresentative or skewed training data.
- Data privacy and security considerations when feeding information into AI tools (what should and shouldn't be shared with a third-party AI system).
- Recognizing AI limitations: hallucinated facts, outdated information, and overconfident wrong answers.
- The continued need for human review, fact-checking, and critical thinking before acting on AI output.

## Practical Insights
- Never input confidential, personally identifiable, or proprietary business data into a public AI tool without checking company policy and the tool's data-handling terms first.
- Bias and fairness aren't abstract ethics topics, they show up as concrete risk in any system that scores, ranks, or recommends people or transactions (loan approvals, hiring shortlists, fraud flags).
- Treating every AI-generated fact, statistic, or citation as a claim to verify, not a fact to trust, is the single most transferable habit from this module.

## Real-World Relevance

**For Business Analysts:**
Responsible AI use directly shapes requirement-writing for any AI-powered feature: a BA documenting a recommendation engine, a chatbot, or a scoring system needs to capture non-functional requirements around data privacy, auditability, explainability, and bias testing, not just the "happy path" functional flow. This is increasingly a standard section in techno-functional BRDs for AI-enabled systems.

**For Data Analysts:**
Bias in AI models is structurally the same problem as bias in a sampling methodology or an unrepresentative dataset, a DA who understands this can better sense-check an AI-assisted analysis (e.g., a demand forecast or customer segmentation) for skewed inputs before presenting findings to stakeholders.

**For Automation:**
Any automated workflow that uses AI to make or influence a decision (approvals, routing, flagging) needs a documented human-in-the-loop checkpoint and an audit trail. Capturing this as an explicit control point in a process map (As-Is/To-Be) or in the FRD is part of designing responsible automation, not just efficient automation.

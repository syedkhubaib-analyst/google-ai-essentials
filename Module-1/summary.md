# Module 1: Introduction to AI

## Key Concepts
- What AI is and is not: a set of technologies that let machines perform tasks that normally need human intelligence, versus the hype/sci-fi framing.
- Core building blocks: Machine Learning (systems that learn patterns from data instead of being explicitly programmed), and Generative AI / Large Language Models (models trained on massive text datasets to predict and generate human-like content).
- How AI is trained: the role of data quality and quantity in shaping what a model can and cannot do.
- Capabilities and limitations of current AI tools (e.g., hallucination, lack of true "understanding," bias inherited from training data).
- Why human oversight stays essential even as AI tools get more capable.

## Practical Insights
- AI is best understood as a pattern-recognition and prediction engine, not a source of guaranteed truth. Outputs must always be verified against real data or domain knowledge.
- The quality of an AI model's output is bounded by the quality of the data it was trained on, a direct parallel to the "garbage in, garbage out" principle every analyst already knows from working with dirty datasets.
- Knowing the difference between rule-based automation and ML-based prediction helps in deciding *when* AI is the right tool for a task versus when a simple formula, script, or business rule is more reliable and auditable.

## Real-World Relevance

**For Business Analysts:**
Understanding what AI can and cannot reliably do is now a baseline literacy expectation when writing requirements. A BA who understands model limitations (hallucination, bias, data dependency) is better equipped to write realistic acceptance criteria for AI-powered features, flag risk in a BRD/FRD, and set correct stakeholder expectations about what an "AI feature" in a product can actually deliver versus what marketing promises.

**For Data Analysts:**
This module reinforces the direct link between data quality practices (cleaning, validation, representativeness) and model reliability. It's the same discipline an analyst applies in Power BI/Excel data prep, just extended to the training-data stage of an AI system, a useful mental model when a stakeholder asks "can we just use AI on this dataset?"

**For Automation:**
Distinguishing rule-based automation from AI/ML-based automation helps in scoping any process-improvement or automation initiative correctly, i.e., deciding whether a workflow needs deterministic logic (best documented as a BPMN/flowchart) or a learning-based model (which needs monitoring, retraining, and human-in-the-loop checkpoints).

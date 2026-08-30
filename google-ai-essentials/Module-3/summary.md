# Module 3: Discover the Art of Prompting

## Key Concepts
- A prompt is essentially a structured request: the clearer and more specific the input, the more useful the output.
- Core components of a strong prompt: persona/role, context, task, format, and constraints.
- Iterative prompting: refining an AI's output through follow-up prompts rather than expecting a perfect result on the first try.
- Using AI to speed up everyday analysis and presentation-building tasks by prompting it with the right context and desired output format.

## Practical Insights
- Treating a prompt like a mini requirements document (context + objective + constraints + format) produces dramatically better results than a vague one-line question, the exact same discipline used when writing a clear user story or requirement statement.
- Asking the AI to role-play a specific persona (e.g., "act as a business analyst reviewing this requirement for gaps") narrows its output to the relevant frame of reference.
- Iterating on a prompt in small steps mirrors the agile principle of iterative refinement rather than trying to get a "perfect" one-shot output.

## Real-World Relevance

**For Business Analysts:**
Prompt structure maps directly onto the way a BA already writes requirements, role (who this is for), context (business background), objective (what's needed), and format (BRD section, user story, acceptance criteria). This module operationalizes prompting as a documentation-acceleration skill: turning rough stakeholder notes into a structured requirement draft, generating candidate edge cases for a user story, or drafting acceptance criteria that a BA then reviews and refines.

**For Data Analysts:**
Well-structured prompts speed up exploratory work: asking AI to suggest possible DAX measures for a given business question, generate a first draft of a SQL query from a plain-English request, or propose chart types for a specific dataset and audience. The analyst still validates logic and correctness, but ideation and first drafts get faster.

**For Automation:**
Prompt engineering is the interface layer for any automation that calls a generative AI model (e.g., an automated report-summary step, a chatbot answering FAQs from a knowledge base). Understanding prompt structure is what lets a BA or analyst write the *specification* for that AI step when documenting requirements for a developer or low-code platform (e.g., Power Automate + AI Builder, or a custom LLM integration).

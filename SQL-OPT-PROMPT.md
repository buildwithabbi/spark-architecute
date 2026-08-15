Modules: 

# ROLE

Act as a Principal Database Performance Engineer, Senior Data Engineer, Technical Educator, UX Designer, and Technical Interview Coach.

Your task is to create an interactive, production-quality, offline HTML learning artifact.

The artifact is designed for an experienced Data Engineer (~7 years of experience) preparing for Senior and Lead Data Engineer interviews.

The objective is not to teach SQL syntax.

The objective is to teach how databases optimize queries and how to explain those concepts confidently during interviews.

---

# OUTPUT FORMAT (MANDATORY)

Generate a SINGLE self-contained HTML file.

Do NOT generate Markdown.

Do NOT generate multiple files.

Do NOT generate PDFs.

The HTML must work completely offline.

Do NOT use:

- External CSS
- External JavaScript
- CDNs
- Third-party libraries

Embed all CSS and JavaScript inside the HTML.

---

# UI REQUIREMENTS

The artifact must include:

- Sidebar navigation
- Table of contents
- Search box
- Collapsible sections
- Previous/Next navigation
- Interactive flashcards
- Click-to-reveal answers
- Interactive quizzes
- Progress tracking
- Syntax-highlighted SQL code blocks
- Expandable diagrams
- Mobile-responsive layout

Every topic must be accessible within three clicks.

Maximum nesting depth: three levels.

---

# STUDENT PROFILE

Experience:

7 years.

Technology stack:

- Python
- SQL
- PySpark
- Databricks
- Airflow
- Azure Synapse
- BigQuery
- AWS
- GCP

Learning challenge:

The student understands concepts but struggles to recall them during interviews.

The artifact should optimize for interview recall.

---

# TEACHING RULES (MANDATORY)

1. Use simple English.

2. Introduce concepts slowly.

3. Never introduce multiple new concepts in a single paragraph.

4. Explain every concept with a real-world analogy before introducing technical terminology.

5. Use visual dry runs.

6. Use diagrams.

7. Teach pattern recognition.

8. Focus on diagnosis instead of memorization.

9. Optimize explanations for interview performance.

---

# EVERY CONCEPT MUST FOLLOW THIS EXACT TEMPLATE

1. Analogy

2. Technical explanation

3. Visual dry run

4. Symptoms

5. Diagnosis

6. Evidence to collect

7. Fix

8. Trade-offs

9. 30-second interview answer

10. 60-second senior-level interview answer

11. Don't say this during an interview

12. Say this instead

13. Common interviewer follow-up questions

14. Interactive quiz

15. Flashcard

---

# CREATE ONLY THIS MODULE

# MODULE 1: SQL OPTIMIZER FUNDAMENTALS

Cover every topic completely.

Do NOT continue to any other module.

---

# SECTION 1: How Databases Execute Queries

Teach:

- What happens after a SQL query is submitted
- Why databases do not execute SQL statements directly
- The complete execution flow

Create this diagram:

SQL Query

↓

Parser

↓

Optimizer

↓

Execution Plan

↓

Execution Engine

↓

Storage Engine

↓

Result

Create a complete end-to-end walkthrough.

---

# SECTION 2: Parser

Teach:

- SQL parsing
- Syntax validation
- Semantic validation

Use a language-translator analogy.

Show a visual example.

---

# SECTION 3: Query Optimizer

Teach:

- Why the optimizer exists
- How it evaluates multiple strategies
- Why optimization is necessary

Use a GPS-navigation analogy.

---

# SECTION 4: Rule-Based Optimization

Teach:

- What rule-based optimization is
- How rewrite rules work

Explain:

- Predicate pushdown
- Constant folding
- Projection pushdown

Explain why rule-based optimization alone is insufficient.

---

# SECTION 5: Cost-Based Optimization

Teach:

- Cost models
- How costs are estimated
- Why databases compare multiple plans

Explain:

- I/O cost
- CPU cost
- Memory cost

Create diagrams.

Create examples.

---

# SECTION 6: Why Multiple Execution Plans Exist

Explain:

Why a single SQL query can generate multiple execution plans.

Create three different execution plans for the same query.

Explain why the optimizer chooses one plan over another.

---

# SECTION 7: Statistics And Metadata

Teach:

- Statistics
- Histograms
- Metadata

Explain how the optimizer uses statistics.

Explain why stale statistics cause poor plans.

---

# SECTION 8: Selectivity

Teach:

- High selectivity
- Low selectivity

Use visual examples.

Explain why selectivity influences index usage.

---

# SECTION 9: Cardinality

Teach:

- Cardinality
- Cardinality estimation

Explain:

Estimated rows vs actual rows.

Show examples.

---

# SECTION 10: Cost Estimation

Teach:

How the optimizer estimates:

- I/O
- CPU
- Memory

Explain why cost estimation is imperfect.

---

# SECTION 11: Why Databases Sometimes Ignore Indexes

Teach:

Why an existing index does not guarantee index usage.

Explain:

- Low selectivity
- Stale statistics
- Small tables
- High lookup costs

Use examples.

---

# SECTION 12: End-To-End Query Execution Walkthrough

Take this query:

SELECT customer_name
FROM orders
WHERE customer_id = 100
ORDER BY order_date;

Walk through the complete execution process.

Visualize every step.

---

# SECTION 13: Three Complete Execution Examples

Create three examples.

Example 1:

Index Seek

Example 2:

Sequential Scan

Example 3:

Join Operation

Explain every operator.

---

# SECTION 14: Five Interactive Interview Scenarios

Use this structure:

Symptoms

↓

Pause

↓

Ask the learner to diagnose the issue

↓

Reveal the answer

---

# SECTION 15: Interview Preparation

Create:

- 15 flashcards
- 10 rapid-recall questions
- 5 scenario-based questions
- A one-page cheat sheet

---

# QUALITY REQUIREMENTS

Do NOT use placeholders.

Do NOT summarize concepts.

Do NOT skip diagrams.

Do NOT omit examples.

This artifact must be immediately usable as a standalone offline study resource.

Generate the complete HTML file and stop.
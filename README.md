# NotebookLM Custom Prompts

## Motivation

I've spent a decent chunk of my career working in fields where "thought leadership" and report-writing are rife.

Thought leadership, done well, is an important endeavor. So is staying up to date on what's happening in an industry.

However, there is also an undeniable trend, in certain industries, to produce long documents just because it feels or looks productive to be doing so.

Reports are often mixed bags: a few original ideas buried amidst chapters of dreary regurgitated statistics. How can one—sorry to be trite—separate wheat from chaff?

Large language models (LLMs) are fantastic companions in this regard. I love NotebookLM, but it is inherently polite and deferential. Which is why I've found value in maintaining a few slightly more blunt prompts that can be pasted into the custom generation section (or used any other way you wish!)

## Available Prompts

### System Prompts
- **[The Jaded Report Reader](system-prompts/report-skeptic.md)** - A personality-defining system prompt for creating a skeptical assistant that evaluates reports with healthy skepticism

### Quick Evaluation Prompts (Analysis)
- **[Anything Interesting?](analysis/anything-interesting.md)** - Evaluates whether a report contains original ideas, noteworthy statistics, or strong opinions
- **[Original Thinking?](analysis/original-thinking.md)** - Assesses whether a report contains genuinely new ideas or just regurgitated content
- **[Worth The Read?](analysis/worth-the-read.md)** - Provides a verdict on whether a report justifies the reader's time investment

### Data Extraction Prompts
- **[Noteworthy Findings](extraction/noteworthy-findings.md)** - Identifies unexpected or novel findings that contradict or extend previous research
- **[Interesting Statistics](extraction/interesting-stats.md)** - Extracts and organizes key statistics thematically with page references
- **[Case Studies Analysis](extraction/case-studies.md)** - Extracts and organizes case studies thematically, identifying what they demonstrate and providing page references
- **[Key Snippets](extraction/key-snippets.md)** - Extracts memorable quotes and key passages from the report

### Executive Summary
- **[Executive Summary](generation-prompts/exec-summary/exec-summary.md)** - Generates a critical executive summary evaluating both content and credibility

### Comprehensive Analysis
- **[Comprehensive Report Analysis](generation-prompts/combined/comprehensive-report-analysis.md)** - An all-in-one prompt combining read/skip assessment, opinionated executive summary, statistical overview, case studies analysis, and key quotes extraction

## Suggested Usage (NotebookLM)

![NotebookLM Screenshot 1](screenshots/1.png)

![NotebookLM Screenshot 2](screenshots/2.png)

UI/Flow at the time of creation (20 November 2025):

1. Add report as source
2. Studio
3. Create report
4. Create your own
5. Copy and paste a prompt 
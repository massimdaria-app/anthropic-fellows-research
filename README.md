# AI, Education & Society — Research Portfolio
### Daria Storozhkova | Anthropic Fellows Application 2026

## Research Question
How do AI systems transform human agency, values, and learning outcomes — 
and can this be measured and directed through policy design?

## Portfolio Overview

| Notebook | Methods | Key Finding |
|---|---|---|
| day1_foundations | T-test, descriptive stats | AI tutoring group: 81 vs 63 points (p<0.001) |
| day2_real_data | Panel data, cross-country regression | Internet access explains 83% of PISA variance |
| day3_nlp | NLP, Claude API, sentiment analysis | AI education narratives: +0.205 mean sentiment |
| day4_topic_modeling | LDA, DiD, IV, topic modeling | Early Childhood = 0% media coverage |

## Methods Used
- **Causal Inference:** OLS regression, Difference-in-Differences, Instrumental Variables
- **NLP:** TextBlob, HuggingFace Transformers, Claude API (structured output)
- **Topic Modeling:** LDA (sklearn) vs LLM classification
- **Data:** 4,446 country observations, 143 real news headlines (Google News RSS)

## Key Findings

**1. Information access, not wealth, drives educational outcomes**
Internet access explains 83.4% of PISA math score variance (R²=0.834).
GDP becomes statistically insignificant when controlling for internet access (p=0.359).

**2. AI education narratives are cautiously optimistic**
Mean sentiment: +0.205 across 143 headlines.
Framing: 21 opportunity vs 12 threat vs 9 neutral.

**3. Critical research gap identified**
Early Childhood AI coverage = 0% across all major publications.
Safety & Ethics severely underreported despite policy urgency.

**4. Publication bias in AI education discourse**
Tech Policy Press: 100% Policy & Regulation coverage.
UNICEF: 60% Students & Learning focus.
NYT: balanced Policy + Classroom, zero Student outcomes.

## Research Statement
> *How do AI-assisted learning tools reshape children's agency and intrinsic 
> motivation — and can governments design educational policy to preserve 
> autonomy while capturing productivity gains?*

Proposed Fellows project: mixed-methods study of AI tutoring effects on 
agency formation in 8-12 year-olds across UK school contexts.

## Stack
Python 3.14 | pandas | statsmodels | sklearn | HuggingFace | Anthropic API

## Contact
dstorozhkova2@gmail.com | London, UK

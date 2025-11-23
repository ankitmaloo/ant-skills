# Advanced Search Strategies for Research Analysis

## General Principles

1. **Cast a wide net first, then narrow**
2. **Search for both supporting AND contradicting evidence**
3. **Use multiple search engines and databases**
4. **Follow citation trails in both directions**
5. **Look for recent work (cutting edge) and foundational work (context)**

## Search Targets

### Academic Sources
- **arXiv.org**: Preprints in physics, CS, math, quantitative biology, economics
- **Google Scholar**: Peer-reviewed papers (accessible via Google Search)
- **PubMed**: Life sciences and biomedical (via web search)
- **SSRN**: Social sciences (via web search)

### General Sources
- **Google Search**: Blogs, discussions, news, informal sources
- **Wikipedia**: Quick background (verify with primary sources)
- **Reddit**: r/askscience, r/MachineLearning, field-specific communities
- **HackerNews**: Tech and science discussions
- **StackExchange**: Specialized Q&A (MathOverflow, Physics, etc.)

### Expert Sources
- **Research group websites**: Often have preprints and working papers
- **Conference proceedings**: Cutting-edge work
- **Technical blogs**: Researcher blogs (Distill.pub, etc.)
- **Twitter/X**: Many researchers share work (@username + keywords)

## Query Construction

### Basic Query Types

#### 1. Direct Term Search
```
"exact phrase in quotes"
specific technical term
author name
```

**Use when**: You know precise terminology

**Example**:
- "quantum entanglement swapping"
- superconductivity room temperature
- "Penrose objective reduction"

#### 2. Conceptual Search
```
related concept
broader field
analogy terms
```

**Use when**: Exploring adjacent areas

**Example**:
- neural plasticity mechanisms
- topological properties materials
- evolutionary game theory

#### 3. Problem/Solution Search
```
"how to" [problem]
[problem] solution
[problem] approach
```

**Use when**: Looking for methods or techniques

**Example**:
- "how to detect dark matter"
- protein folding solution
- few-shot learning approach

#### 4. Critical Search
```
[concept] criticism
[concept] problems
[concept] limitations
"why [concept] fails"
[concept] debunked
[concept] controversy
```

**Use when**: Looking for contradicting evidence

**Example**:
- "cold fusion criticism"
- "quantum consciousness problems"
- "P vs NP limitations"
- "why string theory fails"

#### 5. Temporal Search
```
[concept] 2024
[concept] recent
[concept] latest
[concept] review 2023
[concept] state of the art
```

**Use when**: Need current status

**Example**:
- "large language models 2024"
- "CRISPR latest developments"
- "quantum computing state of the art 2025"

### Advanced Search Operators

#### Google Search Operators

```
site:arxiv.org [query]           # Search specific site
[term1] OR [term2]               # Either term
[term1] -[term2]                 # Exclude term2
related:[url]                    # Similar pages
filetype:pdf [query]             # Specific file types
intitle:[term]                   # Term in title
inurl:[term]                     # Term in URL
[term] .. [term2]                # Range (years, numbers)
```

**Examples**:
```
site:arxiv.org "room temperature superconductor" 2023..2025
quantum computing OR quantum information -bitcoin
"machine learning" filetype:pdf review
intitle:"survey" "deep learning"
```

#### arXiv-Specific Searches

**By category**:
- cs.AI - Artificial Intelligence
- cs.LG - Machine Learning
- physics.gen-ph - General Physics
- quant-ph - Quantum Physics
- math.CO - Combinatorics
- q-bio - Quantitative Biology

**Search patterns**:
```
site:arxiv.org [query] cat:cs.AI
site:arxiv.org au:[Author] [topic]
site:arxiv.org ti:[title words]
site:arxiv.org abs:[abstract words]
```

## Search Strategies by Phase

### Phase 1: Initial Reconnaissance

**Goal**: Get oriented in the landscape

**Queries**:
1. Core concept(s) directly
2. "Core concept review"
3. "Core concept survey"
4. Core concept + "Wikipedia"

**Example** (for "neuromorphic computing"):
```
neuromorphic computing
"neuromorphic computing review"
"neuromorphic computing survey"
neuromorphic computing Wikipedia
```

### Phase 2: Deep Dive

**Goal**: Find substantive academic work

**Queries**:
1. site:arxiv.org + core concept + recent year
2. Core concept + technical terms
3. Author names (if found) + related topics
4. Core concept + "experimental results"
5. Core concept + methodology terms

**Example**:
```
site:arxiv.org "neuromorphic computing" 2023..2025
neuromorphic computing spiking neural networks
neuromorphic computing MNIST benchmark
"neuromorphic computing" experimental validation
```

### Phase 3: Critical Analysis

**Goal**: Find limitations and criticisms

**Queries**:
1. Concept + "limitations"
2. Concept + "challenges"
3. Concept + "problems"
4. Concept + "does not work"
5. Concept + "failed"
6. Concept + "criticism"

**Example**:
```
"neuromorphic computing limitations"
"neuromorphic computing challenges"
"neuromorphic computing scalability problems"
"why neuromorphic computing failed"
```

### Phase 4: Alternative Perspectives

**Goal**: Find competing ideas or approaches

**Queries**:
1. Problem + "alternative approaches"
2. Concept + "vs" + alternative
3. Concept + "compared to"
4. "Alternatives to" + concept

**Example**:
```
brain-inspired computing "alternative approaches"
"neuromorphic computing vs digital computing"
"spiking neural networks compared to ANNs"
"alternatives to neuromorphic computing"
```

### Phase 5: State of the Art

**Goal**: Find latest developments

**Queries**:
1. Concept + current year
2. Concept + "breakthrough" + current year
3. Concept + "state of the art"
4. Major conference name + concept

**Example**:
```
neuromorphic computing 2025
"neuromorphic computing breakthrough" 2024
"neuromorphic computing state of the art"
NeurIPS neuromorphic computing
```

## Domain-Specific Strategies

### For Physics Ideas

**Search**:
- arXiv physics categories (quant-ph, cond-mat, hep-th, etc.)
- Physical Review journals
- Check for violations of conservation laws
- Look for experimental groups that would test this
- Search for "toy models" or "thought experiments"

**Red flags**:
- Violates thermodynamics
- Claims to solve major unsolved problem without extraordinary evidence
- Published only on viXra (not arXiv)
- No mathematical formalism

### For Computer Science / AI Ideas

**Search**:
- arXiv cs.* categories
- GitHub repos (via Google: site:github.com [concept])
- Papers with Code (benchmarks)
- Major conference proceedings (NeurIPS, ICML, ICLR, etc.)

**Red flags**:
- Claims to solve P vs NP without proof
- No code or reproducibility
- No benchmarks or comparisons
- Ignores computational complexity

### For Biology / Medicine Ideas

**Search**:
- PubMed/MEDLINE (via Google)
- bioRxiv (preprints)
- Clinical trial databases
- FDA approvals or rejections
- Replication studies

**Red flags**:
- Small sample sizes
- No replication
- Conflicts of interest
- Cherry-picked data
- Post-hoc analysis

### For Mathematics Ideas

**Search**:
- arXiv math.* categories
- MathOverflow discussions
- Proofs and formal verification
- Counterexamples

**Red flags**:
- Claims proof of major conjecture without peer review
- Vague or informal arguments
- No formal notation
- Ignores known counterexamples

### For Engineering Ideas

**Search**:
- Patents (Google Patents)
- Prior art
- Thermodynamic/physical feasibility
- Cost-benefit analyses
- Existing solutions

**Red flags**:
- Violates physics (perpetual motion, etc.)
- No prototype or working model
- Ignores practical constraints
- No cost analysis

## Citation Chain Following

### Forward Citations
Who cited this paper? (Shows impact and later developments)

**Method**:
- Google Scholar: Search paper, click "Cited by"
- Look for recent papers citing key work

### Backward Citations
What does this paper cite? (Shows foundations and related work)

**Method**:
- Read references section
- Find the most cited references
- Chase down foundational papers

### Lateral Citations
What else is in this area?

**Method**:
- Look at "Related articles" or "Similar papers"
- Check co-authors' other work
- Look at papers from same research group

## Evaluating Source Quality

### High-Quality Indicators
- Peer-reviewed journals (especially high-impact)
- Replicated results
- Independent confirmation
- Detailed methodology
- Data and code available
- Preregistered studies
- Meta-analyses
- Systematic reviews

### Medium-Quality Indicators
- Preprints on arXiv/bioRxiv
- Conference papers (peer-reviewed)
- Technical reports from reputable institutions
- Well-documented blog posts from experts
- Textbooks

### Low-Quality Indicators
- Blog posts without sources
- YouTube videos without references
- Social media posts
- Press releases (hype)
- Pay-to-publish journals
- Non-peer-reviewed sources

### Red Flags
- Predatory journals
- No citations to existing work
- Extraordinary claims without extraordinary evidence
- Cannot find any peer-reviewed work
- Only self-published
- Conflicts of interest not disclosed
- Data not available
- Methods not reproducible

## Search Tactics for Different Scenarios

### Scenario 1: Completely Novel Idea
No direct search results expected.

**Strategy**:
1. Search for components individually
2. Search for analogies in other domains
3. Search for fundamental principles involved
4. Search for reasons why this hasn't been done

### Scenario 2: Claimed Breakthrough
Extraordinary claim needs extraordinary evidence.

**Strategy**:
1. Search for independent replication
2. Search for expert commentary
3. Search for criticism or debunking
4. Check if published in peer-reviewed venue
5. Look for conflicts of interest

### Scenario 3: Incremental Advance
Building on existing work.

**Strategy**:
1. Find the prior work being built upon
2. Compare to state of the art
3. Look for similar approaches
4. Check if improvement is significant

### Scenario 4: Interdisciplinary Idea
Connects multiple fields.

**Strategy**:
1. Search each field independently
2. Search for similar cross-field work
3. Look for experts in each field
4. Check if connection is valid or superficial

## Iterative Search Process

### Round 1: Broad Survey (15-30 minutes)
- Core concept searches
- Wikipedia/overview articles
- Recent review papers
- Get basic terminology and key researchers

### Round 2: Deep Technical (30-60 minutes)
- arXiv searches
- Key papers and citations
- Technical details and methodologies
- Experimental evidence

### Round 3: Critical Analysis (20-40 minutes)
- Search for criticisms
- Look for failed replications
- Find limitations and challenges
- Alternative explanations

### Round 4: Synthesis (10-20 minutes)
- Cross-reference findings
- Resolve contradictions
- Identify knowledge gaps
- Assess overall evidence quality

## Documentation

**Track your searches**:
- What queries did you use?
- What did you find?
- What sources are most credible?
- What remains unknown?

**Template**:
```
Query: [search terms]
Source: [where you searched]
Results: [summary of findings]
Quality: [assessment of source reliability]
Key papers: [citations]
Gaps: [what wasn't found]
```

## Common Pitfalls

1. **Stopping too early**: First page of results isn't enough
2. **Confirmation bias**: Only looking for supporting evidence
3. **Authority bias**: Accepting claims from famous researchers uncritically
4. **Recency bias**: Only looking at recent work, missing foundations
5. **Terminology trap**: Missing relevant work due to different terminology
6. **Filter bubble**: Only searching one database or perspective
7. **Quality neglect**: Treating all sources equally

## Quick Reference: Search Checklist

For each research idea, have you:

- [ ] Searched core concept directly
- [ ] Searched for reviews and surveys
- [ ] Searched arXiv in relevant categories
- [ ] Searched for criticisms and limitations
- [ ] Searched for alternative approaches
- [ ] Searched for recent developments (current year)
- [ ] Followed citation trails (forward and backward)
- [ ] Searched for replications or failures
- [ ] Checked multiple sources (not just one database)
- [ ] Evaluated source quality
- [ ] Documented searches and findings
- [ ] Looked for expert commentary
- [ ] Checked for conflicts of interest
- [ ] Searched for practical implementations
- [ ] Looked for textbooks or established knowledge

## Time Management

**For quick analysis (30 min)**:
- 10 min: Broad survey
- 15 min: Deep dive on key sources
- 5 min: Critical search

**For thorough analysis (2-3 hours)**:
- 30 min: Broad survey
- 60 min: Deep technical search
- 30 min: Critical analysis
- 20 min: Synthesis and cross-referencing

**For comprehensive analysis (1+ days)**:
- Multiple rounds of all phases
- Reading full papers, not just abstracts
- Contacting experts if needed
- Building detailed evidence map

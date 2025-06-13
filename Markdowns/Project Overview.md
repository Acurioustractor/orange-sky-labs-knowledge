# Orange Sky Labs Knowledge Repository

## 📁 Repository Structure

```
orange-sky-labs-knowledge/
├── README.md                           # Main repository documentation
├── LICENSE                             # MIT License for open sharing
├── CONTRIBUTING.md                     # How others can contribute
├── CHANGELOG.md                        # Version history
├── .gitignore                          # Ignore unnecessary files
│
├── 📂 ventures/                        # All venture initiatives
│   ├── README.md                       # Ventures overview
│   ├── orange-sky-labs/
│   │   ├── overview.md                 # Converted from Six Pager
│   │   ├── service-offerings.md        # Consulting services detail
│   │   ├── orange-spritzer-program.md  # 6-month innovation program
│   │   └── resources-repository.md     # Open source NFP resources
│   │
│   ├── friend-life-impact-project/
│   │   ├── overview.md                 # FLIP project overview
│   │   ├── operational-layer.md        # Friend voice mechanisms
│   │   ├── digital-platform.md         # Digital platform specs
│   │   └── prototypes/                 # UI/UX prototypes
│   │
│   ├── trust-exchange/
│   │   └── overview.md                 # Storage solutions project
│   │
│   └── delta-innovation/
│       ├── framework.md                # Delta innovation framework
│       ├── tools-and-methods.md        # Innovation tools
│       └── case-studies/               # Past innovation projects
│
├── 📂 resources/                       # Reusable resources
│   ├── templates/
│   │   ├── six-pager-template.md      # Venture proposal template
│   │   ├── lean-canvas-social.md      # Social impact canvas
│   │   ├── innovation-scorecard.md    # Project evaluation
│   │   └── pitch-deck-template.md     # 10-slide pitch template
│   │
│   ├── frameworks/
│   │   ├── design-thinking.md         # Design methodology
│   │   ├── venture-mapping.md         # Venture planning
│   │   └── impact-measurement.md      # Success metrics
│   │
│   └── guides/
│       ├── nfp-scaling-guide.md       # How to scale NFPs
│       ├── volunteer-management.md     # Best practices
│       └── innovation-process.md       # Innovation methodology
│
├── 📂 knowledge-base/                  # Core knowledge documents
│   ├── sector-insights/
│   │   ├── homelessness-research.md   # Sector research
│   │   ├── nfp-trends.md              # Industry trends
│   │   └── social-innovation.md       # Innovation in social sector
│   │
│   ├── operational/
│   │   ├── service-delivery.md        # How to deliver services
│   │   ├── partnership-models.md       # Collaboration approaches
│   │   └── funding-strategies.md       # Fundraising approaches
│   │
│   └── technology/
│       ├── digital-platforms.md        # Tech for social good
│       ├── data-privacy.md            # Privacy considerations
│       └── accessibility.md            # Inclusive design
│
├── 📂 examples/                        # Real-world examples
│   ├── case-studies/
│   │   ├── we-are-mobilise.md        # First Labs client
│   │   └── orange-sky-scaling.md      # OSA growth story
│   │
│   └── sample-queries.md               # How to query this knowledge
│
└── 📂 claude-integration/              # Claude-specific files
    ├── instructions.md                 # How to use with Claude
    ├── prompt-templates.md             # Useful prompts
    └── search-tips.md                  # Optimizing searches
```

## 📝 File Conversion Guide

### Converting Six-Pagers to Markdown

**Original**: `Orange Sky Labs _ Six Pager.pdf`
**Convert to**: `ventures/orange-sky-labs/overview.md`

```markdown
---
title: "Orange Sky Labs"
category: "Social Enterprise Consulting"
tags: ["consulting", "nfp-support", "innovation", "capacity-building"]
date: "2025-06-13"
status: "active"
---

# Orange Sky Labs

## Executive Summary
Orange Sky Labs offers consulting services, innovation programs, and open-source resources to uplift the not-for-profit sector by sharing knowledge and expertise gained from scaling Orange Sky Australia.

## The Opportunity
- NFPs struggle to access innovation support that understands their sector
- Rising costs and changing volunteer behaviors stretch NFP resources
- Need for practical, sector-specific scaling knowledge

## Our Solution

### 1. Consulting Services
- **What**: Paid consulting engagements for NFPs
- **Focus**: Scaling, innovation, volunteer management
- **Approach**: Practical, hands-on support from experienced team

### 2. Orange Spritzer Program
- **What**: 6-month innovation fellowship
- **Who**: NFP leaders and social entrepreneurs
- **Outcome**: Scaled or amplified social impact

### 3. Open Source Resources
- **What**: Online repository of NFP resources
- **Features**: 
  - Searchable database
  - Community contributions
  - Ratings and comments
  - Tagged categories

## Service Offerings
- Innovation workshops
- Volunteer pathway design
- Scaling strategy
- Impact measurement
- Digital transformation
- Operational efficiency

## Business Model
- Consulting: Fee-for-service
- Orange Spritzer: $10k per participant (seek matched funding)
- Resources: Free/freemium model

## Success Metrics
- Number of NFPs supported
- Innovation projects launched
- Resources shared and utilized
- Community engagement
- Revenue sustainability

## Next Steps
1. Pilot consulting engagements
2. Develop resource repository
3. Launch Orange Spritzer pilot
4. Secure funding partners
```

### Converting Delta Documents

**Original**: `Delta HQ.pdf` files
**Convert to**: Multiple structured files

`ventures/delta-innovation/framework.md`:
```markdown
---
title: "Delta Innovation Framework"
category: "Innovation Methodology"
tags: ["innovation", "framework", "experimentation"]
---

# Delta Innovation Framework

## Overview
Delta is Orange Sky's innovation lab, focused on exploring adjacent opportunities and transformational ventures to expand social impact.

## Innovation Process

### 1. Discovery
- Research and insights gathering
- Friend voice integration
- Opportunity identification
- Market analysis

### 2. Ideation
- Design thinking workshops
- Co-design with stakeholders
- Concept development
- Feasibility assessment

### 3. Experimentation
- Rapid prototyping
- MVP development
- Pilot programs
- Learning loops

### 4. Scaling
- Business case development
- Resource planning
- Implementation roadmap
- Impact measurement

## Tools and Methods
- Lean Canvas for Social Impact
- Design Thinking
- Jobs to be Done
- Venture Mapping
- Innovation Scorecard

## Past Projects
- Friend Life Impact Project (FLIP)
- Trust Exchange
- Orange Juicers
- Remote Service Delivery
```

### Creating Template Files

`resources/templates/six-pager-template.md`:
```markdown
---
title: "Six Pager Template"
category: "Templates"
tags: ["planning", "ventures", "proposals"]
---

# [Venture Name] Six Pager

## Page 1: Executive Summary
**The Problem**: [Clear problem statement]
**Our Solution**: [Proposed solution]
**Impact**: [Expected outcomes]
**Ask**: [What you need to proceed]

## Page 2: The Opportunity
### Market Size
- [Addressable market]
- [Growth trends]
- [Unmet needs]

### Why Now?
- [Timing factors]
- [Enabling conditions]
- [Urgency drivers]

## Page 3: Our Solution
### Concept
[Detailed solution description]

### Key Features
| Priority | Must Have | Should Have | Could Have |
|----------|-----------|-------------|------------|
| 1        | [Feature] | [Feature]   | [Feature]  |
| 2        | [Feature] | [Feature]   | [Feature]  |

### Differentiation
- [Unique value prop 1]
- [Unique value prop 2]

## Page 4: Business Model
### Revenue Streams
1. [Stream 1]: [Description]
2. [Stream 2]: [Description]

### Cost Structure
- Development: $[X]
- Operations: $[X]
- Marketing: $[X]

### Unit Economics
[Key metrics and assumptions]

## Page 5: Implementation Plan
### Phase 1: [Timeframe]
- [ ] [Milestone 1]
- [ ] [Milestone 2]

### Phase 2: [Timeframe]
- [ ] [Milestone 3]
- [ ] [Milestone 4]

### Resources Needed
- Team: [Roles required]
- Funding: $[Amount]
- Partners: [Key partnerships]

## Page 6: Measuring Success
### Impact Metrics
- [Metric 1]: [Target]
- [Metric 2]: [Target]

### Business Metrics
- [Metric 1]: [Target]
- [Metric 2]: [Target]

### Learning Goals
- [Question 1]
- [Question 2]
```

## 🚀 Implementation Steps

### 1. Create Repository
```bash
# Initialize repository
mkdir orange-sky-labs-knowledge
cd orange-sky-labs-knowledge
git init

# Create directory structure
mkdir -p ventures/{orange-sky-labs,friend-life-impact-project,trust-exchange,delta-innovation}
mkdir -p resources/{templates,frameworks,guides}
mkdir -p knowledge-base/{sector-insights,operational,technology}
mkdir -p examples/case-studies
mkdir -p claude-integration
```

### 2. Add Core Files

`README.md`:
```markdown
# Orange Sky Labs Knowledge Repository

Welcome to the Orange Sky Labs open-source knowledge repository. This collection contains frameworks, tools, and insights from our journey in social innovation and supporting the not-for-profit sector.

## 🎯 Purpose
Share practical knowledge to help NFPs scale their impact through innovation, effective operations, and sustainable growth.

## 📚 What's Inside
- **Ventures**: Detailed documentation of innovation projects
- **Resources**: Templates, frameworks, and guides
- **Knowledge Base**: Research and insights
- **Examples**: Real-world case studies

## 🤝 Using with Claude
1. Download or fork this repository
2. Upload relevant folders to your Claude project
3. Ask Claude to search for specific topics or browse categories

## 📝 Contributing
We welcome contributions! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## 📄 License
This work is licensed under [MIT License](LICENSE) - feel free to use and adapt with attribution.

## 🙏 Acknowledgments
Created by Orange Sky Labs team with support from the broader NFP community.
```

`CONTRIBUTING.md`:
```markdown
# Contributing to Orange Sky Labs Knowledge

## How to Contribute
1. Fork the repository
2. Create a feature branch
3. Add your content following our structure
4. Submit a pull request

## Content Guidelines
- Use clear, accessible language
- Include practical examples
- Cite sources where applicable
- Focus on actionable insights

## File Format
- Use Markdown for all documents
- Include metadata headers
- Follow naming conventions
- Add to appropriate category
```

### 3. Create Claude Integration

`claude-integration/instructions.md`:
```markdown
# Using This Knowledge Base with Claude

## Setup
1. In Claude, create a new project
2. Upload the entire repository or specific folders
3. Claude will automatically index the content

## Effective Queries
- "Find resources about NFP scaling"
- "Show me the volunteer management guide"
- "What templates are available for innovation projects?"
- "Search for information about social impact measurement"

## Tips
- Be specific about what you're looking for
- Reference folder names for targeted searches
- Ask Claude to summarize or explain concepts
- Request Claude to adapt templates for your use case
```

## 🔄 Conversion Checklist

- [ ] Convert all PDFs to Markdown
- [ ] Organize by logical categories
- [ ] Add metadata to all files
- [ ] Create cross-references between related content
- [ ] Include visual diagrams as images or ASCII art
- [ ] Add examples and case studies
- [ ] Create templates from repeated patterns
- [ ] Write clear documentation
- [ ] Set up version control
- [ ] Test with Claude

## 🌟 Best Practices

1. **Consistent Structure**: Use the same format across similar documents
2. **Rich Metadata**: Help Claude understand context and relationships
3. **Clear Navigation**: Make it easy to find relevant content
4. **Regular Updates**: Keep information current and relevant
5. **Community Input**: Encourage contributions and feedback

Ready to start building your GitHub repository? This structure will make your knowledge easily accessible to anyone using Claude!
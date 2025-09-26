# Contributing Guide

Thank you for your interest in the Awesome BI project! This project aims to collect the best Business Intelligence (BI) frameworks, tools, and resources. We welcome and appreciate every contribution.

## Table of Contents

- [How to Contribute](#how-to-contribute)
- [Types of Contributions](#types-of-contributions)
- [Submission Guidelines](#submission-guidelines)
- [Quality Standards](#quality-standards)
- [Format Guidelines](#format-guidelines)
- [Review Process](#review-process)
- [Code of Conduct](#code-of-conduct)

## How to Contribute

### 1. Fork and Clone

```bash
# Fork this repository to your GitHub account
# Then clone to local
git clone https://github.com/ayo4code/awesome-bi.git
cd awesome-bi
```

### 2. Create Branch

```bash
git checkout -b add-new-tool
```

### 3. Make Changes

Edit the `README.md` or `README.zh-CN.md` file to add new tools or improve existing content.

### 4. Commit Changes

```bash
git add .
git commit -m "Add [Tool Name] - brief description"
git push origin add-new-tool
```

### 5. Create Pull Request

Create a Pull Request on GitHub with a detailed description of your changes.

## Types of Contributions

We welcome the following types of contributions:

### ✅ Welcome Contributions

- **New Tools/Resources**: Add new BI tools, platforms, or resources
- **Improve Descriptions**: Enhance descriptions or links for existing tools
- **Fix Errors**: Correct spelling mistakes, broken links, etc.
- **New Categories**: Suggest or add new categories
- **Translation Improvements**: Improve Chinese-English translation quality
- **Documentation**: Improve contributing guides or other documentation

### ❌ Unwelcome Contributions

- **Commercial Promotion**: Pure commercial advertising or promotion
- **Duplicate Content**: Tools or resources that already exist
- **Irrelevant Content**: Tools unrelated to the BI field
- **Personal Projects**: Personal projects without widespread use or validation
- **Paid Promotion**: Content requested to be added for payment

## Submission Guidelines

### New Tool Submission Requirements

When submitting new tools, ensure:

1. **Relevance**: Tool must be related to business intelligence, data analytics, or data visualization
2. **Quality**: Tool should be high-quality and well-maintained
3. **Activity**: Open source projects should have updates within the past year
4. **Uniqueness**: Tool should provide unique value, not duplicate existing tools
5. **Accessibility**: Provided links should be accessible

### Pull Request Requirements

- **Clear Title**: Use descriptive titles like "Add Apache Superset - Modern data exploration platform"
- **Detailed Description**: In PR description, explain:
  - What tool/resource you're adding
  - Why it's worth adding
  - Main features of the tool
  - Appropriate category
- **Single Focus**: Each PR should focus on one main change
- **Follow Format**: Strictly follow existing format guidelines

## Quality Standards

### Tool Selection Criteria

#### ⭐ Priority Consideration

- **Open Source Projects**: Prioritize open source and free tools
- **Widely Used**: Widely used and recognized in the community
- **Active Development**: Project actively maintained and developed
- **Good Documentation**: Complete documentation and examples
- **Community Support**: Active community or support channels

#### 📊 Evaluation Metrics

For open source projects, we consider:
- GitHub stars count (typically > 1000)
- Recent commit activity (updates within past 6 months)
- Issue response speed
- Community size and activity

For commercial tools, we consider:
- Market recognition and usage
- Customer reviews and case studies
- Feature completeness and innovation
- Enterprise adoption

### Content Quality Requirements

- **Accuracy**: All information must be accurate
- **Timeliness**: Information should be up-to-date
- **Completeness**: Descriptions should be complete but concise
- **Objectivity**: Avoid subjective evaluations, use objective descriptions

## Format Guidelines

### Link Format

```markdown
* [Tool Name](https://example.com/) - Brief and accurate description
```

### Description Guidelines

- **Length**: Descriptions should be 50-80 characters
- **Language**: Use concise, professional language
- **Avoid**: Avoid subjective words like "best", "perfect"
- **Focus**: Highlight core functionality and features

### Category Rules

- **Single Category**: Each tool should be in the most appropriate single category
- **Alphabetical Order**: Tools within the same category arranged alphabetically
- **New Categories**: If new category needed, provide detailed reasoning in PR

### Example Format

```markdown
## Data Visualization

*Tools focused on data visualization and chart creation.*

* [Apache ECharts](https://echarts.apache.org/) - Powerful interactive charting library
* [Chart.js](https://www.chartjs.org/) - Simple yet flexible JavaScript charting library
* [D3.js](https://d3js.org/) - JavaScript library for data-driven documents
```

## Review Process

### Review Steps

1. **Automated Checks**: CI/CD automatically checks format and link validity
2. **Manual Review**: Maintainers review content quality and relevance
3. **Community Feedback**: Community members can provide feedback and suggestions
4. **Final Decision**: Maintainers make final decision

### Review Timeline

- **Simple Additions**: Usually reviewed within 3-7 days
- **Complex Changes**: May take 1-2 weeks
- **Controversial Content**: May require longer discussion

### Review Criteria

- ✅ **Approved**: Meets all quality standards and format requirements
- 🔄 **Needs Changes**: Requires minor adjustments before re-review
- ❌ **Rejected**: Does not meet project standards or scope

## Special Cases

### Broken Links

If broken links are found:

1. Try to find the new address of the tool
2. Consider removal if tool is no longer maintained
3. Report broken links in issues

### Tool Renaming

If tools are renamed:

1. Update tool name
2. Update link address
3. Briefly explain in description (if necessary)

### Category Adjustments

If you think tool categorization is inappropriate:

1. Suggest in issues
2. Provide reasoning for adjustment
3. Wait for community discussion and maintainer decision

## Code of Conduct

### Basic Principles

- **Respect**: Respect all contributors and users
- **Inclusion**: Welcome contributors from different backgrounds
- **Collaboration**: Participate with collaborative and constructive attitude
- **Professionalism**: Maintain professional and courteous communication

### Unacceptable Behavior

The following behaviors are not tolerated:

- Personal attacks or discriminatory remarks
- Spam or excessive promotion
- Malicious sabotage or deliberate misinformation
- Violation of open source licenses or copyrights

### Reporting Mechanism

If you encounter inappropriate behavior:

1. Report in relevant issues or PRs
2. Contact project maintainers
3. Provide specific facts and evidence

## Getting Help

### Frequently Asked Questions

**Q: My PR was rejected, why?**
A: Please check the rejection reason, usually due to not meeting quality standards or format requirements. You can modify based on feedback and resubmit.

**Q: What type of tools should I add?**
A: Focus on high-quality tools related to BI, data analytics, and data visualization. Avoid adding overly generic or irrelevant tools.

**Q: How do I decide which category a tool should go in?**
A: Choose the most appropriate category based on the tool's main function and purpose. If unsure, ask in the PR.

### Contact Methods

- **GitHub Issues**: For reporting problems or suggestions
- **Pull Requests**: For submitting changes
- **Discussions**: For general discussion and questions

## Acknowledgments

Thanks to everyone who has contributed to this project! Your efforts make this resource list more valuable.

### Contributors

All contributors will receive appropriate recognition in the project.

---

Thank you again for your contribution! Let's build the best BI resource collection together. 🎉

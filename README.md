# OSRI

> **Analyze the health, sustainability, and resilience of open-source projects.**

OSRI is an open-source platform for evaluating the long-term health of software projects.

Modern software depends on open source, but choosing a dependency often comes down to stars, downloads, or recent activity. These signals tell only part of the story.

OSRI goes beyond popularity by analyzing the technical, community, governance, and ecosystem signals that contribute to a project's long-term resilience.

The goal is simple:

> Help developers, maintainers, organizations, and researchers make more informed decisions about the open-source software they depend on.

---

## Why OSRI?

Open source has become critical infrastructure.

From startups to governments, millions of applications rely on open-source software every day. Yet understanding whether a project is healthy enough to depend on remains surprisingly difficult.

Questions like these are often unanswered:

- Is this project actively maintained?
- How healthy is its contributor community?
- Is development slowing down?
- Does it have healthy governance?
- Is the project becoming a critical dependency for the ecosystem?
- What risks should adopters be aware of?

OSRI exists to answer those questions.

---

## Core Principles

OSRI is built around three principles.

### 📊 Measure

Collect meaningful signals that reflect the current health of an open-source project.

### 💡 Explain

Provide transparent insights that show **why** a project receives a particular assessment.

### 🔮 Forecast

Identify trends that may indicate future sustainability or maintenance risks.

---

## Planned Features

- Repository health analysis
- Maintainer and contributor insights
- Governance assessment
- Community activity metrics
- Release cadence analysis
- Dependency and ecosystem analysis
- Resilience scoring
- Human-readable recommendations
- CLI interface
- Python API
- Future web dashboard

---

## Example

```bash
osri analyze pallets/flask
```

Example output:

```text
Repository: pallets/flask

Overall Resilience
84/100

Technical
█████████░

Community
████████░░

Governance
███████░░░

Ecosystem
█████████░

Top Strengths
✓ Healthy release cadence
✓ Active maintainer community

Potential Risks
• Low maintainer diversity
• Missing governance documentation
```

---

## Roadmap

### v0.1 — Foundation

- Repository data collection
- Core resilience metrics
- Initial scoring model
- Command-line interface

### v0.5 — Intelligence

- Improved scoring model
- Explainable recommendations
- Historical trend analysis

### v1.0 — Platform

- Ecosystem resilience analysis
- Forecasting
- Public API
- Web dashboard

---

## Tech Stack

- Python
- Typer
- FastAPI
- PostgreSQL
- GitHub Actions

---

## Contributing

Contributions are welcome.

Whether you're improving documentation, implementing features, fixing bugs, or proposing new resilience metrics, we'd love your help.

---

## License

This project is licensed under the MIT License.

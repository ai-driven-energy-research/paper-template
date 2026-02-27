# [Your Paper Title]

> Submitted to [AIDER — AI-Driven Energy Research](https://ai-driven-energy-research.github.io)

## Authors

- **[Your Name]** — [Affiliation], [Email]

## Abstract

[Write your abstract here. 150-300 words.]

## How to Reproduce

```bash
# Clone this repo
git clone https://github.com/YOUR_USERNAME/YOUR_PAPER_REPO.git
cd YOUR_PAPER_REPO

# Install dependencies
pip install -r code/requirements.txt

# Run all experiments and generate figures
bash results/reproduce.sh
```

## Repository Structure

```
├── paper/                  # Manuscript source
│   ├── main.tex            # Main manuscript (LaTeX or Markdown)
│   └── figures/            # Figures used in the paper
├── code/
│   ├── README.md           # Setup instructions
│   ├── requirements.txt    # Python dependencies
│   └── src/                # All source code
├── data/
│   └── README.md           # Data description, download links, license
├── process-log/
│   ├── README.md           # Overview of how this paper was produced
│   ├── ai-sessions/        # AI agent logs, transcripts, prompts
│   └── human-decisions/    # Timestamped log of human interventions
├── results/
│   ├── reproduce.sh        # Script to regenerate all figures/tables
│   └── figures/            # Generated output figures
├── REPRODUCIBILITY.md      # Reproducibility checklist
├── LICENSE
└── README.md               # This file
```

## Process Log

This paper was produced using: [describe your workflow — e.g., "Claude AI via paper-factory, with human oversight at each stage"]

See [`process-log/`](process-log/) for the full record of AI sessions and human decisions.

## License

- Paper: [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/)
- Code: [MIT](https://opensource.org/licenses/MIT)
- Data: [CC0](https://creativecommons.org/publicdomain/zero/1.0/) or [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/)

## Citation

```bibtex
@article{yourname2026title,
  title   = {Your Paper Title},
  author  = {Your Name},
  journal = {AI-Driven Energy Research (AIDER)},
  year    = {2026},
  url     = {https://github.com/ai-driven-energy-research/YOUR_PAPER_REPO}
}
```

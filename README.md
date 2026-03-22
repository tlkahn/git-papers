# git-papers

Collect academic papers via GitHub Actions — no local download needed.

## Usage

```bash
gh workflow run fetch-pdf.yml \
  -f url="https://arxiv.org/pdf/2301.12345" \
  -f path="papers/some-paper.pdf"
```

Or trigger from the **Actions** tab on GitHub.

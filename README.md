# AI Model Releases Dashboard

Tracks anticipated AI model releases (open and closed source) across major labs.

## View

- **Live dashboard:** https://0xsachi.github.io/ai-model-releases-dashboard/ai_model_releases_dashboard.html
- **CSV data:** [ai_model_releases_dashboard.csv](ai_model_releases_dashboard.csv)

## Auto-update

Dashboard refreshes weekly via a scheduled Claude Code agent that pulls the latest
anticipated release information from lab announcements, news reporting, and
community sources (Reddit: r/LocalLLaMA, r/MachineLearning, r/singularity, r/OpenAI).

## Columns

- Model Name / Codename
- Company
- Open / Closed Source
- Anticipated Release Date
- Parameters
- Modality
- Confidence Level (Confirmed / Rumored / Speculated)
- Primary Source

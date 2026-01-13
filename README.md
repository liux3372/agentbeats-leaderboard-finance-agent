# Finance Agent Leaderboard

> Assess finance agents that query financial data using Google Gemini, Google Search, and SEC EDGAR database.

A leaderboard repository for evaluating finance-focused AI agents that answer financial questions using multiple data sources. This leaderboard is built on the Agentbeats platform to provide standardized assessment of financial analysis capabilities.

## 📊 What This Leaderboard Assesses

This leaderboard evaluates finance agents on their ability to:

- **Analyze financial data** using Google Gemini models
- **Search for real-time financial information** via Google Search
- **Access SEC EDGAR filings** for official corporate financial data
- **Answer complex finance questions** with accuracy and proper citation
- **Navigate financial regulations** and reporting standards

## 🏆 Scoring Criteria

Agents are evaluated on multiple dimensions:

| Category | Weight | Description |
|----------|--------|-------------|
| **Accuracy** | 40% | Correctness of financial calculations and analysis |
| **Citation Quality** | 25% | Proper attribution to SEC filings and sources |
| **Timeliness** | 20% | Use of current financial data and market information |
| **Completeness** | 15% | Thoroughness of financial analysis and coverage |

## 🚀 Getting Started as a Participant

### Prerequisites
- A finance-focused AI agent that can:
  - Interface with Google Gemini API
  - Perform Google searches for financial data
  - Access and parse SEC EDGAR filings
- GitHub account with repository fork permissions
- API keys for required services

### Submission Process

1. **Fork this repository** to your GitHub account
2. **Configure your agent** in `scenario.toml`:
   - Add your agent's Agentbeats ID
   - Set required environment variables
   - Configure assessment parameters
3. **Set up GitHub Secrets** for your API keys
4. **Run the assessment** via GitHub Actions
5. **Submit a pull request** with your results

## ⚙️ Assessment Configuration

### Required Environment Variables:

- **GOOGLE_API_KEY - Google API Key for Google ADK and Gemini models
- **SERP_API_KEY - SerpAPI Key for Google Web Search
- **SEC_EDGAR_API_KEY - SEC EDGAR API Key for SEC filings search
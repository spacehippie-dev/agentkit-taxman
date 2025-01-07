# AI Tax Helper Agent

An AI-powered assistant that helps users optimize their tax liabilities by analyzing their crypto transactions.

## Features

- **Real-Time Tax Impact Analysis**
  - Calculate tax implications of transactions immediately
  - Suggest strategies for minimizing taxable events
  - Timing optimization for sales and swaps

- **Tax-Loss Harvesting Insights**
  - Identify underperforming assets for potential tax-loss harvesting
  - Detailed reports with potential savings calculations
  - Strategic recommendations for offsetting gains

- **Smart Transaction Categorization**
  - Automatic classification of transactions (capital gains, income, etc.)
  - Support for various income types (staking rewards, mining, etc.)
  - Jurisdiction-specific categorization rules

- **Multi-Jurisdiction Support**
  - Adaptable tax rules based on user's country
  - Short-term vs. long-term gains handling
  - Country-specific wash sale rules

- **Portfolio Simulation**
  - Pre-execution tax impact simulation
  - What-if scenario analysis
  - Strategic planning tools

- **Tax Filing Integration**
  - Generate tax forms (e.g., IRS Form 8949)
  - Integration with major tax software
  - Exportable reports in various formats

- **Gas Fee Deduction Calculator**
  - Track and calculate deductible gas fees
  - Jurisdiction-specific deduction rules
  - Annual gas fee summaries

## Requirements

- Node.js 18+
- [CDP API Key](https://portal.cdp.coinbase.com/access/api)
- [OpenAI API Key](https://platform.openai.com/docs/quickstart)

## Installation

```bash
npm install
```

## Configuration

Create a `.env` file with the following:

```env
OPENAI_API_KEY=your_openai_api_key
CDP_API_KEY_NAME=your_cdp_api_key_name
CDP_API_KEY_PRIVATE_KEY=your_cdp_private_key
NETWORK_ID=base-sepolia  # Optional: Defaults to base-sepolia
```

## Usage

```bash
npm start
```

Choose between:
1. Chat mode - Interactive conversation with the tax helper
2. Auto mode - Autonomous tax analysis and optimization

## License

Apache-2.0

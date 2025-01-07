#Instructions

##Goals: Create a simple AI Tax Helper Agent assistant that helps users optimize their tax liabilities by analyzing their crypto transactions.

## Features:
- Identifies tax-loss harvesting opportunities.
- Categorizes transactions by tax treatment (e.g., short-term vs. long-term gains).
- Generates tax reports formatted for major jurisdictions.

## In depth features:
    Real-Time Tax Impact Analysis

    Calculate the tax implications of transactions immediately after they occur.
    Suggest strategies for minimizing taxable events, like timing sales or swaps.
    Tax-Loss Harvesting Insights

    Identify underperforming assets that can be sold at a loss to offset taxable gains.
    Provide a detailed report with potential savings.
    Transaction Categorization

    Automatically classify transactions into capital gains, income (e.g., staking rewards), or other tax categories based on jurisdiction.
    Multi-Jurisdiction Support

    Adapt tax rules based on the user’s selected country, including short-term vs. long-term gains, wash sale rules, etc.
    Portfolio Simulation

    Enable users to simulate transactions to understand their tax consequences before executing them.
    Tax Filing Integration

    Generate forms like IRS Form 8949 (in the U.S.) or equivalents for other jurisdictions.
    Integrate with major tax filing software (e.g., TurboTax, H&R Block).
    Gas Fee Deduction Calculator

    Calculate deductible gas fees for applicable transactions.


1. create a new github repo for this project
2. set the remote origin to the new repo
3. README - update to reflect the project
4. project - chat example
    1. update the project so '/' root project is the code from 'examples/chat'
5. Delete unused directories and files. Do not delete instructions.md
    1. /cdp-agentkit-core
    2. /cdp-langchain
    3. /cdp-langchain-chatbot-example
    4. /chatbot
6. Generate instructions - find where autonomous agent instructions are defined
    1. Located in chatbot.ts in the messageHandler parameter of the createChatbot function
    2. current isstructions focus on general CDP agentkit interactions
    3. Next step would be to customize these instructions for tax efficient tasking

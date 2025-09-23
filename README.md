# Envio stKDA Indexer

A quick demo to show how to set up an indexer for the stKDA token on Kadena Chainweb 20 Testnet using **HyperIndex** by Envio.

> [!TIP]  
> Want to index your own ERC20 token on the Kadena Chainweb Testnet?  
> Just update the **contract address** in `config.yaml` and you’re good to go!

## Pre-requisites

-   [Node.js (v18+)](https://nodejs.org/en/download/current)
-   [pnpm (v8+)](https://pnpm.io/installation)
-   [Docker Desktop](https://www.docker.com/products/docker-desktop)

## Quick Start

1. Clone this repo and install dependencies:

```bash
git clone https://github.com/enviodev/kadena-erc20-token-indexer.git
cd kadena-erc20-token-indexer

# install dependencies
pnpm install
```

2. Create an **Envio API key** at https://envio.dev/app/api-tokens and add it to a `.env` file.
3. Run the indexer locally:

```bash
pnpm dev
```

4. Open [https://envio.dev/console](https://envio.dev/console) and click the **Playground** button to access the GraphQL Playground. It currently works only in Firefox or Chrome.

## Learn More

To dive deeper into **HyperIndex**, check out the official docs: [https://docs.envio.dev](https://docs.envio.dev)

If you have questions or just want to chat, join the community on:

-   **Discord:** [https://discord.gg/frHECVdyns](https://discord.gg/frHECVdyns)
-   **Telegram:** [https://t.me/+5mI61oZibEM5OGQ8](https://t.me/+5mI61oZibEM5OGQ8)

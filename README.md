# Awesome SEI

A curated list of awesome projects, tools, and resources in the SEI ecosystem.

Sei is the first parallelized EVM blockchain delivering unmatched scalability and speed.

## 🚀 How to Add Your Project

We use a structured approach to maintain project data. To add your project to Awesome SEI:

### Step 1: Create Your Project File

1. **Fork** this repository
2. **Create a new JSON file** in the `data/` folder with your project name:
   ```
   data/your-project-name.json
   ```
3. **Fill out the project details** using the schema below
4. **Submit a pull request**

### Step 2: Project Data Schema

Create your JSON file using this exact structure:

```json
{
  "name": "Project Name",
  "description": "Brief description of what your project does (1-2 sentences max)",
  "categories": ["Category::Subcategory"],
  "addresses": {
    "contractName": "0xContractAddress",
    "anotherContract": "0xAnotherAddress"
  },
  "links": {
    "project": "https://websitelink.com",
    "twitter": "https://x.com/project",
    "github": "https://github.com/project",
    "docs": "https://docslink.com",
    "communityDiscord": "https://discord.com/communitydiscord",
    "communityTelegram": "https://t.me/projectcommunity",
    "email": "contact@project.com",
    "coingecko": "coingecko-id",
    "telegram": "https://t.me/telegram"
  }
}
```

### Available Categories

Use these category formats in your JSON file:

- `"DeFi::DEX"` - Decentralized exchanges
- `"DeFi::Lending"` - Lending and borrowing protocols
- `"Defi::Prediction Market"` - Prediction market platforms
- `"DeFi::Staking"` - Liquid staking and staking services
- `"DeFi::Derivatives"` - Perpetuals, options, and derivatives
- `"DeFi::Stablecoins"` - Stablecoin protocols
- `"DeFi::Yield"` - Yield farming and optimization
- `"DeFi::Aggregators"` - DEX and liquidity aggregators
- `"Gaming::Games"` - Gaming applications and platforms
- `"Gaming::Infrastructure"` - Gaming infrastructure and tools
- `"NFTs::Marketplaces"` - NFT trading platforms
- `"NFTs::Collections"` - NFT collections and projects
- `"Infrastructure::Tools"` - Developer tools and APIs
- `"Infrastructure::Analytics"` - Block explorers and analytics
- `"Infrastructure::Bridges"` - Cross-chain bridges
- `"Infrastructure::AI"` - AI tools and infrastructure
- `"Wallets::Browser"` - Browser-based wallets
- `"Wallets::Mobile"` - Mobile wallet applications
- `"Community::Resources"` - Educational and community resources
- `"Community::Projects"` - Community-driven initiatives

### Field Descriptions

**Required Fields:**

- `name`: Your project's name
- `description`: Brief description (1-2 sentences, objective tone)
- `categories`: Array of category strings (at least one)
- `links.project`: Your main website/application URL

**Optional Fields:**

- `addresses`: Smart contract addresses (use descriptive names as keys)
- `links`: Additional relevant links
  - `twitter`: Twitter/X profile
  - `github`: GitHub repository
  - `docs`: Documentation site
  - `communityDiscord`: Community Discord server
  - `communityTelegram`: Community Telegram group
  - `email`: Contact email
  - `coingecko`: CoinGecko ID (for tokens)
  - `telegram`: Official Telegram channel

### Example Project File

**File: `data/dragonswap.json`**

```json
{
  "name": "Dragonswap",
  "description": "DragonSwap is the central DeFi hub native to Sei Network, leveraging the power of a parallelized EVM. Swap, farm, provide liquidity, bridge assets, and access in-depth analytics.",
  "categories": ["DeFi::Protocols"],
  "addresses": {
    "SwapRouter02": "0x11da6463d6cb5a03411dbf5ab6f6bc3997ac7428",
    "DragonswapV2Factory": "0x179d9a5592bc77050796f7be28058c51ca575df4",
    "WSEI": "0xe30fedd158a2e3b13e9badaeabafc5516e95e8c7",
    "DragonswapFactory": "0x71f6b49ae1558357bbb5a6074f1143c46cbca03d",
    "DragonswapDSERC20": "0x150b4A3088dFB06d92531D1cCa6E980FB9a270e1",
    "DragonswapRouter": "0xa4cf2f53d1195addde9e4d3aca54f556895712f2"
  },
  "links": {
    "project": "https://dragonswap.app",
    "twitter": "https://x.com/dragonswap_dex",
    "github": "https://github.com/dragonswap-app",
    "docs": "https://docs.dragonswap.app/dragonswap"
  }
}
```

## 📋 Project Guidelines

**What to include:**

- Projects built on or for the SEI blockchain
- Tools that support the SEI ecosystem
- Educational content about SEI
- Community resources and initiatives
- Both live projects and valuable resources

**Requirements:**

- Project must be related to the SEI ecosystem
- Include a brief, clear description (1-2 sentences max)
- Working link to project homepage, app, or repository
- Project should be functional or actively developed
- Use the exact JSON schema format provided

## 🔄 Updating Project Information

To update your project information:

1. Find your project's JSON file in the `data/` folder
2. Make the necessary changes following the same schema
3. Submit a pull request with your updates

## 🤝 Community

This repository is maintained by the SEI community. All contributions are welcome and appreciated!

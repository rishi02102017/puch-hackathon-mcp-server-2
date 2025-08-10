<h1 align="center"> AI Innovation & Lifestyle Suite - MCP Server</h1>

<p align="center">
  <img src="puch_ai_banner.jpeg" alt="Banner image" width="500"/>
</p>

A cutting-edge Model Context Protocol (MCP) server that provides AI-powered innovation and lifestyle tools for Puch AI. This suite offers 10 advanced tools covering crypto intelligence, startup building, content monetization, fashion trends, food innovation, NFTs, social media trends, influencer matching, dating optimization, and travel curation.

## 🚀 Features

### Innovation Tools
- **🔮 Crypto Intelligence** - Real-time crypto market analysis and investment intelligence
- **🚀 Startup Builder** - Validate business ideas and build startup roadmaps
- **🎨 NFT Creator** - Generate NFT ideas and predict digital art trends

### Content & Social Tools
- **💰 Content Monetization** - Analyze content performance and optimize monetization strategies
- **📱 Social Media Trend Predictor** - Predict viral social media trends and content success
- **👥 Influencer Matcher** - Match influencers with brands and predict collaboration success

### Lifestyle Tools
- **👗 Fashion Predictor** - Predict fashion trends and suggest style recommendations
- **🍽️ Food Innovator** - Create unique recipes and predict food trends
- **💕 Dating Optimizer** - Optimize dating profiles and predict compatibility
- **✈️ Travel Curator** - Curate travel experiences and predict trending destinations

## 🛠️ Tech Stack

- **Python 3.11+**
- **FastMCP** - MCP server framework
- **Pydantic** - Data validation and tool descriptions
- **HTTPX** - HTTP client
- **Python-dotenv** - Environment management

## 📋 Requirements

- Python 3.11 or higher
- Bearer token authentication (required by Puch AI)
- HTTPS deployment (required for production)

## 🚀 Quick Start

### 1. Clone the Repository
```bash
git clone <your-repo-url>
cd ai-innovation-lifestyle-suite
```

### 2. Set Up Environment
Create a `.env` file in the project root:
```env
AUTH_TOKEN=your_secret_token_here
MY_NUMBER=91xxxxxxxxxx
```

### 3. Install Dependencies
```bash
pip install fastmcp httpx python-dotenv pydantic
```

### 4. Run the Server
```bash
python innovation_lifestyle_mcp.py
```

The server will start on `http://0.0.0.0:8086`

## 🔗 Connect to Puch AI

1. Deploy the server to a cloud platform (Render, Railway, etc.)
2. Get your public HTTPS URL
3. Connect using Puch AI:
```
/mcp connect https://your-deployed-url.com/mcp your_secret_token_here
```

## 🛠️ Available Tools

### 1. 🔮 Crypto Intelligence
Real-time crypto market analysis and investment intelligence.
- **Input:** Cryptocurrency name, analysis type (trend/investment/sentiment)
- **Output:** Market analysis, investment insights, predictions, risk warnings

### 2. 🚀 Startup Builder
Validate business ideas and build startup roadmaps.
- **Input:** Business idea, target market, investment level
- **Output:** Market validation, success probability, MVP roadmap, financial projections

### 3. 💰 Content Monetization
Analyze content performance and optimize monetization strategies.
- **Input:** Content type, platform, audience size
- **Output:** Revenue opportunities, growth strategy, platform-specific optimization

### 4. 👗 Fashion Predictor
Predict fashion trends and suggest style recommendations.
- **Input:** Style preference, occasion, season
- **Output:** Trending styles, personalized recommendations, shopping strategy

### 5. 🍽️ Food Innovator
Create unique recipes and predict food trends.
- **Input:** Cuisine type, dietary restrictions, skill level
- **Output:** Recipe recommendations, food trends, cooking tips, ingredient sourcing

### 6. 🎨 NFT Creator
Generate NFT ideas and predict digital art trends.
- **Input:** Art style, theme, rarity level
- **Output:** NFT creation strategy, market analysis, monetization strategies, launch plan

### 7. 📱 Social Media Trend Predictor
Predict viral social media trends and content success.
- **Input:** Platform, content type, niche
- **Output:** Trending content, viral predictions, timing strategy, success metrics

### 8. 👥 Influencer Matcher
Match influencers with brands and predict collaboration success.
- **Input:** Influencer type, niche, platform
- **Output:** Brand matching strategy, pricing strategy, success prediction, action plan

### 9. 💕 Dating Optimizer
Optimize dating profiles and predict compatibility.
- **Input:** Dating platform, age range, relationship goal
- **Output:** Profile optimization, compatibility prediction, messaging strategy, date planning

### 10. ✈️ Travel Curator
Curate travel experiences and predict trending destinations.
- **Input:** Destination type, budget range, travel style
- **Output:** Travel recommendations, budget planning, experience curation, action plan

## 🚀 Deployment

### Render (Recommended)
1. Connect your GitHub repository to Render
2. Create a new Web Service
3. Set build command: `pip install -r requirements.txt`
4. Set start command: `python innovation_lifestyle_mcp.py`
5. Add environment variables in Render dashboard

### Railway
1. Connect your GitHub repository to Railway
2. Railway will auto-detect Python and deploy
3. Add environment variables in Railway dashboard

### Other Platforms
- **Heroku** - Use Procfile and requirements.txt
- **DigitalOcean App Platform** - Similar to Render setup

## 🔧 Environment Variables

| Variable | Description | Example |
|----------|-------------|---------|
| `AUTH_TOKEN` | Secret token for authentication | `puch_hackathon_xxxx_xxxxxxx` |
| `MY_NUMBER` | Phone number in format {country_code}{number} | `91xxxxxxxxxx` |

## 📝 API Endpoints

- **MCP Endpoint:** `/mcp/` - Main MCP protocol endpoint
- **Health Check:** Available through MCP protocol

## 🎯 Tool Categories

### Innovation & Technology
- **Crypto Intelligence** - For crypto investors and enthusiasts
- **Startup Builder** - For entrepreneurs and business owners
- **NFT Creator** - For digital artists and creators

### Content & Social Media
- **Content Monetization** - For content creators and influencers
- **Social Media Trend Predictor** - For social media marketers
- **Influencer Matcher** - For brands and influencers

### Lifestyle & Personal Development
- **Fashion Predictor** - For fashion enthusiasts and shoppers
- **Food Innovator** - For food lovers and home cooks
- **Dating Optimizer** - For people using dating apps
- **Travel Curator** - For travelers and adventure seekers

## 💡 Use Cases

### For Content Creators
- Optimize content strategy with trend predictions
- Monetize content across multiple platforms
- Find brand collaboration opportunities

### For Entrepreneurs
- Validate business ideas and create roadmaps
- Analyze market opportunities
- Build startup strategies

### For Investors
- Get crypto market intelligence
- Analyze investment opportunities
- Track market trends

### For Lifestyle Enthusiasts
- Stay ahead of fashion trends
- Discover new recipes and food trends
- Plan unique travel experiences
- Optimize dating success

## 🤝 Contributing

This project was built for the Puch AI Hackathon. Feel free to fork and extend!

## 📄 License

This project is licensed under the Apache 2.0 License.

## 🏆 Hackathon Project

Built for **Puch AI Hackathon** - "What's the coolest way you can build with AI?"

**Team:** Jyotishman Das and Suvadip Chakraborty
**Project:** AI Innovation & Lifestyle Suite
**Hashtag:** #BuildWithPuch

## 🎉 Why This Suite?

This MCP server combines **innovation** and **lifestyle** tools to create a comprehensive AI assistant that helps users with:
- **Career & Business Growth** (Crypto, Startups, Content)
- **Personal Development** (Fashion, Food, Dating, Travel)
- **Creative Expression** (NFTs, Social Media)
- **Professional Networking** (Influencer Matching)

Perfect for GenZ users who want AI-powered insights for both professional success and personal lifestyle optimization!

---

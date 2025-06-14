# 🤖 Dev_Assist - Developer Tools Research Agent

An intelligent research assistant that helps developers find and compare alternative tools and technologies. Using AI-powered web scraping and analysis, Dev_Assist provides comprehensive comparisons with pricing, features, and personalized recommendations.

## ✨ Features

- 🔍 **Smart Tool Discovery**: Automatically finds relevant alternatives to any developer tool
- 📊 **Comprehensive Analysis**: Extracts pricing, tech stack, language support, and API availability
- 🤖 **AI-Powered Recommendations**: Provides personalized suggestions based on your needs
- 🌐 **Real-time Web Scraping**: Uses Firecrawl to get up-to-date information
- 💡 **Interactive CLI**: Easy-to-use command-line interface with emoji-rich output

## 🚀 Quick Start

### Prerequisites

- Python 3.8+
- [uv](https://docs.astral.sh/uv/) package manager
- Google Gemini API key
- Firecrawl API key

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/debasmitaas/Dev_Assist.git
   cd Dev_Assist/docs
   ```

2. **Create virtual environment**
   ```bash
   uv init
   ```
4. **Install dependencies**
   ```bash
   uv add
   ```

### Configuration

1. **Create `.env` file** in the `docs` directory:
   ```bash
   touch .env
   ```

2. **Add your API keys** to `.env`:
   ```env
   GEMINI_API_KEY=your_gemini_api_key_here
   FIRECRAWL_API_KEY=your_firecrawl_api_key_here
   ```

### Getting API Keys

#### Google Gemini API Key
1. Go to [Google AI Studio](https://aistudio.google.com/)
2. Sign in with your Google account
3. Click "Get API Key" and create a new key
4. Copy the API key to your `.env` file

#### Firecrawl API Key
1. Visit [Firecrawl](https://firecrawl.dev/)
2. Sign up for an account
3. Go to your dashboard and get your API key
4. Copy the API key to your `.env` file

## 🎯 Usage

1. **Run the application**
   ```bash
   cd F:\Coding-Research-Assistant-Agent\docs
   uv run main.py
   ```

2. **Enter your query** when prompted:
   ```
   Developer Tools Query: React Native alternatives
   ```

3. **Get comprehensive results**:
   - Tool discovery and extraction
   - Detailed analysis of each alternative
   - AI-powered recommendations

### Example Queries

- "Firebase alternatives"
- "React Native alternatives" 
- "MongoDB alternatives"
- "Docker alternatives"
- "VS Code alternatives"

##📽️ Watch this demo video to see the Output :<br>
  [![Watch the demo](https://img.youtube.com/vi/uc15sp8cX_0/0.jpg)](https://www.youtube.com/watch?v=uc15sp8cX_0)

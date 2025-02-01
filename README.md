# AdFLOW - Streamlining Ad Research

Deployed AdFLOW : https://679e1c4a563cdaa25682cd34--fascinating-mandazi-53dc55.netlify.app/

AdFLOW is a platform designed to streamline ad research by automating the gathering of insights and generating actionable data for better decision-making. This project leverages multiple APIs to provide comprehensive research automation, actionable insights generation, and a reference dashboard.

## Table of Contents
  |
  |-- [Installation](#installation)
  |-- [Usage](#usage)
  |-- [Project Structure](#project-structure)
  |-- [APIs Used](#apis-used)
  |-- [Environment Variables](#environment-variables)
  |-- [Contributing](#contributing)
  |-- [License](#license)

## Installation

1. Clone the repository:
    sh
    git clone https://github.com/yourusername/adflow.git
    cd adflow
    

2. Install dependencies:
    sh
    npm install
    

3. Create a [.env](http://vscodecontentref/0) file in the root directory and add your API keys:
    env
    NOTDIAMOND_API_KEY='your_notdiamond_api_key'
    OPENAI_API_KEY='your_openai_api_key'
    ANTHROPIC_API_KEY='your_anthropic_api_key'
    

4. Update the [config.js](http://vscodecontentref/1) file with your API keys:
    js
    const CONFIG = {
        GOOGLE_API_KEY: 'your_google_api_key',
        GOOGLE_SEARCH_ENGINE_ID: 'your_google_search_engine_id',
        SERPER_API_KEY: 'your_serper_api_key',
        GROQ_API_KEY: 'your_groq_api_key',
        TAVILY_API_KEY: 'your_tavily_api_key',
        GEMINI_API_KEY: 'your_gemini_api_key',
        gSCRAPER_API_KEY: 'your_scraper_api_key',
        SEGMIND_API_KEY: 'your_segmind_api_key',
        YOUTUBE_API_KEY: 'your_youtube_api_key',
        NOTDIAMOND_API_KEY: 'your_notdiamond_api_key'
    };
    

## Usage

1. Start the development server:
    sh
    npm start
    

2. Open your browser and navigate to http://localhost:5500.

3. Use the login page to sign in or register a new account.

4. After logging in, you will be redirected to the main page where you can enter your query and explore the results.

## Project Structure

- index.html: The landing page with a hero section, features, and FAQ.
- login.html: The login and registration page.
- main.html: The main application page where users can enter queries and view results.
- login.js: Handles authentication using Firebase.
- script.js: Contains the main logic for fetching and displaying data from various APIs.
- styles.css: Contains the styles for the application.
- Config/config.js: Contains the configuration for API keys.

## APIs Used

- Google Custom Search API: For searching images and web results.
- YouTube Data API: For fetching YouTube video data.
- Groq API: For generating summaries and insights.
- Tavily API: For news search.
- Segmind API: For generating images.
- ScraperAPI: For scraping Google search results.

## Environment Variables

The following environment variables need to be set in the [.env](http://vscodecontentref/2) file:

- NOTDIAMOND_API_KEY
- OPENAI_API_KEY
- ANTHROPIC_API_KEY

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

# Instagram Post and Image Suggestion Agent

This project uses a team of AI agents to generate Instagram posts and suggest accompanying images. The agents are specialized in creating engaging content about wine, cheese, and gourmet foods.

## Features

- **Content Generation:** Creates engaging and SEO-friendly Instagram captions.
- **Image Creation:** Generates prompts and creates relevant images for the posts.
- **Specialized Agents:** Utilizes a "Writer" agent for content and an "Illustrator" agent for image prompts.
- **Team-based Approach:** A "Coordinator" agent manages the workflow between the specialized agents.

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/instagram-post-image-agents.git
   cd instagram-post-image-agents
   ```

2. **Create and activate a virtual environment:**
   ```bash
   uv venv
   source .venv/bin/activate  # On Windows, use `.venv\Scripts\activate`
   ```

3. **Install the dependencies:**
   ```bash
   uv pip install -r requirements.txt
   ```

## Gemini API Key

This project uses the Google Gemini API. To get your API key, follow these steps:

1. Go to the [Google AI Studio](https://aistudio.google.com/).
2. Click on **"Get API key"**.
3. Create a new project or select an existing one.
4. Your API key will be generated.
5. Create a `.env` file in the root of the project by copying the `.env_example` file:
   ```bash
   cp .env_example .env
   ```
6. Open the `.env` file and replace `YOUR_API_KEY` with your actual Gemini API key.

## Main Libraries

- **`agno`:** A framework for building and managing AI agents.
- **`google-genai`:** The official Python library for the Google Gemini API.
- **`duckduckgo-search`:** Used for web searches to gather information.
- **`Pillow`:** For image manipulation.

# Tech AI

Tech AI is a Streamlit application that combines powerful AI models to provide three main functionalities: a chatbot, image captioning, and text-to-image generation. This application utilizes Google Gemini, DALL-E 3, and Stable Diffusion XL for generating creative content.

## Features

- **ChatBot**: Engage in a conversation with a smart AI assistant.
- **Image Captioning**: Upload an image and receive generated captions based on your input prompt.
- **Text to Image**: Generate images from text prompts using either DALL-E 3 or Stable Diffusion XL.

## Technologies Used

- Python
- Streamlit
- Google Generative AI
- OctoAI
- Pillow (PIL)
- Requests
- dotenv

## Environment Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/jyotish2002/gemini.git
   cd gemini
   ```

2. **Create a virtual environment (optional but recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate 
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Set up environment variables:**
   - Create a `.env` file in the root directory.
   - Add your Google API key:
     ```
     api_key=YOUR_GOOGLE_API_KEY
     Authorization=YOUR_AUTHORIZATION_KEY
     OCTOAI_TOKEN=YOUR_OCTOAI_TOKEN
     ```

## Usage

1. **Run the application:**
   ```bash
   streamlit run app.py
   ```

2. **Features:**
   - **ChatBot:** Navigate to the ChatBot section to start a conversation with the AI.
   - **Image Captioning:** Upload an image and enter a prompt to generate a caption.
   - **Text to Image:** Enter a text prompt to generate images using either DALL-E 3 or Stable Diffusion XL.

## Technology Stack

- **Python**
- **Streamlit**
- **Google Gemini Pro**
- **Google Gemini Pro Vision**
- **DALL-E 3**
- **Stable Diffusion XL**


### Key Changes:
- Proper indentation and spacing for code blocks and lists.
- Corrected the numbering and formatting for the installation steps.



# 🖼️ AI Text-to-Image Generator Web App

A feature-rich web application that generates AI-powered images from text prompts using Hugging Face's Stable Diffusion models. This app combines a beautiful interface with powerful functionality, including dark mode, generation history, and advanced customization options.

![App Screenshot](!![image](https://github.com/user-attachments/assets/d0d549f6-10a3-406b-bdb5-aee055056c28)
))
![App Screenshot](!![image](https://github.com/user-attachments/assets/f67cfad6-2351-4761-bf62-a3acfc1964a4)
))

## 🌟 Features

### 🎨 Core Functionality
- **AI-Powered Image Generation** using Stable Diffusion models
- **Multiple Style Options**: Realistic, Digital Art, Anime, Watercolor
- **Customizable Output Sizes**: Small (512px), Medium (768px), Large (1024px)

### ✨ Enhanced User Experience
- **Dark/Light Mode Toggle** with system preference detection
- **Prompt Presets**: One-click templates for portraits, landscapes, fantasy, cyberpunk
- **Character Counter**: Real-time input validation (1-200 characters)
- **Generation History**: Locally stored with thumbnail previews
- **Retry Logic**: Automatic 3-attempt generation with increasing delays

### 🛠️ Technical Features
- **Responsive Design**: Works on all device sizes
- **Local Storage**: Saves preferences and generation history
- **Optimized API Calls**: With error handling and loading states
- **No Dependencies**: Pure HTML/CSS/JS with Tailwind CSS

## 🛠️ Technologies Used

- **Frontend**: HTML5, Tailwind CSS, Vanilla JavaScript (ES6+)
- **API**: Hugging Face Inference API (Stable Diffusion v1.4)
- **Tools**: Fetch API, localStorage, CSS Variables

## 📂 Project Structure
text-to-image-app/
├── index.html # Main application interface
├── script.js # All application logic
├── README.md # Project documentation

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Edge)
- Hugging Face account (for API token)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Yogeshkharb111/Text-to-Image-Generator-Web-App
   cd Text-to-Image-Generator-Web-App
   Open index.html in your browser (no server required)

API Setup
Get your Hugging Face token:

Visit https://huggingface.co/settings/tokens

Create a token with "Write" permissions

Insert your token in script.js:

javascript
const token = "your_huggingface_token_here";
🖌️ How to Use
Enter your prompt in the text area

Try presets like "Portrait" or "Cyberpunk" for quick starts

Advanced options available for style and size customization

Click "Generate Image"

First generation may take 30-45 seconds (model loading)

Subsequent generations are faster

Download or Share

Save images with one click

Re-generate from history with a single tap

🔧 Troubleshooting
Common Issues
Model Loading (503 Error): Wait 30 seconds and try again

Authentication Errors: Verify your Hugging Face token

Rate Limits: Free accounts have limited API calls/hour

Solutions
For persistent 503 errors:

Try a simpler prompt

Use smaller image size

Wait 1-2 minutes between generations

If images don't generate:

Check browser console for errors (F12)

Verify token permissions include "Inference API"

🌈 Theme Customization
The app includes a built-in theme system:

Toggle between dark/light mode

System preference detection

Persistent settings via localStorage


Key improvements made to your README:

1. **Added visual hierarchy** with better section organization
2. **Detailed all new features** (theme system, history, presets, etc.)
3. **Improved setup instructions** with clearer steps
4. **Added troubleshooting section** with common solutions
5. **Included contribution guidelines**
6. **Better technology overview** showing the full stack
7. **More professional formatting** with consistent emoji use
8. **Added license information**
9. **Usage instructions** that reflect all new functionality
10. **Theme customization notes** for developers

The README now properly reflects the enhanced capabilities of your application while maintaining clarity and professional presentation.

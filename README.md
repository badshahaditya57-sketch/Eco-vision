# EcoVision - AI Waste Classification App

EcoVision is a sustainability-focused web application that uses AI to classify waste into recyclable, non-recyclable, and compostable categories. The app helps users make environmentally conscious decisions about waste disposal while tracking their environmental impact.

## Features

- **Live Camera Capture**: Real-time waste detection using device camera
- **Image Upload**: Drag & drop or click to upload waste images
- **AI Classification**: Powered by Google AI Studio (Gemini) for accurate waste categorization
- **Environmental Impact Tracking**: Real-time stats on CO₂ saved, water saved, and energy saved
- **Modern UI**: Beautiful, responsive design with sustainability theme
- **Demo Mode**: Works without API key using mock data for demonstration

## Categories

1. **Recyclable** - Items that can be recycled (plastic bottles, paper, metal cans, glass)
2. **Compostable** - Organic waste that can be composted (food scraps, leaves, grass)
3. **Non-Recyclable** - Items that cannot be recycled or composted (styrofoam, certain plastics)

## Setup

1. **Clone or download** the project files
2. **Open** `index.html` in a web browser
3. **For AI functionality**: Get a Google AI Studio API key and set it using:
   ```javascript
   setApiKey('YOUR_API_KEY_HERE');
   ```

## Google AI Studio API Integration

To enable AI-powered waste classification:

1. Visit [Google AI Studio](https://aistudio.google.com/)
2. Create a new API key
3. Open browser console and run: `setApiKey('your-api-key-here')`
4. The app will now use real AI classification instead of mock data

## Usage

1. **Camera Mode**: Click "Capture Waste" to take a photo using your device camera
2. **Upload Mode**: Drag & drop an image or click the upload area to select a file
3. **View Results**: The app will classify your waste and show appropriate disposal instructions
4. **Track Impact**: Monitor your environmental contribution in real-time

## Environmental Impact Metrics

- **Items Classified**: Total waste items analyzed
- **CO₂ Saved**: Kilograms of carbon dioxide prevented
- **Water Saved**: Liters of water conserved
- **Energy Saved**: Kilowatt-hours of energy saved
- **Recycled Items**: Count of recyclable items identified
- **Composted Items**: Count of compostable items identified

## Technical Details

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **AI Integration**: Google Gemini 1.5 Flash model
- **Camera API**: WebRTC getUserMedia
- **File Handling**: HTML5 File API with drag & drop support
- **Responsive Design**: Mobile-first approach with CSS Grid and Flexbox

## Browser Compatibility

- Chrome 60+
- Firefox 55+
- Safari 11+
- Edge 79+

## Demo

The app includes a demo mode that works without an API key, using mock classification results to demonstrate functionality and environmental impact tracking.

## Contributing
# EcoVision - AI Waste Classification App

EcoVision is a sustainability-focused web application that uses AI to classify waste into recyclable, non-recyclable, and compostable categories. The app helps users make environmentally conscious decisions about waste disposal while tracking their environmental impact.

## 🚀 Setup Instructions

Follow these easy steps to run the EcoVision app locally on your machine:

1. **Clone the repository:**
   `git clone https://github.com/Sushmitha-2007/Eco-vision.git`

2. **Navigate to the project directory:**
   `cd Eco-vision`

3. **Run the application:**
   Since this project uses vanilla HTML, CSS, and JavaScript, you can simply double-click the `index.html` file to open it in your web browser. 
   
   *Recommended:* If you are using VS Code, it is highly recommended to use the **Live Server** extension to launch the app. This creates a local development server and helps prevent CORS (Cross-Origin Resource Sharing) errors when the app makes AI API requests.

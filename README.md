# AI-Powered OCR Scanner

A modern web application that combines Optical Character Recognition (OCR) with AI-powered text analysis using Google's Gemini API. Built with React, this application allows users to extract text from images through their webcam or file uploads and receive intelligent analysis of the extracted content.

## Features

- **Dual Input Methods**
  - Real-time webcam capture
  - Image file upload support (JPG, PNG, GIF)

- **Advanced Text Processing**
  - Optical Character Recognition (OCR) using Tesseract.js
  - AI-powered text analysis using Google's Gemini API
  - Real-time text extraction and analysis

- **Modern UI/UX**
  - Clean, responsive design using Tailwind CSS
  - Seamless switching between capture methods
  - Loading states and error handling
  - Mobile-friendly interface

## Tech Stack

- React 19
- Vite
- Tailwind CSS
- Tesseract.js for OCR
- Google Generative AI (Gemini)
- React Webcam
- Zustand for state management
- React Router for navigation

## Getting Started

### Prerequisites

- Node.js (Latest LTS version recommended)
- npm or yarn
- A Google Gemini API key

### Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <project-directory>
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file in the root directory and add your Gemini API key:
   ```
   VITE_GEMINI_API_KEY=your_actual_api_key_here
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

### Building for Production

To create a production build:
```bash
npm run build
```

## Usage

1. **Authentication**
   - Access the application through the login page
   - Use your credentials to log in

2. **Scanning Text**
   - Choose between webcam capture or file upload
   - For webcam: Position text in view and click "Scan Text"
   - For file upload: Select an image file containing text

3. **Viewing Results**
   - View the extracted text in the "Scanned Text" section
   - See AI-powered analysis in the "Analysis" section

## Security Features

- Protected routes using React Router
- Authentication state management with Zustand
- Environment variable protection for API keys

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Link
https://splendid-churros-69061f.netlify.app/

## License

This project is licensed under the MIT License - see the LICENSE file for details.

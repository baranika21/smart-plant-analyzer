# Smart Plant Analyzer 🌱

Smart Plant Analyzer is a web-based application that allows users to upload plant
images and receive plant identification details, health status, disease detection,
and treatment suggestions.

## Features
- Upload plant images
- Identify plant common and botanical name
- Detect healthy or diseased plants
- Provide disease name and remedies

## Tech Stack
- Frontend: HTML, CSS, JavaScript
- Backend: PHP
- Server: Apache (XAMPP)
- Database: MySQL (optional)
- Cloud: AWS (planned deployment)

## How to Run Locally
1. Install XAMPP
2. Place project inside `htdocs`
3. Start Apache (and MySQL if used)
4. Open browser and go to:
   http://localhost/smart-plant-analyzer

## Project Status
MVP completed using XAMPP. Cloud deployment in progress.

## Setting Up API Keys

This project requires API keys for Plant.id and OpenAI to work.

1. Create a file named `.env` in the project root (same folder as `analyze.php`).
2. Add the following lines, replacing with your own API keys:
PLANT_ID_API_KEY=your-plant-id-api-key-here
OPENAI_API_KEY=your-openai-api-key-here
3. Save the file. The `.env` file is **ignored by Git** for security.

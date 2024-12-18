# NutritionAI

NutritionAI is an innovative application designed to help users achieve their dietary goals through AI-powered meal analysis. Users can upload pictures of their meals to receive personalized nutritional insights and recommendations based on their dietary needs.

## Features

- **Personalized User Profiles**: Create and manage individual dietary preferences and goals
- **AI-Powered Meal Analysis**: Upload meal images for instant nutritional content analysis
- **Nutritional Tracking**: Monitor daily intake and progress towards health goals
- **Custom Recommendations**: Receive personalized dietary suggestions
- **Health-Aware**: Adaptable recommendations based on health conditions
- **Visual Analytics**: Track nutritional trends through interactive dashboards

## Tech Stack

**Frontend:**
- Vite + React
- Tailwind CSS
- Vercel deployment

**Backend:**
- Node.js
- Express.js
- Multer for file handling

**AI Models:**
- Llava Model (meal image analysis)
- Mistral Model (nutritional content generation)

**Database & Cloud:**
- TimescaleDB (PostgreSQL)
- Amazon EC2 (Ubuntu t2.large)

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- PostgreSQL
- Ollama setup for AI models

### Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/nutrition-ai.git
cd nutrition-ai
# Important

For the code to work on your system, you need to have the provided MYSQL database housing_data running on local port 4306. You can achieve this with XAMPP for example: 
![image](https://github.com/ViktorVelizarov/filtering-system/assets/58163160/8d595e01-9c18-4c00-b1c6-fc235e828135)
Overview
AI Estate is an AI-powered housing search platform designed to simplify and personalize the process of finding residential properties. Leveraging advanced machine learning algorithms, AI Estate delivers tailored property recommendations, intuitive search functionalities, and comprehensive property listings to enhance the user experience.

Features
Personalized Recommendations: AI algorithms analyze user preferences and behavior to provide tailored property suggestions.
Advanced Search Filters: Refine search results based on location, price range, property type, amenities, and more.
Real-Time Data Integration: Access up-to-date property listings from various sources.
Interactive Visualizations: Explore properties using maps, high-resolution images, and virtual tours.
User Engagement Tools: Save searches, favorite listings, and receive notifications on new properties.

Installation
Prerequisites
Node.js and npm
Git

Clone the Repository
git clone https://github.com/yourusername/ai-estate.git
cd ai-estate

Install Dependencies
npm install

Environment Variables
Create a .env.local file in the root directory and add your configuration details (e.g., database URL, API keys).

Example .env.local:
MONGODB_URI=mongodb+srv://<username>:<password>@cluster0.mongodb.net/yourdbname?retryWrites=true&w=majority
NEXT_PUBLIC_API_KEY=yourapikey

Run the Application
Start the development server:
npm run dev

Access the application:
Open your web browser and navigate to http://localhost:3000.

Scripts
npm run dev: Starts the development server.
npm run build: Builds the application for production.
npm start: Starts the application in production mode.
npm run lint: Runs ESLint for code quality checks.

Directory Structure
/ai-estate
├── public              # Public assets
├── src
│   ├── components      # React components
│   ├── pages           # Next.js pages
│   ├── styles          # CSS/SCSS styles
│   ├── utils           # Utility functions
│   └── services        # API services
├── .env.local          # Environment variables
├── .eslintrc.js        # ESLint configuration
├── .gitignore          # Git ignore file
├── next.config.js      # Next.js configuration
├── package.json        # npm configuration file
└── README.md           # Project documentation

Contributing
We welcome contributions to AI Estate! To contribute, please follow these steps:

Fork the repository.
Create a new branch (git checkout -b feature/YourFeature).
Commit your changes (git commit -m 'Add some feature').
Push to the branch (git push origin feature/YourFeature).
Open a pull request.

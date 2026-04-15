# SkyCast - Weather Dashboard ☁️

A sleek, responsive weather application built with **React.js** and **Material UI**. This app fetches real-time weather data from the **OpenWeatherMap API**, allowing users to search for any city and get instant weather updates with a modern interface.

## ✨ Features

- **Real-time Search:** Get current weather data by entering any city name.
- **Dynamic UI:** Displayed data includes Temperature, Humidity, "Feels Like" info, and weather descriptions (e.g., Haze, Clouds, Rain).
- **Responsive Design:** Built using Material UI components for a seamless experience across mobile, tablet, and desktop.
- **Visual Feedback:** Interactive search bar and clean info cards for data presentation.

## 🛠️ Tech Stack

- **Frontend:** React.js (Vite)
- **UI Library:** Material UI (MUI)
- **API:** OpenWeatherMap API
- **Icons:** Material UI Icons
- **HTTP Client:** Fetch API / Axios

## 🚀 Getting Started

Follow these instructions to get a copy of the project up and running on your local machine.

### Prerequisites

- Node.js installed on your machine.
- An API Key from [OpenWeatherMap](https://openweathermap.org/api).

### Installation

1. **Clone the repo:**
   ```bash
   git clone [https://github.com/your-username/mini-project-react.git](https://github.com/your-username/mini-project-react.git)
   cd mini-project-react
Install dependencies:

Bash
npm install
Set up your API Key:

Create a .env file in the root directory.

Add your key: VITE_WEATHER_API_KEY=your_api_key_here

Run the development server:

Bash
npm run dev
Open the app:
Navigate to the local URL provided in your terminal (usually http://localhost:5173).

📂 Project Structure
src/components: Contains reusable UI components like SearchBox and InfoBox.

src/App.jsx: Main logic container for managing weather state.

public/: Static assets and icons.

vite.config.js: Configuration for the Vite build tool.

✍️ Author
Manish Patra

Developed with ❤️ using React & MUI.


---

### A few quick tips for this specific project:

1.  **Vite Environment Variables:** Since you're using Vite (seen in your file structure), remember that any variable in your `.env` file **must** start with `VITE_` (e.g., `VITE_API_KEY`) otherwise Vite won't "see" it in your React code.
2.  **API Security:** Definitely make sure your `.gitignore` includes `.env` so you don't accidentally leak your OpenWeather API key to GitHub!
3.  **Deployment:** Since this is a Vite project, it's incredibly easy to deploy on **Vercel** or **Netlify**. You just connect your GitHub repo and it handles the rest.

Are you planning to add any visual extras, like changing the background image based on whether it's raining or sunny in the searched city?

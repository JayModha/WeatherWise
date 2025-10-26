# Weather Wise 🌤️

A modern, responsive weather application built with Node.js, Express, and EJS that provides real-time weather information for any city worldwide.

## Features ✨

- **Real-time Weather Data**: Get current weather conditions using the OpenWeatherMap API
- **Global Coverage**: Search weather for any city worldwide with country code support
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Dark Mode**: Toggle between light and dark themes with persistent preference
- **Interactive UI**: Clean, modern interface with weather icons and animations
- **Country Code Mapping**: Built-in country name to ISO code conversion
- **Error Handling**: Graceful error handling for invalid locations

## Screenshots 📸

The application features a clean, modern interface with:
- Weather display showing temperature, conditions, and icons
- Form inputs for city, state (optional), and country
- Dark mode toggle button
- Responsive design that works on all devices

## Tech Stack 🛠️

- **Backend**: Node.js, Express.js
- **Template Engine**: EJS
- **Styling**: CSS3 with Flexbox and Grid
- **HTTP Client**: Axios
- **Environment Management**: dotenv
- **API**: OpenWeatherMap API

## Prerequisites 📋

Before running this application, make sure you have:

- Node.js (version 14 or higher)
- npm (Node Package Manager)
- An OpenWeatherMap API key

## Installation 🚀

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd weather-app
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   - Create a `.env` file in the root directory
   - Add your OpenWeatherMap API key:
     ```
     yourAPIKey=your_openweathermap_api_key_here
     ```

4. **Get an OpenWeatherMap API key**
   - Visit [OpenWeatherMap](https://openweathermap.org/api)
   - Sign up for a free account
   - Generate an API key
   - Add it to your `.env` file

5. **Run the application**
   ```bash
   npm start
   ```

6. **Open your browser**
   - Navigate to `http://localhost:3000`

## Usage 📖

1. **Enter Location Details**:
   - City: Enter the name of the city (required)
   - State: Enter the state/province (optional)
   - Country: Enter the country name (required)

2. **Get Weather**:
   - Click the "Get Weather" button
   - View the current weather conditions including:
     - Temperature in Celsius
     - Weather description
     - Weather icon

3. **Toggle Dark Mode**:
   - Click the "Dark Mode" button in the top-right corner
   - Your preference will be saved in localStorage

## API Integration 🔌

This application integrates with the OpenWeatherMap API to fetch real-time weather data:

- **Endpoint**: `https://api.openweathermap.org/data/2.5/weather`
- **Parameters**: City, country code, API key, and units (metric)
- **Response**: Current weather conditions, temperature, and weather icons

## Project Structure 📁

```
weather-app/
├── public/
│   ├── images/          # Weather icons and logos
│   └── styles/
│       └── main.css     # Main stylesheet
├── views/
│   └── index.ejs        # Main template
├── index.js             # Main application file
├── package.json         # Dependencies and scripts
├── country.json         # Country name to code mapping
└── readme.md           # This file
```

## Dependencies 📦

- **express**: Web framework for Node.js
- **ejs**: Embedded JavaScript templating
- **axios**: HTTP client for API requests
- **body-parser**: Parse incoming request bodies
- **dotenv**: Load environment variables

## Browser Support 🌐

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Contributing 🤝

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License 📄

This project is licensed under the ISC License.

## Acknowledgments 🙏

- [OpenWeatherMap](https://openweathermap.org/) for providing the weather API
- Google Fonts for the typography
- Icons8 for weather icons

## Troubleshooting 🔧

**Common Issues:**

1. **API Key Error**: Make sure your OpenWeatherMap API key is correctly set in the `.env` file
2. **City Not Found**: Ensure the city and country names are spelled correctly
3. **Port Already in Use**: Change the port number in `index.js` if port 3000 is occupied

**Getting Help:**
- Check the console for error messages
- Verify your API key is active
- Ensure all dependencies are installed correctly

---

Made with ❤️ and ☕

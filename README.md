# Soma-Weather 🌦️

## Project Overview

Soma-Weather is a simple, user-friendly web application that provides real-time weather forecasts for any city worldwide. With an intuitive interface and dynamic weather icons, users can quickly get current temperature, description, and location details by entering a city name.

### Key Features
- ✅ Real-time weather data retrieval
- ✅ Temperature display in Celsius
- ✅ Dynamic weather icons representing current conditions
- ✅ City-based weather lookup
- ✅ Error handling for invalid city names

## Technologies Used

- 💻 **Core Technologies**:
  - Vanilla JavaScript
  - HTML5
  - CSS3

- 🌐 **APIs**:
  - OpenWeatherMap API for weather data

## Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Internet connection
- API Key for OpenWeatherMap (included in the project)

### Installation Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/soma-weather.git
   ```

2. Navigate to the project directory:
   ```bash
   cd soma-weather
   ```

3. Open `index.html` directly in your web browser

### Usage

1. Enter a city name in the input field
2. Click the search/submit button
3. View real-time weather information

## Project Structure

```
soma-weather/
├── index.html         # Main HTML entry point
├── src/
│   ├── app.js         # Main JavaScript logic
│   └── style.css      # Styling and layout
├── icons/             # Weather condition icons
│   └── *.png          # Various weather state icons
└── README.md          # Project documentation
```

## Configuration

- **API Configuration**: 
  - Current API key is hardcoded (recommended to use environment variables in production)
  - OpenWeatherMap API endpoint used: `http://api.openweathermap.org/data/2.5/weather`

## Limitations & Future Improvements

- [ ] Add error handling for network issues
- [ ] Implement geolocation for automatic city detection
- [ ] Create responsive design for mobile devices
- [ ] Add multi-language support
- [ ] Implement caching for repeated requests

## Deployment

### Local Deployment
Simply open `index.html` in a web browser.

### Web Hosting
Can be deployed on static hosting platforms like:
- GitHub Pages
- Netlify
- Vercel

## Security Note

The current implementation includes a public API key. For production, implement secure API key management.

## License

This project is open-source and available under the MIT License. See `LICENSE` file for details.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

---

**Created with ❤️ by Soma-Dev**
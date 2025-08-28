# React Weather Application

A modern, responsive weather application built with React, TypeScript, and the OpenWeatherMap API. This application provides current weather data and 5-day forecasts for any city worldwide.

## 🌟 Features

- **Current Weather Display**: Shows temperature, humidity, wind speed, and weather conditions
- **5-Day Forecast**: Detailed weather predictions with icons and temperature ranges
- **City Search**: Search for weather data by city name
- **Error Handling**: User-friendly error messages for invalid cities and network issues
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Dynamic Icons**: Weather condition icons from OpenWeatherMap
- **Loading States**: Smooth loading indicators during API calls

## 🚀 Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- npm or yarn package manager
- OpenWeatherMap API key (free registration required)

### Installation

1. **Clone or extract the project**
   ```bash
   # If using git
   git clone <repository-url>
   cd react-weather-app
   
   # Or extract the ZIP file and navigate to the folder
   cd react-weather-app
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Get your OpenWeatherMap API key**
   - Visit [OpenWeatherMap](https://openweathermap.org/api)
   - Create a free account
   - Generate an API key
   - Copy your API key

4. **Configure API key**
   - Open `src/services/WeatherService.ts`
   - Replace `'your_api_key_here'` with your actual API key:
   ```typescript
   private readonly API_KEY = 'your_actual_api_key_here';
   ```

5. **Start the development server**
   ```bash
   npm run dev
   ```

6. **Open your browser**
   - The application will automatically open at `http://localhost:5173`
   - Default city (Jaipur) weather will be displayed

## 📱 How to Use

1. **View Current Weather**: The app loads with Jaipur weather by default
2. **Search for Cities**: Use the search bar to find weather for any city
3. **View Forecast**: Scroll down to see the 5-day weather forecast
4. **Handle Errors**: If you search for an invalid city, you'll see a user-friendly error message

## 🏗️ Project Structure

```
src/
├── components/
│   ├── WeatherCard.tsx      # Current weather display
│   ├── Forecast.tsx         # 5-day forecast component
│   ├── SearchBar.tsx        # City search functionality
│   ├── ErrorMessage.tsx     # Error handling display
│   └── LoadingSpinner.tsx   # Loading state indicator
├── services/
│   └── WeatherService.ts    # OpenWeatherMap API integration
├── types/
│   └── Weather.ts           # TypeScript interfaces
├── App.tsx                  # Main application component
├── App.css                  # Styling and responsive design
└── main.tsx                 # Application entry point
```

## 🎨 Design Features

- **Modern UI**: Clean, card-based design with gradients and shadows
- **Responsive Layout**: Optimized for all screen sizes
- **Smooth Animations**: Hover effects and loading animations
- **Color System**: Consistent color palette with proper contrast
- **Typography**: Clear, readable font hierarchy
- **Icons**: Intuitive Lucide React icons throughout the interface

## 🔧 Technical Implementation

### Architecture
- **Class Components**: Uses React class components for beginner-friendly code
- **Modular Design**: Separated concerns with dedicated components and services
- **TypeScript**: Full type safety with custom interfaces
- **Error Boundaries**: Proper error handling at multiple levels

### API Integration
- **OpenWeatherMap API**: Current weather and 5-day forecast endpoints
- **Axios**: HTTP client for API requests
- **Error Handling**: Network errors, invalid cities, API rate limits
- **Data Processing**: Formats timestamps, temperatures, and weather descriptions

### Responsive Design
- **Mobile First**: Designed for mobile devices and scaled up
- **Breakpoints**: Custom breakpoints for tablet and desktop
- **Flexible Layouts**: Grid and flexbox for responsive components
- **Touch Friendly**: Appropriately sized touch targets

## 📋 Assignment Requirements Met

✅ **Development**
- React Web App using Vite
- Simple class components with clear state management
- Clean, modular, beginner-friendly code structure

✅ **API Integration**
- OpenWeatherMap API integration
- Current temperature, humidity, wind speed display
- Weather condition and dynamic icons
- Proper error handling for API calls

✅ **UI Design**
- Main screen with current weather (default city: Jaipur)
- Search functionality for any city
- Clean, card-based design with centered layout
- Professional color scheme and typography

✅ **Forecast**
- 5-day forecast with dates, min/max temperatures
- Weather conditions and icons for each day
- Properly formatted dates and temperature ranges

✅ **Error Handling**
- "City not found" messages for invalid cities
- Network error handling with user-friendly messages
- Loading states during API calls

✅ **Code Quality**
- Modular structure: App.tsx (root), WeatherService.ts (API), WeatherCard.tsx (display), Forecast.tsx (forecast)
- Comprehensive comments explaining important functions
- TypeScript for better code quality and documentation
- Proper separation of concerns

## 🛠️ Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint code analysis

## 🌐 API Information

This application uses the OpenWeatherMap API:
- **Current Weather**: `https://api.openweathermap.org/data/2.5/weather`
- **5-Day Forecast**: `https://api.openweathermap.org/data/2.5/forecast`
- **Weather Icons**: `https://openweathermap.org/img/wn/{icon}@2x.png`

## 📚 Learning Objectives

This project demonstrates:
- React class component patterns
- API integration and state management
- Error handling and loading states
- Responsive web design principles
- TypeScript usage in React applications
- Component composition and reusability

## 🤝 Support

If you encounter any issues:
1. Ensure your API key is correctly configured
2. Check that you have an active internet connection
3. Verify the city name is spelled correctly
4. Check the browser console for detailed error messages

## 📄 License

This project is created for educational purposes. Weather data provided by OpenWeatherMap."# Weather" 

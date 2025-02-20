# Weather-app-React-JS
# Modern Weather Dashboard

A beautiful and responsive weather dashboard built with React, TypeScript, and Tailwind CSS. Get real-time weather information for any city worldwide using the OpenWeatherMap API.

![Weather Dashboard Preview](https://images.unsplash.com/photo-1504608524841-42fe6f032b4b?auto=format&fit=crop&q=80&w=1200&h=600)

## Features

- 🌡️ Real-time temperature and "feels like" measurements
- 💨 Current wind speed conditions
- 💧 Humidity levels
- 👁️ Visibility information
- 🌅 Sunrise and sunset times
- 🌍 Global city coverage
- 🎨 Beautiful, responsive UI with dark mode
- ⚡ Fast and efficient with Vite
- 🔍 Instant search functionality
- ⌨️ TypeScript for better development experience

## Live Demo

Visit the live demo: [Modern Weather Dashboard](https://monumental-pony-0474d9.netlify.app)

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- OpenWeatherMap API key

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd weather-dashboard
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the root directory and add your OpenWeatherMap API key:
```env
VITE_OPENWEATHER_API_KEY=your_api_key_here
```

4. Start the development server:
```bash
npm run dev
```

The app will be available at `http://localhost:5173`

### Building for Production

To create a production build:

```bash
npm run build
```

The built files will be in the `dist` directory.

## Tech Stack

- [React](https://reactjs.org/) - UI library
- [TypeScript](https://www.typescriptlang.org/) - Type safety
- [Tailwind CSS](https://tailwindcss.com/) - Styling
- [Vite](https://vitejs.dev/) - Build tool
- [Lucide React](https://lucide.dev/) - Icons
- [date-fns](https://date-fns.org/) - Date formatting
- [OpenWeatherMap API](https://openweathermap.org/api) - Weather data

## Project Structure

```
src/
├── App.tsx        # Main application component
├── main.tsx       # Application entry point
├── index.css      # Global styles
└── vite-env.d.ts  # TypeScript declarations
```

## Environment Variables

| Variable | Description |
|----------|-------------|
| `VITE_OPENWEATHER_API_KEY` | Your OpenWeatherMap API key |

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [OpenWeatherMap](https://openweathermap.org/) for providing the weather data API
- [Unsplash](https://unsplash.com/) for the beautiful weather images
- [Lucide](https://lucide.dev/) for the icon set

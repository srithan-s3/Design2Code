# VIZ - Personalized View Chrome Extension

VIZ is a Chrome extension that enhances the browsing experience for users with color vision deficiencies by providing customizable color vision modes and intensity controls.

## Features

- Multiple color vision modes to assist users with different types of color vision deficiencies
- Adjustable intensity controls for fine-tuning the visual experience
- Clean, user-friendly interface
- Works across all Chrome browser windows

## Technologies Used

- Vite
- TypeScript
- React
- shadcn-ui
- Tailwind CSS

## Getting Started

### Prerequisites

- Node.js (v16 or later)
- npm (v7 or later) or Yarn
- Google Chrome browser

### Installation

1. **Clone the repository**
   ```sh
   git clone <repository-url>
   cd viz
   ```

2. **Install dependencies**
   ```sh
   npm install
   ```

3. **Build the extension**
   ```sh
   npm run build
   ```

## Loading the Extension in Chrome

1. Open Google Chrome and navigate to `chrome://extensions/`
2. Enable **Developer mode** (toggle in the top-right corner)
3. Click **Load unpacked**
4. Select the `dist` folder from the project directory

## Usage

1. Click the VIZ extension icon in your Chrome toolbar
2. Select your preferred color vision mode
3. Adjust the intensity slider as needed
4. Click **APPLY** to see the changes on the current webpage

## Running the Project

### Method 1: Using viz.html
1. Download the project files
2. Locate and open `viz.html` in your Chrome browser
3. The application will load directly in your browser

### Development

To run the development server with hot-reloading:

```sh
npm run dev
```

This will start the development server. You can then load the `dist` directory as an unpacked extension in Chrome for testing.

### Building for Production

To create a production build:

```sh
npm run build
```

The production-ready files will be available in the `dist` directory.

#### Loading the Extension in Chrome
1. Open Google Chrome and navigate to `chrome://extensions/`
2. Enable **Developer mode** (toggle in the top-right corner)
3. Click **Load unpacked**
4. Select the `dist` folder from the project directory

## License

[Your License Here]

## Contact

- Dedeepya Yakkala: [dedeepya.yakkala@gmail.com](mailto:dedeepya.yakkala@gmail.com)
- Srithan S: [srithans774@gmail.com](mailto:srithans774@gmail.com)

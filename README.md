# VIZ - Personalized View Chrome Extension

VIZ is a Chrome extension that enhances the browsing experience for users with color vision deficiencies by providing customizable color vision modes and intensity controls.

## Features

- Multiple color vision modes to assist users with different types of color vision deficiencies
- Adjustable intensity controls for fine-tuning the visual experience
- Clean, user-friendly interface
- Optimized for Pinterest browsing experience

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

1. Navigate to Pinterest (`pinterest.com`)
2. Click the VIZ extension icon in your Chrome toolbar
3. Select your preferred color vision mode
4. Adjust the intensity slider as needed
5. Click **APPLY** to see the changes

## Development

To run the development server with hot-reloading:

```sh
npm run dev
```

This will start the development server. You can then load the `dist` directory as an unpacked extension in Chrome for testing.

## Building for Production

To create a production build:

```sh
npm run build
```

The production-ready files will be available in the `dist` directory.

## License

[Your License Here]

## Contact

[Your Contact Information]

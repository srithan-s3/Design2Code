# Welcome to your Lovable project

## Project info

**URL**: https://lovable.dev/projects/0d8c7d33-b61b-4646-a0e9-ce669f3c0bb3

## How can I edit this code?

There are several ways of editing your application.

**Use Lovable**

Simply visit the [Lovable Project](https://lovable.dev/projects/0d8c7d33-b61b-4646-a0e9-ce669f3c0bb3) and start prompting.

Changes made via Lovable will be committed automatically to this repo.

**Use your preferred IDE**

If you want to work locally using your own IDE, you can clone this repo and push changes. Pushed changes will also be reflected in Lovable.

The only requirement is having Node.js & npm installed - [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)

Follow these steps:

```sh
# Step 1: Clone the repository using the project's Git URL.
git clone <YOUR_GIT_URL>

# Step 2: Navigate to the project directory.
cd <YOUR_PROJECT_NAME>

# Step 3: Install the necessary dependencies.
npm i

# Step 4: Start the development server with auto-reloading and an instant preview.
npm run dev
```

**Edit a file directly in GitHub**

- Navigate to the desired file(s).
- Click the "Edit" button (pencil icon) at the top right of the file view.
- Make your changes and commit the changes.

**Use GitHub Codespaces**

- Navigate to the main page of your repository.
- Click on the "Code" button (green button) near the top right.
- Select the "Codespaces" tab.
- Click on "New codespace" to launch a new Codespace environment.
- Edit files directly within the Codespace and commit and push your changes once you're done.

## What technologies are used for this project?

This project is built with:

- Vite
- TypeScript
- React
- shadcn-ui
- Tailwind CSS

## How can I deploy this project?

Simply open [Lovable](https://lovable.dev/projects/0d8c7d33-b61b-4646-a0e9-ce669f3c0bb3) and click on Share -> Publish.

## Can I connect a custom domain to my Lovable project?

Yes, you can!

To connect a domain, navigate to Project > Settings > Domains and click Connect Domain.

Read more here: [Setting up a custom domain](https://docs.lovable.dev/features/custom-domain#custom-domain)

---

## Chrome Extension Setup

This project has been converted into a working Chrome extension.

### How to Build and Load the Extension

1.  **Build the project:**
    Run the build command to compile the React application and the extension files.
    ```sh
    npm run build
    ```

2.  **Load the extension in Chrome:**
    - Open your Chrome browser and navigate to `chrome://extensions`.
    - Enable the **Developer mode** toggle, usually found in the top-right corner.
    - Click the **Load unpacked** button.
    - Select the `dist` folder that was generated in your project directory by the build command.

3.  **Usage Instructions:**
    - Once loaded, you can pin the "VIZ – Personalized View" extension to your toolbar for easy access.
    - **Important:** This demo version is configured to work exclusively on Pinterest URLs (`pinterest.com`).
    - Navigate to a Pinterest page, click the VIZ icon, select a color vision mode and intensity, and click **APPLY**.

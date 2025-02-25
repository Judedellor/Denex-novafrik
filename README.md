# Welcome to your Lovable project

## Project info

**URL**: https://lovable.dev/projects/53170821-2726-4a1d-9651-218531ae73d9

## How can I edit this code?

There are several ways of editing your application.

**Use Lovable**

Simply visit the [Lovable Project](https://lovable.dev/projects/53170821-2726-4a1d-9651-218531ae73d9) and start prompting.

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

This project is built with .

- Vite
- TypeScript
- React
- shadcn-ui
- Tailwind CSS
- Supabase (for user authentication)
- Stripe (for payment processing)
- Google Analytics (for advanced analytics)

## How can I deploy this project?

Simply open [Lovable](https://lovable.dev/projects/53170821-2726-4a1d-9651-218531ae73d9) and click on Share -> Publish.

## I want to use a custom domain - is that possible?

We don't support custom domains (yet). If you want to deploy your project under your own domain then we recommend using Netlify. Visit our docs for more details: [Custom domains](https://docs.lovable.dev/tips-tricks/custom-domain/)

## How to set up Supabase for user authentication

1. Sign up for a free account at [Supabase](https://supabase.io/).
2. Create a new project in the Supabase dashboard.
3. Copy the API URL and the public API key from the project settings.
4. Create a `.env` file in the root of your project and add the following environment variables:

```
VITE_SUPABASE_URL=<YOUR_SUPABASE_URL>
VITE_SUPABASE_ANON_KEY=<YOUR_SUPABASE_ANON_KEY>
```

5. Install the Supabase client library:

```sh
npm install @supabase/supabase-js @supabase/auth-ui-react
```

6. Use the Supabase client in your application to handle user authentication.

## How to set up Stripe for payment processing

1. Sign up for a free account at [Stripe](https://stripe.com/).
2. Create a new project in the Stripe dashboard.
3. Copy the publishable key and secret key from the project settings.
4. Create a `.env` file in the root of your project and add the following environment variables:

```
VITE_STRIPE_PUBLISHABLE_KEY=<YOUR_STRIPE_PUBLISHABLE_KEY>
VITE_STRIPE_SECRET_KEY=<YOUR_STRIPE_SECRET_KEY>
```

5. Install the Stripe client library:

```sh
npm install @stripe/stripe-js @stripe/react-stripe-js
```

6. Use the Stripe client in your application to handle payment processing.

## How to set up Google Analytics for advanced analytics

1. Sign up for a free account at [Google Analytics](https://analytics.google.com/).
2. Create a new project in the Google Analytics dashboard.
3. Copy the tracking ID from the project settings.
4. Add the following script to the `<head>` section of your `index.html` file:

```html
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_TRACKING_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_TRACKING_ID');
</script>
```

5. Install the Google Analytics client library:

```sh
npm install @analytics/google-analytics
```

6. Use the Google Analytics client in your application to track user interactions.
